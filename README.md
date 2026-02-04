# Promp.str 📝⚡

**Promp.str** (pronounced *Prompt-ster*) is a developer-centric utility designed to bridge the gap between raw text and structured prompt engineering. It allows you to manage AI instructions as modular strings (.str), making it easier to build, test, and refine complex prompts for the **Google AI Studio** ecosystem.

## ✨ Features

- **Structured Prompt Modules:** Break down massive prompts into reusable string components.
- **Variable Interpolation:** Effortlessly inject dynamic data into your templates for automated testing and batch processing.
- **AI Studio Optimized:** Specifically tailored to work with Gemini models and Google AI Studio's logic.
- **Token Efficiency:** Built-in tools to refine and minify prompt strings to maximize context window usage.
- **Logic Orchestration:** Treat prompts as code, enabling cleaner versioning and logic flow.

## 🚀 Why Promp.str?

Prompting is no longer just writing a paragraph; it's engineering a data structure. **Promp.str** treats your instructions as dynamic assets rather than static text files. This is ideal for developers building:
*   Custom Gemini-powered agents.
*   Complex RAG (Retrieval-Augmented Generation) pipelines.
*   Automated content workflows requiring consistent persona and formatting.

## 🛠 Installation & Usage

*(Add your specific installation steps here, for example:)*

```bash
git clone https://github.com/yourusername/promp.str.git
cd promp.str
npm install # or pip install -r requirements.txt

# Load a .str template
from prompstr import PromptBuilder

template = PromptBuilder("summarizer.str")
final_prompt = template.build(context="Long document text here...", tone="Professional")

# Send to Gemini API
response = model.generate_content(final_prompt)


# Load a .str template
from prompstr import PromptBuilder

template = PromptBuilder("summarizer.str")
final_prompt = template.build(context="Long document text here...", tone="Professional")

# Send to Gemini API
response = model.generate_content(final_prompt)
