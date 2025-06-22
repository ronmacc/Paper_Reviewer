<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Chatbot</title>
</head>
<body>
  <h1>Chatbot</h1>

  <p>This is a <strong>Streamlit app</strong> that lets you upload PDFs and ask questions about documents.</p>

  <hr>

  <h2>Requirements</h2>
  <ul>
    <li>Python 3.10+</li>
    <li>Git</li>
    <li>Optional: <a href="https://code.visualstudio.com/">Visual Studio Code</a></li>
  </ul>

  <hr>

  <h2>Setup Instructions</h2>

  <h3>1. Clone the Repository</h3>
  <pre><code>git clone https://github.com/ronmacc/llm-chatbot.git
cd llm-chatbot</code></pre>

  <h3>2. Create a Virtual Environment</h3>
  <pre><code>python -m venv .venv</code></pre>

  <h3>3. Activate the Environment (Windows PowerShell)</h3>
  <pre><code>.venv\Scripts\Activate.ps1</code></pre>
  <p><em>If blocked, run this first:</em></p>
  <pre><code>Set-ExecutionPolicy -ExecutionPolicy RemoteSigned -Scope Process</code></pre>

  <h3>4. Install Required Packages</h3>
  <pre><code>pip install streamlit openai python-dotenv PyPDF2 langchain</code></pre>

  <hr>

  <h2>5. Add Your <code>.env</code> File</h2>
  <p>Create a file named <code>.env</code> in the root of the project with:</p>
  <pre><code>OPENAI_API_KEY=your_openai_key_here</code></pre>

  <hr>

  <h2>6. Run the App</h2>
  <pre><code>streamlit run app.py</code></pre>
  <p>The app will open in your browser at <a href="http://localhost:8501">http://localhost:8501</a>.</p>

  <hr>

  <h2>Deactivate When Done</h2>
  <pre><code>deactivate</code></pre>

  <hr>

  <h2>Optional: Save Requirements</h2>
  <p>To generate a <code>requirements.txt</code> file for others to install:</p>
  <pre><code>pip freeze > requirements.txt</code></pre>
  <p>Others can install with:</p>
  <pre><code>pip install -r requirements.txt</code></pre>

</body>
</html>
