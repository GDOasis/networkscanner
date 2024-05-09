# networkscanner
# PowerShell Network Security Monitoring Script

This PowerShell script is designed for network security monitoring purposes. It retrieves the external IP address of the system and compares it against a list of known good IP addresses. If the current external IP address does not match any of the known good IP addresses, it logs the event as potentially abnormal.

## Usage

1. Ensure you have PowerShell installed on your system.
2. Clone or download this repository to your local machine.
3. Customize the script by updating the `$knownGoodIPs` array with your own list of known good IP addresses.
4. Run the script by executing the `NetworkSecurityMonitoring.ps1` file using PowerShell.
5. Monitor the output for any potentially abnormal IP addresses.

## Script Details

- **Get-ExternalIPAddress**: This function retrieves the external IP address of the system using the ipify API.
- **$knownGoodIPs**: An array containing a list of known good IP addresses. Update this array with your own list of known good IPs.
- **Main script**: Retrieves the external IP address and compares it against the list of known good IPs. If an abnormal IP is detected, it logs the event.

## Contributing

Contributions are welcome! If you have suggestions, improvements, or bug fixes, feel free to open an issue or create a pull request.

## License

This project is licensed under the [MIT License](LICENSE).
