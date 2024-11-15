Generating text & audio from images
An app that uses Hugging Face AI models to generate text from an image, which then generates audio from the text.

This application uses three steps to complete the above-mentioned task:

Image to text model to let the machine understand the scenario based upon the content of the photo
Use an LLM to generate a short story based on the text that was generated in step 1
Lastly, we will use a text to speech model to generate audio for the story from the LLM
System Design
system-design

Models
Image to text model: nlpconnect/vit-gpt2-image-captioning
Text to story model: gpt-3.5-turbo
Story to speech model: bark
Requirements
python -m pip install -r requirements.txt
Run App Locally
source build.sh
Run App with Streamlit Cloud
Launch App

License
Distributed under the MIT License. See LICENSE for more information.
