# Edge and Internet Explorer Restriction Tool

This application is designed to apply restrictions on Microsoft Edge and disable Internet Explorer on Windows systems. It modifies the Windows Registry to block specific URLs and features in Edge and uses DISM to disable Internet Explorer.

## Features

- **Microsoft Edge Restrictions:**
  - Blocks downloads and access to settings.
  - Restricts installation of extensions.
  - Blocks specific internal Edge pages and URLs.
  - Restricts sign-in to specific accounts.
  - Disables synchronization.

- **Internet Explorer:**
  - Disables Internet Explorer using DISM.

## Installation

1. Clone the repository to your local machine.
2. Open the solution in Visual Studio.
3. Build the project to compile the application.

## Usage

1. Run the compiled application with administrator privileges.
2. The application will display a progress bar indicating the status of the operations.
3. Once completed, the message "All operations completed successfully" will be displayed, and the exit button will become visible.

## Important Notes

- **Administrator Rights:** The application must be run with administrator rights to make changes to the registry and system settings.
- **Compatibility:** Ensure that the registry settings are compatible with your version of Windows and Microsoft Edge.
- **Backup:** Always back up the registry before making changes to prevent potential system issues.

## Contributing

Contributions are welcome! Please fork the repository and submit a pull request with your changes.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contact

For any inquiries or issues, please open an issue on the GitHub repository.

