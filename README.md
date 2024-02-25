In this project, an end-to-end LLM project using LLAMA-2 was implemented in order to create a web application for blog generation. The Llama-2 hugging face model weight was utilized during development and implementation. 
A family of pre-trained and fine-tuned LLMS, with scales ranging from 7B to 70B parameters (7B, 13B, and 70B), is included in the Llama-2 release. 
The local environment in which this project was implemented had four cores and eight logical processors. 
It was simpler to use the 7B parametered llama-2 model. 

**Project execution steps:**
1. Get the most recent model weights from the community of hugging face. (Website: huggingface.co/TheBloke/Llama-2-7B-Chat-GGML/tree/main)
2. Save it to a project folder, then open Visual Studio Code to begin implementing it.
3. Write requirment.txt to install required libraries.
4. Assuming best practices for coding, create a virtual environment to execute project. (Command: python -m venv <env_name> )
5. Rub: **pip install -r .\requirements.txt** (Deployment requires some time)
6. Streamlit has been used forthe development of web application interfaces.Three inputs are required from the user: the blog's topic, word count, and writing for the blog i.e. Type of Audience.It generates content based on the specified parameters by utilizing the llama2 model in the background.
7.Run: **python -m streamlit run app . py** is the command to execute app.py. Because of my low-end local machine, it took about two to three minutes to produce the result. For your reference, a sample screenshot is attached.
