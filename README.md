### Table of contents
[1. Speech cognitive services](https://github.com/sciamanna/Rebeca/new/main#using-speech-services-for-translation)
# Using speech services for translation
Recently Microsoft migrate azure speech translate the _Speech Service_ this example teaches how to create a recognsise using the new sdk

```python
recongnizer = tl.TranlationRecognizer (translation_config=speech-config)
```

and use it to translate between languages

```python
print("Say something in english to be tranlated to spanish and german:")
result = recognizer.recognize_once()
```
[** Visit**](https://github.com/LaloCo/SpeechCognitiveService_Translate)
