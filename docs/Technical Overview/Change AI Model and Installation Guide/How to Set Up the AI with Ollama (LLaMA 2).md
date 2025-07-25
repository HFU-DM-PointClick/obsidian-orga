
### Requirements

- OS: Windows, macOS, or Linux
- At least **8 GB of RAM** recommended


### Step 1: Install Ollama

**For all platforms (via `curl`):**

`curl -fsSL https://ollama.com/install.sh | sh`

Alternatively, download the installer from: [https://ollama.com](https://ollama.com)


### Step 2: Download LLaMA 2 model

To pull the 7B model:

`ollama pull llama2:7b`

for the beginning we need the 7b version, without changing the code beforehand, the game will not work.

This will download the model (~3–4 GB). Once downloaded, it's available locally.


### Step 3: Run the model

Start the model with:

`ollama run llama2:7b`

You should see something like:

`Starting llama2:7b... Listening on http://localhost:11434`


---


### How to change the model (in Godot)

1. Inside the Godot script (e.g. `interrogation_ai.gd`), find this section:

`"model": "llama2:7b"`

![[Pasted image 20250725180853.png]]

and open the file "interrogation.gd"


2. To use a different model (e.g. `mistral` or `llama3`), simply change this line of code:

![[Pasted image 20250725181007.png]]
and change "llama2:7b" to the model you want to use, but make sure to pull the model first:

`ollama pull "modelname"`

---

### ✅ Quick Command Overview

|Purpose|Command|
|---|---|
|Install Ollama|`curl -fsSL https://ollama.com/install.sh \| sh`|
|Download LLaMA 2 model|`ollama pull llama2:7b`|
|Run the model|`ollama run llama2:7b`|
|Check connection|`curl http://localhost:11434`|
|List downloaded models|`ollama list`|