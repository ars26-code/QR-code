# QR-code

### Overview

This Python script generates unique QR codes containing randomly generated alphanumeric data. Each time the script is executed, it creates a different QR code, which can be used for various purposes such as marketing, sharing links, and more.

### Features

- **Unique QR Code Generation**: Each QR code is generated with a different random string, ensuring uniqueness.
- **Customizable Data Length**: Users can specify the length of the random string encoded in the QR code.
- **Automatic Display and Saving**: The generated QR code is saved to a PNG file and displayed on the screen.
- **Simple and Easy to Use**: The code is straightforward to execute, making it accessible for all levels of users.

### Requirements

- **Python**: This script requires Python 3.x to run.
- **Libraries**: The following libraries are required:
  - `qrcode`
  - `Pillow` (for image handling)

### Installation

1. **Install Python**: Make sure you have Python 3 installed on your machine. You can download it from [python.org](https://www.python.org/downloads/).

2. **Install Required Libraries**: Use pip to install the necessary libraries. Run the following command in your terminal or command prompt:
   pip install qrcode[pil]
   

### Usage

To generate a unique QR code, simply run the script. Here’s how:

1. Save the entire code in a Python file, e.g., `unique_qr_generator.py`.

2. Open a terminal or command prompt.

3. Navigate to the directory where the script is saved.

4. Run the script using the following command:

   ```bash
   python unique_qr_generator.py
   ```

### Example

When you run the script, it will:

- Generate random alphanumeric data.
- Create a QR code based on that data.
- Save the QR code as `unique_qr_code.png`.
- Display the QR code image.

### Customization

- **Change Data Length**: Modify the `generate_random_data(length)` function's `length` parameter to increase or decrease the string length as desired.
  
  ```python
  random_data = generate_random_data(16)  # For 16-character long data
  ```

- **Change Filename**: You can change the filename in the `create_qr_code()` function call to save the QR code with a different name:

  ```python
  create_qr_code(random_data, 'my_custom_qr_code.png')
  ```

### Contribution

Contributions are welcome! If you have suggestions for improvements or new features, feel free to open an issue or submit a pull request.

### Acknowledgment

- The `qrcode` library is developed by `lincolnloop`, which allows easy QR code generation in Python.
- The `Pillow` library (PIL Fork) is used for image processing.
- Thanks to the open-source community for creating and maintaining these libraries.


