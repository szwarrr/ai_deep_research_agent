# Deep Research Agent with OpenAI Agents SDK & Firecrawl

A next-generation research assistant that combines **OpenAI’s Agents SDK** with **Firecrawl’s deep research tools** to deliver comprehensive, high-quality insights on any topic or question.

## Key Features

* **Deep Web Research** – Automatically searches the internet, extracts relevant content, and synthesizes results.
* **Advanced Analysis** – Uses OpenAI Agents to enrich findings with context, explanations, and insights.
* **User-Friendly Interface** – Streamlit-based, clean, and intuitive for smooth interaction.
* **Report Export** – Download research results as Markdown files for easy sharing.

## Workflow

1. **Input** – Provide a research topic and your API credentials.
2. **Research** – Firecrawl searches the web, collects, and filters relevant data.
3. **Initial Report** – Generates a concise summary of the findings.
4. **Enhancement** – A second AI agent deepens the report with detailed analysis and context.
5. **Output** – Displays the enhanced report and offers a download option.

## Requirements

* Python 3.8+
* OpenAI API key
* Firecrawl API key
* Dependencies listed in `requirements.txt`

## Installation

```bash
# Clone the repository
git clone https://github.com/Shubhamsaboo/awesome-llm-apps.git
cd advanced_ai_agents/single_agent_apps/ai_deep_research_agent

# Install dependencies
pip install -r requirements.txt
```

## Usage

1. Launch the app:

   ```bash
   streamlit run deep_research_openai.py
   ```
2. Add your **OpenAI API key** and **Firecrawl API key** in the sidebar.
3. Enter your topic in the main input box.
4. Click **Start Research** and wait for processing.
5. View and download the enhanced research report.

## Example Topics

* Latest developments in quantum computing
* Impact of climate change on marine ecosystems
* Advancements in renewable energy storage
* Ethical considerations in artificial intelligence
* Emerging trends in remote work technologies

## Technical Overview

The app uses two AI agents:

1. **Research Agent** – Gathers broad and deep information using Firecrawl’s multi-iteration search and extraction system.
2. **Elaboration Agent** – Expands the initial summary with explanations, case studies, examples, and real-world applications.

