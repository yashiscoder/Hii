# YK.dev — Yash Kumawat's Portfolio

<div align="center">

### AI/ML Engineer & Developer

A personal portfolio showcasing my projects, technical skills, research, certification, and ways to connect.

[**🌐 View Live Portfolio**](https://yashiscoder.github.io/Hii/) · [GitHub](https://github.com/yashiscoder) · [LinkedIn](https://www.linkedin.com/in/kumawatyash/)

![HTML5](https://img.shields.io/badge/HTML5-Markup-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-Styling-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-Interactions-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![GitHub Pages](https://img.shields.io/badge/Deployed%20on-GitHub%20Pages-222222?style=for-the-badge&logo=githubpages&logoColor=white)

</div>

---

## About

Welcome to my personal portfolio. I'm Yash Kumawat, an MCA student and developer interested in Artificial Intelligence, Machine Learning, NLP, and software development. I build practical projects that combine intelligent systems with web and backend technologies.

The portfolio is designed as a dark, modern, responsive single-page website with interactive motion effects and sections for my background, projects, achievements, and contact information.

## ✨ Highlights

- **Responsive design** for desktop, tablet, and mobile screens
- **Interactive navigation** with a mobile menu
- **About and skills** section covering AI/ML, programming, web development, and databases
- **Featured projects** with GitHub repositories and live demos where available
- **Research and certification** section with relevant links
- **Contact section** with email and social profiles
- **Accessibility considerations**, including keyboard focus styles and reduced-motion support
- **SEO and social sharing metadata**, including a canonical URL, Open Graph tags, and structured data
- **GitHub Pages deployment** with `robots.txt` and `sitemap.xml`

## 🧰 Built With

- **HTML5** — page structure and semantic content
- **CSS3** — responsive layouts, custom styling, transitions, and animations
- **Vanilla JavaScript** — dynamic content, navigation, interactions, and motion effects
- **Google Fonts** — Syne and DM Mono
- **GitHub Pages** — static website hosting

> This portfolio is a static website. It does not require a Node.js build step or a backend server.

## 🚀 Featured Projects

### 1. SecurePass-Manager
A console-based password manager written in C++ with user authentication, password-strength analysis, email validation, CRUD operations, and file-based persistence.

- **Technologies:** C++, OOP, vectors, regular expressions, file handling
- **Repository:** [SecurePass-Manager](https://github.com/yashiscoder/SecurePass-Manager)

### 2. AgriPredict — Crop Recommendation
A machine-learning crop recommendation project that predicts suitable crops from soil and environmental parameters. The trained model is serialized as a Pickle (`.pkl`) file and integrated into a web application.

- **Technologies:** Python, Flask, HTML, JavaScript, Pickle
- **Repository:** [Agri-Predict](https://github.com/yashiscoder/Agri-Predict)
- **Demo:** [Open project demo](https://yashiscoder.github.io/Agri-Predict/)

### 3. CivicSentiment
A sentiment-analysis web application that classifies text as Positive, Negative, Neutral, or Irrelevant using a Logistic Regression model. It includes confidence scores, sentiment history, and real-time predictions.

- **Technologies:** Python, FastAPI, Logistic Regression, NLTK, text preprocessing, HTML, CSS, JavaScript
- **Repository:** [CivicSentiment](https://github.com/yashiscoder/CivicSentiment)
- **Demo:** [Open project demo](https://yashiscoder.github.io/CivicSentiment/)

## 🏆 Research & Certification

### Research Publication
**Secure and Scalable Data Access Control in Cloud Computing: A Cryptographic Approach**

Research on cryptographic approaches to cloud data access, including secure key management, encryption mechanisms, and access control.

- [Read the paper (PDF)](https://www.ijnrd.org/papers/IJNRD2504301.pdf)
- [View publication](https://www.ijnrd.org/viewpaperforall.php?paper=IJNRD2504301)

### Google Cloud Career Readiness
**Associate Cloud Engineer Track**

Coursework and practical labs covering cloud infrastructure, virtual machines, networking, storage, IAM, containerized applications, and cloud monitoring.

## 🧠 Skills

- **AI & Machine Learning:** Python, NumPy, Pandas, Scikit-learn, Machine Learning, Deep Learning, NLP, CNNs, RNNs
- **Programming:** C++, JavaScript, Data Structures
- **Web & Backend:** Angular, .NET, FastAPI, REST APIs, Salesforce
- **Databases & Tools:** MySQL, MongoDB, Git

## 📂 Repository Structure

The website is primarily a static HTML file with supporting assets and deployment metadata. Keep the image and document paths referenced by the site in the repository.

```text
Hii/
├── index.html
├── robots.txt
├── sitemap.xml
├── images/
│   └── yk.jpg
├── Yash Kumawat.pdf
└── README.md
```

The actual repository may contain additional files. If your resume or certificate filenames differ, update the links in `index.html` to match the exact names and paths.

## 💻 Run Locally

No build tools are required.

1. Clone the repository:

   ```bash
   git clone https://github.com/yashiscoder/Hii.git
   cd Hii
   ```

2. Open `index.html` in your browser.

   Alternatively, start a local static server with Python:

   ```bash
   python -m http.server 8000
   ```

3. Visit [http://localhost:8000](http://localhost:8000).

## 🌍 Deploy with GitHub Pages

1. Push the website files to the `main` branch of the `Hii` repository.
2. On GitHub, open **Settings → Pages**.
3. Under **Build and deployment**, choose **Deploy from a branch**.
4. Select the `main` branch and the `/ (root)` folder, then save.
5. After deployment, visit [https://yashiscoder.github.io/Hii/](https://yashiscoder.github.io/Hii/).

Whenever you push changes to the configured branch, GitHub Pages will publish the updated static site.

### Important paths

The current site metadata points to:

- **Canonical URL:** `https://yashiscoder.github.io/Hii/`
- **Sitemap:** `https://yashiscoder.github.io/Hii/sitemap.xml`
- **Robots file:** `https://yashiscoder.github.io/Hii/robots.txt`

If you deploy the site under a different repository or custom domain, update these URLs in `index.html`, `robots.txt`, and `sitemap.xml`.

## 🔧 Customization

- **Portfolio content:** edit the `CONFIG` object in `index.html` to update the introduction, skills, project descriptions, research, certification, and social links.
- **Appearance:** edit the CSS variables near the top of the `<style>` section.
- **Profile photo:** replace `images/yk.jpg` with your image, keeping the same path or updating the HTML reference.
- **Resume and certificate:** ensure the PDF files exist at the paths referenced in the JavaScript configuration.
- **SEO:** keep the page title, description, canonical URL, Open Graph metadata, and sitemap in sync with the live site.

## 📬 Connect

- **GitHub:** [@yashiscoder](https://github.com/yashiscoder)
- **LinkedIn:** [Yash Kumawat](https://www.linkedin.com/in/kumawatyash/)
- **X:** [@kumawatyash060](https://x.com/kumawatyash060)
- **Email:** [kumawatyash060@gmail.com](mailto:kumawatyash060@gmail.com)

I'm open to suitable internship and full-time opportunities, collaborations, and interesting projects.

---

<div align="center">

**Learning · Building · Growing**

If you like my work, feel free to ⭐ this repository.

</div>
