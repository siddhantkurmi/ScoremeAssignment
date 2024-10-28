# Implementing Llama-3.2-1B Model

## Summary

This notebook, Model.ipynb, provides a step-by-step implementation of the LLaMA-3.2-1B model for predicting the next n tokens. The structure is designed for easy review, guiding the user through each stage of the process.

Setup: The notebook retrieves a secret token from the environment, allowing secure access to model resources.
Model Download: The model is then downloaded and set up for use.
Quantization: After downloading, the model is quantized to optimize inference efficiency.
Prediction Function: Using the custom prediction function, the model generates the next n tokens based on input text.
Inference Time Calculation: The inference time is calculated by measuring the total time taken to predict the tokens, then dividing by the number of tokens generated.

## Instructions 

Update HF_TOKEN: Add your Hugging Face API token in the .env file under HF_TOKEN. Ensure your Hugging Face account has the necessary permissions to access the Meta LLaMA model. If you’re not authorized, you can visit this link to enable access.

Set Up Environment: Create a virtual environment and install dependencies by running the requirements.txt file. This will ensure all required libraries are available for the notebook.

Run model.ipynb: Open model.ipynb and run each cell sequentially to execute the full model pipeline and generate results.
