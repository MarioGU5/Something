# Spleeter tutorial

## Let's first intall spleeter and youtube-dlp to extract auido

```
#Anaconda3 is required to be installed.
pip install spleeter #done
pip install yt-dlp
#Download this for post-processing: https://www.gyan.dev/ffmpeg/builds/

```

## Download Criminal Caga Tió by Venga Monjas:

yt-dlp -x --audio-format mp3 -o "C:/Users/zlc436/Desktop/OTHERS/mamarracha/cagatio/raw_data/criminal_cagatio.mp3" https://www.youtube.com/watch?v=-SQTZ_eWOJ4 --ffmpeg-location C:/Users/zlc436/Desktop/OTHERS/mamarracha/cagatio/raw_data/ffmpeg-2025-04-21-git-9e1162bdf1-full_build/bin/ffmpeg.exe

## Decompose song by different instruments: 

spleeter separate -C:/Users/zlc436/Desktop/OTHERS/mamarracha/cagatio/raw_data/criminal_cagatio.mp3 -p spleeter:5stems -o C:/Users/zlc436/Desktop/OTHERS/mamarracha/cagatio/output/1_decomposed/

