🤖 AI News Agent | Farsi Tech News Summarizer 📡 <br>
Welcome to AI News Agent, an automated system designed to fetch the latest AI and technology news from predefined websites and intelligently summarize them into concise, declarative Farsi snippets.

📌 Features : <br>

🔍 News Scraping: Extracts articles from trusted sources using RSS feeds or HTML parsing. <br>
🧠 LLM-based Summarization: Generates 2–3 line Farsi summaries per article using advanced language models. <br>
🌐 Automatic Source Discovery: Optionally discovers new relevant sources (configurable). <br>
💌 Email Delivery: Sends a daily news digest to your inbox for easy sharing. <br>
🗓️ Daily Automation: Runs a scheduled pipeline to keep your content fresh. <br>


📁 Project Structure :
``` bash
ai-news-agent/
├── app/
│   ├── agents/                # Core agents: crawler, summarizer, etc.
│   ├── pipelines/             # Daily automation pipeline
│   ├── data/                  # Raw HTML, summaries, logs
│   ├── emailer/               # Email integration module
│   ├── config/                # Sources list, API keys, settings
│   └── utils/                 # Helpers, formatters, etc.
├── tests/                     # Unit tests
├── notebooks/                 # Experiments (e.g., summarization quality)
├── main.py                    # Entry point for daily run
├── requirements.txt           # Python dependencies
├── .env                       # Secrets and API keys (excluded from Git)
└── README.md                  # You're reading it 😉
```

🧠 How It Works
The main.py script orchestrates a daily pipeline that:

Crawls: Fetches the latest articles from specified tech/AI sources.
Summarizes: Uses an LLM (e.g., GPT, DeepSeek) to create concise Farsi summaries.
Formats: Compiles a clean digest in the format [Title + 2–3 Line Summary + Link].
Delivers: Sends the digest to your email inbox for easy sharing.

Tailored for Telegram channel: `Dunijet_ai` 

🤝 Contributing
Contributions are welcome! Whether you want to enhance the summarization agent, add new sources, or improve Farsi formatting, feel free to submit a pull request 💡.


👨‍💻 Author
Built with 💜 by Ali Moeinian
