# Virtual_talking_friend
This is a virtual talking friend which if you write something in the console it will repeat the same what you will write in the console.
I have done it by using Pycharm which is an python code editor.
For the code I have used a pip (python installation package) which is **pip install pyttsx3 (python text to speech version 3)**
In the code I have imported the package pyttsx3 but before that in the terminal I have installed the same package.
Then I have created a variable called friend which is the virtual talking friend and put the value as pyttsx3.init() init means initiate.
Then I have created another variable called speech and put the value as input("Say Something: ")- This block means the virtual talking friend will input as Say Something in the console and let's us enter the text.
Then I put friend.say (speech) which means it will have to say what I enter and what I enter is stored in the variable called speech as when he asks Say Something we type
after the question and whatever comes after the quetion is stored in the variable called speech.
And then at the last I have said friend.runAndWait()
And when we run the Program your virtual friend is ready.
