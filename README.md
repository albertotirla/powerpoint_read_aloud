# powerpoint read aloud

## description

This project is a simple python script which speaks the text content of powerpoint slides, by feeding it to the google tts API and then saving the result to a file called `output.mp3` by default.

Since this is a personal project intended for usage by self, then anyone else second, it's a very crood implementation written in only afew lines. The current limitations are:

* the output file output.mp3 is hard-coded
* the tts language is hardcoded as romanian
* there isn't a way to modify speed, pitch and other tts parameters, even if the gtts api allows it
* probably other things as well

Those limitations aren't because of any particular reason, I just don't have any use for the additional features outlined above. If anyone does, pull requests are welcome

## installing

1. Make a virtual environment

`python3 -m venv .venv`

2. Activate the environment

`source .venv/bin/activate

3. Populate the venv with the required packages

`pip install -r requirements.txt`

## running

`python3 main.py`
