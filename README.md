# Text to Morse Code Converter

A small Python script that converts plain text into International Morse Code using a lookup table.

- Core implementation: [`text_to_morse_code_converter.py`](text_to_morse_code_converter.py)
- Main API:
  - [`text_to_morse`](text_to_morse_code_converter.py) — convert a string to Morse code.
  - [`morse_code`](text_to_morse_code_converter.py) — dictionary mapping characters to Morse sequences.

## Features
- Supports A–Z, 0–9 and common punctuation.
- Preserves word boundaries: spaces become ` / ` in output.

## Usage
Run the script and enter text when prompted:

```sh

python .\text_to_morse_code_converter.py
