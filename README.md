csvtoexcel
==========
csvtoexcel is a tool that converts a .csv file to .xlsx (Excel).

By default `csvtoexcel` creates a file with the same filename, but the file
extension changed from ".csv" to ".xlsx".
The `-o`/`--output` option can be used choose a different filename for the
output. 

Usage
-----

    > csvtoexcel <file.csv>
    <Creates the file file.xlsx>

    > csvtoexcel <file.csv> -o <other_file.xlsx>
    <Creates the file other_file.xlsx>

Install
-------
The recommended way to install `csvtoexcel` is via [pipx]:

    pipx csvtoexcel

[pipx]: https://github.com/pypa/pipx