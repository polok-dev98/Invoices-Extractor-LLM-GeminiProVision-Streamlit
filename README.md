
## Code Description

The code in this repository comprises a Streamlit-based application that integrates Google's Generative AI service, specifically utilizing the `gemini-pro-vision` model provided by the `google.generativeai` library. The project is about to invoices extractor app. you can upload a image and make query, the app able to ans your query.

### Components:

- **`app.py`**: The main application file containing the Streamlit app setup. It allows users to input textual prompts and upload images. Upon submission, the application interfaces with Google's Generative AI to generate a response based on the provided prompt and image.

- **`requirements.txt`**: Lists all the necessary Python packages required to run the application. Use `pip install -r requirements.txt` to install dependencies.

- **`.env.example`**: An example file illustrating the environment variable setup. Create a `.env` file with your Google API key for proper configuration.

### Functionality:

The `get_gemini_response` function serves as the interface with Google's Generative AI. It takes input text, to generate a response by utilizing the `gemini-pro` model.


### Usage:

1. Clone the repository:

    ```bash
    git clone https://github.com/polok-dev98/Gemini-LLM-QuestionAnswering-apps-with-streamlit.git
    cd your_project
    ```

2. Install dependencies:

    ```bash
    pip install -r requirements.txt
    ```

    Make sure to configure your environment variables by creating a `.env` file with your Google API key.

3. Run the application:

    ```bash
    streamlit run app.py
    ```
