# 🧠 Reddit User Persona Generator (Gemini + Reddit API)

This is a Python-based CLI tool that scrapes a Reddit user's public content and uses **Google's Gemini LLM** to generate a detailed UX-style **user persona**, backed by citations from their Reddit activity.

---

## ✅ How to Use

### 1️⃣ Clone the repository

```bash
git clone https://github.com/your-username/reddit-persona-generator.git
cd reddit-persona-generator


2️⃣ Create and activate a virtual environment
# macOS / Linux
python3 -m venv venv
source venv/bin/activate

# Windows
python -m venv venv
venv\Scripts\activate

3️⃣ Install dependencies

pip install -r requirements.txt

4️⃣ Set up your API credentials

Copy the example environment file and fill it in:
cp .env.example .env


Edit .env and add your keys:


GOOGLE_API_KEY=your_google_api_key
REDDIT_CLIENT_ID=your_reddit_client_id
REDDIT_CLIENT_SECRET=your_reddit_client_secret
REDDIT_USER_AGENT=your_custom_user_agent


5️⃣ Run the script
Use a Reddit profile URL:


python main.py https://www.reddit.com/user/<reddit_username>/


✅ A persona file will be saved to the personas/ folder like:


personas/kojied_persona.txt

