# CaptionGenerator

## Instructions to Run
- Install all the packages listed in requirements.txt using " pip install -r requirements.txt"  and run the notebook.


 -Download the models using
 
$ wget https://github.com/mozilla/DeepSpeech/releases/download/v0.9.3/deepspeech-0.9.3-models.pbmm


$ wget https://github.com/mozilla/DeepSpeech/releases/download/v0.9.3/deepspeech-0.9.3-models.scorer


-Install FFMPEG for Ubuntu
$ sudo apt-get install ffmpeg
 
 
 TO get the output run 
 
 $ python3 generator/main.py --model /home/koushik/CaptionGenerator/deepspeech-0.9.3-models.pbmm --scorer /home/koushik/CaptionGenerator/deepspeech-0.9.3-models.scorer --file /home/koushik/CaptionGenerator/video.mp4


video.mp4 is the input video and output is stored in output folder in STR format
