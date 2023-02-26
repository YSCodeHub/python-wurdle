# Build a Wordle Clone With Python and Rich

This repository holds the code for building wordle clone.

The tutorial uses the [walrus operator](https://realpython.com/python-walrus-operator/), which was introduced in [Python 3.8](https://realpython.com/python38-new-features/).

## Dependencies

The project uses [Rich](https://rich.readthedocs.io/) for style, color, and formatting in the terminal. You should first create a virtual environment:

```console
$ python -m venv venv
$ source venv/bin/activate
```

You can then install `rich` with `pip`:

```console
(venv) $ python -m pip install rich
```

## Run the Application

Enter the `source_code_final` folders. You can then run the Wordle clone by running `wyrdl.py` as a script:

```console
(venv) $ python wurdl.py
```

Check out the `wordlist.txt` file for a list of the words that are available (in step 2 and later). Edit this file if you want to play with your own words.