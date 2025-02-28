# AI-Powered Personalized Tutor 🎓🤖

An **AI-Powered Personalized Learning Agent** developed using **LangGraph, LangChain, and OpenAI**, designed to create dynamic study plans, generate lessons, craft quizzes, and provide personalized feedback—making education more adaptive and scalable.

## 🌟 Features
- ✅ **Study Planner** – Generates structured topics based on learning goals 📅
- ✅ **Lesson Generator** – Creates in-depth, easy-to-understand lessons 📖
- ✅ **Quiz Creator** – Designs interactive multiple-choice quizzes for self-assessment 🎯
- ✅ **Performance Evaluator** – Analyzes quiz results and provides tailored feedback 📊
- ✅ **Next Steps Recommender** – Suggests further learning paths for continuous growth 🚀

---

## 🔧 How It Works
Using **LangGraph**, the AI agent is structured with an **agentic workflow**, ensuring seamless integration between study planning, content generation, assessment, and progress tracking.

1️⃣ The **Study Planner** defines topics based on user input.  
2️⃣ The **Lesson Generator** creates structured and comprehensive lessons.  
3️⃣ The **Quiz Creator** formulates multiple-choice questions for self-assessment.  
4️⃣ The **Performance Evaluator** analyzes quiz results and provides insights.  
5️⃣ The **Next Steps Recommender** suggests further learning paths.

---

## 📦 Installation

### Prerequisites
Ensure you have the following installed:
- Python 3.8+
- pip
- Git
- OpenAI API Key

### Clone the Repository
```sh
git clone <your-repo-url>
cd <your-repo-name>
```

### Install Dependencies
```sh
pip install -r requirements.txt
```

### Set Up Environment Variables
Create a `.env` file and add your OpenAI API Key:
```env
OPENAI_API_KEY=your_openai_api_key
```

---

## 🚀 Usage

### Run the AI Tutor
```sh
streamlit run app.py
```
This launches the **Streamlit UI**, allowing users to interact with the learning agent.

### Example Usage
```python
# Example: Generate a study plan for Python programming
prompt = "Create a structured study plan for learning Python as a beginner."
```

---

## 📂 Project Structure
```
|-- src/
|   |-- planner.py        # Study Planner module
|   |-- lesson_generator.py # Lesson generation logic
|   |-- quiz_creator.py   # Quiz generation module
|   |-- evaluator.py      # Performance evaluation logic
|   |-- recommender.py    # Next steps recommendation module
|
|-- app.py                # Streamlit UI implementation
|-- requirements.txt       # Required dependencies
|-- README.md             # This documentation
```

---

## 🚀 Roadmap
- ✅ Initial prototype with study plan, lesson, and quiz generation
- ⏳ Improve AI-driven adaptive learning recommendations
- ⏳ Enhance interactive engagement with multimedia content
- ⏳ Implement progress tracking and reporting

---

## 🤝 Contributing
Feel free to contribute by submitting issues or pull requests. Follow the repository's contribution guidelines.

---

## 📜 License
This project is licensed under the **MIT License** - see the [LICENSE](LICENSE) file for details.

---

## 📞 Contact
📱 **WhatsApp**: [+2348067718392](https://wa.me/2348067718392)  
🔗 **LinkedIn**: [Abdullahi Ahmad Babura](https://www.linkedin.com/in/abdullahi-ahmad-babura)

