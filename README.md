# Monkeytype Name Checker ✅

My first project with Python, used to check the availability of names on https://monkeytype.com/.

## Running the File

1. Download and install the latest version of [**Python**](https://www.python.org/downloads/).  
2. After doing so, open **Command Prompt** and enter the following: `pip install requests` and `pip install colorama`
3. Now download the [**rmni.py**](https://github.com/willrmni/monkeytype-name-checker/blob/main/rmni.py) file.
4. Navigate to **File Explorer**, locate the directory [rmni.py](https://github.com/willrmni/monkeytype-name-checker/blob/main/rmni.py) is in and enter `cmd` in the address bar. This will open the file's directory in **Command Prompt**.
5. In the new **Command Prompt** window, enter the following: `python rmni.py`

From here, the [**list of words**](https://github.com/willrmni/monkeytype-name-checker/tree/main?tab=readme-ov-file#personalizing-the-list) in the [rmni.py](https://github.com/willrmni/monkeytype-name-checker/blob/main/rmni.py) file will be checked against the **Monkeytype API**.

## Personalizing the List

* By default, the list is the [1,000 most common US English words](https://gist.github.com/SivilTaram/9597125e4134cc81648027b1c6f6395f).
* To customize on a large scale, I suggest using [**ChatGPT**](https://chatgpt.com/), as it saves tons of time. Here is the prompt I used:

  > Make a list with the provided words following this rule: usernames = ["", ""] *(enter your list of words here, without parenthesis)*

* If you choose to do the same, go to a text editor of your choice *(Notepad, Notepad++, Visual Studio Code, etc.,)* replace **line 33** *(and below as needed)* with the text ChatGPT provided you, save the file, and [run it](https://github.com/willrmni/monkeytype-name-checker/edit/main/README.md#running-the-file)!

## Rate Limit
* The **Monkeytype API** seems to rate limit an IP for a period of time after a certain amount of requests. I don't know the amount of time or requests, and I will not be dedicating my time to discovering or publishing these queries and/or their bypasses.
