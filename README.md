<img src="./assets/linkedin_aihawk.png">

<!-- At first glance, the branding and messaging clearly conveys what to expect -->
<div align="center">


# Anthill-Coder

#### 🤖🔍 Your AI-powered agentic developers. Anthill analyzes, creates, and modifies large codebases.

</div>
<br />

<!-- Message Clarity -->
## 🚀 Join the Anthill Community 🚀 

Connect with like-minded individuals and get the most out of Antill.

💡 **Get support:** Ask questions, troubleshoot issues, and find solutions.

🗣️ **Share knowledge:** Share your experiences, tips, and best practices.

🤝 **Network:** Connect with other professionals and explore new opportunities.

🔔 **Stay updated:** Get the latest news and updates on AIHawk.

<!-- Strong Call to Action -->
### Sign up 👇

[![Telegram](https://img.shields.io/badge/Telegram-2CA5E0?style=for-the-badge&logo=telegram&logoColor=white
)](https://t.me/anthillcoder)

## Table of Contents

1. [Introduction](#introduction)
2. [Features](#features)
3. [Demo](#demo)
4. [Installation](#installation)
5. [Configuration](#configuration)
6. [Usage](#usage)
7. [Documentation](#Documentation)
8. [Troubleshooting](#troubleshooting)
9. [Conclusion](#conclusion)
10. [Contributors](#contributors)
11. [License](#license)
12. [Disclaimer](#Disclaimer)

## Introduction

Anthill-Coder is a cutting-edge, chat interface designed to revolutionize software development. Today's Current AI chat interfaces are too unwieldy for most software developers. By leveraging the power of agentic ai, Anthill-Coder can be your own personal development team, allowing you to get your project to production fast.

### The Challenge of Modern AI Chat Interfaces

Current AI chatbots are not optimal for software developers. While popular chat interfaces like ChatGPT and Claude have opened up a world of opportunities, they are still innefficient tools for developing software. Users often have to submit multiple prompts to get the output they are looking for, must copy over large quantities of code to test and then iterate. This process can be not only time-consuming but also emotionally draining.

### Enter Anthill-Coder: Your personal development team

Anthill-Coder steps in as a game-changing solution to these challenges. Anthill-Coder is not just a tool, but a team of agents that tirelessly work together to build your project. With just a single prompt, Anthill will generate and make modifications to your project across a large number of files, allowing you to be the tech lead and focus on more interesting challenges.

## Features
1. **Starting Objectives**
   - Tell Antill what you would like to build
   - Anthill will decide how many agents to spawn to complete the goal
   - Each agent will see your objective and coordinate tasks with each other
   - The completed project will be saved to output/generated_artifacts
2. **New Objectives**
    - Tell Anthill what you would like to modify in your project
    - Anthill will find the relevant files and coordinate changes across each file
3. **Constraints**
    - Constraints are optional and allow you to set limits on what each agent can do. 
4. **Tracking changes**
    - Anthill will also track any manual changes that you make to the generated project, and will keep these in mind when iterating new changes.
5. **Feedback**
    - Anthill provides realtime feedback on its progress in natural language
6. **Inference Optimization**
    - Anthill greatest strenth is its ability to optimize inference per token. By breaking the objective into many smaller tasks, it is able to use smaller context windows per task and therefore achieve a higher rate of inference compared to a single context window chat interface

## Demo
    Click the below link to see Anthill Coder in action
    https://youtu.be/zmBZtUpUpEU

## Installation

1. **Download and Install Node:**

    **macOS**
    Using Homebrew (recommended)

    Open Terminal.
    Install Homebrew if not already installed:
    ```
    /bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
    ```

    Install Node.js:
    ```
    brew install node
    ```

    **Windows**

    Visit the official Node.js website: https://nodejs.org/
    Download the Windows Installer (.msi) for the LTS version.
    Run the installer and follow the installation wizard.
    Restart your computer after installation.


    **Linux**
    **Ubuntu/Debian**

    Open Terminal.
    Update package index:
    ```
    sudo apt update
    ```
    Install Node.js:
    ```
    sudo apt install nodejs npm
    ```

2. **Clone the repository:**
   ```bash
   git clone https://github.com/georgemg100/anthill-coder
   cd anthill-coder
   ```

## Configuration
### 1. .env
This file contains sensitive information. Never share or commit this file to version control.

- `ANTHROPIC_API_KEY: [Your Anthropic API Key]`
    - Replace with you Anthropic API Key Claude integration
    - Note: You need to add credit to your Anthropic account to use the API. You can add credit by visiting the [Anthropic billing dashboard](https://console.anthropic.com/settings/plans).
- `ANTHILL_LICENSE_KEY: [Your Anthill License Key]`
    - Visit https://anthillcoder.xyz to get your free license key


#### Usage

   run --init when you are building a project from scratch. Make sure your output/generated_artifacts directory is empty before running init

   run --iterate when you want to modify or add to an existing project

## Usage
0. **Example Usage**
   ```
    node src/main.js --init --objectives 'Create a crypto meme token for the ethereum block chain' --constraints ''
   ```
   ```
    node src/main.js --init --objectives 'Create a twitch bot that filters out negative sentiment. Include instructions for set up' --constraints ''
   ```
   ```
    node src/main.js --init --objectives 'Create a react front end integrated with an express backend' --constraints ''
   ```
   ```
    node src/main.js --iterate --objectives 'Add facebook login to the home page' --constraints ''
   ```
1. **Parent directory**
    - ensure you are in the parent directory when you run Anthill
2. **Init or Iterate**
    - Run init when you are generating a project from scratch
    Run iterate when you want to modify an existing project
3. **Run Anthill**
    For a new project
    ```
    node main.js --init --objectives '<one or more objectives>' --constraints '<zero or more constraints>'
    ```
    When iterating the project
    ```
    node main.js --iterate --objectives '<one or more objectives>' --constraints '<zero or more constraints>'
    ```
  
If you encounter any issues, you can open an issue on [GitHub](https://github.com/georgemg100/anthill-coder/issues).
  Please add valuable details to the subject and to the description. If you need new feature then please reflect this.  
  I'll be more than happy to assist you!

## Contributors

- [georgemg100](https://github.com/georgemg100) - Creator and Lead Developer

Anthill-Coder is still in beta, and your feedback, suggestions, and contributions are highly valued. Feel free to open issues, suggest enhancements

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Disclaimer
 The creator does not assume any responsibility for its use. The use of automated tools may have implications on your device, and caution is advised.