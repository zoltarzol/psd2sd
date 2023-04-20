# Sketch in Photoshop, let Stable Diffusion do the rest

## The idea
You draw something in Photoshop, and every time your image is saved, the Stable Diffusion API is called to generate an image based on your drawing.
The resulting image is displayed inside the Notebook

## Requirements
Besides the *requirements.txt* (includes for the Notebook code), you'll need 3 files in the base directory:
- **prompt.txt**: contains your prompt, the textual description of what you want to generate
- **nprompt.txt**: contains your negative prompt (what you don't want)
- **base.psd**: the PSD file you will be editing inside Photoshop

## Usage
- Run the Notebook: a first image will be generated (based on the information from the 3 files mentioned above)
- Update and save in Photoshop: a new image is automatically generated
- Update one of the prompt files: a new image is automatically generated
