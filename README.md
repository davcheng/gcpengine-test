## Quickstart
```
$ python transcribe.py

usage: transcribe.py [-h] path

Google Cloud Speech API sample application using the REST API for batch
processing.

Example usage:
    python transcribe.py resources/audio.raw
    python transcribe.py gs://cloud-samples-tests/speech/brooklyn.flac

positional arguments:
  path        File or GCS path for audio file to be recognized

optional arguments:
  -h, --help  show this help message and exit
```



##Transcribe with word time offsets
```
$ python transcribe_word_time_offsets.py

usage: transcribe_word_time_offsets.py [-h] path

Google Cloud Speech API sample that demonstrates word time offsets.

Example usage:
    python transcribe_word_time_offsets.py resources/audio.raw
    python transcribe_word_time_offsets.py         gs://cloud-samples-tests/speech/vr.flac

positional arguments:
  path        File or GCS path for audio file to be recognized

optional arguments:
  -h, --help  show this help message and exit
```


##Transcribe
```
$ python transcribe_streaming.py

usage: transcribe_streaming.py [-h] stream

Google Cloud Speech API sample application using the streaming API.

Example usage:
    python transcribe_streaming.py resources/audio.raw

positional arguments:
  stream      File to stream to the API

optional arguments:
  -h, --help  show this help message and exit
```

python transcribe.py gs/
