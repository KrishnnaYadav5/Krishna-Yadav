from ds_python_interpreter import ds_python_interpreter

content = """# Krishna Yadav
### Aspiring Developer & Designer | Java

---

## 📧 Contact Information
* **Phone:** 9136055615 [cite: 3]
* **Gmail:** [Krishnna.yadav55@gmail.com](mailto:Krishnna.yadav55@gmail.com) [cite: 4]
* **LinkedIn:** [linkedin.com/in/krishnayadav5/](https://www.linkedin.com/in/krishnayadav5/) [cite: 5]
* **Portfolio:** [behance.net/krishnayadav228](https://www.behance.net/krishnayadav228) [cite: 6]
* **Location:** Ghatkopar, Mumbai (Ready to relocate) [cite: 6]

---

## 🎓 Education
* **Masters in Computer Applications (MCA)** | 2024 – 2026 [cite: 8, 22]
    * Navinchandra Mehta Institute of Technology and Development (NMITD), University of Mumbai [cite: 9]
* **Bachelors of Commerce (B.Com)** | 2020 – 2023 [cite: 10, 23]
    * Tolani College of Commerce (Autonomous), University of Mumbai [cite: 11]

---

## 🛠 Technical Skills
* **Programming Languages:** Java, PHP, Python, HTML, CSS, JavaScript [cite: 13, 14]
* **Frameworks & Tools:** Angular, Excel, Power BI, GitHub, Bootstrap, Figma (UI/UX, illustration) [cite: 16, 18]
* **Databases:** MySQL, MongoDB [cite: 17, 19]
* **Design Tools:** Figma, Adobe Illustrator, Adobe Photoshop, Corel Draw [cite: 20, 21]

---

## 💼 Internship Experience

### Data Analytics | Digital Bros Ltd (United Kingdom)
*Feb 15, 2026 – Apr 10, 2026* [cite: 24, 25, 26]
* Collected and compiled music industry data from YouTube and various websites using Instant Data Scraper, importing datasets into Excel for detailed analysis. [cite: 27]
* Cleaned and transformed raw data by removing duplicates and unnecessary URL columns, restructuring unorganized datasets into a standardized format. [cite: 28]
* Utilized advanced Excel features (filters, sorting) to enhance data quality and chronological organization. [cite: 29]
* Built interactive dashboards using charts and pivot tables to analyze top-performing songs and identify high-ranking genres. [cite: 30]

### AIML | Edunet Foundation (India)
*Dec 10, 2025 – Jan 21, 2026* [cite: 31, 32]
* Optimized AI prompts using the **P.R.E.P (Point, Reason, Example, Point)** framework to improve response consistency and accuracy. [cite: 33]
* Automated end-to-end AI workflows using **n8n** by integrating pre-built models and APIs to streamline multi-step processes. [cite: 33]
* Deployed an interactive chatbot using **Python, Streamlit, and Gemini** to provide context-aware user responses and enhanced UX. [cite: 33]

---

## 🚀 Projects

### Student Wellness Companion Chatbot
*Python, Streamlit, Gemini API* [cite: 38]
* Developed a mental wellness chatbot that detects emotional states in real-time and delivers empathetic support. [cite: 39]
* Integrated evidence-based relaxation techniques (breathing exercises) and provided direct connections to professional crisis resources. [cite: 39]

### Market Basket Analysis
*Python, Jupyter Notebook* [cite: 35]
* Identified over 50 cross-selling opportunities, providing insights to potentially increase average transaction value by 15%. [cite: 36]
* Visualized complex association rules (Support vs. Confidence) to optimize product placement for stakeholders. [cite: 37]

### Smart Spending System
*Java, MySQL, JDBC* [cite: 40]
* Designed a bookkeeping system allowing users to perform CRUD operations and record daily expenses efficiently. [cite: 41]
* Implemented features for account management, transaction tracking, balance monitoring, and data persistence. [cite: 42]

---

## 📜 Certifications
* **Create REST APIs with Spring and Java** – Codecademy Skill Path [cite: 44, 45]
* **Skill Enhancement Program (TEL Certification)** – ICAI & Tolani College [cite: 46]
    * Focus: Excel, Communication, Multi-tasking, and Management Skills. [cite: 47]

---

## 🌟 Extra-Curricular Activities
* **NGO Sukshum Special School:** Contributed to social initiatives by designing promotional brochures, exam worksheets, and funding proposals (Letter of Acknowledgement). [cite: 49, 50]
* **Technical Committee Member:** Led event promotion and designed posters for the college cultural fest (Certificate of Appreciation). [cite: 51, 52]
"""

ds_python_interpreter(code=f"with open('Krishna_Yadav_Resume.md', 'w') as f: f.write('''{content}''')")
