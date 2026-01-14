# 📝 GUIDE DE MODIFICATION DU PROGRAMME

Ce guide explique comment **Yvan Gastaut** (ou toute autre personne) peut modifier l'ordre des morceaux du programme et voir les changements en direct sur le site.

---

## 🎯 DEUX OPTIONS POSSIBLES

### **Option 1 : Modification Simple (RECOMMANDÉE)**
Yvan envoie ses modifications par email/WhatsApp, et vous mettez à jour le site.

### **Option 2 : Modification Directe**
Yvan peut modifier le fichier HTML lui-même et mettre à jour le site (nécessite un compte GitHub).

---

## ⚡ OPTION 1 : MODIFICATION SIMPLE (5 minutes)

### **Pour Yvan :**
1. Regarder le programme sur : https://githublien.github.io/concert-bleu-fevrier-2026/Programme_Concert_1er_Fevrier_2026.html
2. Noter l'ordre souhaité des morceaux (par exemple : "Mettre Blue Moon en 3ème position")
3. Envoyer les modifications par email ou WhatsApp

### **Pour vous (Mickaël) :**
1. Ouvrir le fichier `Programme_Concert_1er_Fevrier_2026.html`
2. Modifier l'ordre des morceaux (copier-coller les sections)
3. Sauvegarder le fichier
4. Dans PowerShell, taper :
   ```powershell
   cd "D:\De nombreux projets dossier important pour IA\Concert-Bruno-Membrey-Fevrier-2026"
   .\deploy-github.ps1
   ```
5. Attendre 1-2 minutes → Le site est mis à jour !

**Avantages :**
- ✅ Simple et rapide
- ✅ Pas besoin de connaissances techniques pour Yvan
- ✅ Vous gardez le contrôle

---

## 🔧 OPTION 2 : MODIFICATION DIRECTE PAR YVAN

Si Yvan veut modifier lui-même le programme :

### **Prérequis :**
- Compte GitHub
- Accès au dépôt (vous devez l'inviter comme collaborateur)

### **Étapes pour Yvan :**

1. **Aller sur GitHub :**
   - https://github.com/GitHublien/concert-bleu-fevrier-2026

2. **Cliquer sur le fichier :**
   - `Programme_Concert_1er_Fevrier_2026.html`

3. **Cliquer sur l'icône crayon** (Edit this file)

4. **Modifier l'ordre des morceaux :**
   - Chaque morceau est dans une section `<div class="piece">...</div>`
   - Copier-coller les sections pour changer l'ordre
   - Exemple : déplacer le morceau V avant le morceau III

5. **Sauvegarder :**
   - Descendre en bas de la page
   - Cliquer sur **"Commit changes"**
   - Ajouter un message : "Modification de l'ordre des morceaux"
   - Cliquer sur **"Commit changes"**

6. **Attendre 1-2 minutes :**
   - GitHub Pages met à jour le site automatiquement
   - Rafraîchir la page : https://githublien.github.io/concert-bleu-fevrier-2026/Programme_Concert_1er_Fevrier_2026.html

**Avantages :**
- ✅ Yvan peut modifier quand il veut
- ✅ Changements visibles en 1-2 minutes
- ✅ Historique de toutes les modifications

**Inconvénients :**
- ⚠️ Nécessite un compte GitHub
- ⚠️ Yvan doit comprendre la structure HTML de base

---

## 📋 EXEMPLE DE MODIFICATION

### **Avant (ordre actuel) :**
```
I   - Les mots bleus
II  - Plus bleu que tes yeux
III - L'amour est bleu
IV  - Volare
V   - Le beau Danube bleu (Piano)
```

### **Après (nouvel ordre) :**
```
I   - Les mots bleus
II  - L'amour est bleu
III - Plus bleu que tes yeux
IV  - Le beau Danube bleu (Piano)
V   - Volare
```

Pour faire ce changement, il suffit de **copier-coller** les sections `<div class="piece">...</div>` dans le bon ordre.

---

## 🎯 RECOMMANDATION

**Pour ce concert, je recommande l'Option 1 :**
- Yvan regarde le programme
- Il vous envoie ses suggestions d'ordre
- Vous mettez à jour en 5 minutes
- Le site est mis à jour automatiquement

**C'est plus simple et plus rapide !**

Si Yvan veut vraiment modifier lui-même (Option 2), je peux :
1. L'inviter comme collaborateur sur GitHub
2. Lui créer un guide simplifié avec captures d'écran
3. Lui montrer comment modifier juste l'ordre des morceaux

---

## 📞 BESOIN D'AIDE ?

Si vous voulez que je vous aide à :
- Modifier l'ordre des morceaux
- Inviter Yvan comme collaborateur
- Créer un guide simplifié pour Yvan

Dites-moi simplement ce que vous préférez ! 🎵
