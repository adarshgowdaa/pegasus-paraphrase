# pegasus-paraphrase

## Introduction

In this project, we will use the PEGASUS model from Google Research to paraphrase text. Particularly, we will be using the transformers library to apply the PEGASUS model to perform the text paraphrasing. PEGASUS is an acronym for Pre-training with Extracted Gap-sentences for Abstractive Summarization Sequence-to-sequence models.

#### Example:

```
# Input

Python is a programming language with many characteristics, such as an intuitive syntax and powerful data structures, which can lead to efficient code. It's no wonder that this, as well as experienced developers, are benefitting. Programmers use Python for different tasks. Some use it as their primary language because it is concise and easy to read. Others include it in their toolkit because of its impressive batteries (libraries) that are available for pursuing practically any task imaginable.

# Output:

Python is a programming language with many characteristics, such as an intuitive syntax and powerful data structures, which can lead to efficient code. This, as well as experienced developers, are benefiting. Python is used by programmers for different tasks. It is easy to read and some people use it as their primary language. Other people include it in their toolkit because of its impressive batteries.


```

### Cloning the repository

--> Clone the repository using the command below :

```bash
git clone https://github.com/adarshgowdaa/pegasus-paraphrase

```

--> Move into the directory where we have the project files :

```bash
cd pegasus-paraphrase

```

--> Create a virtual environment (Optional) :

```bash
# Let's install virtualenv first
pip install virtualenv

# Then we create our virtual environment
virtualenv envname

```

--> Activate the virtual environment :

```bash
envname\scripts\activate

```

--> Install the requirements :

```bash
pip install -r requirements.txt

```

#

### Running the App

--> To run the App, use :

```bash
python ./main.py

```
