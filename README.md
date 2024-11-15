🚀 GemmaDoc: AI-Powered Document Q&A

Unleash the power of Generative AI and LangChain to transform how you interact with documents. With GemmaDoc, upload your PDFs, ask natural language questions, and receive precise, context-aware answers—all within a sleek, interactive Streamlit interface.
🔍 Why GemmaDoc?

    Manual Document Search is Outdated
    Parsing through large documents manually is time-consuming and inefficient. GemmaDoc automates this process, giving you instant insights.

    Context-Aware Q&A
    Get accurate answers based on the context of your documents, thanks to advanced vector embeddings and cutting-edge AI models.

    Interactive and Scalable
    With a user-friendly interface, GemmaDoc is perfect for researchers, professionals, and developers seeking streamlined document analysis.

🛠 How It Works
Pipeline Overview

    Document Upload & Parsing
        Upload your PDFs, which are processed using LangChain's PyPDFLoader.
        Text is split into manageable chunks for efficient querying.

    Vector Embedding
        Generate vector representations of document content using Google Generative AI Embeddings for high-quality semantic understanding.

    Vector Store Creation
        Store the embedded vectors in a FAISS vector database to enable fast and accurate similarity searches.

    Question Processing
        Input your question in natural language.
        The system retrieves the most relevant document chunks using semantic search.

    Response Generation
        An AI model (powered by ChatGroq) processes the context and crafts a detailed, accurate response.

    Answer Presentation
        View the answer along with the most relevant document snippets for transparency and reliability.

🧰 What’s Under the Hood?
Key Technologies

    LangChain: The backbone for document loading, chunking, and chaining AI responses.
    Google Generative AI Embeddings: Provides state-of-the-art vector embeddings for semantic search.
    FAISS: Ensures fast and scalable vector searches.
    Streamlit: Delivers an intuitive and interactive web app interface.
    ngrok: Exposes the local app to the web, enabling seamless sharing and access.

✨ Features

    🗂 Document Upload
        Easily upload multiple PDFs for analysis.

    💡 Intelligent Q&A
        Get concise, context-aware answers in seconds.

    📚 Contextual Transparency
        See the relevant sections of the document used to generate the answer.

    ⚡️ Fast Response Time
        Optimized pipeline ensures quick and accurate results.

    🌐 Public Access
        Run the app anywhere using ngrok for remote sharing.

🚀 Quick Start

    Clone the repository:

git clone https://github.com/krsatyam90/Generative-Q-A-Interactive-Document-Assistant

Install the dependencies:

pip install -r requirements.txt

Set up your environment variables in a .env file:

GROQ_API_KEY=your_groq_api_key
GOOGLE_API_KEY=your_google_api_key

Run the app locally:

streamlit run app.py

Use ngrok to expose your app:

    ngrok http 8501

🤔 Use Cases

    Researchers: Analyze lengthy reports or research papers efficiently.
    Professionals: Quickly find critical insights from legal, financial, or technical documents.
    Developers: Explore how to integrate AI-driven Q&A into your workflows.

📌 Future Enhancements

    Adding support for multiple file types (e.g., Word, Excel).
    Enhancing response accuracy with hybrid AI models.
    Implementing user authentication for secure access.

📄 Contributing

We welcome contributions! Fork the repo, make your changes, and submit a pull request. Let’s make document interaction smarter together.
📧 Contact

Have questions or suggestions? Feel free to reach out at satyamgangwal.90@gmail.com.
