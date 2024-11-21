# Shiren Gaiden [DC] DATABG Extractor / Rebuild

# Extract
- Put `DATABG.bin` in the same folder of `DATABG_ext.exe` to extract and convert all images.

# Rebuild
- The first time you execute `DATABG_rebuild.exe` it will ask you to find the output `DATABG.bin`, please note this should point to GDI extracted contents
- When modifying palettized images (`MN` and `mapname`) in folders, please remember to **ALWAYS** edit the original indexed image by paste-in your modified image. This will ensure the correct grayscale palette is kept intact!
- LZ40 compression is the king, but I'm not aware of literal byte density of your new images! In case you'll ever hit such limit, the program will warn you to simplify the image.

# ♥ Support ♥
* https://ko-fi.com/vincentnl
* https://patreon.com/vincentnl

# Credits
Original LZX (LZ40) format by CUE Reference / tools: https://www.romhacking.net/utilities/826/
