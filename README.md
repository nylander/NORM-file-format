# Convert you data to the norm format

- Last modified: ons maj 25, 2022  05:34
- Sign: nylander

---

![](img/norm_normal_file_format.png)

## File format `.norm`

1. Open the data in a program,
2. Take a screenshot,
3. Paste the screenshot in a MS Word document.
4. Change the file suffix to `.norm`

## The script

The current version attempts to open an infile with the user's preferred
application (according to file type), and then proceeds with steps 2--4 above.
Furthermore, the screenshot is taken of the opened application (and not the whole desktop).

## Installation

See file [INSTALL](INSTALL)

## Usage

Examples:

    ./src/tonorm data/spreadesheet.xlsx
    ./src/tonorm data/image.png
    ./src/tonorm data/text.txt


