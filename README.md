# Health-App-using-LLM

### Health Management App using Google Gemini LLM

This project is a **Health Management App** designed to analyze food items in an uploaded image, estimate the total calorie count, and provide detailed nutritional information for each food item detected. Leveraging **Streamlit** for a user-friendly interface and **Google's Gemini Pro Vision API**, the app allows users to upload images, which the system processes to generate accurate calorie insights.  

#### Key Features
- **Google Gemini Pro Vision API Integration**: Utilizes a generative AI model to interpret and analyze images with food items.
- **Calorie Breakdown**: Outputs a list of detected food items and the calories for each, plus an overall calorie summary.
- **User-Friendly Interface**: Built on Streamlit for ease of interaction, allowing text input for prompts and image upload for analysis.

#### Technologies Used
- **Python and Streamlit**: For building the front-end interface.
- **Google Generative AI**: Powering the back-end with the `gemini-pro-vision` model for food recognition and calorie estimation.
- **PIL (Python Imaging Library)**: For handling image uploads and display.
- **Environment Variables**: Managed via `dotenv` to keep API keys secure.

