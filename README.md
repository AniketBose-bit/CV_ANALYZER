# CV_ANALYZER
The **CV Match Analyzer** is a tool designed to help users assess how well their CV aligns with job descriptions by analyzing and comparing key sections. Built using `Streamlit` for an interactive interface, the tool allows users to upload their CV in PDF format and input job description URLs.Using `pdfplumber`, it extracts text from the CV, and using `Selenium`, it scrapes job descriptions from the URLs supplied. Next, employing **TF-IDF (Term Frequency-Inverse Document Frequency)** vectorization, the similarity between the CV and job descriptions is computed; the match percentage is then determined using `scikit-learn} and **cosine similarity**. The application uses `Matplotlib` to visualize the top matched keywords and proposes new keywords to improve the CV. An analysis results CSV report is available for download by users.
