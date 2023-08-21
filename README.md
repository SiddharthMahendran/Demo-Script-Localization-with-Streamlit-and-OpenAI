# Demo-Script-Localization-with-Streamlit-and-OpenAI
This repository contains the code and report for the Emplay Assignment on Demo Script Localization. The assignment focuses on localizing demo scripts using OpenAI's language model and presenting the pipeline through a Streamlit UI app.

##Table of Contents
1)Overview
2)Key Features
3)Setup
4)Usage
5)Report
6)Error Analysis
7)Future Improvements
8)References

##Overview
The assignment involves localizing demo scripts by translating text and replacing names. The pipeline incorporates OpenAI's language model for translation, Streamlit for the UI app, and ngrok for deployment. Users can upload documents, specify target language, and input their names for localization.

##Key Features
- Streamlit UI App: An interactive Streamlit app offers an intuitive interface for users to upload demo scripts, choose languages, and provide names for localization.
- Translation and Localization: The pipeline translates text using OpenAI's language model and replaces provided names as per user input.
- Name Replacement: Names in the document are replaced both separately and together, ensuring accurate localization.
- Deployment: ngrok is utilized to create a public URL and deploy the Streamlit app, making it accessible remotely.
- Error Handling: The app includes basic error handling to manage missing inputs and connectivity issues.

##Setup
1)Clone the repository.
2)Install the required packages: pip install openai python-docx streamlit pyngrok.
3)Set your OpenAI API key in the code.
4)Run the Streamlit app using streamlit run app.py.
5)Access the app using the ngrok-generated public URL.

##Usage
1)Upload a DOCX file containing the demo script.
2)Specify the target language (e.g., "es" for Spanish).
3)Input your first name and last name for name replacement.
4)Click the "Localize" button to generate the localized demo script.
5)Download the localized document from the app.

##Report
For a detailed report on the thought process, experiments conducted, and conclusions drawn from the project, refer to the Report section.

##Error Analysis
The Error Analysis section discusses encountered errors, challenges, and solutions during the development and testing of the pipeline.

##Future Improvements
Explore potential enhancements and optimizations for the pipeline, user interface, and translation quality. Suggestions and contributions are welcome.

##References
- Emplay Assignment Details
- OpenAI Documentation
- Streamlit Documentation
- ngrok Documentation
