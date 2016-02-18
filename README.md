# Sphinx website for NiData

This code uses Sphinx to automatically build documentation for the NiData python package.

### Installation

1. Clone the repository to your local machine.
2. From within the repository directory, run `pip install requirements.txt`
3. Make sure that the NiData code is in your Python path. To test, run `python -c 'import nidata'`.

### Generating the documentation
1. From within the repository directory, run `make html`


### Outputs

The main output is `_build/html/index.html`.
