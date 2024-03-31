### WiFi Module Library

This Python library provides easy-to-use functions for various WiFi capabilities on Linux systems with WiFi adapters capable of monitor mode.

### Usage

1. **Download the Library**:
   - Go to the [releases tab](https://github.com/pauwol/linux-wifi/releases) of this repository or clone the code by downloading the zip file.

2. **Setup**:
   - Extract the downloaded zip file.
   - Navigate to the extracted directory.
   - Run the setup script using either `sudo python setup.py` or `sudo python3 setup.py`.

3. **Usage**:
   - After setup, the library is ready to use.
   - Use the `wifi` command followed by a flag to execute different actions:
     - Deauthenticate a WiFi: `-da`
     - Connect to a WiFi: `-c`
     - Scan for available WiFis: `-s`
     - Create a wireless access point: `-ap`

   **Note**: Some functions may require two WiFi adapters, but support for single adapter setups is planned for the future.

### Getting Started

- Ensure you have the necessary permissions to run the commands (e.g., using `sudo`).
- Remember to handle commands that require `sudo` appropriately to ensure proper functionality.

### Contribution

Feel free to contribute to this project by suggesting improvements, reporting issues, or submitting pull requests. Your feedback is valuable!

### License

This project is licensed under the [MIT License](LICENSE).
