# Text to Math Problem Solver and Data Search Assistant

This project uses the LangChain framework, Streamlit for UI, and Groq's LLM (Gemma2-9b-It) to create a math problem solver and a general data search assistant. The app can handle mathematical queries, logic-based reasoning questions, and general searches through Wikipedia.

## Features
- Solve mathematical problems using Groq's Gemma2-9b-It LLM.
- Provide reasoning and logic-based solutions.
- Perform Wikipedia searches to answer general knowledge queries.
- Interactive chat interface using Streamlit.

## Usage
- Open the live app in your browser (https://text-to-math-problem-solver-uing-app-gemma-2-afatujggehnba9tet.streamlit.app/)
- Enter your Groq API key in the sidebar to enable the assistant.
- Input any math problem or general question in the text area.
- Click the "Find my answer" button to get the solution.
- The response, along with reasoning or calculations, will be displayed in the chat interface.

## Tools Used
- Wikipedia Tool: Fetches information from Wikipedia for general queries.
- Math Solver: Solves math-related problems, providing step-by-step explanations.
- Reasoning Tool: Handles logic-based or reasoning questions using a customized prompt template.

## API Key
- You will need a Groq API key to run the app. Enter the key in the sidebar to authenticate and start querying the LLM.

## Dependencies
- Python 3.7+
- Streamlit
- LangChain
- Groq API
- WikipediaAPIWrapper
