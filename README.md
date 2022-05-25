# Convert you data to the norm format!

![](img/norm_normal_file_format.png)

## File format `.norm`

1. Open your data in any program (most often MS Excel),
2. take a screenshot,
3. paste the screenshot in a MS Word document,
4. change the file suffix to `.norm`.

## The script

The current [script](src/tonorm) attempts to open an infile with the user's
preferred application (according to file type), and then proceeds with steps
2-4 above.  Furthermore, the screenshot is taken of the opened application and
not the whole desktop.

## Installation

See file [INSTALL](INSTALL)

## Usage

Examples:

    $ ./src/tonorm data/spreadsheet.xlsx
    $ ./src/tonorm data/image.png
    $ ./src/tonorm data/text.txt

