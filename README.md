# Saikumar Reddy Naidu - Portfolio

Personal portfolio website showcasing my work as a Data Engineer specializing in Python, SQL, AWS, and API Development.

🔗 **Live Site**: [snaidu20.github.io](https://snaidu20.github.io)

## 👨‍💻 About Me

I'm a Data Engineer working in healthcare, focused on making complex clinical and device data reliable, accessible, and useful for better decisions. Currently working at Upsilonsoft LLC (Client: Bristol Myers Squibb) on IoT-enabled patient vitals streaming and early-risk detection systems.

**Tech Stack**: Python | SQL | AWS | API

## 🚀 Featured Projects

### 🌊 MicroPlastiNet – Multi-modal Microplastic Detection & Source Attribution
**Graph ML & Environmental AI • 2026**
- End-to-end engineering prototype for microplastic detection, classification, and source attribution along coastal Georgia rivers
- Combines IoT edge node (ESP32-CAM with turbidity, TDS, NIR sensors), CNN vision classifier, 1D-CNN spectral classifier, and Graph Neural Network on a 200-node hydrological flow graph
- Uses Integrated Gradients on the GNN to trace concentration spikes back through river networks (Ogeechee, Savannah, Altamaha) to upstream sources
- Includes Plotly Dash compliance dashboard, LLM-powered audit report generator, and cybersecurity layer (HMAC-SHA256, replay protection, key rotation) with 6/6 adversarial tests passing
- Runs on physics-informed synthetic data; designed to plug in real NOAA NCEI, Rochman Lab spectra, ERA5, and HydroSHEDS data when access is granted
- **Tech Stack**: Python, PyTorch, PyTorch Geometric, GNN, CNN, Plotly Dash, IoT, Cryptography
- [💻 GitHub](https://github.com/snaidu20/MicroPlastiNet) | [🚀 Live Dashboard](https://naidusai-microplastinet.hf.space)

### 🛡️ PolicyGraphAudit-RT – Runtime-Aware Privacy Compliance Auditor
**Graph ML & Privacy Engineering • 2026**
- Heterogeneous graph neural network that fuses privacy policy prose, Play Store data-safety labels, and embedded third-party SDKs into a tri-partite knowledge graph per Android app
- 8 node types and 11 edge relations linking policy claims to label fields to inferred SDK behavior
- Trains an R-GCN under 30% edge masking to classify policy-vs-practice discrepancies into four classes: CONSISTENT, POLICY_LABEL_MISMATCH, OVER_DISCLOSURE, UNDECLARED_COLLECTION
- Achieves **Macro F1 = 0.956** on held-out test set (39 apps, 521 labeled pairs), outperforming text-only and policy-only baselines
- Generates 252 per-app PDF audit reports with ranked discrepancies, policy evidence quotes, and SDK chains; ships with Plotly Dash dashboard, SDK heatmap, and model card
- **Tech Stack**: Python, PyTorch, PyTorch Geometric, R-GCN, Heterogeneous GNN, NLP, Plotly Dash
- [💻 GitHub](https://github.com/snaidu20/PolicyGraphAudit-RT) | [🚀 Live Dashboard](https://policygraphaudit.pplx.app)

### 🩻 MedGemma Medical Image Analyzer
**AI & Medical Imaging • 2026**
- Developed an AI-powered chest X-ray analyzer using Google's MedGemma foundation model
- Auto-detects imaging modality and generates detailed radiology reports
- Reports are tailored for both clinicians and patients
- Deployed via GPU-backed cloud environments for real-time inference
- **Tech Stack**: Google MedGemma, Medical Imaging, AI/ML, Radiology, Cloud GPU
- [💻 GitHub & Demo Video](https://github.com/snaidu20/Google_medgemma_medical_image_analyzer/tree/main/medgemma-chest-xray-analyzer)

### 🧬 TrialMatchAI – Clinical Trial Matching AI System
**AI & Healthcare • 2025**
- AI-powered system that matches patients to suitable clinical trials
- Analyzes patient data (age, diagnoses, lab results) against active trials from ClinicalTrials.gov
- Uses machine learning and semantic search to rank trials by predicted eligibility
- Provides explainable reports to support physician decision-making
- Automates trial matching to speed up enrollment and connect patients with life-saving treatments
- **Tech Stack**: AI/ML, NLP, Semantic Search, Healthcare
- [💻 GitHub](https://github.com/snaidu20/Clinical-Trial-Matching-AI-Agent/tree/main/trialmatch-ai)

### 🌱 IoT-Based Smart Irrigation System
**Published Research • 2020**
- Designed IoT irrigation system using sensors and wireless communication
- Optimized water flow based on real-time soil moisture data
- Unique approach using Solenoid valves integrated with sensor data to control water supply directly (turning ON/OFF water supply rather than motor)
- **Tech Stack**: Arduino, Sensors, IoT
- [📄 Read Publication](https://www.ijrte.org/portfolio-item/A1979059120/)

### 📦 Global Supply Chain Demand Pressure Monitoring System
**Supply Chain Analytics • 2026**
- Developed system tracking real-time global availability of critical part numbers
- Aggregates data from open market sources (TrustedParts, FindChips)
- Combines with internal demand signals to compute Demand Pressure Index
- Guides procurement decisions: buy, hold, delay, or expedite
- Enables proactive and data-driven supply planning
- **Tech Stack**: Power BI, Python, Analytics, API
- [📊 Dashboard](https://lnkd.in/eNMwrD9n) | [💻 GitHub](https://lnkd.in/ezfRFHH7)

### 📍 Location-Based Student Attendance System
**Web App Development • Security • 2022**
- Secure attendance system verifying physical presence through GPS
- Matches student and faculty locations with time-based passcode
- Prevents proxy and remote check-ins
- **Tech Stack**: GPS, Mobile Development, Security, Authentication
- [🎥 Demo & Docs](https://drive.google.com/drive/folders/10vj8j9zrqjEkeGk2CrLhaeLHK9vO9jJb?usp=sharing) | [💻 GitHub](https://github.com/snaidu20/StudentAttendance)

### 🏥 IoT Patient Vitals Streaming Pipeline
**Healthcare IoT • Bristol Myers Squibb**
- Building real-time data pipelines for medical device streams
- Early-risk detection and patient monitoring
- **Tech Stack**: AWS, Medical IoT, Real-time, Healthcare

### 💼 Enterprise Data Lake Modernization
**Cloud Migration • Progress Solutions**
- Migrated on-prem datasets to cloud (AWS S3/Azure)
- Built automated ETL pipelines
- Reduced pipeline run times by 40%
- **Tech Stack**: AWS S3, PySpark, ETL, Azure

## 🛠️ Technical Skills

### Data Engineering
- **Languages**: Python, SQL, Scala, PySpark
- **ETL**: Informatica, Collibra, Custom Pipelines
- **Big Data**: Apache Spark, EMR

### Cloud & Infrastructure
- **AWS**: S3, EMR, Lambda, Glue
- **Azure**: Blob Storage, Data Lake
- **Certifications**: AWS Certified Data Engineer - Associate

### IoT & Healthcare
- **Hardware**: Arduino, Raspberry Pi
- **Medical IoT**: Patient Vitals Monitoring, Sensor Integration
- **Real-time Streaming**: Healthcare Device Data Pipelines

### Analytics & Visualization
- **BI Tools**: Power BI, Excel
- **Data Governance**: Informatica, Collibra
- **Analytics**: Predictive Modeling, Statistical Analysis

## 💼 Professional Experience

### Data Engineer | Upsilonsoft LLC (Bristol Myers Squibb)
**May 2025 – Present**
- Analyze large-scale patient & IoT-healthcare data for clinical workflow improvements
- Build data pipelines ingesting sensor-driven medical device streams
- Collaborate on connected health system initiatives with device telemetry
- Develop automated insights for smarter diagnostics and patient-care decisions

### Data Engineer Intern | Progress Solutions
**Jun 2024 – May 2025**
- Migrated multiple on-prem datasets into cloud data lake (AWS S3/Azure)
- Built automated ETL pipelines using Python, SQL, and PySpark
- Reduced pipeline run times by 40% through optimization
- Implemented schema evolution and metadata tracking

### Project Engineer | Wipro
**Apr 2021 – Jul 2022**
- Designed dashboards showing system health and workflow bottlenecks
- Developed predictive model for identifying overload conditions
- Implemented automation reducing processing time by 30%
- Integrated data signals from multiple internal systems

## 🎓 Education

### Master of Science in Computer Science
**Florida Atlantic University** | 2024
- Internet of Things, Artificial Intelligence, Deep Learning
- NLP, AI in Healthcare, Information Theory
- Systems & Network Administration

### Bachelor of Engineering in Electronics and Communication
**Anna University** | 2020
- Wireless Communication, Antenna & Wave Propagation
- Microcontrollers, Embedded Systems, Signal Processing

## 📜 Certifications

- ☁️ AWS Certified Data Engineer - Associate
- 📊 PMP - Project Management Professional
- 📈 Power BI (Pragmatic Works)
- 🤖 AI Foundations: Thinking Machines (LinkedIn Learning)
- 💰 Financial Modeling & Forecasting (LinkedIn Learning)
- 📊 Career Essentials in Business Analysis (Microsoft & LinkedIn)

## 📊 Key Achievements

- 🔌 **2** Published IoT Research Projects
- 📊 **40%** Pipeline Runtime Optimization
- ☁️ AWS Certified Data Engineer
- 🎓 **6** Professional Certifications

## 📫 Contact

- 📧 Email: [snaidu2022@fau.edu](mailto:snaidu2022@fau.edu)
- 📱 Phone: [+1 912-306-7209](tel:+19123067209)
- 💼 LinkedIn: [linkedin.com/in/reddysaiu](https://www.linkedin.com/in/reddysaiu)
- 📍 Location: Winder, Georgia, US

## 🌐 Website Technology

This portfolio is built with:
- **Frontend**: HTML5, CSS3 (Vanilla)
- **Hosting**: GitHub Pages
- **Design**: Custom responsive design with modern CSS
- **Features**: Smooth scrolling, responsive navigation, project showcase

## 📄 License

© 2026 Saikumar Reddy Naidu. All Rights Reserved.

---

**Last Updated**: April 2026
