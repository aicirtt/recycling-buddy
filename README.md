# recycling-buddy


This bot helps users easily determine whether an item is recyclable or just trash by simply uploading or taking a picture. Additionally, if the item is recyclable, the bot will provide the 5 nearest recycling spots based on the user's location.

📸 How It Works
1. Upload or Take a Picture:
- Users can upload or take a picture of the item they want to check.
2. Get a Classification:
- The bot will analyze the image and categorize the item as either Recyclable or Trash.
3. Find Nearby Recycling Spots:
- If the item is recyclable, the bot will prompt the user to input their location.
- The bot will then provide the 5 nearest recycling spots where the item can be properly disposed of.

🖼️ Best-Case Scenario Pictures
We've included a few best-case scenario pictures in the code files to help you get started. These images are optimized for testing and can be used to understand how the bot works in different scenarios.

Feel free to explore and use these images at https://t.me/Recyclops_bot to test the accuracy and functionality of the bot!

----------
This bot was adapted from the trained model at this link [https://www.kaggle.com/code/bouweceunen/garbage-detection-with-tensorflow/notebook].
The locations of the recycling bins were adapted from gov.sg's api and cleaned up.


#Part 1: Overview of the Proposed Solution
Our telebot provides a user-friendly interface to help users determine if their trash is recyclable. By simply interacting with the bot, users can classify their waste and receive suggestions on the five nearest recycling spots based on their current location. The key advantage of this solution lies in its simplicity and accessibility, allowing users to make environmentally-conscious decisions effortlessly. Additionally, we adapted and researched how to use Garbage Detection with TensorFlow, ensuring accurate classifications and recommendations.

#Part 2: Setup and Running Instructions
To run this solution, we use a telebot as the primary interface for user interaction. The implementation involves adapting and researching Garbage Detection techniques using TensorFlow. For location recommendations, we sourced and cleaned recycling bin location data using the data.gov.sg API. The cleaned data is then used to suggest the top few recycling locations to users based on their proximity. Ensure that all dependencies are installed, and the environment is properly set up as per the instructions below to run the telebot smoothly.
