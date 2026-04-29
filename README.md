### Hi there! 👋 I'm Lucas Besbati

I'm a senior studying Informatics at the University of Washington with a background in biology, and I'm driven by a simple question: *how can we use machine learning to understand the building blocks of life?* From predicting RNA structures to training object detection models on bonsai trees, I love working at the intersection of code and the natural world.

**About Me**
- 🧬 ML + bioinformatics researcher at the UW DAIS Lab
- 🎓 B.S. Informatics @ UW · A.S. Biology @ Cascadia College
- 🖥️ Full-stack experience building tools for local businesses and student orgs
- 👾 League of Legends enthusiast
- 📫 Let's connect: [linkedin.com/in/besbati/](https://www.linkedin.com/in/besbati/)

---

### 🔬 Undergraduate Research

**DAIS DeepTracer — University of Washington**
*Machine Learning & Bioinformatics Research Assistant · Oct 2024 – Jun 2025*

Contributed to the DeepTracer project under Drs. Dong Si and Jie Hou, focused on improving RNA 3D structure prediction from cryo-EM density maps. Built automated database scrapers and ChimeraX pipelines to curate a large-scale RNA density map training dataset used to train the lab's deep learning models.

- Developed Python scrapers to collect and process structural biology data from public repositories
- Automated molecular visualization workflows in ChimeraX, reducing manual data prep time
- Contributed to a training dataset supporting ongoing RNA motif classification research

**Tech:** Python, PyTorch, ChimeraX, BeautifulSoup

---
 
### 🎓 Capstone Project
 
**Pacific Bonsai Museum — Digital Asset Management Redesign**
*Software Consultant Capstone · Dec 2025 – Present*

[Smart Image Uploader for Pacific Bonsai Museum](https://team-bloom-capstone-image-uploader-1.onrender.com)
 
We have worked with the Pacific Bonsai Museum to rebuild how they catalog and search their image library. The museum's current SharePoint setup makes it hard for staff to find specific bonsai portraits or pull relevant images for exhibits, so we're wrapping a computer vision pipeline around the tools they already use day-to-day — no migration, no new platform for staff to learn.
 
**Project Goals**
- Streamline and future-proof media organization and storage for the museum
- Build an upload and tagging interface that non-technical museum staff can use without training
- Extend the museum's SharePoint setup to support text-to-image search, auto-generated metadata, and dynamic folder structures

**Process & My Contributions**
 
We're a five-person team consisting of two developers, a project manager, and two UX designers. I am the lead developer and have worked to build a user-friendly interface that seamlessly integrates with the museum's existing Sharepoint system to create an intuitive media processing solution. The interface allows the museum staff to more easily work through their backlog of photos as well as process new media without needing technical skills or an extensive knowledge of Sharepoint.

Using Microsoft's Azure API, users are able to automatically batch-tag photos with AI-generated alt text. These tags not only serve as a visual description of each image, but also enable text-to-image search in Sharepoint through vector searching. Additionally, our interface provides several configurable metadata fields which can also be applied automatically to any selection of images. When combined with the changes we've made to the underlying Sharepoint storage, this solution makes the museum's digital asset management system more dynamic, organized, and searchable.

On the team side, we've been running regular check-ins with museum staff since winter quarter. They aren't engineers, so a lot of the work has been translating their actual workflow into something we can build against and that they can maintain easilt. We presented an MVP at the end of winter, took feedback, scoped a few features down, and updated the project plan going into spring. The tagging logic in particular went through a couple of redesigns once curators saw it in action.
 
**Takeaways**
- Building for non-technical end users forces different tradeoffs than building for yourself. The curators care more about whether the tagging is *consistent* than whether the model is state-of-the-art.
- Real-world data is messier than benchmark data. We spent more time curating a dataset than we did tuning a model which we had to abandon anyways.
- Deadends are a natural outcome of the design process. As a developer, you must be ready to change courses or abandon ideas.
- A lot of "engineering" on a real client project is translation — between what the client says they want, what they actually need, and what we can ship in a quarter.
**Next Steps**
- Finalize the metadata suggestion logic and dynamic folder rules in Power Automate
- Run end-to-end testing with museum staff using their actual image backlog
- Write handoff documentation so the system stays maintainable after the team graduates
**Tech:** PyTorch · YOLOv8 · Azure · SharePoint · Power Automate
 
---

### 🛠️ Projects

**CareerFlo**

An internship tracker that helps UX/UI and SDE job seekers stay organized and interview-ready. Integrated the OpenAI API to power resume review feedback and mock interview simulations, giving students a lightweight alternative to expensive coaching tools.

- Built a React frontend with resume upload and AI-powered feedback generation
- Designed mock interview flows that adapt questions based on target role (UX vs. SDE)

**Tech:** JavaScript, React, HTML/CSS, OpenAI API

---

**AI Football Match Predictor**

Scraped and analyzed historical football match data to build a classifier that predicts match outcomes with ~70% accuracy. Focused on feature engineering from raw match stats and iterating on model selection to improve predictions.

- Collected and cleaned multi-season match data using web scraping with BeautifulSoup
- Engineered features from rolling averages, home/away splits, and head-to-head records
- Evaluated multiple classifiers with scikit-learn, achieving 70% prediction accuracy

**Tech:** Python, Pandas, BeautifulSoup, scikit-learn

---

**Local Business & Student Organization Websites**

Developed interactive websites for a local food review business and two UW student organizations, improving their online visibility and member engagement.

**Tech:** JavaScript, HTML/CSS

---

### 🧰 Tech I Work With

**Languages:** Python · Java · JavaScript / TypeScript · R · SQL · HTML/CSS

**Frameworks & Libraries:** React · scikit-learn · Pandas · NumPy · PyTorch

**Tools:** Git · Jupyter · Azure · SharePoint · Power Automate
