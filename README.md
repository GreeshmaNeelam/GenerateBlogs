# GenerateBlogs
GenerateBlogs is a lightweight, Streamlit-based web application designed to automate blog writing using LLaMA 2, a powerful large language model. The app utilizes LangChain for prompt engineering and CTransformers to run the LLaMA 2 model locally, ensuring efficient and private content generation.

# Model Setup

Due to large file size, the LLaMA 2 model is not included in this repository.

To use this project, please follow the steps below to download the model manually:

1. Visit the official Hugging Face repository:
   👉 [TheBloke/LLaMA-2-7B-GGML](https://huggingface.co/TheBloke/LLaMA-2-7B-GGML)
2.  Download the **Model**: [`llama-2-7b-chat.ggmlv3.q8_0.bin`]

3. Create a folder named `models` (if it doesn't already exist) in the root of this project.
4. Place the downloaded `.bin` file inside the `models/` directory.
5. Your project directory should now look like this:
GenerateBlogs/
├── app.py
├── requirements.txt
├── models/
│ └── llama-2-7b-chat.ggmlv3.q8_0.bin


**Install the dependencies** -
pip install -r requirements.txt

▶️**Run the App** - 
streamlit run app.py


