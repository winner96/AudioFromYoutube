# AudioFromYoutube
How i got audios using avspeech set csv file.

avspeech set: https://looking-to-listen.github.io/avspeech/download.html

PROBLEM OF THE CODE:

  1) takes long time as it use only 1 thread.
  2) in avspeech csv there are multiple videos from equal youtube-id.
   this code does not download more audios if audio from previous youtube-id was downloaded.
   
   
  This code is just for reference using ffmpeg, youtube-dl for future use.
