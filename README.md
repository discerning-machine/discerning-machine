# Discerning-Machine
A that discerns.

In order to launch it from the command line or as a Python subprocess:
```bash
echo "Theodotos-Alexandreus: What is the difference here, machine?" \
  | uvx discerning-machine \
    --provider-api-key sk-proj-... \
    --github-token ghp_... 
```

Or, with a local pip installation:
```bash
pip install discerning-machine
```
Set the environment variables:
```bash
export PROVIDER_API_KEY="sk-proj-..."
export GITHUB_TOKEN="ghp_..."
```
Then:
```bash
discerning-machine -a multilogue.txt
```
Or:
```bash
discerning-machine multilogue.txt > response.txt
```
Or:
```bash
discerning-machine -a multilogue.txt > tmp && echo tmp > multilogue.txt
```

Or use it in your Python code:
```Python
# Python
import discerning_machine
```
