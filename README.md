# asr_research

## Задача 1

Написать программу, которая распознает голосовые фразы:

1."привет я разработчик" и отвечает "сегодня выходной".

2."Я сегодня не приду домой" и отвечает "Ну и катись отсюда".

## Задача 2

Используя платформу Huggingface, провести анализ моделей или использовать готовую библиотеку Python для разделения аудиодорожки на отдельные персоны и распознать текст, сказанный каждой персоной на аудио.

## Инструменты
- speech_recognition
- gTTS
- vosk
- SbertPuncCase
- nltk
- pyannote
- AudioSegment
- whisper
- numpy
- gc

## Инфо

- Python 3.11.5
- Платформа Mac OS
 
Для работы кода необходимо создать токен по для доступа по инструкции: 
https://huggingface.co/pyannote/speaker-diarization-3.1

Токен нужен в следующей части кода:

pipeline = Pipeline.from_pretrained(
  "pyannote/speaker-diarization-3.1",
  use_auth_token="HUGGINGFACE_ACCESS_TOKEN_GOES_HERE")

