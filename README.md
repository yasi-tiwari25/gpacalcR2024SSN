# IT GPA & CGPA Calculator

A responsive web-based **GPA and CGPA Calculator** built for **Information Technology (IT) students mainly R2024 - Relative Grading** to calculate semester GPA and overall CGPA quickly and accurately.

This project supports **Semester 1 to Semester 8 GPA calculation** along with a **weighted CGPA calculator** based on official semester credits.

---

## Features

### GPA Calculator
- Calculate GPA for **Semester 1 – Semester 8**
- Grade-based dropdown selection
- Accurate **credit-weighted GPA calculation**
- Semester-specific subjects and credits
- GPA displayed up to **3 decimal places**

### CGPA Calculator
- Calculate **overall CGPA**
- Enter GPA for only the semesters whose results are known
- Automatically calculates weighted CGPA using semester credits
- No manual credit entry required

### Responsive UI
- Clean modern interface
- Mobile responsive design
- Consistent layout across all semester pages
- Proper alignment and spacing
- Reusable CSS styling

---

## Technologies Used

- **HTML5**
- **CSS3**
- **JavaScript**

---

## Project Structure

```text
project-folder/
│── index.html
│── sem1.html
│── sem2.html
│── sem3.html
│── sem4.html
│── sem5.html
│── sem6.html
│── sem7.html
│── sem8.html
│── cgpa.html
│── styles.css
```

---

## GPA Calculation Formula

Semester GPA is calculated using:

```text
GPA = Σ(Grade Point × Subject Credits)
      --------------------------------
            Total Credits
```

Example:

```text
(10×3 + 9×4 + 8×3) / Total Credits
```

---

## CGPA Calculation Formula

CGPA is calculated using weighted semester credits:

```text
CGPA = Σ(Semester GPA × Semester Credits)
       ----------------------------------
             Total Credits
```

This ensures **accurate CGPA calculation** instead of a simple average.

---

## Semester Credits Used

| Semester | Credits |
|----------|----------|
| Semester 1 | 22 |
| Semester 2 | 23 |
| Semester 3 | 23.5 |
| Semester 4 | 22.5 |
| Semester 5 | 20 |
| Semester 6 | 22 |
| Semester 7 | 20 |
| Semester 8 | 14 |

---

## How to Run the Project

### Method 1: Open Directly

1. Download or clone the repository

```bash
git clone <your-repository-link>
```

2. Open:

```text
index.html
```

in your browser.

3. Select a semester or open the CGPA calculator.

---

### Method 2: Using VS Code Live Server

1. Open the project folder in **VS Code**
2. Install the **Live Server** extension
3. Right-click:

```text
index.html
```

4. Click:

```text
Open with Live Server
```

---

## Screens Included

- Semester 1 GPA Calculator
- Semester 2 GPA Calculator
- Semester 3 GPA Calculator
- Semester 4 GPA Calculator
- Semester 5 GPA Calculator
- Semester 6 GPA Calculator
- Semester 7 GPA Calculator
- Semester 8 GPA Calculator
- CGPA Calculator
- Homepage Navigation (`index.html`)

---

---

## Author

**Yasi Tiwari**

Built to simplify GPA and CGPA calculation for IT students.
