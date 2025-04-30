# magstripe-python
Tool for reading/writing to magnetic stripe cards that follow ISO/IEC 7813 standards | Compatible with MSR605 and MSR605X magnetic stripe encoders

## Instructions

### Install Dependencies

```bash
$ pip install -r requirements.txt
```

### Start Flask Server

```bash
$ python3 app.py

* Running on http://0.0.0.0:8000/
...
```
## Compatibility

This should work with *any* card utilizing a magnetic stripe that follows ISO/IEC 7813 standards.

## Acknowledgements

Magstripe-python is an extension of the work done by Damien Bobillot, who wrote the Python
driver for the MSR605's serial interface and Raphael Michel who wrote the wrapper around the driver.

As both Damien and Raphael's work is GPL, this is licensed under the terms of the GPL, as well.