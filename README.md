# Langflow Tool Calling Agent Test: Math Flow  

This repository demonstrates a test of Langflow's *Tool Calling Agent*, showcasing how different tools can be seamlessly integrated into AI workflows to enhance their capabilities.  

The primary objective of this project is to build a loan calculator that answers user queries based on their profile information while integrating Langflow components like the calculator and OpenAI GPT-4o.  

---

## Repository Contents  

### Files  
1. **`Math_Flow.json`**  
   - Contains the complete flow and components used in the Langflow setup.  
   - Includes inputs like user profiles and questions, a *Tool Calling Agent*, a calculator tool, and an OpenAI component.  

2. **`Math_with_LLM.docs`**  
   - Provides sample questions and user profiles used during the testing phase.  
   - Helps understand the types of inputs the flow is designed to handle.  

---

## Project Highlights  

1. **Tool Calling Agent Integration:**  
   - Demonstrates how to use the *Tool Calling Agent* as a wrapper to integrate multiple tools.  

2. **Calculator as a Tool:**  
   - Solves basic arithmetic and loan-related queries, enhancing the accuracy of responses.  

3. **User Profiles:**  
   - Tailors outputs based on user-specific inputs like age, risk appetite, yearly salary, and monthly expenses.  

4. **OpenAI Component:**  
   - Connects to GPT-4o using an OpenAI API key to process questions and provide context-aware outputs.  

---

## How to Use  

### 1. Setup Langflow  
- Install Langflow from its official documentation: [Langflow GitHub](https://github.com/langflow/langflow).  
- Ensure you have access to the OpenAI API key for the LLM component.  

### 2. Import the Flow  
- Open Langflow and log in.  
- Import the `Math_Flow.json` file to load the pre-built flow.  

### 3. Customize Inputs  
- Use the sample inputs from `Math_with_LLM.docs` to test different scenarios.  
- Modify the user profile or question inputs as needed.  

### 4. Run and Observe  
- Execute the flow in Langflow's playground to see how the agent works.  
- Check how outputs change based on different profiles and questions.  

---

## Deployment Options  

Once finalized, the flow can be deployed using Langflow’s built-in deployment options:  
- Python API  
- cURL commands  
- Exported Python code  

---

## Acknowledgments  

Special thanks to Langflow for providing an intuitive low-code platform that enables AI engineers and data scientists to create powerful solutions with ease.  

---

## Feedback  

If you have any feedback or suggestions, feel free to open an issue or reach out!  This
