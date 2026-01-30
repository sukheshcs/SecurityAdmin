# SecurityAdmin

**Professional System Monitoring and Active Defense Tool**

SecurityAdmin is a robust Windows application designed for comprehensive system monitoring and active defense. It provides real-time insights into network connections, manages startup applications, and tracks system health to ensure your environment remains secure and optimized.

## Features

*   **Network Monitoring**: Real-time tracking of active network connections to identify suspicious activity.
*   **Startup Guardian**: Manage and monitor applications that launch at system startup to improve boot times and prevent unauthorized persistence.
*   **System Health**: Track vital system metrics to ensure optimal performance.
*   **Background Service**: Operates efficiently in the background with system tray integration.
*   **Modern UI**: Built with a responsive and intuitive React-based interface.

## Tech Stack

*   **Electron**: For cross-platform desktop application development.
*   **React**: For building the user interface.
*   **PowerShell**: utilized for deep system integration and monitoring capabilities on Windows.
*   **Recharts**: For visualizing system data.
*   **Lucide React**: For a clean and consistent icon set.

## Getting Started

### Prerequisites

*   Node.js (Active LTS version recommended)
*   npm (comes with Node.js)
*   Windows OS (for full functionality due to PowerShell dependencies)

### Installation

1.  Clone the repository:
    ```bash
    git clone https://github.com/Sukhesh/SecurityMon.git
    cd SecurityMon
    ```

2.  Install dependencies:
    ```bash
    npm install
    ```

### Running Locally

To start the application in development mode:

```bash
npm start
```

### Building for Production

To create a production build (AppX package for Windows):

```bash
npm run dist
```

The output files will be located in the `release_v6` directory (as configured in `package.json`).

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Author

*   **Sukhesh** - [sukheshcs@gmail.com](mailto:sukheshcs@gmail.com)
