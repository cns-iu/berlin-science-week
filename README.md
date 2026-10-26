# Berlin Science Week

## HRA-HPO Slides



## Quarto

We will use the **quarto** system for creating slides with a markdown-like syntax

First, install the [quartp](https://quarto.org/quarto] following the installation instructions for your system. I have found it useful to create the slides using [ VS Code](https://code.visualstudio.com) but any editor will work.


You will need to create a Python virtual environment and use to install some packages needed by the quarto ecosystem

```bash
python3 -m venv venv
source venv/bin/activate
pip install --upgrade pip
pip install jupyter ipykernel 
```

* Before running quarto (each time), you will need to activate the environment
and then start the server.
```bash
source venv/bin/activate
quarto preview 
```



## GitHub actions

The slides will be created on GitHub io upon checking in via a GitHub action.