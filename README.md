<h1>250319_AI</h1>
ChatGPT와 Cursor을 사용해 파이썬으로 프로그래밍을 해봄

# 파이썬 음성 녹음 및 TTS 프로그램

이 프로그램은 Python을 사용하여 만든 데스크톱 애플리케이션으로, 음성을 녹음하고 저장한 후 다시 들려주는 기능과 텍스트를 음성으로 변환하는 기능을 제공합니다.

## 기능

- 마이크를 통한 음성 녹음
- 녹음된 음성 재생
- 녹음 목록 관리 (삭제 기능 포함)
- 텍스트를 음성으로 변환 (TTS)
- 음성 속도 조절

## 사용된 기술

- Python 3
- Tkinter (GUI)
- PyAudio (음성 녹음 및 재생)
- pyttsx3 (텍스트 음성 변환)
- Threading (비동기 처리)

## 설치 방법

1. Python 3.6 이상이 설치되어 있어야 합니다.
2. 필요한 라이브러리를 설치합니다:

```bash
pip install -r requirements.txt
```

Windows에서 PyAudio 설치에 문제가 있는 경우, 다음 링크에서 운영체제와 Python 버전에 맞는 whl 파일을 다운로드하여 설치할 수 있습니다:
https://www.lfd.uci.edu/~gohlke/pythonlibs/#pyaudio

## 사용 방법

1. 프로그램을 실행합니다:

```bash
python voice_recorder_tts.py
```

2. 프로그램은 세 개의 탭으로 구성되어 있습니다:
   - **음성 녹음**: 마이크로 음성을 녹음할 수 있습니다.
   - **텍스트 음성 변환**: 텍스트를 입력하고 음성으로 변환할 수 있습니다.
   - **녹음 목록**: 저장된 녹음 파일들을 관리하고 재생할 수 있습니다.

### 음성 녹음 방법
1. '녹음 시작' 버튼을 클릭하여 녹음을 시작합니다.
2. '녹음 중지' 버튼을 클릭하여 녹음을 종료합니다.
3. 녹음 파일은 'recordings' 폴더에 저장됩니다.

### TTS 사용 방법
1. 텍스트 입력 영역에 텍스트를 입력합니다.
2. 필요한 경우 음성 속도를 조절합니다.
3. '텍스트 읽기' 버튼을 클릭하여 텍스트를 음성으로 변환합니다.

## 주의사항

- 한국어 TTS는 시스템에 한국어 음성이 설치되어 있어야 정상적으로 작동합니다.
- PyAudio는 일부 시스템에서 설치가 복잡할 수 있습니다.

## 저작권 및 라이선스

이 프로젝트는 오픈 소스로 제공됩니다. 


<img src="https://github.com/gomtam/image/blob/main/250319/KakaoTalk_20250319_170316269.png" width="600">
<img src="https://github.com/gomtam/image/blob/main/250319/KakaoTalk_20250314_124755052.png" width="600">
<img src="https://github.com/gomtam/image/blob/main/250319/KakaoTalk_20250319_170248452.png" width="600">
