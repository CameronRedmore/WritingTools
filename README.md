# Writing Tools - OpenAI Edition

https://github.com/user-attachments/assets/0dd14cee-8307-4714-99f0-631fb6de1510

## 🚀 What is Writing Tools - OpenAI Edition?

This is a modified version of the original [Writing Tools](https://www.github.com/theJayTea/WritingTools), which swaps out the Gemini 1.5 Flash model for OpenAI compatible inference instead.

Writing Tools is a powerful text editing tool that uses Google's Gemini 1.5 Flash model to provide a variety of text editing options, such as proofreading, rewriting, summarizing, and more. 

### 🌟 Why Choose Writing Tools in general?

- **System-wide Functionality**: Works instantly in any application where you can select text. Does not overwrite or mess with your clipboard.
- **Privacy-focused**: Your API key and config files stay on *your* device. NO logging, diagnostic collection, tracking, or ads are added by the project itself. The application is also invoked *only* on your command.  however due to the nature of sending data to a third party API, these third-party APIs can perform tracking etc. as they wish. (Use local inference via the OpenAI compatible version for enhanced privacy).
- **Supports Many Languages**: Works for any language the model-behind can handle! It can even *translate* text across many languages better than Google Translate (type *"translate to x language"* in the `Describe your change...` box).
- **Themes & Dark Mode**: Choose between **2 themes**: a blurry gradient theme and a plain theme that resembles the Windows + V pop-up! Also has full **dark mode support**.
- **Customizable**: Set your own hotkey for quick access.

### 🌟 Why Choose Writing Tools - OpenAI Edition?

- **OpenAI Compatibility**: Works with any OpenAI compatible endpoint, allowing local or cloud-based inference.
- **Local Inference for Enhanced Privacy**: Run models locally to ensure absolutely no data leaves your device at all, avoiding pesky third-party privacy policies and terms of use with tools such as [TabbyAPI](https://github.com/theroyallab/tabbyAPI), [vLLM](https://github.com/vllm-project/vllm), [llama.cpp](https://github.com/ggerganov/llama.cpp/blob/master/examples/server/README.md) or [KoboldCPP](https://github.com/LostRuins/koboldcpp), along with many others.
- **Best-in-Class Cloud Inference**: [OpenAI](https://www.openai.com)'s cloud-based models are some of the best in the world, and this version of Writing Tools allows you to use them with ease.
- **More Options**: Many providers offer OpenAI compatibility, allowing you to choose the best provider for your needs. Examples include [Anthropic](https://www.anthropic.com/), [MistralAI](https://mistral.ai/), and even [Google Gemini itself](https://cloud.google.com/vertex-ai/generative-ai/docs/multimodal/call-vertex-using-openai-library), again with many other options not listed here too.

## ✨ Features

- **Proofread**: The smartest grammar and spelling corrector. Sorry not sorry, Grammarly Premium.
- **Rewrite**: Improve the phrasing of your text.
- **Make Friendly/Professional**: Adjust the tone of your writing.
- **Summarize**: Create concise summaries of longer texts.
- **Extract Key Points**: Highlight the most important information.
- **Create Tables**: Convert text into a structured Markdown table (use [Obsidian](https://obsidian.md/) or [Markdown-to-Excel](https://tableconvert.com/markdown-to-excel) to work with the markdown table).
- **Custom Instructions**: Give specific directions for text modifications (e.g. `Translate to French`).

## 🖱 How to Use

1. Select any text in any application.
2. Press your hotkey (default: Ctrl+Space).
3. Choose an option from the popup menu or enter a custom instruction.
4. Watch as your text is magically improved!

## 🛠 Installation

1. Go to the [Releases](https://github.com/CameronRedmore/WritingTools/releases) page and download the latest `Writing Tools.zip` file.
   
2. Extract it where you want, run `Writing Tools.exe`, and enjoy! :D

   *Note: If you extract Writing Tools into a protected system folder like Program Files, you'll need to run it as administrator on the first launch or it won't be able to create its config file (in the same folder as its exe).*
   
4. To let it automatically start when you boot your PC, add a shortcut of the `Writing Tools.exe` to the Windows Start-Up folder (Open Run and type `shell:startup` to get to this folder). 

## 🔒 Privacy

As with the original Writing Tools, this version does not itself collect any data. However, just like the original Writing Tools, the third-party APIs it uses may collect data according to their own privacy policies.

To ensure no data ever leaves your device at all, use Local Inference with OpenAI compatible servers as described above!

This version of Writing Tools is also Open-Source, licensed under the same GNU General Public License v3.0 as the original Writing Tools.
This allows for perusal, modification, and distribution of the code, ensuring transparency and privacy.

## 💡 Tips

- Use "Proofread" for quick grammar and spelling checks. Better than Grammarly premium can ever be :)
- Try "Rewrite" when you want to improve the entire phrasing.
- "Summarize" is great for condensing long articles or documents.
- Experiment with custom instructions for specific writing needs.

## 👨‍💻 To run Writing Tools directly from the code

If you prefer to run it directly from the `main.py` file:

1. Download the code by clicking this button above:
   ![image](https://github.com/user-attachments/assets/4c6cab79-4918-451c-9ad1-1bbcf8472275)

2. Right-click the folder of the code you downloaded, and click Open in Terminal.
   You'll only have to do this once: Type `pip install -r requirements.txt`.
   Of course, you'll need to have [Python installed!](https://www.python.org/downloads/).

3. Any time you want to run the program, just type `pythonw main.py` in your terminal. That's it! 🎉

## 🐞 Known Issues
On some devices, the hotkey detection or text selection detection sometimes acts up or does not work correctly.

To fix it, just restart Writing Tools (you can close it by right-clicking its taskbar tray icon and clicking Exit, or with Task Manager).

This issue is being investigated — it seems to be due to an unreliable hotkey detection API.

## 👨‍💻 To compile the application yourself:

Here's how to compile it with PyInstaller:

1. Install PyInstaller: `pip install pyinstaller`
2. Run the build script: `pyinstaller-build-script.py`

## 🤝 Contributing

I welcome contributions! If you'd like to improve Writing Tools, feel free to open a Pull Request.

## 📬 Contact

My email: jesaitarun@gmail.com

Made with ❤️ by a high school student. Check out my other AI app, [Bliss AI](https://play.google.com/store/apps/details?id=com.jesai.blissai), a novel AI tutor free on the Google Play Store!

## 📄 License

Distributed under the GNU General Public License v3.0.

---

