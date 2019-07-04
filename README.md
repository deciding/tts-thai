# Thai Text to Speech (Thai TTS)

*Open Source Thai Text to speech*

I build Thai text to speech from [Language Resources (Google) tools](https://github.com/google/language-resources). You can use Thai TTS in docker.

***Please create a voice data set if used for business purposes.***

## Build

Build own Thai text to speech (Thai language) : https://github.com/wannaphongcom/tts-thai/tree/master/build_docker

## Use

### Docker

by docker :

```
docker pull wannaphong/thaitts
docker run -d -p 5000:5000 wannaphong/thaitts
```

Use :

```
http://127.0.0.1:5000/tts?text=ทดสอบ ระบบ
```

Leave a space between words and Use Thai words only.

## Audio Example

SoundCloud : https://soundcloud.com/j5muzwuozouf/sets/thai-tts-1

## License

Source code : licensed under an [Apache License, Version 2.0](LICENSE).

Datasets , Data and Docs : licensed under a [Creative Commons Attribution 4.0 International License (CC BY 4.0)](http://creativecommons.org/licenses/by/4.0).



Thank you VISTEC.

Thank you Google.



Wannaphong Phatthiyaphaibun

wannaphong@kkumail.com