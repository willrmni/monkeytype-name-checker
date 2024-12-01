# Monkeytype Name Checker ✅

My first project with Python, used to check the availability of names on https://monkeytype.com/.

## Running the File

* First, download and install the latest version of **Python** [here](https://www.python.org/downloads/).
* Next, open **Command Prompt** and enter the following: `pip install colorama`
* Now, in **File Explorer**, locate the directory the [rmni.py](https://github.com/willrmni/monkeytype-name-checker/blob/main/rmni.py) file is in and enter `cmd` in the address bar. This will open the correct directory in **Command Prompt**. 

![image](https://github.com/user-attachments/assets/a95eb324-9340-4e88-a101-74b93f091aac)


* Now that you're in the correct directory, enter the following: `python rmni.py`

![image](https://github.com/user-attachments/assets/6e72dddf-bd56-4a2d-91b1-6c92a45348f1)

* From here, the list of words in the [rmni.py](https://github.com/willrmni/monkeytype-name-checker/blob/main/rmni.py) file will be checked against the Monkeytype API.

![image](https://github.com/user-attachments/assets/0971538c-1543-4e84-aa37-0f4d4cda82af)

## Personalizing the List

* By default, the list is the 1,000 most common US English words found [here](https://gist.github.com/SivilTaram/9597125e4134cc81648027b1c6f6395f).
* To customize on a large scale, I suggest using ChatGPT, as it saves tons of time. Here is the prompt I used:

> Make a list with the provided words following this rule: usernames = ["", ""] (without parenthesis, enter a list of words you'd like)

![image](https://github.com/user-attachments/assets/058a48b2-ac35-4667-ba43-3ff02f028d4f)

* Now in the text editor of your choice *(Notepad, Notepad++, Visual Studio Code, etc.,)* replace **line 33** *(and below as needed)* with the text ChatGPT provided you. Use CTRL + S to save, and [run it]()!

![Side-by-side](https://github.com/user-attachments/assets/c033ee49-492d-474d-90e6-bf35da9a8e64)

## Rate Limit
* The Monkeytype API seems to rate limit IPs for a certain amount of time after a certain amount of requests. I do not know the specifics, nor do I intend to exploit the way their API operates.
