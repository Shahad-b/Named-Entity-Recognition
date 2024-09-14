# 🌟 Named Entity Recognition

## 🎯 Purpose

This project aims to demonstrate named entity recognition (NER) for both English and Arabic languages. It utilizes Hugging Face Transformers and Gradio to extract and highlight named entities from the input text.

## 📂 Main Files

1. **`Text-to-text_pipeline`**: 
   - Contains the logic for loading NER models for English and Arabic.
   - Defines functions to extract entities from input sentences and return them as a Pandas DataFrame.
   - Includes example sentences for testing the NER functionality.

2. **`Gradio_components`**: 
   - Sets up the Gradio interface to display highlighted entities.
   - Contains predefined sentences for demonstration purposes and custom CSS for right-to-left text alignment.

3. **`Named_Entity_Recognition`**: 
   - Contains the logic for loading NER models for English and Arabic.
   - Defines functions to extract entities from input text and return them with highlighted entities.
   - Sets up the Gradio interface for user interaction.

## 🔄 Hugging Face Text-to-Text Pipeline

The Hugging Face text-to-text pipeline allows you to use pre-trained models for various natural language processing tasks. In this project, we leverage the NER pipeline to process input text, identify named entities, and return them in a structured format.

## 🚀 Instructions to Run the Code in Hugging Face

1. **Access the Project**:
   - Click on the following link to access the running Gradio interface: [Named Entity Recognition Project](https://huggingface.co/spaces/shahad-b/Named_Entity_Recognition).

2. **Test the Application**:
   - Once the interface is loaded, you can input text and select a language (English or Arabic).
   - Click on the submit button to see the recognized named entities highlighted in the output.

## 📊 Expected Output from the Gradio Interface

When you input text and select a language (English or Arabic), the Gradio interface will display the recognized named entities. The application will highlight these entities in the output text, showing their types (such as PERSON, ORGANIZATION, and LOCATION) alongside the original input.

## 🎥 Explainer Video

You can view the video here: [Project Video](<https://drive.google.com/file/d/1KyBjZE9bNuB5K5WEVYVehS_zVDVbatH-/view?usp=sharing>).
