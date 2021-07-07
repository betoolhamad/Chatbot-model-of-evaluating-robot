# Chatbot model of evaluating robot
This chatbot is made to make people evaluating. I have trained the bot to be able to respond to people's questions which is related to the evaluation and interact with them using python language.

<h3> Prerequisites : </h3>   
 Python and any sourse code editor. I'm using Visual Studio Code and i use (miniconda) prompt in windows to install pakages and run the script.    
 
 So, before starting to work on our chatbot we need to download a few python packages in our enviroment. 
 
**First, create virtual enviroment we will run this command in the terminal (Prompt (miniconda)) :**
 ```
 conda create --name bot python=3.6
 ```
 which bot is name of my enviroment.  
 
 **Second, we will install anconda pip inside our enviroment via run :**
  ```
  conda install -c anaconda pip
 ```
 
 **Third, we will start run the enviroment via command:**
  ```
  activate bot
 ``` 
**Finally, we are inside our enviroment.**

Now we will install python pakages we need it to our chatbot script which is the Requirements.txt file has the pakages we want to install and its attached above.
So, we will enter the dirctory that has this text file to install pakages. by run `cd` and append to it the path of that txt file.  

Now we will simply use pip to install the following:  
- nltk  
- numpy
- tensorflow  
- tflearn  
- 
by run :
 ``` 
 pip install -r Requirements.txt 
  ``` 

**Now our enviroment is ready!**

<h3> training : </h3>  
After we write our code, it's time to train our bot. We will use the data that we write ourselves in the JSON file.   
This is the format of JSON file which i was created.

<img width="700" alt="2021-07-08 (5)" src="https://user-images.githubusercontent.com/43522153/124837754-28ee7b80-df8e-11eb-9480-4b4345f6e9dd.png">

This is the result when I talked with the robot I called it Bandi :)



**Note: I faced a problem when I was writen the JSON file, when I add or remove tags from the JSON file and rerun the program, it doesn't seem to change any of the responses. After looking, finally, I found the way to fix this problem, which is to delete the data.pickle file, which is directly created when writing a JSON file. That is the solution to why the JSON file doesn't change when I was tried to edit it..**










