# VoxTrace

This program was built primarily for academic use, but whoever would need it is free to do so, as long as it respects the license.

All this program is based on two legs : WhisperX and Pyannote. 
- [WhisperX](https://github.com/m-bain/whisperX) was developed by Max Bain©.
- [Pyannote](https://github.com/pyannote/pyannote-audio) is an open-source toolkit for speaker diarization.

This program has one major goal : to realise the transcription and diarization of a given audio file, for example a research interview. The output is a text file containing the retranscription, with one paragraph per speaker.

## Disclaimer
The goal was to create a program to be run on Google Colab platform, so that anyone with a Google account could leverage the power of ASR (Automatic-Speech-Recognition). However, realising the transcription online means you cannot have the guarantee that your data are safe ! If you want to trancribe sensitive data, please install WhisperX locally and run it from your machine ! 

The author or any of VoxTrace's contributors cannot be held responsible for the misuse of the program, or a potential dissemination of your data due to the trancription through the Internet ! Please refer to the license for further information related to this topic.

## How to use this program
To use this program, simply download it, open it with Google Colab and follow the instructions. Minimal to no prior coding experience is expected to be able to use it, as the inputs are done through fields and without the need to open any code block or to directly change the variables inside of the program.

The parameters are optimised to run long audio files (more than one hour) together with free T4 GPUs, accessible to anyone in Google Colab.

## Increase the performance
However, if you possess a premium Colab account, you can access more powerful GPUs. If you have access to these, you are probably not afraid of small python scripts. Feel free to tweak the parameters in the first block to increase the performance.

Cheers !
