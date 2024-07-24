---
title: CustomizedLLMApp
emoji: 💬
colorFrom: yellow
colorTo: purple
sdk: gradio
sdk_version: 4.36.1
app_file: app.py
pinned: false
---

An example chatbot using [Gradio](https://gradio.app), [`huggingface_hub`](https://huggingface.co/docs/huggingface_hub/v0.22.2/en/index), and the [Hugging Face Inference API](https://huggingface.co/docs/api-inference/index).
................................................................................................................................................................

# Assistant Pilot

This is a college project that develops an interactive communication system that uses the Gradio library and uses the Hugging Face Inference API to provide intelligent feedback to users The application is designed to act as a pilot assistant, helping them with tasks types of aircraft and questions.

## features

1. **Chat Interface**: The application provides a chat-based interface where users can interact with the assistant and ask questions.
2. **Intelligent Response**: The Assistant uses pre-trained speech models (in this case the "zephyr-7b-beta" model from Hugging Face) to find and deliver appropriate responses more information on user questions
3. **Context Awareness**: The assistant maintains conversation history and can provide a tailored response to the user first.
4. **Customizable parameters**: The user can configure the maximum number of new tokens, temperature, and top-p (nucleus sampling) parameters to control response generation by the assistant.
5. **Sample Questions**: The application provides a variety of sample questions that users can use to get started and understand the assistant’s capabilities.

## Survey

Follow these steps to activate the co-pilot.

1. Make sure you have Python and the necessary dependencies (Gradio and Hugging Face Hub) installed.
2. Run the Python script `main.py` to launch the application.
3. The Gradio interface opens in your default web browser.
4. You can start a chat with the assistant by typing your questions or questions in the chat input field.
5. Modify adjustable parameters as needed to fine-tune the assistant response.
6. Analyze sample questions to get a better understanding of the facilitator’s capabilities.
## Custom designs

You can modify the following parts to customize the co-pilot.

1. **Assistant Persona**: You can change the configuration messages that display the personality and actions of the assistant.
2. **Inference Model**: You can use a different pre-trained language model by modifying the line `client = InferenceClient("HuggingFaceH4/zephyr-7b-beta")`.
3. **Gradio Interface**: You can customize the Gradio chat interface by changing the parameters passed to the `gr.ChatInterface` function.
4. **Sample Questions**: You can add or modify sample questions to suit your specific application.

## Dependencies

This project is based on the following Python libraries:

- `gradio`: to create an interactive dialog interface.
- `huggingface_hub`: to access the Hugging Face Inference API to generate responses.

Be sure to configure these dependencies before running the application.

## conclusion

Pilot Assistant is a college project that demonstrates the use of Gradio and Hugging Face Inference APIs to create interactive and intelligent assistants for pilots It demonstrates how natural language processing and machine learning can be used to provide users with helpful information and about context. This work can be further expanded and customized to meet the specific needs of the airline.
