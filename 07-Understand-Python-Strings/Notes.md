# Understanding Python Strings

## Storing and Manipulating Strings

Text in Python is stored as a series of individual characters, each represented by a sequence of bytes. Understanding how text is stored and manipulated helps you work more effectively with strings.

- **Booleans**: Stored as 1 bit (either `True` or `False`).
- **Bits and Bytes**: 1 byte consists of 8 bits, and 1 byte can store 256 different values (`2^8`).
- **Integers**: Typically stored in 4 bytes, which allows for 2^32 different values.
- **Floating Point Numbers**: Usually stored in 8 bytes for greater precision.
- **Text (Strings)**: Each character in a string is typically stored as 1 byte. A string is essentially a sequence of characters, each represented by its corresponding byte, which is why it’s called a "string"—we string together individual bytes to form text.

## Encoding Strings with ASCII, Unicode, and UTF-8

Understanding how text is encoded is important for handling various character sets and languages.

- **ASCII**: A 1-byte encoding standard that represents the Latin/English alphabet. Each character is stored in 1 byte.
- **Unicode**: A more expansive encoding system, using up to 6 bytes to represent any character, symbol, glyph, or language globally.
- **UTF-8**: A more efficient encoding format for storing Unicode strings. UTF-8 uses 1 byte for common characters (like those in ASCII) and expands to more bytes as needed for less common symbols, efficiently balancing memory usage and flexibility.

## Escape Characters for Strings

Escape characters allow you to differentiate between string literals and control characters within strings.

- Common escape sequences include `\n` for a newline, `\t` for a tab, and `\\` for a backslash. These characters allow you to format text and control how strings are outputted or manipulated within the program.

## Operators and String Functions

Python provides powerful operators and functions for manipulating strings:

### String Operators:
- **Concatenation (`+`)**: Joins two or more strings together.
- **Repetition (`*`)**: Repeats a string a specified number of times.
- **Slicing (`[]`)**: Extracts a portion of a string using indices.
- **Range Slicing (`[:]`)**: Retrieves a subset of characters from the string by specifying a range of indices.

### Common String Functions:
- **`upper()`**: Converts the string to uppercase.
- **`lower()`**: Converts the string to lowercase.
- **`capitalize()`**: Capitalizes the first letter of the string.
- **`split()`**: Splits the string into a list, using a specified delimiter.
- **`join()`**: Joins a list of strings into one string with a specified separator.
- **`ord()`**: Returns the Unicode code point of a character.
- **`chr()`**: Converts a Unicode code point to its corresponding character.
- **`len()`**: Returns the length of the string.

---

These enhanced notes should give a clearer understanding of how strings are stored, manipulated, and encoded in Python. Let me know when you're ready to proceed to the next step!


