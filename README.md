# testScuola
progetto di gruppo


```markdown
# 📘 Esercizio GitHub – Pagina Personale

Benvenuti! In questo esercizio ogni sviluppatore dovrà creare una **pagina HTML personale** e aggiungere un **link** alla pagina principale (`index.html`).  
Lo scopo è imparare a usare GitHub in modo collaborativo, con branch, commit e pull request.

---

## ✅ Obiettivo

- Creare una pagina `nome-cognome.html` con il proprio nome.
- Aggiungere un link alla propria pagina dentro `index.html`.
- Usare un branch personale e aprire una pull request.

---

## 🧭 Istruzioni passo per passo

### 1. Clona il repository

```bash
git clone https://github.com/<nome-org-o-utente>/<nome-repo>.git
cd <nome-repo>
```

### 2. Crea un branch personale

```bash
git checkout -b feature/nome-cognome
```

Esempio:
```bash
git checkout -b feature/luigi-petrossi
```

### 3. Crea la tua pagina HTML

Crea un file chiamato `nome-cognome.html` con questo contenuto:

```html
<!DOCTYPE html>
<html lang="it">
<head>
  <meta charset="UTF-8">
  <title>Nome Cognome</title>
</head>
<body>
  <h1>Nome Cognome</h1>
  <p>Questa è la mia pagina personale per l’esercizio GitHub.</p>
</body>
</html>
```

### 4. Aggiungi il link in `index.html`

Dentro la lista `<ul>`, aggiungi:

```html
<!-- Nome Cognome -->
<li><a href="nome-cognome.html">Nome Cognome</a></li>
```

### 5. Salva e fai commit

```bash
git add .
git commit -m "feat: aggiunta pagina personale Nome Cognome"
```

### 6. Push del branch

```bash
git push -u origin feature/nome-cognome
```

### 7. Apri una Pull Request

- Vai su GitHub → il tuo repository
- Clicca “Compare & pull request”
- Scrivi titolo e descrizione
- Clicca “Create pull request”

---



