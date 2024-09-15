# simple-selenium
This project has a simple invalid login selenium test. The main purpose of this project is to use selenium and javascript for web automation and to try awsomemocha reporter to output the results

# Selenium JavaScript Automation Project

## Overview

This project demonstrates how to set up and run Selenium WebDriver tests using JavaScript, Node.js, and Mocha. It includes automatic browser driver management and enhanced reporting with Mochawesome.

## Prerequisites

Before you begin, ensure you have the following installed:

- Node.js (LTS version recommended)
- npm (comes with Node.js)
- A code editor or IDE (e.g., Visual Studio Code, IntelliJ IDEA)

## Installation

### 1. Install Node.js

Choose one of the following methods:

- **Option 1**: Download and install directly from the [official Node.js website](https://nodejs.org/)
- **Option 2**: Use Homebrew (for macOS users):
  ```bash
  brew install node


### 2. Install an IDE
Choose and install your preferred Integrated Development Environment (IDE). Some popular options include:
Visual Studio Code
IntelliJ IDEA
WebStorm

### 3. Set Up the Project
Create a new directory for your project:
bash
mkdir selenium-javascript-automation
cd selenium-javascript-automation

Initialize a new Node.js project:
```bash
npm init -y

Install Selenium WebDriver
```bash
npm install selenium-webdriver

Install WebDriverManager for automatic browser driver management:
```bash
npm install webdriver-manager

Install Mocha test framework
```bash
npm install mocha --save-dev

Set up Mochawesome for enhanced reporting
```bash
npm install mochawesome mochawesome-report-generator --save-dev


## Project Structure
After installation, your project structure should look like this:
text
selenium-javascript-automation/
├── node_modules/
├── tests/
│   └── example.test.js
├── package.json
├── package-lock.json
└── README.md
