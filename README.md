🎶 Emotion-Based Music Player 🎶
Welcome to the Emotion-Based Music Player, a fun, interactive, and smart music player that reads your emotions and adapts accordingly! 😄😌😡😢

Built for TOHacks 2021, this web app utilizes cutting-edge machine learning algorithms to detect your mood through facial recognition, then recommends a custom playlist and changes the background theme based on your emotion! 🧠💻🎧

🚀 Getting Started:
Ready to get the app running on your local machine? Follow these simple steps:

Clone this repository:

bash
Copy
Edit
git clone https://github.com/your-username/emotion-music-player.git
cd emotion-music-player
Install dependencies:

bash
Copy
Edit
pip install -r requirements.txt
Run the server:

bash
Copy
Edit
python manage.py runserver
🔧 Prerequisites:
Check out the required dependencies in requirements.txt to ensure the app runs smoothly. Some of the key libraries used are:

tensorflow-cpu: For training and using the emotion detection model 🧠

opencv-python-headless: Used for facial recognition 👀

Django: Backend framework for smooth integration 🖥️

gunicorn: For hosting the app on Heroku ⚙️

🌍 Deployed App:
Experience the magic right now! The web app is already deployed on Heroku:

Live Demo - Emotion-Based Music Player 🎧

💡 How It Works:
Using a Haar Cascade face detection model 🧑‍💻, combined with a CNN classifier trained on TensorFlow 📊, the app detects four key emotions—Angry, Happy, Calm, and Sad—from your facial expression. The app then dynamically changes the music playlist and background according to your mood! 🎶

🔬 Built With:
HTML/CSS: For creating the attractive front-end design 💅

JavaScript: To handle the interactive music player functionality 🎵

Django: Backend integration to power the emotion-based logic 🔄

OpenCV: Face detection for emotion recognition 📸

TensorFlow: For training the emotion classifier 🔍

📊 Training the Model:
The emotion detection model was trained using a dataset from the Kaggle Facial Expression Recognition Challenge. The dataset consists of 48x48 grayscale images of faces, and we used the four most common emotional expressions: Angry, Happy, Calm, and Sad. 🤖💓

Final Accuracy: 58.33%
Validation Accuracy: 54.99%

📁 Dataset:
You can access the dataset used to train the model from Kaggle's Facial Expression Recognition Challenge. A direct link to the dataset can be found here.

🌟 Contribute:
Feel free to fork this repository and create a pull request if you have any suggestions or improvements. Let's make music and emotions even more fun! 🎉🎶

Enjoy your personalized music experience! 😎🎧
