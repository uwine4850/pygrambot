<div align="center">
  <img width=300px height=200px src="https://github.com/uwine4850/pygrambot/tree/master/docs/pgb_logo.svg" alt="Project logo">
</div>

<h1 align="center" style="margin: 0">Pytelegrambot</h1>

## Content
* [Guide to Basic Operations](https://github.com/uwine4850/pygrambot/tree/master/docs/create_project.md)
* [Guidelines for creating middlewares](https://github.com/uwine4850/pygrambot/docs/tree/master/create_middlewares.md)
* [Built-in data types](https://github.com/uwine4850/pygrambot/tree/master/docs/data_objects.md)


## About the project <a name = "about"></a>

Pytelegrambot is a python framework for creating telegram bots. The framework is completely asynchronous. The main idea of ​​this project is to make the architecture of telegram bots as structured, as possible and easy to use and understand.

## Getting Started <a name = "getting_started"></a>

To create your own project, follow these instructions.

### Installing

To install, run the following command:

```
pip install pytelegrambot
```
After executing the command, the framework will be available in your python virtual environment.

### Create and set up a project

First you need to create a python file (in this example, there will be a "main" file) and write the following code in it:
```
from pygrambot.cli import bot_cli
```
Bot console commands are now available. To create bot configuration files, run the following command:
```
python3 main.py init
```
The config directory has now been created in the root directory of the project, which contains the configuration files. For the minimum performance of the bot, you need to specify your own bot token.
To start the bot, you need to enter the command:
```
python3 main.py start
```

> How to use the bot further can be found in the [additional instructions](https://github.com/uwine4850/pygrambot/tree/master/docs/create_project.md).