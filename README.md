# ash
Automated
Smart 
Helper

## Description
Basically let's turn models like ChatGPT into Jarvice.
Our goal is to make an application that can run on a local workstation or home lab server that functions much like Alexa or Siri, but with the power of the latest technology behind it... and Amazon not stealing your information.

## Information:

- JS front end that can be run locally.
    - Configure Mic and Speaker to be used by the AI
    - Collects audio data from Mic/User
    - Sends data to the back end of the app
    - Plays response audio files for user
- Tacotron 2 back end for TTS and STT processing
    - Take input audio and translate to text
    - send that text to the AI API for response processing
    - Take AI response and translate it to speech for user
    - send speech to front end to be processed
- AI/API back end for the brains of the operation
    - Run text as input for configured AI back end
    - Transfer response to the Tacotron2 back end