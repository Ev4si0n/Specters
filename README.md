<p align="center">
<img src="https://raw.githubusercontent.com/Phantom8015/Specters/refs/heads/main/website/favicon.png" width="150" height="150"/>
</p>
<h1 align="center">Specters</h1>
<p align="center">Specters is a powerful web-based file explorer with terminal integration, system monitoring, and modern UI. Built with Node.js and designed for efficiency and ease of use.</p>

Note: This has not been tested outside of Ubuntu/Debian. Stability is not guaranteed if you are not using them.

## Features

- **File Management** - Browse, upload, download, and manage files with drag-and-drop support
- **Terminal Integration** - Built-in web terminal for running commands directly from the browser
- **System Monitoring** - Real-time CPU, memory, and GPU usage monitoring
- **File Preview** - Preview text files, images, and media directly in the browser
- **Fast & Responsive** - Built with modern web technologies for optimal performance
- **Modern UI** - Clean, intuitive interface inspired by modern design principles

## Installing 
1. **Run the installer script**

### On your server:
```bash
curl -fsSL https://raw.githubusercontent.com/Phantom8015/Specters/main/install.sh | bash
```
### On your PC:
1. **Open your browser (on your pc)**
   Navigate to `http://<YOUR-SERVER-IP>:3000`

## Manual Installation


### Requirements

- **Operating System**: Linux (on the server)
- **Node.js**: Version 16 or higher
- **Git**: For cloning the repository
- **NPM**: For installing dependencies

### On your server:
1. **Clone the repository**
   ```bash
   git clone https://github.com/Phantom8015/Specters.git
   cd Specters
   ```

2. **Install dependencies**
   ```bash
   npm i
   ```

3. **Start Specters**
   ```bash
   npm start
   ```

### On your PC:
1. **Open your browser**
   Navigate to `http://<YOUR-SERVER-IP>:3000`


## Security Considerations

- The application allows file system access - ensure proper firewall rules
- Run behind a reverse proxy (nginx) for production
- Consider implementing authentication for sensitive environments
- Regularly update dependencies for security patches

## Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## License

This project is open source and available under the [MIT License](LICENSE).

## Issues & Support

- **Issues**: [GitHub Issues](https://github.com/Phantom8015/Specters/issues)
- **Contact**: [Phantom8015](https://github.com/Phantom8015)
