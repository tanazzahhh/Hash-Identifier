# Hash Identifier 

This Python tool helps identify the type of a given hash using regex patterns and basic validation. It supports multiple hash types and provides confidence scores to help you understand possible matches.

>  For educational use only — do not use maliciously.

---

## Features

- Supports common hash types (MD5, SHA-1, SHA-256, SHA-512, NTLM, MySQL, etc.)
- Uses regex pattern matching to identify hash types
- Shows multiple possible matches with confidence scores
- Validates hash length and format
- Easy to use via command line (CLI)

---

## Requirements

- Python 3.x  
(No external libraries required)

---

## Files Included

- `hash_identifier.py`: Main script to identify hashes.
- `README.md`: Instructions and documentation.

---

## How to Use

1. **Clone or download this repo**
```bash
git clone https://github.com/tanazzahhh/Hash-Identifier
cd Hash-Identifier
```

2. **Run the script with a hash**
```bash
python hash_identifier.py <your_hash_here>
```

3. **Example Usage**
```bash
python hash_identifier.py 5d41402abc4b2a76b9719d911017c592
```

---

## Test Hashes

Try out these example hashes to see the tool in action:

| Plaintext | Hash Type | Hash |
|-----------|-----------|------|
| `hello` | MD5 | `5d41402abc4b2a76b9719d911017c592` |
| `hello` | SHA-1 | `aaf4c61ddcc5e8a2dabede0f3b482cd9aea9434d` |
| `hello` | SHA-256 | `2cf24dba5fb0a30e26e83b2ac5b9e29e1b161e5c1fa7425e73043362938b9824` |
| `password` | NTLM | `8846f7eaee8fb117ad06bdd830b7586c` |

---

## Future Enhancements

- GUI interface using Tkinter
- Integration with hash-cracking APIs
- Allow reverse lookup (try to crack common hashes)

---

## Author

**Tanazzah Shaikh**  
Cybersecurity Student & Builder  
[GitHub](https://github.com/tanazzahh)

---

