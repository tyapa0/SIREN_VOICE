

[日本語にする ](https://github-com.translate.goog/tyapa0/SIREN_VOICE?_x_tr_sl=en&_x_tr_tl=ja&_x_tr_hl=ja&_x_tr_pto=wapp) 

# SIREN_VOICE
Waveform learning using the SIREN algorithm and shader code output.
This is a toolset for learning prepared waveforms using the SIREN algorithm and outputting the waveforms as shaders.

# Description
* requirements.txt  
This file lists the required libraries.

* siren_voice.snd.glsl  
This is a completed data sample prepared as a music shader for minimal_gl.

* siren_voice_mod.ipynb  
This is a python code using the SIREN algorithm. It is recommended to run it in vs code, a Jupyter notebook-specific file.

# Installation
※This is how to build it on Windows.
All done on the command line.

First, git clone. Next, create the environment with venv.
```
git clone https://github.com/tyapa0/SIREN_VOICE.git
python -m venv venv
```
Next, activate the venv, install pytourch, and then include all the libraries using requirements.txt.

```
.\venv\Scripts\activate
pip install torch==2.3.1 torchvision==0.18.1 torchaudio==2.3.1 --index-url https://download.pytorch.org/whl/cu121
pip install -r requirements.txt
```
Read siren_voice_mod.ipynb into vscode. It is recommended that you have the Jupyter add-on installed. Phython must already be in the environment to run it.
Run the appropriate Phython from vscode.

# link
This is a tool to convert it into an exe.  
https://github.com/yosshin4004/minimal_gl

The original SIREN algorithm and Jupyter note are here.  
https://github.com/vsitzmann/siren

Good Luck.