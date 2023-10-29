# spHeader

spHeader initializes the scratchpad properly so it can load the dumped games without any trouble.

## Header file:
- Size: 64 bytes
- Contains all the sizes in the `.jam` file's `SPsize` line in little endian, appended with `0xFF` to make it 64 bytes long.

## Usage

`python .\spheader.py input.jam input.sp`
