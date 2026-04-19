# KGlearning — Landing Page

Page de vente pour **Python pour Comptable — Le Guide Pratique**  
Par M.M. Mardochée KIKIGBAGBAN

🔗 **Live** : https://christmardochee.github.io/kglearning/  
🛒 **Acheter** : https://pzbcbrry.mychariow.shop/prd_rsxgkm

---

## Déploiement (5 minutes)

### 1. Créer le repo sur GitHub

- Va sur https://github.com/new
- **Repository name** : `kglearning`
- Visibilité : ✅ **Public** (obligatoire pour GitHub Pages gratuit)
- Clique **Create repository**

### 2. Uploader les fichiers

Sur la page du repo vide, clique **"uploading an existing file"** puis glisse :

```
index.html
README.md
```

Clique **Commit changes**.

### 3. Activer GitHub Pages

- Va dans **Settings** → **Pages** (menu gauche)
- Source : **Deploy from a branch**
- Branch : `main` / `(root)`
- Clique **Save**

⏳ Attendre 1-2 minutes, puis ton site est live à :

```
https://christmardochee.github.io/kglearning/
```

---

## Quand tu auras kglearning.com

Dans **Settings → Pages → Custom domain** :  
Entre `kglearning.com` et active **Enforce HTTPS**.

Chez ton registrar, ajoute ces enregistrements DNS :

```
A     @    185.199.108.153
A     @    185.199.109.153
A     @    185.199.110.153
A     @    185.199.111.153
CNAME www  christmardochee.github.io
```

---

## Structure du repo

```
kglearning/
├── index.html     ← landing page Python pour Comptable
└── README.md
```

Pour ajouter d'autres livres plus tard :

```
kglearning/
├── index.html                  ← page d'accueil boutique
├── python-comptable.html       ← landing livre 1
├── machine-learning.html       ← landing livre 2
└── README.md
```
