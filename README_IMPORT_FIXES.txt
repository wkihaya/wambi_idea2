
FIX FOR IMPORT ERRORS

bpy, mathutils:
- These are ONLY available inside Blender's Python.
- They will NEVER resolve in VSCode or venv.
- Correct usage:
  blender --python script.py

cv2:
- Provided by opencv-python

mediapipe:
- Installed via pip

deepface:
- Installed via pip

COMMANDS:
pip install -r requirements.txt

BLENDER SCRIPT RUN:
"C:\Program Files\Blender Foundation\Blender 5.0\blender.exe" --python blender_script.py
