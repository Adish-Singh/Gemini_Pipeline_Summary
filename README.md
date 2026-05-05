🧠 Gemini Prompt Chaining Pipeline

A simple AI workflow pipeline built using Python and Google Gemini API that demonstrates multi-step prompt chaining:
Input → Summarize → Critique → Improve

🚀 Features:
🔹 Multi-step AI pipeline
🔹 Text summarization
🔹 Automated critique of generated output
🔹 Improved final response using feedback loop
🔹 Built using Gemini (gemini-3-flash)

🏗️ How It Works:
Summarization:
Converts input text into 3–5 bullet points

Critique:
Identifies missing or unclear information

Refinement:
Produces an improved, clearer summary

📦 Tech Stack:
Python
Google Gemini API
Google Colab (for development)

⚙️ Setup:
1. Install dependencies
pip install google-genai

3. Set up API key
If using Colab:
from google.colab import userdata
from google import genai
client = genai.Client(api_key=userdata.get("GEMINI_API_KEY"))

Or locally:
export GOOGLE_API_KEY=your_api_key_here

▶️ Usage:
summary, critique, improved = run_pipeline(text)
print(summary)
print(critique)
print(improved)

📌 Example Output:
Summary:
AI is transforming industries
Improves automation and decision-making
Raises ethical concerns

Critique:
Lacks detail on specific applications
Does not mention limitations

Improved Version:
More structured and complete explanation incorporating missing points

🎯 Purpose:
This project demonstrates:
Prompt engineering fundamentals
AI workflow design
Output refinement using chained reasoning

🔮 Future Improvements:
Add web interface (Flask/React)
Support file inputs (PDF, articles)
Add style/tone customization
Integrate with larger AI systems

📂 Project Structure
.
├── README.md
└── Gemini_Text_Summary_Pipeline.ipynb

🧑‍💻 Author:
Code written by Adish Singh
Built as part of an AI systems learning project.
