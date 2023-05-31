# AI Voice

This guide will walk you through the process of setting up a Voice-to-Voice AI system like the ones in my video. With this setup, you will be able to convert Change the voice of a song.

## Prerequisites

Before starting the setup process, ensure that you have the following:

1. Ultimate Vocal Remover: Make sure you have Ultimate [Vocal Remover](https://ultimatevocalremover.com/).For voice conversion, this will help by not converting  intrumentals. For training, this will help make the erquality of the dataset better.
2. Audio slicer: this will split up the dataset **for trining(Not required for voice conversion)* 
3. Google Collab: You'll need this to run the programm https://colab.research.google.com/github/LuluHuman/AiVoice/edit/main/RBVC_WebUI.ipynb

## Setting Up Voice-to-Voice AI

1. Under `Install dependencies` click on the start/play button on the left. This will install the required files
2. After installing the files you would see a tick. Then do the same for `Load WEB GUI`
3. Below `Show code` you would see a url like this `https://bd399b5556668d9f2a.gradio.live/` click on the url

## Customization and Advanced Options

The Voice-to-Voice AI setup can be customized and expanded based on your requirements. Here are some suggestions for further exploration:

- Speech Synthesis Parameters: The OpenAI API provides additional configuration options for speech synthesis, such as adjusting the speaking rate, pitch, and volume. Refer to the OpenAI API documentation for more details on how to customize the speech synthesis parameters.

- User Interface Enhancements: You can modify the web interface to suit your preferences or integrate the voice-to-voice functionality into your own applications or systems.

- Integration with other Services: Consider integrating the voice-to-voice functionality with other services or APIs to create more advanced applications. For example, you could combine the generated speech output with a voice recognition system or integrate it into a chatbot.

## Troubleshooting

If you encounter any issues during the setup process or while using the Voice-to-Voice AI system, consider the following troubleshooting steps:

1. Verify API Key: Double-check that you have correctly set the `OPENAI_API_KEY` variable in the `config.py` file.

2. Check Dependencies: Ensure that all the required dependencies are installed. Refer to the `requirements.txt` file
