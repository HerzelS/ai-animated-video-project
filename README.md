# AI-Animated Video Project 🎥

This repository contains all components required to create a professional AI-generated animated video using free and open-source tools.

## 🎯 Project Goal
Produce a high-quality short video (1–3 minutes) with AI-generated voice, visuals, and animations.

## 🧰 Tools Used
- [Coqui TTS](https://github.com/coqui-ai/TTS) for voiceover
- [Stable Diffusion](https://github.com/AUTOMATIC1111/stable-diffusion-webui) for visuals
- [Deforum](https://github.com/deforum-art/deforum-for-automatic1111-webui) for animation
- [Kdenlive](https://kdenlive.org/) for editing
- [Audacity](https://www.audacityteam.org/) for sound cleanup
- [Pixabay](https://pixabay.com/music/) for music

## 📂 Folder Structure
See each folder for task-specific files (scripts, prompts, outputs, etc.)

## ▶️ Quick Start
1. Write or update `script/narration.txt`
2. Run `scripts/generate_voiceover.py`
3. Run `scripts/generate_images.py` with prompts from `prompts/`
4. Run `scripts/animate.py` or use Blender/Deforum
5. Open `render_video.kdenlive` and assemble
6. Export to `output/final_video.mp4`

## 📜 License
MIT License
 
