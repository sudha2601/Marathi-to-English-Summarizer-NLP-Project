
**🇮🇳 RajyaSaar — Marathi Political Text Summarization using mBART**

RajyaSaar is a Natural Language Processing (NLP) project that leverages the multilingual transformer model mBART (facebook/mbart-large-50) to generate concise summaries of Marathi political news articles.

This project is fine-tuned specifically for summarizing long and complex political content written in Marathi, making it easier for readers to grasp the core message quickly. It has been trained and evaluated on a custom dataset of political articles with corresponding human-written summaries.

💡 **What It Does**
🗳️ Takes Marathi political text as input and generates short, accurate summaries in Marathi.

⚙️ Uses mBART-50, a multilingual sequence-to-sequence model by Facebook AI, fine-tuned for the Marathi language.

📊 Evaluated using ROUGE metrics to ensure the quality of generated summaries.

🧠 Trained on real-world political news data, enabling the model to understand context, entities, and political dynamics.

📁 Outputs include a fine-tuned model and tokenizer, which are saved and zipped for deployment.

🧰 **Tech Stack**
Model: facebook/mbart-large-50

Libraries: Transformers, Datasets, PyTorch, Evaluate, ROUGE Score, Pandas

🔮 **Example**
Input (Marathi Political News):
“२०१४ मध्ये औरंगाबाद मध्य आणि मुंबईतील भायखळा या दोन मतदारसंघातून एमआयएमचे आमदार निवडून आले होते...”

Generated Summary:
“२०१९ मध्ये एमआयएमने धुळे शहर आणि मालेगाव मधील जागा जिंकल्या, फारूक शाह आणि मुफ्ती इस्माईल विजयी.”
