# 📰 Fake News Generator & Detector using AI  
*A dual-system AI tool: Generate fake news with GPT-2 and detect it with a calibrated classifier.*    

## 🌟 Features  
- **🤖 GPT-2 Generator**: Creates realistic/satirical fake news headlines.  
- **🔍 Fake News Detector**: TF-IDF + Naive Bayes classifier with confidence scoring.  
- **🎮 Gradio UI**: Interactive web interface for real-time testing.  
- **⚡ Fast Inference**: End-to-end pipeline in one notebook.  

## 🚀 Quick Start  
1. **Clone the repo**:  
   ```bash
   git clone https://github.com/yourusername/fake-news-ai.git
   cd fake-news-ai
Install dependencies:

bash
pip install -r requirements.txt
Launch the app:

Run the Jupyter notebook:

bash
jupyter notebook fake_news_clean_final.ipynb
Or convert to a script and run:

bash
python fake_news_clean_final.py

Try it out:

Enter a prompt (e.g., "Government mandates smartphone sleep mode").

Click Submit to generate and classify the headline.

📂 Project Structure
text
.
├── fake_news_clean_final.ipynb    # Main notebook (Generator + Detector + UI)
├── fake_news_clean_final.py       # (Optional: Converted script)
├── requirements.txt               # Dependencies
├── assets/                        # Demo images
│   └── demo_screenshot.jpg        # Screenshot of Gradio UI
└── README.md
🛠️ Technologies
Generator: GPT-2 (transformers)

Detector: scikit-learn (TF-IDF + MultinomialNB)

UI: gradio

Backend: torch, pandas

📊 Example Output
Prompt	Generated Headline	Detection Result
"Government bans smartphones after 10PM"	"Government Approves Mandatory Smartphone Sleep Mode..."	FAKE (61.63% confidence)
⚠️ Ethical Disclaimer
Warning: This project is for research/education only.

Misusing generative AI to spread misinformation is harmful.

Always label AI-generated content clearly.

📜 License
MIT

🙌 Credits
Developer: Muskan Varshney

Guide: Mr. Gaurav Singh

Libraries: Hugging Face, Gradio, scikit-learn
