# Python v JavaScript: Dawn of JStice

For this assignment, your task is to convert the following Python code to JavaScript:

```python
import random
import string

def generate_password(length=12):
    characters = string.ascii_letters + string.digits + string.punctuation
    
    # Select `length` random characters from the character set above
    password = ''.join(random.choice(characters) for _ in range(length))
    
    return password

# Generate and print a password
print(generate_password())
```

To accomplish this, follow these steps:

1. Identify the Python-specific functions and modules used (e.g., `random`, `string`).
2. Find JavaScript equivalents for these functions and modules.
3. Fill out the `generatePassword()` function in the `generate_password.js` file.
4. Test your JavaScript function to ensure it generates passwords correctly by loading the `index.html` page in the [Live Preview](https://marketplace.visualstudio.com/items?itemName=ms-vscode.live-server) extension.
5. If you are feeling adventurous, you may also test your JavaScript function using [Jest](https://jestjs.io/).