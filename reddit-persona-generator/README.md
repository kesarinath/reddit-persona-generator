# 🧠 Reddit User Persona Generator (Gemini + Reddit API)

This is a Python-based CLI tool that scrapes a Reddit user's public content and uses **Google's Gemini LLM** to generate a detailed UX-style **user persona**, backed by citations from their Reddit activity.

---

## ✅ How to Use

### 1️⃣ Clone the repository

```bash
git clone https://github.com/your-username/reddit-persona-generator.git
cd reddit-persona-generator
cd reddit-persona-generator



2️⃣ Create and activate a virtual environment
# macOS / Linux
```python
python3 -m venv venv
source venv/bin/activate

# Windows
```python
python -m venv venv
venv\Scripts\activate

3️⃣ Install dependencies
```python
pip install -r requirements.txt

4️⃣ Set up your API credentials for reddit and gemini

1.Sign in to your Reddit account
2. Visit the Developer Portal
3. Scroll Down to "Developed Applications"
4. Fill the Form and Get Your Credentials

Once the app is created, you’ll see:

      client ID → The string below the app name (not labeled)
      client secret → Displayed next to "secret"
      user agent → You define this yourself in your script


Edit .env and add your keys:

```bash
GOOGLE_API_KEY=your_google_api_key
REDDIT_CLIENT_ID=your_reddit_client_id
REDDIT_CLIENT_SECRET=your_reddit_client_secret
REDDIT_USER_AGENT=your_custom_user_agent


5️⃣ Run the script
Use a Reddit profile URL:

```bash
python main.py https://www.reddit.com/user/<reddit_username>/


✅ A persona file will be saved to the personas/ folder like:


personas/kojied_persona.txt

