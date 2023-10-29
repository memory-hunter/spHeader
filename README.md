# spHeader

spHeader initializes the scratchpad properly so the DoJa emulator loads the dumped games without any trouble.

## Header:
- Size: 64 bytes
- Contains all the sizes in the `.jam` file's `SPsize` line in little endian, appended with `0xFF`s to make it 64 bytes long.

## Usage

`python .\spheader.py input.jam input.sp`
