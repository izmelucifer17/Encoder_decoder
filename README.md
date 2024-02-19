# Encoder-Decoder

This Python notebook contains functions for encoding and decoding data using various methods such as binary, hexadecimal, and Base64.

## Functions included:

1. **int_to_binary**: Converts an integer to a binary string.
2. **binary_to_int**: Converts a binary string to an integer.
3. **char_to_ascii**: Converts a string to its ASCII representation.
4. **ascii_to_char**: Converts ASCII codes to their corresponding characters.
5. **encode_base64**: Encodes a string into Base64 format.
6. **decode_base64**: Decodes a Base64 encoded string.
7. **encode_hex**: Encodes a string into hexadecimal format.
8. **decode_hex**: Decodes a hexadecimal string.
9. **binary_to_text**: Converts a binary string to text.
10. **ascii_to_text**: Converts ASCII codes to text.
11. **detect_base**: Detects the encoding format of a given string and decodes it accordingly.

## Usage:

To use these functions, simply call them with the appropriate arguments. For example:

```python
# Encoding a string into Base64
encoded_string = encode_base64("Hello, World!")

# Decoding a Base64 encoded string
decoded_string = decode_base64(encoded_string)

print("Encoded:", encoded_string)
print("Decoded:", decoded_string)
```

## Note:

This notebook includes a demonstration at the end that prompts the user to input a string for decoding. The function `detect_base` will determine the encoding format of the string and decode it accordingly.

**Author:** Lucifer@17
