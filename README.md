# Welcome to Harshita's GitHub Page!

👋 Hi there! I'm Harshita Mandalika, a Master's in Computer Science graduate from Texas A&M University with a strong interest in Machine Learning, Deep Learning, Data Analytics, Natural Language Processing, and Recommender Systems.

I am passionate about building intelligent, data-driven systems that turn complex information into useful insights and support better decision-making. My projects focus on applied AI, information retrieval, semantic matching, product feedback analytics, recommender systems, multimodal learning, and analytics-driven applications.

🎓 During my Master's at Texas A&M University, I worked on projects involving research paper recommendation, NLP-based document matching, product review analysis, multimodal prediction, and AI-powered analytics tools.

⭐ My research paper, [**"Prediction of Dengue Fever using Machine Learning,"**](https://www.inderscienceonline.com/doi/abs/10.1504/IJAISC.2023.137356) was published in the **International Journal of Artificial Intelligence and Soft Computing** by Inderscience.

🔍 I am currently exploring research directions in **Recommender Systems, Information Retrieval, Trustworthy Personalization, Privacy-Preserving Machine Learning, Responsible AI, and User Preference Modeling**.

## Skills

- 💻 **Programming Languages:** Python, SQL, JavaScript, HTML, CSS
- 🤖 **Machine Learning & AI:** Machine Learning, Deep Learning, Predictive Modeling, Classification, Regression, Clustering, Feature Engineering, Model Evaluation
- 🔎 **NLP, Retrieval & Recommendation:** Natural Language Processing, Information Retrieval, Recommender Systems, Ranking, Semantic Similarity, Collaborative Filtering, Content-Based Filtering, Retrieval-Augmented Generation
- 🧰 **Libraries & Frameworks:** PyTorch, Scikit-learn, Pandas, NumPy, Matplotlib, Seaborn, Flask, FastAPI, Streamlit
- 🟰 **Mathematics & Statistics:** Linear Algebra, Calculus, Discrete Mathematics, Probability, Statistics
- 📊 **Data & Visualization:** Data Analysis, Data Mining, Data Visualization, Tableau, Excel
- 🌈 **Soft Skills:** Communication, Critical Thinking, Problem Solving, Analytical Thinking, Attention to Detail, Time Management

## Projects

Here are some of the projects I have worked on across machine learning, NLP, recommender systems, information retrieval, and data analytics:

1. **Medical Literature RAG + Eval Dashboard**
   - Built a hybrid RAG pipeline over 574 PubMed abstracts achieving RAGAS faithfulness of 0.90 and answer relevancy of 0.60 across 25 benchmark queries spanning 6 clinical conditions.
   - Implemented Reciprocal Rank Fusion combining ChromaDB dense vector search and BM25 sparse retrieval with metadata filtering by condition and publication year.
   - Built a live eval dashboard in Streamlit surfacing 4 RAGAS metrics per query with gauge charts and MLflow-backed historical trend charts; tracked 10 metrics per run across all pipeline executions.
   - 🔗 [View on GitHub](https://github.com/harshitamandalika/medical-rag)

2. **Clinical Note Summarization**
   - Fine-tuned Mistral 7B on clinical note summarization using QLoRA/PEFT, improving ROUGE-L from 17.2% to 60.8% over the few-shot baseline across 100 held-out clinical notes.
   - Reduced trainable parameters by 99.9% (7.2B to 6.8M) using LoRA adapters, enabling training on a single T4 GPU via 4-bit NF4 quantization.
   - Evaluated fine-tuned model using ROUGE and BERTScore in a three-way comparison against zero-shot and few-shot baselines.
   - 🔗 [View on GitHub](https://github.com/harshitamandalika/clinical-note-summarization)

3. **Prediction of Dengue Fever**
   - Built ML models to predict dengue fever cases using preprocessing, feature selection, and hyperparameter tuning, finding that climatic factors alone were insufficient for accurate prediction. This work has been **published** in the **Inderscience Journal- 'International Journal of Artificial Intelligence and Soft Computing'**.
   - 🔗 [View on GitHub](https://github.com/harshitamandalika/Prediction-of-Dengue-Fever-using-Machine-Learning./tree/main)

4. **Send Me Studies**
   - A personalized research paper recommender that ranks papers using BM25 similarity and summarizes top results with LLMs. Sends recommendations via email and updates user profiles based on feedback extracted from email replies. Profiles evolve over time using liked abstracts and LLM-refined interests, helping generate increasingly personalized and relevant recommendations.
   - 🔗 [View on GitHub](https://github.com/harshitamandalika/ISR_Project)
     
5. **Resume IQ**
   - Built an NLP-based ATS optimizer that compares PDF resumes with job descriptions and generates alignment scores, matched/missing keywords, validated skills, and bullet-level revision feedback.
   - Developed a modular pipeline using PyMuPDF, Sentence-BERT, KeyBERT, and rule-based NLP to extract resume sections, measure semantic alignment, validate skill evidence, and evaluate bullet quality.
   - 🔗 [View on GitHub](https://github.com/harshitamandalika/ResumeIQ---NLP-Project)

6. **E-commerce Analytics Copilot**
   - Built an analytics copilot that translates natural-language questions into SQL, chart recommendations, and business insights over 541K+ e-commerce transactions.
   - Used LangChain and a router-based LangGraph workflow to handle explain-only, SQL-only, and SQL-plus-chart requests with SQL validation and retry handling.
   - 🔗 [View on GitHub](https://github.com/harshitamandalika/Business-Analytics-Copilot)

7. **Prioritix AI**
   - Built an NLP-based analytics system to convert 10K+ app reviews into structured user feedback signals for product and engineering decision-making.
   - Applied sentiment/urgency classification, TF-IDF, and K-Means clustering to identify recurring user pain-point themes from high-urgency negative reviews.
   - 🔗 [View on GitHub](https://github.com/harshitamandalika/prioritix-ai)

8. **VitaFin: Health and Budget Tracker Dashboard**
   - An interactive dashboard that brings both health and budget visualizations together in one place.
   - Built with Python, Flask, JavaScript, Vue.js, and Chart.js, it allows users to input personal data and view dynamic, real-time trends through a clean, responsive interface—demonstrating full-stack development and insightful data integration.
   - 🔗 [View on GitHub](https://github.com/ApurvaMandalika9/DataVizProject-VitaFin)
   
9. **Meal Nutrition Analysis using Multimodal data**
   -  Developed a multimodal deep learning model combining CGM time-series data, meal images, and tabular health features to estimate lunch calories.
   -  Fused modality-specific embeddings into a joint representation, achieving 0.3374 RMSRE on unseen test data.
   - 🔗 [View on GitHub](https://github.com/harshitamandalika/Multimodal-Calorie-Predictor)

10. **Improving CLIP Training for Multimodal Learning**
   - Developed advanced training algorithms to enhance CLIP model performance in retrieval and zero-shot classification tasks and achieved an average score of 19.12.
   - The approach achieved 2nd place in a competition, showcasing innovations in optimizing multimodal learning.

11. **Sleep Health and Lifestyle EDA**
   - Exploratory data analysis on 400 lifestyle records to uncover the true drivers of sleep quality — revealing that stress (r = −0.90) far outweighs physical activity (r = 0.02) as a predictor, with additional insights by occupation, age, and cardiovascular markers.
   - Built with Python (pandas, seaborn, matplotlib).
   - 🔗 [View on GitHub](https://github.com/harshitamandalika/Sleep-Health-and-Lifestyle-EDA)
     
12. **Brain Tumor Detection**
    - Proposed three methods to detect Brain tumors from MRI scans.
    - The first method involved detecting brain tumors using image processing alone. This included the following: pre-processing, filtering, image segmentation, and morphological operations. The second and third methods involved using Gaussian Blur and Canny Edge Detection techniques, followed by training on CNN.

13. **Credit Card Fraud Detection**
    - Worked with a highly imbalanced and large dataset for classifying credit card transactions as fraudulent and non-fraudulent.
    - Performed extensive data preprocessing, data balancing and training of an ML model.
    - Obtained an accuracy of 99.999% and achieved ‘0’ false negatives. Further, used Apache Spark to reduce training time.

14. **Detection of Lung Diseases using Deep Learning**
    - Developed a deep learning model to classify chest X-rays into 14 lung disease categories and accurately predicted cases with no pathological findings.

15. **Bank Marketing Segmentation**
    - Predicted whether a particular customer will opt for term deposits.
    - Used Machine Learning to train the algorithms on the dataset. Several pre-processing steps are applied to the dataset and refined for future use. Firstly, the outliers in the dataset are removed and then a label encoder is used to transform the data. Then, the data is balanced and trained using ML algorithms.
    - 🔗[View on Github](https://github.com/harshitamandalika/Bank-Marketing-Segmentation)

16. **Leaf Disease Detection**
    - Explored the PlantVillage dataset and used it to classify leaf images into healthy and diseased.
    - Convolutional Neural Networks is used for training and classification of these images.

17. **Employees Database using SQL**
    - Employees database consists of 6 tables namely, employees, dept_manager, departments, titles, salaries, and dept_emp.
    - Used SQL queries to extract the necessary information.
    - 🔗[View on Github](https://github.com/harshitamandalika/Employees-Database-using-SQL)
     
18. **Bank Customers Analysis using Tableau**
    - Built an interactive Tableau dashboard to analyze bank customer demographics across job type, age group, gender, and region, helping identify high-potential customer segments for targeted marketing and improved customer conversion.
    - 🔗[View on Github](https://github.com/harshitamandalika/Bank-Customers-Analysis)

19. **Analyzing Customer Churn using Power BI**
    - Retaining existing customers is more cost-effective than acquiring new ones, making churn reduction a top priority for many companies. This project leverages Power BI to analyze the key reasons behind customer churn.
    -  🔗[View on Github](https://github.com/harshitamandalika/Analyzing-Customer-Churn-using-PowerBI)

## Connect with Me

<!-- <a href="https://github.com/your-username" target="_blank"><img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white"></a> -->
<a href="https://www.linkedin.com/in/harshita-mandalika/" target="_blank"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white"></a>
<a href="mailto:harshitamandalika029@gmail.com" target="_blank"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white"></a>


Feel free to explore my repositories and connect with me! Whether you're interested in collaborating on a project, discussing the latest trends in machine learning, or just grabbing a virtual coffee, I'm always open to new connections and exciting opportunities. Let's innovate together and make a positive impact through technology! 🚀✨
