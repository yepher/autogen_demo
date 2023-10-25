# Integrate AutoGen into your Chatbot: Code Interpreter Clone

This is code from the Medium article [Integrate AutoGen into your Chatbot: Code Interpreter Clone](https://levelup.gitconnected.com/integrate-autogen-into-your-chatbot-code-interpreter-clone-2ba71e264ad3).


## How to Run


### CLone Project

```
git clone git@github.com:yepher/autogen_demo.git
cd autogen_demo
```

### Setup Python venv

```
python -m venv ./.venv
source .venv/bin/activate
```

### Install Dependencies

```
pip install --upgrade pip
pip install -r requirements.txt
```

### Run

```
# First time:
cd autogen_demo
source .venv/bin/activate
export OPENAI_API_KEY="sk-...."

# Run it
./.venv/bin/chainlit run app.py
```
