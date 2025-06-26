# 📄 MU-QP-Renamer

**MU-QP-Renamer** is a lightweight browser-based tool that helps students and faculty of **Mumbai University** automatically rename question paper files to a standardized and readable format like:

```

TCS 2022 May.pdf
SE 2023 December.pdf

```

It simplifies bulk file renaming based on subject, year, and month extracted from filenames.

---

## 🔧 Features

- ✅ Rename multiple files at once
- ✅ Fully client-side (no uploads, no data stored)
- ✅ Clean, readable naming convention
- ✅ Supports key MU subjects:
  - TCS (Theoretical Computer Science)
  - SE (Software Engineering)
  - CN (Computer Networks)
  - DWM (Data Warehousing and Mining)
  - IP (Internet Programming)

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

