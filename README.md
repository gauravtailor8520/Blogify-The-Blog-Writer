# 📑💭 Blogify - The AI Blog Writer

[![Python](https://img.shields.io/badge/Python-3.8%2B-blue.svg)](https://python.org)
[![Streamlit](https://img.shields.io/badge/Streamlit-1.0%2B-red.svg)](https://streamlit.io)
[![LangChain](https://img.shields.io/badge/LangChain-Latest-green.svg)](https://langchain.com)
[![Hugging Face](https://img.shields.io/badge/🤗%20Hugging%20Face-Transformers-yellow.svg)](https://huggingface.co)

## 🌟 Overview

**Blogify** is an AI-powered blog content generation tool that leverages the power of Meta's Llama 3 model through Hugging Face and LangChain to create high-quality, engaging blog content. With an intuitive Streamlit interface, users can generate creative blog titles and comprehensive blog posts tailored to their specific needs.

## 🚀 Features

- **🎯 Smart Title Generation**: Generate 10 creative and attention-grabbing titles for any topic
- **📝 Content Generation**: Create high-quality, informative blog posts with customizable length
- **🔑 Keyword Integration**: Seamlessly incorporate specific keywords into your content
- **🎨 User-Friendly Interface**: Clean and intuitive Streamlit web application
- **🧠 AI-Powered**: Uses Meta-Llama-3-8B-Instruct model for superior content quality
- **⚡ Real-time Generation**: Instant content creation with adjustable parameters

## 📁 Project Structure

```
Blogify-The-Blog-Writer/
├── app.py                    # Main Streamlit application
├── requirements.txt          # Python dependencies
├── secret_api_keys.py       # API keys configuration
├── code_dev.ipynb          # Development notebook
├── code.ipynb              # Additional notebook
├── README.md               # Project documentation
└── __pycache__/            # Python cache files
```

## 🛠️ Installation & Setup

### Prerequisites
- Python 3.8 or higher
- Hugging Face account and API token

### Step 1: Clone the Repository
```bash
git clone https://github.com/yourusername/Blogify-The-Blog-Writer.git
cd Blogify-The-Blog-Writer
```

### Step 2: Install Dependencies
```bash
pip install -r requirements.txt
```

### Step 3: Configure API Keys
1. Create a Hugging Face account at [huggingface.co](https://huggingface.co)
2. Generate an API token from your account settings
3. Update `secret_api_keys.py` with your token:
```python
hugging_face_api_key = "your_actual_api_token_here"
```

### Step 4: Run the Application
```bash
streamlit run app.py
```

## 🎮 How to Use

### 1. Title Generation
1. **Navigate to the Title Generation section**
2. **Enter your topic** in the expandable input field
3. **Click "Submit topic"** to generate 10 creative titles
4. **Review the suggestions** and choose your favorite

### 2. Blog Content Generation
1. **Navigate to the Blog Generation section**
2. **Enter your chosen title** in the input field
3. **Set the desired word count** using the slider (100-1000 words)
4. **Add keywords** by typing them and clicking "Add Keyword"
5. **Click "Submit Info"** to generate your complete blog post

## 🔧 Technical Details

### Dependencies
- **langchain**: Framework for developing applications with language models
- **streamlit**: Web application framework for Python
- **langchain-huggingface**: Hugging Face integration for LangChain
- **transformers**: State-of-the-art machine learning library

### AI Model
- **Model**: Meta-Llama-3-8B-Instruct
- **Temperature**: 0.6 (balanced creativity and coherence)
- **Provider**: Hugging Face Hub

### Key Components
- **Prompt Templates**: Carefully crafted prompts for optimal content generation
- **Chain Architecture**: LangChain chains for streamlined processing
- **Session State Management**: Persistent keyword storage across interactions

## 🎯 Use Cases

- **Content Creators**: Generate blog posts for websites and social media
- **Digital Marketers**: Create SEO-optimized content with targeted keywords
- **Students**: Develop articles and essays on various topics
- **Businesses**: Produce informative content for company blogs
- **Writers**: Overcome writer's block with AI-assisted content creation

## 🔒 Security Considerations

- **API Key Management**: Store API keys securely and never commit them to version control
- **Environment Variables**: Consider using `.env` files for production deployments
- **Rate Limiting**: Be mindful of Hugging Face API rate limits

## 🚧 Future Enhancements

- [ ] Multiple AI model support
- [ ] Content export functionality (PDF, Word, Markdown)
- [ ] SEO optimization features
- [ ] Content plagiarism checking
- [ ] Multi-language support
- [ ] Template customization
- [ ] Content history and saving

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request. For major changes, please open an issue first to discuss what you would like to change.

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- **Meta AI** for the Llama 3 model
- **Hugging Face** for model hosting and API
- **LangChain** for the framework
- **Streamlit** for the web interface

## 💬 Support

If you encounter any issues or have questions, please:
1. Check the existing issues on GitHub
2. Create a new issue with detailed information
3. Provide steps to reproduce any bugs

---



*Happy Blogging! 📝✨*
