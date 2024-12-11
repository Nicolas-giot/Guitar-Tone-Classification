# Guitar-Tone-Classification
Nicolas Giot (individual submission)
Implementation Track

This project is designed to take in 60 seconds of pure guitar audio and feed it to an AI model that determines if the tone was distorted or not. All data was recorded by me and I made use of ChatGPT to assist creating the model and getting it working.

HOW TO RUN: take a file from the .wav (copy it into main file or path to specific .wav file) and input it as the file_path in the Classifier IPYNB. After inputing .wav file path and running all cells, it should output a set of numbers from 0-1, the more that are closer to 0, the cleaner the model thinks the audio is, the closer to 1, the more distorted the model thinks the audio is. It will also decide and output its end prediction at the top of the output for the final Classifier cell. 
[I could not figure out how to include the raw .wav files because they were too big for github, so I made a google doc folder that I will include here. download files from there to feed into the model https://drive.google.com/drive/folders/1ME5WmYhDBj9TZplP9tcf6p_z9apJSa4K?usp=sharing]
