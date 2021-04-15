# Batch 2 Graduation Map

As part of the Batch 2 Graduation, we want to showcase everyone on a map from the regions they're from. This can be quite a challenging task to make sure we get everyone in the right places.

This repository is used for collecting photos that can be used for the map. If you have any questions, let one of the staff know!

## Photo Upload Instructions

Normal GitHub workflow for contributing to a project:

1. Fork repository at the top right
1. Go to your fork
1. Add a **SQUARE** photo of yourself to the region folder you're currently in, with the file name as your name and pod number (for example `europe/karan-sheth-2.1.3.jpg`, **note: name in lowercase**)
1. Make a PR for your changes
1. Then... *Relax*!

You can find a few examples in the folder if you're unsure!

Pull Requests will only get merged if:
- Photo is a square (ratio 1:1)
- File name is all lower case, with `-` separating your first, last name and pod number.
- In the appropriate region folder


Any questions raise an issue and one of us can help

## Cropping Instructions (Staff only)

Use this [script](https://github.com/MLH-Fellowship/batch-1-photos/blob/main/circle-crop.py) made by Natalie Smith.

Set up a Python 3 virtual environment
```
virtualenv .venv
source .venv/bin/activate
pip install -r requirements.txt
```

Run
```
python circle-crop.py
```
