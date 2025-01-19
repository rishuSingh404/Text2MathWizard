# Text-to-Math Problem Solver and Data Search Assistant 🧮

Welcome to **Text-to-Math Problem Solver and Data Search Assistant**, a Streamlit-powered application designed to solve mathematical problems, answer logic-based questions, and provide information using Wikipedia. This app leverages **Google's Gemma 2 AI** (via ChatGroq) for intelligent problem-solving and reasoning.

---

## Features ✨

- **Mathematical Problem Solver:** 
  Solve complex math problems and get detailed, step-by-step solutions.
  
- **Logic and Reasoning Questions:** 
  Handle text-based logical and reasoning queries with structured, point-wise explanations.

- **Wikipedia Search:** 
  Retrieve summaries and information from Wikipedia for any topic.

- **Interactive Chat Interface:** 
  A user-friendly conversational interface for asking and receiving answers dynamically.

---

## How It Works 🛠️

1. **Input Your Groq API Key:**  
   Provide your API key via the sidebar to initialize the app.
   
2. **Ask Your Question:**  
   Enter a mathematical problem, reasoning question, or a general topic for information search.

3. **Choose a Tool:**  
   The app automatically selects the appropriate tool:
   - Math problems: Uses the **Math Tool**.
   - Logic/reasoning: Uses the **Reasoning Tool**.
   - General search: Uses the **Wikipedia Tool**.

4. **Get a Response:**  
   Receive clear, concise, and actionable responses, often presented step-by-step.

---

## Setup Instructions ⚙️

### Prerequisites
- Python 3.8 or higher
- A valid **Groq API Key** (required for ChatGroq's Gemma 2 model)

### Installation

1. **Clone this repository:**
   ```bash
   git clone https://github.com/your-username/your-repo-name.git
   cd your-repo-name
Install dependencies:

bash
Copy
Edit
pip install -r requirements.txt
Run the app:

bash
Copy
Edit
streamlit run app.py
Enter your Groq API key in the sidebar when prompted.

Example Usage 🎉
Example Question:
"I have 5 bananas and 7 grapes. I eat 2 bananas and give away 3 grapes. Then I buy a dozen apples and 2 packs of blueberries. Each pack of blueberries contains 25 berries. How many total pieces of fruit do I have at the end?"

Response:
Initial count: 
5
+
7
=
12
5+7=12.
After consuming: 
12
−
2
−
3
=
7
12−2−3=7.
Adding new purchases: 
7
+
12
+
(
2
×
25
)
=
69
7+12+(2×25)=69.
Final Answer: 69 pieces of fruit.

Technologies Used 💻
Streamlit: For the web interface.
LangChain: For tool orchestration and prompt management.
ChatGroq (Gemma 2): As the core AI model for reasoning and problem-solving.
WikipediaAPIWrapper: For searching and retrieving Wikipedia content.