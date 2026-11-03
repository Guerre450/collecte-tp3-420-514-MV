# TP3 collecte
## getting started

### Vscode
you will need the following:
- vscode
- jupyter plugin : https://marketplace.visualstudio.com/items?itemName=ms-toolsai.jupyter&ssr=false
- python
#### Create a python env
```bash
# linux -ou- git bash
python3 -m venv venv
source venv/bin/activate
```
```ps1
# powershell
python -m venv venv
Set-ExecutionPolicy -Scope CurrentUser -ExecutionPolicy RemoteSigned -Force
.\venv\Scripts\Activate.ps1
```
#### install dependencies
```bash
# linux -ou- git bash
pip3 install -r requirements.txt
``` 
```ps1
# powershell
pip install -r requirements.txt
```
now you can execute cells