


# Chatbot model of evaluating robot
This chatbot is made to make people evaluating. I have trained the bot to be able to respond to people's questions which is related to the evaluation and interact with them using python language.

# Prerequisites :   
 Python and any source code editor. I'm using Visual Studio Code and i use (miniconda) prompt in windows to install packages and run the script.    
 
 So, before starting to work on our chatbot we need to download a few python packages in our enviroment. 
 
**First, create virtual enviroment we will run this command in the terminal (Prompt (miniconda)) :**
 ```
 conda create --name bot python=3.6
 ```
 bot is name of my enviroment.  
 
 **Second, we will install anconda pip inside our enviroment via run :**
  ```
  conda install -c anaconda pip
 ```
 
 **Third, we will start run the enviroment via command:**
  ```
  activate bot
 ``` 
**Finally, we are inside our enviroment.**

Now we will install python packages we need it to our chatbot script which is the Requirements.txt file has the packages we want to install and its attached above.
So, we will enter the dirctory that has this text file to install pakages. by run `cd` and append to it the path of that txt file.  

Now we will simply use pip to install the following:  
- nltk  
- numpy
- tensorflow  
- tflearn  
by run :
 ``` 
 pip install -r Requirements.txt 
  ``` 

**Now our enviroment is ready!**

# Training: 
After we write our code which is attached above, it's time to train our bot. We will use the data that we write ourselves in the JSON file.   
This is the format of JSON file which i was created.

<img width="700" alt="2021-07-08 (5)" src="https://user-images.githubusercontent.com/43522153/124837754-28ee7b80-df8e-11eb-9480-4b4345f6e9dd.png">

This is the result when I talked with the robot I called it Bandi :)



https://user-images.githubusercontent.com/43522153/124925943-aacdbb80-e005-11eb-8bc8-1fe6aeb62cc1.mp4


**Note: I faced a problem when I was writen the JSON file, when I add or remove tags from the JSON file and rerun the program, it doesn't seem to change any of the responses. After looking, I found the way to fix this problem, which is to delete the data.pickle file, (it is directly created when I write in a JSON file)**




