# Speakers Test
Windows GUI app for testing audio speakers functionality  
![screenshot](https://user-images.githubusercontent.com/57393100/191909149-3580d782-7075-4fbb-becf-bb5e9e222d9e.png)

## requirements
- python 3.9+
- simpleaudio 1.0.4
- auto-py-to-exe (to compile)

## compile
Use auto-py-to-exe to compile the program into the exe binary  
```pip install auto-py-to-exe```  
- Select Choose One File, Window Based
- Choose the icon ```sound.ico```
- Add additional files - Add Folder - select ```assets/``` directory
- Push the Convert .PY to .EXE button

## run
```\bin\soundtest.exe```  
or  
```pip install -r requirements.txt```  
```python soundtest.py```

## note
If you encounter problems with installing simpleaudio lib with venv activated, disable it first.
