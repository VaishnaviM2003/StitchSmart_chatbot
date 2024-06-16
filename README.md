# StitchSmart_chatbot: Interactive Chatbot for Dress Design Selection and Tailor Connection
This bot is an interactive chatbot designed to assist users in selecting dress designs, managing measurements, and connecting with tailors seamlessly. Built using Python and leveraging natural language processing techniques, it provides a user-friendly interface for dress selection and measurement customization.

## Features
- Natural Language Understanding: Utilizes TF-IDF vectorization and cosine similarity to comprehend user inputs.
- Context Management: Maintains conversation context for smooth multi-turn dialogues.
- External Data Integration: Fetches dress designs and tailor information from JSON files.
- History Tracking: Records user interactions and bot responses in history.txt.
- Reset and Rollback: Supports conversation reset and rollback functionalities.

## Technologies Used
- Python Libraries: numpy, pandas, nltk, scikit-learn, json.
- Development Environment: Google Colab.

## Example Interaction
'''User: hi
Bot: Hello there. Customize stitching services at your doorstep! What dress style are you looking for?

User: 15
Bot: You have chosen the following design: [details]. Please enter the color.

...

User: yes
Bot: Dress Type: [type]
Please select your measurements:
[options]

Bot: Selected Measurements. Please enter the tailor ID you want to connect to from the website.

...

User: Thank you
Bot: Happy to help!''' 

## Future enhancements
- Graphical User Interface (GUI): Implement a GUI for enhanced user interaction.
- Advanced NLP Models: Integrate deep learning models for more sophisticated natural language understanding.
- Web Deployment: Deploy as a web service for broader accessibility.

## Contributors
- Vaishnavi M 
- Srihari M
