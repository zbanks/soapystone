# soapystone

A [`pylint`](http://pylint.pycqa.org/en/latest/) checker to ensure that all of your comments could be left as a message in Dark Souls using an [Orange Guidance Soapstone](https://darksouls.fandom.com/wiki/Messages) (optionally allowing cackling laughter before/after the message).

[The code](soapystone/checker.py) passes its own checker, so is a good example.

See [`phrases.py`](soapystone/phrases.py) for a full list of supported phrases & fills.

## Installation / Usage

TODO

```
env PYTHONPATH=. python3.9 -m pylint --load-plugins=soapystone --disable=all --enable=soapstone soapystone/
```
