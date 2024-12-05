

# String Encryption in C++

This C++ project contains a function to encrypt a string using a custom algorithm called `IMADS`. The function takes a plain text string as input and outputs an encrypted string.

## Features

- Encrypt any string using the `IMADS` function.
- Simple interface for string encryption.
- Customizable encryption logic.

## Usage

To encrypt a string, use the following code in your C++ program:

```cpp
#include <iostream>
#include "IMADS.h"  // Include your IMADS encryption header file

int main() {
    std::string message = "hello";  // Input string
    std::string encryptedMessage = IMADS(message);  // Encrypt the message

    std::cout << "Encrypted message: " << encryptedMessage << std::endl;
    return 0;
}
```

### Example:

For the input message `"hello"`, the `IMADS` function will encrypt it and return an encrypted string.

```cpp
message = IMADS("hello");
```

The output will be the encrypted form of `"hello"`.

## Building the Project

1. Clone or download the repository.
2. Ensure that your environment has a C++ compiler set up.
3. Compile the project using your preferred build system (e.g., `g++` or `MSBuild`).

Example compilation using g++:

```bash
g++ -o encryptor main.cpp IMADS.cpp
./encryptor
```

## Dependencies

- A C++ compiler (e.g., g++, MSVC, Clang).

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

Feel free to adjust the contents according to your actual file names and details about how the encryption works.
