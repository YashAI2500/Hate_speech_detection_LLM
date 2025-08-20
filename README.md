## My Hate-Speech Demo at a Glance 🚀

**Who am I?**  
I’m **Yash**, a 3rd-year B.Tech student 👨🎓 working on NLP.

### 🔧 What I Used  
1. **Model** — Fine-tuned **RoBERTa-base** 🦾 to classify text into **Hate Speech**, **Offensive**, or **Neither**.  
2. **Cloud LLMs** — 💡 **Gemini 2 Flash** (primary) and 🤖 **GPT-4o-mini** (backup) to explain each prediction in 1-2 sentences.  
3. **Interface** — **Gradio** web app 🖥️ for one-click testing; Colab autogenerates a shareable link.

### ⚙️ How It Works  
-  The RoBERTa model fires first ⚡, giving a label + confidence in milliseconds.  
-  That result is sent to Gemini / GPT, which replies with a quick human-friendly rationale 💬.  
-  Gradio then shows: **Label → Confidence → Explanation** in a neat layout.

### 🌟 Why It’s Cool  
-  **Explainability:** Users don’t just see *what* the model thinks, but *why* 🤔.  
-  **Speed:** Lightweight Transformer keeps latency low ⚡, while LLM adds depth.  
-  **Plug-and-play:** Runs entirely from a Colab notebook; no backend setup needed 🔌.

### 📝 Next on My To-Do List  
-  🔐 Hide API keys in env variables.  
-  🧹 Retrain on edge cases like “Go back to your country” for better sensitivity.  
-  🗜️ Merge duplicate code blocks to keep the notebook tidy.

That’s the whole stack—**RoBERTa for detection, Gemini / GPT for explanations, Gradio for the front end**—all wrapped into an easy demo you can try in one click. 🎉

[1] https://ppl-ai-file-upload.s3.amazonaws.com/web/direct-files/attachments/82560513/e7b757aa-4b7b-41e6-9264-6da802b14aee/Hate_speech_openAI.ipynb
