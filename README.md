# StegoHexTool
A minimal CLI Steganography-Tool for hiding and extracting text messages in PNG images using **LSB (Least Significant Bit)** steganography.
Build with C++ and LodePNG.
<br>
<br>

## Features

- Encode any text messages into a PNG image
- Decode hidden messages from a PNG image
- Uses LSB encoding (1 bit per channel)
- Simple command-line-interface
<br>

## Usage

1. Download and run the `StegoHex.exe` executable
2. Choose option (1) for encoding or option (2) for decoding text message
3. Enter the filepath to your PNG image
4. If option (1) is choosen, enter the text message you want to hide

![image](https://github.com/user-attachments/assets/03149c7a-6c27-4267-a9ac-7569fcaafa97)
<br>


## File Output

- Output image will be saved as: `<originalName>_encoded.png`
- If the message is to long for the image size, you'll get an error
<br>

## Notes

- Only works with PNG files (RGBA 8-bit channels)
- Message is null-terminated (`\0`)
- You can hide roughly 1 character per 4 bytes of image data
<br>

## License

MIT License <br>
(c) ch-xedt, 2025
<br>
<br>
