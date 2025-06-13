AI Concepts & Key Terms 
🤖 Artificial Intelligence (AI)

AI refers to machines or software that can perform tasks that typically require human intelligence — such as reasoning, learning, planning, and problem-solving.

🔬 Machine Learning (ML)

A subset of AI where machines learn patterns from data without being explicitly programmed. It includes both supervised and unsupervised learning.

🧐 Deep Learning

A specialized branch of machine learning that uses multi-layered neural networks ("deep" networks) to learn from complex data like images, language, and audio.

🤠 Transformer

A deep learning model architecture based on self-attention mechanisms. Introduced in 2017 by Google, it powers modern AI systems like GPT and BERT. It enables efficient parallel processing and superior understanding of long-range relationships in data.

🌐 Large Language Model (LLM)

A type of AI model based on the Transformer architecture, trained on massive amounts of text data. LLMs generate human-like language and can perform tasks like answering questions, summarizing, translating, and writing code.

Examples: GPT-4, Claude, LLaMA, Gemini

📈 Generative AI (GenAI)

A broader category of AI systems that can create new content such as text, images, code, audio, and video.

LLMs are a subcategory of GenAI focused on generating text.

Other types of GenAI:

Image GenAI: DALL·E, Midjourney

Audio GenAI: ElevenLabs, MusicGen

Video GenAI: RunwayML, Pika

 Transformer = Encoder + Decoder
🔹 Encoder
Reads and understands the input (like a sentence, paragraph, or code)

Breaks it down into key patterns using self-attention

Produces a series of embeddings (numerical representations of meaning)

🔹 Decoder
Takes the encoded information and generates the output
(like translating to another language, answering a question, or writing text)

Uses self-attention and cross-attention (to attend to encoder output)


Hallucination (in AI/LLMs)
Hallucination is when an AI (like ChatGPT or any LLM) generates confident-sounding but incorrect or made-up information.

❗Example:
You ask: “Who founded Cognexa?”
The AI replies: “It was founded by Elon Musk in 2016.”
→ That’s a hallucination if it’s not true.

🧠 Why It Happens:
The model predicts likely words, not facts

It doesn’t “know” — it generates based on patterns in its training data

If training data is missing, inconsistent, or biased → hallucinations occur

🛡️ How to Reduce Hallucinations:
Use RAG (Retrieval-Augmented Generation) to pull real data from a database or documents

Fine-tune on verified internal content

Add human-in-the-loop review for high-stakes outputs


💡 Relationship Summary:

Deep Learning is the technique

Transformer is a model architecture built with deep learning

LLMs are built using Transformers to understand/generate language

GenAI includes LLMs and other generators (image, code, audio)


