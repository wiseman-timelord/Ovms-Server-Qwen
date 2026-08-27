# Ovms-Server-Qwen
Statu: Alpha

### Outline
An agendic manager/organizer similar to Devin is possible to run on windows with live tool-calling on local models through OVMS and Qwen 3.6 27B/35B models...
- I intend to see if the models are up-to scratch, and I have a feeling they will be this time, after experiments with Auto-GPT in past were less-than satisfactory at the time. 
- OpenDevin become OpenHands.
- Have uncensored Qwen35B-int4, supposedly the int4/int8/fp16 will allow for larger output? Supposedly also uncensored is going to degrade coding, so need optimal model tonight, even 27b-fast could be better than current option. 

### Scripts
```
.\installer.py (standalone script, it should not reference any functions/values in other scripts of program, unless it creates them, because it will have to create jsons)
.\launcher.py (startup, shutdown, main loop)
.\OVMS-Qwen-Server.bat
.\scripts\ (for the scripts of the main program)
.\scripts\configure.py (global variables, global constants, global lists, global maps).
.\scripts\displays.py
.\scripts\servers.py
.\scripts\utilities.py
.\data\ (for compiled or web downloaded requirements, and jsons).
.\data\settings.json (for persistent settings).
.\venv\ (local .venv virtual environment for saving of python libraries)
```
