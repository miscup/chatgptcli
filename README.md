# chatgptcli
The command line wrapper for ChatGPT

[ChatGPT-PyPi](https://pypi.org/project/chatgptcli/)


## Install
```
pip install chatgptcli --upgrade
```

## Terminal Chat
```python
from chatgptcli import ChatGPT

ChatGPT(email="email", password="password").chat()
```

## Ask a Question
```python
from chatgptcli import ChatGPT

chatGPT = ChatGPT(email="email", password="password")
print(chatGPT.ask("Write a rap song"))
```
