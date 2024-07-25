# RAG Dermosis - Skincare Chatbot with PDF Reading

Welcome to the RAG Dermosis Skincare Chatbot repository. This project features an advanced conversational AI bot designed to provide personalized skincare advice and recommendations. The bot uses a Retrieval-Augmented Generation (RAG) system to enhance its responses by referencing information from a skin disease diagnosis document.

# Features
- Personalized Skincare Advice: Offers recommendations based on skin type, concerns, and preferences.
- Symptom Identification: Helps identify potential skin conditions by discussing symptoms.
- Product Suggestions: Recommends products suitable for the user's skin type and concerns.
- Routine Creation: Assists users in creating and optimizing their skincare routine.
- General Skincare Tips: Provides general advice on skincare practices and ingredients.
- Interactive Chat: Engages users in a friendly and informative conversation.
- PDF Reading: Extracts and utilizes information from a provided PDF to enhance response accuracy.
- Vector Database: Searches relevant documents using vector similarity for more accurate results.

# Usage
You can interact with the bot by visiting the local Gradio interface. Simply type your skincare-related queries, and the bot will respond with relevant advice and suggestions, enhanced by the information extracted from the PDF.

# Key Components
- Inference Client: Uses Hugging Face's Inference API for generating chatbot responses.
- PDF Processing: Extracts text from the provided PDF file and stores it in the app's documents.
- Vector Database: Builds a vector database using the content of the PDF for document similarity search.
- Response Function: Handles the conversation logic, maintaining the history of interactions, generating responses based on - user input, and retrieving relevant documents from the vector database.
- Gradio Interface: Provides a user-friendly web interface for interacting with the chatbot.

# Contributing
Contributions are welcome! Please feel free to submit a Pull Request.
- Fork the repository
- Create your feature branch (git checkout -b feature/your-feature)
- Commit your changes (git commit -am 'Add your feature')
- Push to the branch (git push origin feature/your-feature)
- Create a new Pull Request
