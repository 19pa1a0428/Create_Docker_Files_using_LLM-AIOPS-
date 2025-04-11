# 🚀 **Creating Docker Files Using LLMs**  
Welcome to the **Creating Docker Files Using LLMs** project! This tool generates Dockerfile structures for various programming languages by leveraging the power of large language models (LLMs). Whether hosted locally or via API, it simplifies Dockerfile creation for developers.  

---

## 🛠️ **Project Overview**  
This project uses LLMs to:  
- Prompt users for a programming language.  
- Automatically generate Dockerfile structures with appropriate base images.  

### 🔧 **Approaches**  
1. **Local Hosting using Ollama 3.2.1B**  
   - A lightweight model suitable for running on personal machines.  
   - Other options include larger models like the 3B parameter model, depending on requirements.  

2. **Hosted API using Gemini 1.5 LLM**  
   - Free API provided by Google AI Studio.  
   - No need to host models locally, saving resources.

---

## 🖥️ **Approach 1: Run Locally with Ollama**  

### Steps to Run Locally:  
1️⃣ **Install Ollama:**  
   Run the following commands in your terminal:  
```
curl -O https://ollama.ai/download/ollama-3.2.1B.tar.gz
tar -xvf ollama-3.2.1B.tar.gz
cd ollama-3.2.1B
./install.sh
```


2️⃣ **Identify and Pull Ollama Model:**  
Use the following command to pull the model:  
```
ollama pull 3.2.1B
```


3️⃣ **Set Up Python Virtual Environment:**  
To avoid version conflicts, set up a virtual environment:  
```
python3 -m venv venv
source venv/bin/activate
```


4️⃣ **Write Python Script:**  
The Python script structure should follow this format:  
```
Import necessary libraries
Prompt user for programming language input
Define functions to interact with Ollama model
Call the function and generate Dockerfile output
```


---

## 🌐 **Approach 2: Use Hosted Gemini 1.5 API**  

### Steps to Run Using Hosted LLM API Key:  

1️⃣ **Generate API Key in Google AI Studio:**  
- Log in to [Google AI Studio](https://ai.google.com/studio).  
- Create a free API key for Gemini 1.5.

2️⃣ **Install Dependencies:**  
Run these commands to install required libraries:  
```
pip install google
pip install google-generativeai
```

3️⃣ **Write Python Script:**  
The Python script structure should follow this format:  
```
Import necessary libraries (e.g., google.generativeai)
Set up API key securely (use dotenv or environment variables)
Configure the library with the API key
Prompt user for programming language input
Define functions to interact with Gemini model
Call the function and generate Dockerfile output
```

---

## 💼 **Use Case in Companies**  

This tool can be distributed within organizations to streamline Dockerfile creation for developers, saving time and reducing costs associated with manual efforts.

---

## 🙏 **Acknowledgment**  

Special thanks to **Abhishek Veeramalla AIOPS Playlist** for providing valuable resources that inspired this project! 🎉

---

## 📜 License  

Feel free to use and modify this project as needed! 🚀  

--- 
