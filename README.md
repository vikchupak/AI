# AI

- https://www.youtube.com/watch?v=9oJIU6A5Z70
- https://github.com/punkpeye/awesome-mcp-servers
- https://www.youtube.com/watch?v=EYVc_ApKl9E

## LLM

An **LLM** is a **Large Language Model** 🧠.

---

### 🔹 What it means

* **Large** → trained on massive datasets (billions of words, code, documents, etc.).
* **Language** → understands and generates natural language (English, Ukrainian, code, SQL, etc.).
* **Model** → a machine learning system (usually a type of neural network called a *transformer*).

---

### 🔹 What LLMs do

* Predict the next word in a sequence → but at scale, this allows them to:

  * Answer questions
  * Write essays, code, or SQL queries
  * Translate languages
  * Summarize text
  * Hold conversations

---

### 🔹 Examples of LLMs

* **GPT-4 / GPT-5** (OpenAI)
* **Claude** (Anthropic)
* **Gemini** (Google DeepMind)
* **LLaMA** (Meta)
* **Mistral** (open-source)

---

### 🔹 Why they matter

LLMs are the "brains" behind AI assistants like ChatGPT, Claude, and Copilot.
They can be combined with **tools, data, and protocols like MCP** to become not just “chatbots” but **agents** that can:

* fetch data,
* run commands,
* interact with real systems.

---

👉 In short: an **LLM is the core AI engine** that understands and generates text.

## AI engine

People often use **AI engine** and **LLM** interchangeably, but they’re not exactly the same thing.

### 🔹 AI Engine

* A broader term — usually means the **whole system that runs AI tasks**, not just the model.
* Can include:

  * One or more LLMs (the “brains”)
  * Other models (image models, speech models, recommendation systems)
  * Tooling (MCP servers, APIs, plugins)
  * Infrastructure (GPU clusters, inference servers, orchestration)
* Basically, the **engine** is the whole “car,” while the **LLM** is just the “engine block.”

👉 Example: ChatGPT or Claude Desktop are “AI engines” built on top of LLMs, plus tools, memory, protocols, etc.

---

### 🔹 Analogy

* **LLM** = the raw brain 🧠 (knows stuff, predicts words).
* **AI engine** = the full assistant 🚗 (brain + tools + interface + memory).

---

✅ So:

* If you’re just talking about the **model itself** → LLM.
* If you mean the **whole usable AI system** (model + runtime + extensions) → AI engine.


## OpenAI engine examples

OpenAI offers several powerful AI engines, which they make accessible to developers through their API. These are not just general-purpose models, but highly specialized engines designed for different tasks. Here are some key examples:

### 1. GPT Models (The Text Engine)

The GPT series is OpenAI's family of Large Language Models (LLMs). They are a type of AI engine specifically designed to process and generate human language.

* **Example Model:** `gpt-4o`, `gpt-4o-mini`, `gpt-3.5-turbo`
* **What it does:** This engine takes a text prompt as input and generates a text response.
* **Real-world uses:**
    * **Chatbots and Virtual Assistants:** Powering conversational AI like ChatGPT.
    * **Content Creation:** Automatically writing articles, emails, marketing copy, and social media posts.
    * **Code Generation:** Generating code snippets, fixing bugs, and explaining complex code.
    * **Summarization and Translation:** Condensing long documents and translating text between languages.

### 2. DALL·E Models (The Image Engine)

DALL·E is OpenAI's AI engine for image generation. It's a deep learning model that can create original, high-quality images and art from a text description.

* **Example Model:** `dall-e-3`
* **What it does:** It takes a text prompt and generates a unique image that matches the description.
* **Real-world uses:**
    * **Art and Design:** Creating unique digital art, logos, and graphic design elements.
    * **Marketing and Advertising:** Generating custom images for campaigns and advertisements without needing stock photos.
    * **Prototyping:** Visualizing product ideas or concepts before they are built.

### 3. Whisper (The Audio Engine)

Whisper is an AI engine for speech recognition and translation. It's an open-source model that is exceptionally good at transcribing spoken language into text.

* **Example Model:** `whisper-1`
* **What it does:** It takes an audio file as input and transcribes the speech into text. It can also translate the speech into English if the original language is different.
* **Real-world uses:**
    * **Transcription Services:** Automatically generating transcripts for meetings, lectures, podcasts, and interviews.
    * **Voice Assistants:** Enabling applications to understand spoken commands.
    * **Multilingual Support:** Translating audio from one language to another to make content more accessible.

### 4. Embeddings Models (The Semantic Engine)

While not as flashy as the others, the embeddings engine is a crucial piece of technology that allows AI to understand the *meaning* of text.

* **Example Model:** `text-embedding-ada-002`
* **What it does:** This engine converts text into a numerical vector (a list of numbers) that represents its semantic meaning. Texts that are semantically similar will have numerical vectors that are close to each other in a multi-dimensional space.
* **Real-world uses:**
    * **Semantic Search:** Building search engines that find information based on what you *mean*, not just the keywords you type. For example, you can search for "dishes that use potatoes" and get results for "potato recipes."
    * **Recommendation Systems:** Recommending content or products that are similar in meaning to what a user has liked before.
    * **Clustering and Classification:** Grouping documents or data points based on their meaning.

These are just some of the key AI engines that OpenAI has developed. The OpenAI API acts as the gateway to all of them, allowing developers to build new and innovative applications by simply calling the right "engine" for the task at hand.

---

***The OpenAI API gives you access to the AI engines behind their models like GPT-4.***

---

## AI Agent

An **AI Agent** is a more complete and **autonomous** system that is built **around** an AI engine (like an LLM) to accomplish a specific goal. Unlike a standalone LLM that simply responds to a prompt, an AI agent can:

* **Reason and Plan:** It can break down a complex, high-level goal into a series of smaller, actionable steps.
* **Use Tools:** It can interact with its environment by calling APIs, using web browsers, accessing databases, or running code.
* **Retain Memory:** It can remember past interactions and context to inform future decisions.
* **Act Autonomously:** It can execute the planned steps and take action without continuous human intervention.

Think of the car analogy again:
* **LLM (Engine):** The motor that provides the power.
* **AI Agent (The Car):** The entire vehicle, including the motor, the steering wheel, the GPS, the brakes, and all the other components that allow it to navigate and reach a destination.

An AI agent would be the system that, when asked to "plan a vacation to Hawaii," would:
1.  **Reason:** Break down the task into "find flights," "book a hotel," and "find activities."
2.  **Use Tools:** Access a flight booking API to search for flights, a travel website API for hotels, and a search engine to find popular activities.
3.  **Act:** Present you with a complete itinerary, or even book the trip for you if given permission.

In summary, the relationship between these terms can be seen as a hierarchy:

* An **AI Engine** is the fundamental technology.
* A **Large Language Model (LLM)** is a specific and powerful type of AI engine.
* An **AI Agent** is an entire system that uses an LLM (or other AI engines) as its "brain" to autonomously perform complex, goal-oriented tasks.

## Generative AI

Generative AI is a category of artificial intelligence that focuses on creating new and original content. Unlike traditional AI that primarily analyzes or classifies existing data, generative AI learns the patterns and structures within a given dataset and uses that knowledge to produce novel outputs. These outputs can be text, images, audio, video, code, or other forms of data.

The core idea is that the AI doesn't just recognize what it has seen; it understands the underlying "rules" of the content to generate something new that is statistically similar but not identical to its training data.

### Key Types of Generative AI Models

The most prominent types of generative models are:

* **Large Language Models (LLMs):** These are trained on massive text datasets to understand and generate human language. They are at the heart of many conversational AI applications.
* **Diffusion Models:** These models work by learning to "denoise" a random image to create a coherent and high-quality one. They are particularly effective at generating photorealistic images and are widely used in text-to-image generators.
* **Generative Adversarial Networks (GANs):** A GAN consists of two competing neural networks: a "generator" that creates content, and a "discriminator" that tries to tell if the content is real or fake. This adversarial process forces the generator to create increasingly realistic outputs.

### Examples of Generative AI

Generative AI is transforming many industries, and its applications are becoming increasingly common in daily life.

#### Text Generation
* **ChatGPT:** The most famous example. It can write articles, stories, emails, and even code based on a simple text prompt.
* **Google Gemini:** A competitor to ChatGPT, also capable of sophisticated text generation, summarization, and conversation.
* **GrammarlyGO:** A writing assistant that can not only fix grammar but also generate entire sentences or paragraphs to improve your writing.

#### Image & Art Generation
* **DALL·E 3 (from OpenAI):** Creates highly detailed and creative images from text descriptions, such as "a vintage photo of a futuristic robot having a picnic in the countryside."
* **Midjourney:** A popular tool for generating high-quality, artistic images. It is favored by many digital artists for its unique aesthetic and creative control.
* **Stable Diffusion:** An open-source model that allows users to create images from text prompts and also to edit existing images in a "generative fill" style.

#### Audio & Music Generation
* **ElevenLabs:** A platform that can generate realistic, human-like voiceovers from text. It can be used for creating audiobooks, podcasts, and video narration.
* **Suno:** A generative AI that can create original songs with lyrics, vocals, and musical accompaniment based on a short prompt.
* **Descript:** An audio/video editing tool that uses generative AI to "overdub" a user's voice, allowing them to correct mistakes or change words in their audio without re-recording.

#### Video & 3D Model Generation
* **Sora (from OpenAI):** A highly advanced model that can generate realistic and imaginative videos from text prompts, creating complex scenes with multiple characters and specific movements.
* **Luma AI:** A tool that can create 3D models and assets from a series of images or video, making 3D modeling accessible to a wider audience.

### Standard RAG vs Agentic RAG

<img width="1584" height="720" alt="image" src="https://github.com/user-attachments/assets/35eeeb6e-fe90-49f7-9495-fef99b65a00d" />

<img width="1098" height="298" alt="image" src="https://github.com/user-attachments/assets/b7984f9e-edaf-4a14-8c36-45d0a0cbfa72" />


