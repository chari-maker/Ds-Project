
# CHARIDS LAB
### Data Science Digital Laboratory

CHARIDS LAB is a web-based digital laboratory designed for students to learn Data Science through practical experiments, Python programming, modules, projects and interactive coding exercises.

## 👨‍💻 Laboratory Owner

- **Name:** Ch. Mallikarjuna Chari
- **Email:** chmallikarjunachari@gmail.com
- **GitHub:** https://github.com/chari-maker
- **Subject Code:** 22DS102006
- **Academic Year:** 2025–2026

## 🚀 Features

- **Home Dashboard:** Central dashboard with quick navigation.
- **Modules:** Five learning modules with study materials.
- **Experiments:** Practical experiments with multiple parts.
- **Python CodeLab:** Write and execute Python code in the browser.
- **Code Execution:** Run code and view program output.
- **Experiment Resources:** Download Python source files and datasets.
- **Video Tutorials:** Watch experiment demonstrations.
- **Projects:** Explore project information and repositories.
- **Student Profile:** View laboratory and profile information.
- **Responsive UI:** Designed for desktop, tablet and mobile devices.

## 📚 Modules

1. Import & Export
2. Web Data & SQL
3. Cleaning & Regex
4. Reshaping Data
5. Visualization

## 🛠️ Technologies Used

- HTML5
- CSS3
- JavaScript
- Python
- Pyodide / WebAssembly
- Browser-based Code Execution

## 📂 Project Structure

```text
CHARIDS-LAB/
│
├── index.html
├── netlify.toml
│
└── assets/
    ├── css/
    │   └── styles.css
    │
    ├── js/
    │   ├── data.js
    │   ├── app.js
    │   ├── codelab.js
    │   └── codelab-py.js
    │
    ├── img/
    │   ├── student-photo.jpg
    │   └── monthly-sales-expenses.png
    │
    ├── modules/
    │   ├── module-1.pdf
    │   ├── module-2.pdf
    │   ├── module-3.pdf
    │   ├── module-4.pdf
    │   └── module-5.pdf
    │
    ├── downloads/
    │   ├── Student.json
    │   ├── Student.xlsx
    │   ├── StudentOutputs.csv
    │   └── other datasets
    │
    └── videos/
        └── Experiment demonstration videos
```

## 💻 Run Locally

1. Download or clone this repository.
2. Open the project folder in VS Code.
3. Open the folder using Live Server.
4. Visit the local website in your browser.

You can also deploy the project directly as a static website.

## 🌐 Deployment

This project supports static hosting platforms such as:

- Vercel
- Netlify
- GitHub Pages

No Node.js build process or npm installation is required for the current static-site setup.

## ⚙️ Updating Profile Information

To update laboratory or profile details, edit:

```text
assets/js/data.js
```

To update the profile photograph, place the image inside:

```text
assets/img/student-photo.jpg
```

Keep the image path in `data.js` consistent with the actual file location.

## 📌 Important Notes

- Keep the `assets` folder and its internal structure unchanged.
- Do not remove the existing JavaScript file connections in `index.html`.
- Python execution takes place in the browser using the configured CodeLab runtime.
- Python package availability depends on the browser runtime and supported packages.
- This is a static website; server-side authentication and shared database storage are not included in the static deployment.

## 📄 License

This project is intended for academic and educational purposes.

---

**CHARIDS LAB – Learn. Build. Experiment.**
