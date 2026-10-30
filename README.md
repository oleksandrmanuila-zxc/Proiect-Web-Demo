
<!-- ===================================================== -->
<!--                    PROJECT README                     -->
<!-- ===================================================== -->

<div align="center">

# 🚀 Proiect de Laborator – Git și GitHub

### Documentație tehnică și prezentarea proiectului

![GitHub](https://img.shields.io/badge/GitHub-Repository-181717?style=for-the-badge&logo=github)
![Git](https://img.shields.io/badge/Git-Version_Control-F05032?style=for-the-badge&logo=git&logoColor=white)
![VS Code](https://img.shields.io/badge/Editor-VS_Code-007ACC?style=for-the-badge&logo=visualstudiocode)

**Realizat în cadrul activităților de laborator**

</div>

---

## 📌 1. Despre proiect

Acest proiect a fost realizat în cadrul activităților de laborator și are ca scop familiarizarea cu sistemul de control al versiunilor Git și cu platforma GitHub.

Proiectul demonstrează utilizarea comenzilor Git, gestionarea fișierelor, organizarea unui repository și documentarea corespunzătoare a unui proiect software folosind limbajul Markdown.

Scopul principal este dezvoltarea competențelor necesare pentru gestionarea eficientă a proiectelor software și colaborarea în cadrul echipelor de dezvoltare.

## 🎯 2. Obiectivele proiectului

Principalele obiective urmărite sunt:

- Înțelegerea conceptelor fundamentale Git și GitHub.
- Crearea și configurarea unui repository.
- Gestionarea fișierelor folosind Git.
- Înțelegerea etapelor de lucru: Working Directory, Staging Area și Repository.
- Realizarea commit-urilor pentru salvarea modificărilor.
- Publicarea proiectului pe GitHub.
- Crearea unui fișier README.md folosind Markdown.
- Organizarea și prezentarea profesională a unui proiect.

## 🛠️ 3. Tehnologii și instrumente utilizate

| Tehnologie | Descriere |
|---|---|
| Git | Sistem distribuit de control al versiunilor |
| GitHub | Platformă online pentru găzduirea repository-urilor |
| Visual Studio Code | Editor de cod sursă |
| Markdown | Limbaj de formatare a documentației |
| Git Bash / Terminal | Interfață pentru executarea comenzilor |

## 💻 4. Cerințe preliminare

Pentru utilizarea și dezvoltarea proiectului sunt necesare următoarele instrumente:

1. Instalarea Git.
2. Instalarea Visual Studio Code.
3. Crearea unui cont GitHub.
4. Acces la un terminal sau Git Bash.
5. Conexiune la internet pentru sincronizarea cu GitHub.

### Resurse utile

- [Git – Website oficial](https://git-scm.com/)
- [GitHub](https://github.com/)
- [Visual Studio Code](https://code.visualstudio.com/)
- [Markdown Guide](https://www.markdownguide.org/)

## ⚙️ 5. Instalare și configurare

### Pasul 1 – Verificarea instalării Git

Deschideți terminalul și executați:

```bash
git --version
```

### Pasul 2 – Configurarea identității Git

```bash
git config --global user.name "Manuila Oleksandr"
git config --global user.email "oleksandr.manuila@student.usv.ro"
```

### Pasul 3 – Clonarea repository-ului

```bash
git clone https://github.com/USERNAME/REPOSITORY.git
```

### Pasul 4 – Accesarea proiectului

```bash
cd REPOSITORY
```

## 🔄 6. Ciclul de viață Git

Unul dintre cele mai importante concepte în utilizarea Git este ciclul de viață al fișierelor.

Acesta cuprinde trei etape principale:

| Etapă | Descriere |
|---|---|
| Working Directory | Zona în care sunt create și modificate fișierele |
| Staging Area | Zona în care sunt pregătite modificările pentru commit |
| Repository | Zona în care modificările sunt salvate permanent prin commit |

### Diagrama procesului

```text
    WORKING DIRECTORY
           |
           | git add
           v
      STAGING AREA
           |
           | git commit
           v
       REPOSITORY
           |
           | git push
           v
         GITHUB
```

### Comenzi Git esențiale

**1. Verificarea stării repository-ului**

```bash
git status
```

**2. Adăugarea fișierelor în Staging Area**

```bash
git add README.md
```

Pentru toate fișierele modificate:

```bash
git add .
```

**3. Salvarea modificărilor prin commit**

```bash
git commit -m "Adauga documentatia initiala"
```

**4. Încărcarea modificărilor pe GitHub**

```bash
git push
```

**5. Verificarea istoricului commit-urilor**

```bash
git log --oneline
```

## 📂 7. Structura proiectului

Structura recomandată a repository-ului este:

```text
Proiect-Laborator/
│
├── README.md
│
├── src/
│   └── main.py
│
├── docs/
│   └── documentatie.md
│
├── images/
│   └── prezentare.png
│
└── .gitignore
```

**Explicația directoarelor:**

- `README.md` – Documentația principală a proiectului.
- `src/` – Conține fișierele sursă ale aplicației.
- `docs/` – Conține documentația suplimentară.
- `images/` – Conține imagini și capturi de ecran.
- `.gitignore` – Specifică fișierele care nu trebuie urmărite de Git.

*Notă: Structura este una orientativă și poate fi adaptată în funcție de cerințele proiectului.*

## 📝 8. Utilizarea Markdown

Markdown permite formatarea rapidă și eficientă a documentației.

Exemple de elemente utilizate:

**Text îngroșat:**

```markdown
**Acesta este un text important.**
```

*Text italic:*

```markdown
*Acesta este un text italic.*
```

**Liste:**

```markdown
- Primul element
- Al doilea element
- Al treilea element
```

**Link-uri:**

```markdown
[Accesează GitHub](https://github.com/)
```

**Imagini:**

```markdown
![Descriere imagine](images/prezentare.png)
```

**Blocuri de cod:**

```markdown
```python
print("Hello, World!")
```
```

Pentru previzualizarea documentației în timp real, se poate utiliza extensia Markdown Preview din Visual Studio Code.

## 📊 9. Exemple de comenzi Git

| Comandă | Funcționalitate |
|---|---|
| `git init` | Inițializează un repository |
| `git clone` | Clonează un repository |
| `git status` | Verifică starea fișierelor |
| `git add` | Adaugă modificări în staging |
| `git commit` | Salvează modificările |
| `git push` | Încarcă modificările pe GitHub |
| `git pull` | Descarcă modificările de pe GitHub |
| `git log` | Afișează istoricul commit-urilor |
| `git branch` | Gestionează ramurile |
| `git merge` | Unește ramuri |

## 🏆 10. Rezultate și competențe dobândite

În urma realizării acestui laborator, au fost dezvoltate următoarele competențe:

- Utilizarea comenzilor de bază Git.
- Gestionarea unui repository local și remote.
- Înțelegerea procesului de versionare a codului.
- Organizarea fișierelor într-un proiect software.
- Documentarea unui proiect folosind Markdown.
- Utilizarea platformei GitHub pentru publicarea proiectelor.
- Familiarizarea cu bunele practici de dezvoltare software.

## 📸 11. Capturi de ecran

Pentru o prezentare mai detaliată a activității, această secțiune poate conține capturi de ecran din timpul realizării laboratorului.

Exemple de imagini recomandate:

1. Repository-ul creat pe GitHub.
2. Proiectul deschis în Visual Studio Code.
3. Executarea comenzilor Git în terminal.
4. Realizarea unui commit.
5. Publicarea modificărilor prin `git push`.

<!-- Adăugați imaginile în directorul images și eliminați comentariile de mai jos pentru a le afișa. -->

<!-- ![Repository GitHub](images/github-repository.png) -->

<!-- ![Visual Studio Code](images/vscode-project.png) -->

## 👨‍🎓 12. Autor

| Informație | Detalii |
|---|---|
| Nume și prenume | [Completați numele] |
| Specializare | [Completați specializarea] |
| Disciplina | [Completați disciplina] |
| Activitate | Laborator – Git și GitHub |
| An universitar | 2026–2027 |
| Instituție | [Completați universitatea] |

## 📚 13. Bibliografie și resurse

1. [Git Documentation](https://git-scm.com/doc)
2. [GitHub Documentation](https://docs.github.com/)
3. [Markdown Guide](https://www.markdownguide.org/)
4. [Visual Studio Code Documentation](https://code.visualstudio.com/docs)
5. [Awesome GitHub Profile README](https://github.com/abhisheknaiidu/awesome-github-profile-readme)

---

<div align="center">

### ⭐ Mulțumesc pentru vizualizarea proiectului!

**Realizat cu Git, GitHub și Markdown.**

</div>
