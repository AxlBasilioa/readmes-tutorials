# Node.js Tutorial

Welcome to this tutorial on Node.js, where you will learn what Node.js is, how to use it, and how to create your first 'Hello World' project.

## What is Node.js?
Node.js is a runtime environment for JavaScript built on Chrome's V8 JavaScript engine. It allows you to run JavaScript code on the server, outside of a web browser. This makes it ideal for developing server applications due to its non-blocking, event-driven I/O model.

## Installing Node.js
To start using Node.js, you first need to install it on your system. You can download the latest version of Node.js from its official website: https://nodejs.org/

### Windows and Mac:
1. Download the installer from https://nodejs.org/
2. Run the installer and follow the instructions.
3. Once installed, you can verify the installation by opening a terminal and typing:
```bash
echo 'node --version'
echo 'npm --version'
```

## Linux:
You can install Node.js from the terminal with the following commands, depending on your distribution:

### Debian and Ubuntu:
```bash
sudo apt update
sudo apt install nodejs npm
```

### Fedora and RedHat:
```bash
sudo dnf install nodejs npm
```

### Creating your first project in Node.js
To create your first 'Hello World' project in Node.js, follow these steps:
```bash
mkdir myNodeProject
cd myNodeProject
npm init -y
echo console.log('Hello World!') > index.js
node index.js
```
You should see the message 'Hello World!' in the terminal.

### Conclusion
Congratulations! You have now created your first project in Node.js and run your first 'Hello World' script. This is just the beginning of what you can do with Node.js. Continue exploring and learning more about this powerful runtime environment!
