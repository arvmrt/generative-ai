## OpenAI GPT


### Getting Started

#### Prerequisites
```
- RHEL8/CENTOS8
- Python 3.12.1
```

#### Create a virtual environment
```
mkdir myenv
pip -m venv myenv
source myenv/bin/activate
```

#### Install Packages 
```
pip install openai
pip install tiktoken
pip install python-dotenv
```

#### Create a ".env" file under the project directory and add the following API KEYS:
```
OPENAI_API_KEY = '<Paste your OpenAI API Key>'
```




