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

### 3. Suggested GitHub Topics (Tags)
Add these to your repo to help people find it:
`prompt-engineering` • `gemini-api`[[2](https://www.google.com/url?sa=E&q=https%3A%2F%2Fvertexaisearch.cloud.google.com%2Fgrounding-api-redirect%2FAUZIYQEHO1U_u71RuZKJ4O_SPsjQGOiEVwjxXRGV7F9ajdreJAGQZSUTWIOWPQ6n-B3r03CkkdOQHbeonTVrl0OF7oAWYUPQsEMd6rHbGgLu5QceoFgMTdUmW_p0VkTi0UlWMwm6oO9SGs8%3D)] • `google-ai-studio`[[2](https://www.google.com/url?sa=E&q=https%3A%2F%2Fvertexaisearch.cloud.google.com%2Fgrounding-api-redirect%2FAUZIYQEHO1U_u71RuZKJ4O_SPsjQGOiEVwjxXRGV7F9ajdreJAGQZSUTWIOWPQ6n-B3r03CkkdOQHbeonTVrl0OF7oAWYUPQsEMd6rHbGgLu5QceoFgMTdUmW_p0VkTi0UlWMwm6oO9SGs8%3D)][[5](https://www.google.com/url?sa=E&q=https%3A%2F%2Fvertexaisearch.cloud.google.com%2Fgrounding-api-redirect%2FAUZIYQHLEDaHAx1xk4FO-Ut1MLszjampy-lEukx8ye3KOtnQ2zBCbH1X6tqitXIhMcI6IWu-F_bQ12RDKb-DBKNVDTZEy21OC8hzRh8-KFJvwuf2czx32_VNfeTNkFFesIMuZDGn8XoX6q4%3D)][[6](https://www.google.com/url?sa=E&q=https%3A%2F%2Fvertexaisearch.cloud.google.com%2Fgrounding-api-redirect%2FAUZIYQFIymgNC3hAz8zcDLgkLrqWI5vxGOU47n3QaYMZHV48pIUXWbLGxJqu2vn8aylEswvapfYvuH7lBb-p0jSbIjK1zEISzW81G6t0no0pHqK21iw-M8NGeGo%3D)][[7](https://www.google.com/url?sa=E&q=https%3A%2F%2Fvertexaisearch.cloud.google.com%2Fgrounding-api-redirect%2FAUZIYQFn0Imd6mzB3guEy4DXIsUAzqnSp1XaFB_NtaRv75RNwzvLJG95OhA-WzThHGV1_B-clhhCoyWIDqGdIpQRN5G0s6jNHVTurqyKVKuwwVVFJ8_ZxG29M_JTnVhGKEIWDfgBOhA4EtDfYWeFJYtDgmGpnvXScILT3uBeynLYxpk427bgn3Lp71KPdPORGzphsqOljdURsOi3d-LeXChaL1Y%3D)] • `llm-tools`[[2](https://www.google.com/url?sa=E&q=https%3A%2F%2Fvertexaisearch.cloud.google.com%2Fgrounding-api-redirect%2FAUZIYQEHO1U_u71RuZKJ4O_SPsjQGOiEVwjxXRGV7F9ajdreJAGQZSUTWIOWPQ6n-B3r03CkkdOQHbeonTVrl0OF7oAWYUPQsEMd6rHbGgLu5QceoFgMTdUmW_p0VkTi0UlWMwm6oO9SGs8%3D)] • `prompt-templates` • `ai-development`[[2](https://www.google.com/url?sa=E&q=https%3A%2F%2Fvertexaisearch.cloud.google.com%2Fgrounding-api-redirect%2FAUZIYQEHO1U_u71RuZKJ4O_SPsjQGOiEVwjxXRGV7F9ajdreJAGQZSUTWIOWPQ6n-B3r03CkkdOQHbeonTVrl0OF7oAWYUPQsEMd6rHbGgLu5QceoFgMTdUmW_p0VkTi0UlWMwm6oO9SGs8%3D)][[3](https://www.google.com/url?sa=E&q=https%3A%2F%2Fvertexaisearch.cloud.google.com%2Fgrounding-api-redirect%2FAUZIYQEd2acFIsGk3_hDDQDkiiO8x9FWPoEDcJRcJnAmH4wOcDa2bm2qTyioO-8QGL8Ykyvfa_keYYWjbfiG5aWqGV01heO9FFs7LPXGte1gdZvoEDYsib1xO62RKLS9ZgWdiF5HcvhBNK_327OU_BDzKXqluI4whWh4XlXAIVwDxRT9LcHaRY-nm_1jij8%3D)][[4](https://www.google.com/url?sa=E&q=https%3A%2F%2Fvertexaisearch.cloud.google.com%2Fgrounding-api-redirect%2FAUZIYQGM5XpJxsZ7sabLQzWDaUsrSQ0MUtz3Zy0EMbKLZkDQUgmJP0bFJWM9ukmhi3A21vM6ls2iRxUVpRzun_hPz9EN8Wv7YNnErhUg5n8%3D)][[7](https://www.google.com/url?sa=E&q=https%3A%2F%2Fvertexaisearch.cloud.google.com%2Fgrounding-api-redirect%2FAUZIYQFn0Imd6mzB3guEy4DXIsUAzqnSp1XaFB_NtaRv75RNwzvLJG95OhA-WzThHGV1_B-clhhCoyWIDqGdIpQRN5G0s6jNHVTurqyKVKuwwVVFJ8_ZxG29M_JTnVhGKEIWDfgBOhA4EtDfYWeFJYtDgmGpnvXScILT3uBeynLYxpk427bgn3Lp71KPdPORGzphsqOljdURsOi3d-LeXChaL1Y%3D)]
