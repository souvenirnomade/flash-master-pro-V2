# Flash Master Pro — APK Android
### Souvenir Nomade · Hage Pierre-Alexandre

Calculateur de puissance flash — Méthode Nath Sakura  
100% hors-ligne · Multi-sources · Optimisation +1.33 IL

---

## 📱 Comment obtenir l'APK (sans rien installer de complexe)

### Étape 1 — Installer les outils sur ton PC Windows

1. **Node.js** → https://nodejs.org → télécharge la version "LTS" → installe normalement
2. **Git** → https://git-scm.com → télécharge → installe normalement
3. Redémarre ton PC après installation

### Étape 2 — Mettre le projet sur GitHub

1. Va sur **github.com** → connecte-toi à ton compte
2. Clique sur le bouton vert **"New"** (nouveau dépôt)
3. Nom du dépôt : `flash-master-pro`
4. Laisse tout par défaut → clique **"Create repository"**
5. GitHub te montre des commandes. Ouvre le **Terminal Windows** (cherche "cmd" dans le menu Démarrer)

Dans le terminal, tape ces commandes une par une :
```
cd Bureau
git init flash-master-pro
cd flash-master-pro
```
Copie tous les fichiers de ce projet dans ce dossier, puis :
```
git add .
git commit -m "Flash Master Pro v1.0"
git branch -M main
git remote add origin https://github.com/TON-PSEUDO/flash-master-pro.git
git push -u origin main
```
(remplace `TON-PSEUDO` par ton nom d'utilisateur GitHub)

### Étape 3 — GitHub compile l'APK automatiquement ☁️

1. Va sur **github.com/TON-PSEUDO/flash-master-pro**
2. Clique sur l'onglet **"Actions"**
3. Tu verras un workflow qui tourne (cercle jaune = en cours, ✅ vert = terminé)
4. Ça prend environ **5 à 10 minutes**

### Étape 4 — Télécharger l'APK

1. Dans l'onglet **Actions**, clique sur le dernier build vert ✅
2. En bas de la page, tu vois **"Artifacts"**
3. Clique sur **FlashMasterPro-debug** → ça télécharge un ZIP
4. Dézippe → tu as ton fichier **app-debug.apk**

### Étape 5 — Installer sur Android

1. Transfère l'APK sur ton téléphone (câble USB ou email)
2. Sur le téléphone : **Paramètres → Sécurité → Sources inconnues** → Autoriser
3. Ouvre le fichier APK → Installer
4. L'appli **Flash Master Pro** apparaît dans tes apps !

---

## 🔄 Mettre à jour l'appli

Si tu veux modifier le calculateur, modifie le fichier `www/index.html`  
puis relance :
```
git add .
git commit -m "Mise à jour"
git push
```
GitHub recompile automatiquement → nouvel APK disponible en 10 min.

---

## ✅ Fonctionnalités

- ⚡ Calcul puissance flash — Méthode Nath Sakura
- 📐 Mode incident & réfléchi / TTL
- 🎨 21 carnations de peau
- 🧵 50+ matières (textiles, métaux, bois, aliments...)
- 📏 Compensation distance (loi inverse carré)
- 🔆 Optimisation +1.33 IL
- 💡 Multi-sources jusqu'à 6 flashs
- 🔲 Calculateur filtres ND (empilement 3 filtres)
- ⚠️ Guide Nath Sakura (si puissance insuffisante)
- ✈️ 100% hors-ligne — fonctionne en avion

---

*Souvenir Nomade · com.souvenirsnomade.flashmasterpro*
