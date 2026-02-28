# Gemini Historical Artifact Description App

This web application uses Google's Gemini AI to generate unique and detailed descriptions of historical artifacts. Users can input an artifact name or historical period, specify the desired word count, and optionally upload an image. The app generates engaging content and shares a fun historical fact while processing.

## Features

- Generate detailed artifact descriptions using Gemini 2.5 Flash
- Specify artifact name/period and word count
- Optional image upload for richer context
- Fun historical facts displayed during generation
- Simple Streamlit web interface

## Setup Instructions

1. **Clone the repository or copy the project files**
2. **Install dependencies**
   ```
   pip install -r requirements.txt
   ```
3. **Set up your Google Gemini API key**
   - The API key is set in `app.py` as `API_KEY`. Replace it with your own if needed.
   - [Get your API key here](https://developers.generativeai.google/)
4. **Run the app**
   ```
   streamlit run app.py
   ```
5. **Open the app**
   - Visit the local URL shown in your terminal (usually http://localhost:8501)

## File Structure

- `app.py` - Main Streamlit application
- `requirements.txt` - Python dependencies
- `README.md` - Project documentation

## Example Usage

1. Enter an artifact name (e.g., "Tutankhamun's Golden Mask")
2. Set the desired word count (e.g., 1200)
3. (Optional) Upload an image of the artifact
4. Click "Generate Artifact Description"
5. Review and use the generated content

## Notes

- Make sure your API key has access to the Gemini 2.5 Flash model.
- For best results, use descriptive artifact names and reasonable word counts.

---

Developed with ❤️ using Streamlit and Google Gemini AI.
