# <img src="https://i.postimg.cc/xdctZvWn/1.png" width="69">  Mumbai University Question Paper Renamer 

**Mumbai University Question Paper Renamer** is a lightweight browser-based tool that helps students and faculty of **Mumbai University** automatically rename question paper files to a standardized and readable format like:

```

TCS 2022 May.pdf
SE 2023 December.pdf

```

It simplifies bulk file renaming based on subject, year, and month extracted from filenames.

---

## 🔧 Features

- Rename multiple files at once  
- Fully client-side (no uploads, no data stored)  
- Clean, readable naming convention  
- Supports key Mumbai University subjects:
  - TCS (Theoretical Computer Science)
  - SE (Software Engineering)
  - CN (Computer Networks)
  - DWM (Data Warehousing and Mining)
  - IP (Internet Programming)
  - M1 (Engineering Mathematics I)
  - M2 (Engineering Mathematics II)
  - M3 (Engineering Mathematics III)
  - M4 (Engineering Mathematics IV)
  - AOA (Analysis of Algorithm)
  - DBMS (Database Management System)
  - OS (Operating System)
  - MP (Microprocessor)
  - DSGT (Discrete Structures and Graph Theory)
  - DS (Data Structure)
  - DLCA (Digital Logic and Computer Architecture)
  - CG (Computer Graphics)
  - EM (Engineering Mechanics)
  - BEE (Basic Electrical Engineering)
  - EG (Engineering Graphics)
  - CP (C Programming)

---


## 📁 Input Filename Format

This tool expects files named in a format like:

```

be\_computer-engineering\_semester-5\_2022\_may\_theoretical-computer-sciencerev-2019-c-scheme.pdf

```

It extracts the year (`2022`), the month (`May`), and maps the subject (`theoretical-computer-science`) to its short form (`TCS`).

---

## 📤 Output Filename Format

Renamed files follow this structure:

```

<Subject-Code> <Year> <Month>.pdf

```

**Example:**

```

TCS 2022 May.pdf

```

---

## 🖥️ How to Use

1. Go to the live tool: [https://mobasheera.github.io/MU-QP-Renamer/](https://mobasheera.github.io/MU-QP-Renamer/)
2. Upload or drag and drop your question paper files.
3. Each file will be automatically renamed and downloaded with the correct format.


---

## 🚀 Tech Stack

- HTML5
- CSS3 (Dark Mode)
- Vanilla JavaScript

---

## 📚 License

This project is licensed under the [MIT License](LICENSE).

---

