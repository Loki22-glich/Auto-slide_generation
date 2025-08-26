# Auto Slide Generation (AI-Powered)

This project **automatically generates professional PowerPoint presentations** using AI.  
It performs:
- **Web Search** for topic research (DuckDuckGo Search)
- **Content Generation** using OpenAI's GPT model
- **Branded PowerPoint Deck Creation** with custom design and formatting

---

## 🚀 Features
✔️ AI-generated structured slide content  
✔️ Web search integration for relevant information  
✔️ Professional slide design with branding  
✔️ Fully automated PowerPoint deck creation (`.pptx`)

---

## 🛠️ Tech Stack
- **Python 3.9+**
- [python-pptx](https://python-pptx.readthedocs.io/) – for PowerPoint generation
- [DuckDuckGo Search (ddgs)](https://pypi.org/project/ddgs/) – for web search
- [OpenAI API](https://platform.openai.com/) – for content generation

---

## 📂 Project Structure
📦 Auto-slide-generation
┣ 📜 auto_deck.py # Main script
┣ 📜 requirements.txt # Required Python packages
┣ 📜 README.md # Project documentation

yaml
Copy code

---

## 🔧 Installation
1. Clone the repo:
   ```bash
   git clone https://github.com/Loki22-glich/Auto-slide_generation.git
   cd Auto-slide_generation
Install dependencies:

bash
Copy code
pip install -r requirements.txt
Set your OpenAI API key as an environment variable:

bash
Copy code
export OPENAI_API_KEY="your_api_key_here"   # Mac/Linux
setx OPENAI_API_KEY "your_api_key_here"     # Windows
▶️ Usage
Run the script with your desired topic:

bash
Copy code
python3 auto_deck.py "Artificial Intelligence in Healthcare"
✅ The script will:

Search the web for your topic

Generate a 7-slide deck outline

Create a branded PowerPoint file

The output file will be saved as:

Copy code
Artificial_Intelligence_in_Healthcare_Branded_Deck.pptx
📋 Example Output
Slide 1: Title

Slide 2: Overview

Slides 3–6: Key points, trends, arguments

Slide 7: Conclusion

⚙️ Requirements
Create a requirements.txt with:

Copy code
python-pptx
ddgs
openai
Install with:

bash
Copy code
pip install -r requirements.txt
✅ To-Do / Future Enhancements
Add image search & auto-insert images into slides

Support custom themes

Multi-language support
