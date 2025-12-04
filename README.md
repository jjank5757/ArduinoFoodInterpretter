# ArduinoFoodInterpretter
Arduino and openAi / machine learning to see and give you information about a food item! 
The arduino will have three lights; red, yellow, green. Regarding whatever food item you show it will diplay the macros on the Arduinos LED. You will receive feedback via voice or a short message regarding nutritional facts related to whatever food item is shown. The point of the project is to enable a quick way of knowing calories, protein, carbs, and fats about any food item. We are incorporating google/VIT-Base-Patch 16-224. 

#HuggingFace
ChatGPT
ArduinoIDE
IDLE Python
VS Code

IT Project

In this project we are going to make an AI Macronutrient counter. The goal is to put food in front of the camera and have the model recognize the food and use Groq's Llama-3.1-8b-instant model to find the macronutrients and display them onto a LED screen.

Download food recognition model from HuggingFace:

     - nateraw/vit-base-food101

 Upload Arduino Code:

     -The code will display the proteins, fats and carboohydrates on a screen.

Connect Python code to Arduino:

     -Put Python code into Visual Studio Code
     
     -Code should reference the food recognition model and Groq Llama-3.1-8b-instant model to classify the food and estimate macronutrients.
