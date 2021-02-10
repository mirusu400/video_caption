# video_caption
Automatically make captions of video using AI.


# Algorithm
1. 비디오에서 음악만을 추출한다.
2. Optional - 음악에서 음성만을 추출한다. [librosa](https://librosa.org/librosa_gallery/index.html) 아용
3. 음성을 텍스트로 변환한다. [STT](https://github.com/buriburisuri/speech-to-text-wavenet) 이용
4. 그에 맞게 smi파일을 작성한다.