

# 📃 AI Resume Critiquer

AI Resume Critiquer is a user-friendly Streamlit web app that leverages OpenAI's GPT-3.5 model to provide insightful, constructive feedback on resumes. Simply upload your resume (PDF or TXT) and get instant analysis tailored to your targeted job role.

## 🔍 Features

* 📄 Upload your resume in PDF or TXT format
* 🎯 Get feedback tailored to your specific job role
* 🧠 AI-powered analysis on:

  * Content clarity and impact
  * Skills presentation
  * Experience descriptions
  * Role-specific improvements
* ✅ Simple and intuitive user interface with Streamlit

## 🚀 Demo

![image](https://github.com/user-attachments/assets/c7c7d5c6-4e8a-4d48-8a9b-079c1140f324)



## 🛠️ Tech Stack

* [Python](https://www.python.org/)
* [Streamlit](https://streamlit.io/)
* [LangChain](https://www.langchain.com/)
* [OpenAI GPT-3.5 Turbo](https://platform.openai.com/)
* [PyPDF2](https://pypi.org/project/PyPDF2/)
* [dotenv](https://pypi.org/project/python-dotenv/)

## 📦 Installation

1. **Clone the repository**

```bash
git clone https://github.com/KaanSezen1923/ai-resume-critiquer.git
cd ai-resume-critiquer
```

2. **Install dependencies**

```bash
pip install -r requirements.txt
```

3. **Set up environment variables**

Create a `.env` file in the root directory:

```
OPENAI_API_KEY=your_openai_api_key
```

4. **Run the app**

```bash
streamlit run main.py
```

## 📁 Project Structure

```
ai-resume-critiquer/
├── main.py
├── .env
├── requirements.txt
└── README.md
```

## ✅ Example Prompt to the Model

> **Role:** Product Manager
> **Resume Content:** Uploaded by user
> **Prompt Sent to Model:**
> *"Please analyze this resume and provide constructive feedback. Focus on clarity, skills, experience, and specific improvements for a Product Manager role..."*

## 🧠 How It Works

1. The user uploads their resume.
2. The app extracts text using `PyPDF2` or reads TXT.
3. LangChain sends a structured prompt to the OpenAI GPT-3.5 model.
4. The model responds with detailed feedback.
5. The response is displayed in the Streamlit interface.

## 🧪 Future Enhancements

* Add support for DOCX files
* Export feedback as PDF
* Include grammar and formatting checks
* Allow multi-resume batch analysis

## 🤝 Contributing

Pull requests are welcome! For major changes, open an issue first to discuss what you would like to change.

## 📝 License

This project is open-source and available under the [MIT License](LICENSE).


