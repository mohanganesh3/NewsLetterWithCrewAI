# NewsletterGen: Your AI-Powered Newsletter Creation Suite 📰

## Mission: Revolutionizing Newsletter Creation with AI 🚀

Welcome to **NewsletterGen**, the ultimate toolkit that combines the power of AI with intelligent workflows to streamline and enhance your newsletter creation process. Whether you're a marketing team, a content creator, or a business looking to engage your audience, NewsletterGen is designed to optimize your content strategy, automate tedious tasks, and deliver high-quality newsletters effortlessly. ✉️✨

Think of NewsletterGen as your **personal AI-powered newsletter team**, ready to provide you with the tools and insights you need to create compelling newsletters. This project uses cutting-edge AI technologies to research topics, generate engaging content, and compile it into professional HTML newsletters. 📈💻

## 🧠 What NewsletterGen Can Do For You

NewsletterGen is packed with features that make newsletter creation efficient and effective:

*   **📊 Data-Driven Research:** Uncover the latest news and trends on any topic with AI-powered web research.
*   **📝 AI-Generated Content:** Generate summaries, rewrites, and contextual explanations for news articles.
*   **🎨 Automated HTML Compilation:** Compile researched and edited content into a ready-to-send HTML newsletter using a customizable template.
*   **⚙️ Streamlined Workflow:** Automate the entire newsletter creation process from research to final output.

---

## 🌐 Project Structure – Your Newsletter Strategy, Simplified

The NewsletterGen project is designed to be modular, scalable, and easy to use. Here’s a quick overview of its structure:

```
NewsletterGen/
├── knowledge/                   # Stores user preferences or other knowledge base files
│   └── user_preference.txt
├── logs/                        # Stores output logs from each stage of the process
│   └── 2024-12-15_12-00-47_research_task.md
│   └── 2024-12-15_12-00-47_newsletter_task.html
│   └── 2024-12-15_12-00-47_edit_task.md
├── src/
│   ├── newsletter/              # Core newsletter generation modules
│   │   ├── config/              # Configuration files (agents, tasks, template)
│   │   │   ├── agents.yaml
│   │   │   ├── tasks.yaml
│   │   │   └── newsletter_template.html
│   │   ├── tools/               # Custom tools for research and content processing
│   │   │   ├── __init__.py
│   │   │   └── research.py
│   │   ├── __init__.py
│   │   ├── crew.py              # Defines the CrewAI agents and tasks
│   │   └── main.py              # Main entry point for running the newsletter generation
│   ├── gui/                     # Streamlit app for user interaction
│   │   └── app.py
├── .env                         # Environment variables (API keys)
├── .gitignore
├── poetry.lock
├── pyproject.toml
└── README.md                    # You’re reading this! 😉
```

---

## 💥 Why NewsletterGen?

### 1. AI-Powered Efficiency:

Imagine having a dedicated team of AI agents working 24/7 to create your newsletters. NewsletterGen automates the research, content generation, and compilation processes, saving you valuable time and resources.

### 2. Data-Driven Content:

NewsletterGen leverages AI to find the most relevant and up-to-date news on your chosen topic, ensuring that your newsletters are informative and engaging.

### 3. Customizable Templates:

Use your own HTML templates to maintain brand consistency and create visually appealing newsletters.

### 4. Streamlined Workflow:

From topic selection to final HTML output, NewsletterGen provides a seamless and automated workflow for newsletter creation.

---

## 🌟 Features That Will Make Your Newsletters Shine

*   **📊 Comprehensive Research:** Stay informed with AI-driven web research that identifies key news stories and trends.
*   **📝 Engaging Content Generation:** Create compelling summaries, rewrites, and contextual explanations to enhance your newsletter content.
*   **🎨 Automated HTML Compilation:** Easily compile your content into professional-looking HTML newsletters using customizable templates.
*   **⚙️ Flexible Configuration:** Customize the behavior of your AI agents and tasks using configuration files.
*   **🖥️ User-Friendly Interface (Streamlit):** Interact with the newsletter generation process through a simple and intuitive Streamlit web app.

---

## 🚀 Getting Started with NewsletterGen

Follow these steps to start using NewsletterGen:

1.  **Clone the Repository:**

    ```bash
    git clone <your_repo_url>
    ```

2.  **Install Dependencies:**

    Use Poetry to manage project dependencies:

    ```bash
    pip install poetry
    poetry install
    ```

3.  **Set Up Environment Variables:**

    Create a `.env` file in the root directory and add your API keys:

    ```
    EXA_API_KEY=your_exa_api_key
    GOOGLE_API_KEY=your_google_api_key
    ```

4.  **Run the Newsletter Generation:**

    ```bash
    poetry run newsletter_gen
    ```

## 🏆 Achieve Newsletter Mastery

With NewsletterGen, you're not just sending out emails; you're delivering valuable, engaging content that keeps your audience informed and connected.

*   **Save Time and Resources:** Automate the tedious aspects of newsletter creation.
*   **Deliver High-Quality Content:** Provide your audience with informative and engaging news.
*   **Maintain Brand Consistency:** Use customizable templates to reflect your brand identity.

## 🤝 Contributing

We welcome contributions from anyone passionate about AI, newsletter creation, or automation.

1.  Fork the repository.
2.  Create a new branch (`git checkout -b feature-name`).
3.  Commit your changes (`git commit -am 'Add new feature'`).
4.  Push your changes (`git push origin feature-name`).
5.  Submit a pull request.
  
## 📬 Get in Touch

*   Author: Mohan Ganesh Gottipati
*   Email: mohanganesh165577@gmail.com
*   GitHub: mohanganesh3
