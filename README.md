# Port-Scanner

# Python Port Scanner

This Python script provides a basic port scanning functionality using the socket module in Python. It allows users to specify an IP address and a range of ports to scan, and it checks whether those ports are open on the specified IP address.

## Usage

1. Clone the repository or download the `port_scanner.py` script.
2. Make sure you have Python 3 installed on your system.
3. Run the script using the command `python3 port_scanner.py`.
4. Follow the prompts to enter the IP address and the range of ports you want to scan.

## Features

- Validates user input for IP addresses and port ranges.
- Scans for open ports within the specified range.
- Basic user interface with ASCII art header.

## Dependencies

This script requires Python 3 and does not have any additional dependencies beyond the standard library.

## Notes

- This port scanner is basic and does not use multithreading. Scanning all ports (0-65535) is not advised without proper optimization.
- Closed and filtered ports are not distinguished; the script only reports open ports.

## License

This script is provided under the [MIT License](LICENSE).
