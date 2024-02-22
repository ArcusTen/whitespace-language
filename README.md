# *Whitespace Language Decoder*

*This Python script is a decoder for the Whitespace language. Whitespace is an esoteric programming language where the only characters that are considered by the interpreter are spaces, tabs, and linefeeds. Any other characters are ignored, making the code visually obscure.*

## *Prerequisites*

- *Python 3.x*
- *Python* `pwn` *library (*`pwntools`*)*

## *Usage*

1. *Clone the repository or download the script.*
2. *Ensure you have the* `pwntools` *library installed. You can install it via pip:*
   ```
   pip install pwntools
   ```

3. *Run the script with Python, providing the filename of the Whitespace code as an argument:*
   ```
    python script.py <filename>
   ```


## *Description*

*This script reads a file containing Whitespace code and decodes it into human-readable ASCII characters. It performs the following steps:*

1. *Reads the provided file as binary data.*
2. *Replaces specific bytes representing whitespace characters with binary digits ('0' and '1').*
3. *Converts the modified binary data into an ASCII string.*
4. *Decodes the ASCII string to retrieve the original human-readable text.*

## *Example*

*Consider a file named* `sample.txt` *containing Whitespace code. To decode it:*

```
python3 main.py sample.txt
```

## *Note*

*Ensure that the Whitespace code in the provided file is properly formatted and follows the rules of the Whitespace language.*

*For more information on the Whitespace language, refer to* *[the Whitespace language specification](https://en.wikipedia.org/wiki/Whitespace_(programming_language)).*

***Author:** Muhammad Haris (Arcus)*

