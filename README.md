# Translate

Translate uses the Yandex.Translate API from the command line to translate its arguments.

## Get API key

To use Yandex.Translate, you must obtain a unique key:
https://tech.yandex.ru/keys/get/?service=trnsl

## Set environment variable
```
$ export YANDEXAPIKEY="Your API key"
```

## Translate

```
$ ./translate 'Hello, World!'
Привет, Мир!
```
