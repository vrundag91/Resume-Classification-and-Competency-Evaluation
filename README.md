<h1>Resume-Classification-and-Competency-Evaluation</h1>
<h2>🚀 Project Overview</h2>
<p>This project provides an AI-powered resume analysis and competency evaluation system using GPT4All and Python-based text analysis.The system allows users to:</p>
<ul>
  <li>Upload a resume (PDF format)</li>
  <li>Analyze competencies based on predefined categories</li>
  <li>Visualize the competency distribution</li>
  <li>Ask AI-driven questions based on the resume content</li>
</ul>
<p>The model ensures that answers are strictly based on the uploaded resume and extracted competencies, making it a focused AI assistant for hiring, HR analysis, and professional profiling.</p>

<h2>📊 Sample Illustration</h2>
<p>Once the resume is analyzed, the system generates a pie chart representing the distribution of detected competencies.</p>
<p>In this example, competencies such as Organizing & Executing, Supporting, and Displaying Job-Related Skills are highlighted based on the resume content.</p>

<h2>🔧 Technologies Used</h2>

<h3>Core Components</h3>
<ul>
  <li>Python (for backend processing)</li>
  <li>PyMuPDF (fitz) – Extracts text from PDFs</li>
  <li>Regular Expressions (re) – Detects competencies based on keyword matching</li>
  <li>Matplotlib – Plots the competency pie chart</li>
  <li>GPT4All – Generates AI-driven responses based on resume text + competency analysis</li>
</ul>

<h3>Model Used</h3>
<p>Mistral-7B-Instruct (Q4_0.gguf) via GPT4All – Efficient for local inference without requiring cloud-based APIs.</p>

<h2>🛠️ Installation Guide</h2>

<h4>Step 1: Clone the Repository</h4>

```
git clone https://github.com/your-username/resume-analysis-competency.git
cd resume-analysis-competency
```

<h4>Step 2: Install Required Packages</h4>

```
pip install pymupdf matplotlib gpt4all
```

<h4>Step 3: Download the GPT4All Model</h4>
Download Mistral-7B-Instruct (Q4_0.gguf) from <a href="https://www.nomic.ai/gpt4all" target="_blank">GPT4All Model Page</a> and place it in the project folder.
