# Email Writer Assistant Chrome Extension

## Overview
The **Email Writer Assistant** is a Chrome extension designed to help users generate AI-powered email replies directly within their Gmail interface. Whether you’re replying to an email or drafting a new one, this extension will assist you in crafting professional, friendly, or casual responses based on the email content and tone preferences you set.

**Note**: This extension is currently under revision and is not yet fully published. We're working hard to improve the user experience and functionality. Please stay tuned for updates!

## Features
- **AI-Powered Responses**: Automatically generate email replies using advanced AI algorithms.
- **Tone Selection**: Choose from multiple tone options (Professional, Casual, Friendly).
- **Seamless Gmail Integration**: Works directly within the Gmail interface for a smooth user experience.
- **Copy to Clipboard**: Effortlessly copy generated replies to the clipboard for easy pasting.

## Installation

### Steps to Install:
1. **Visit the Chrome Web Store**:
   - Go to the [Chrome Web Store](https://chrome.google.com/webstore).
   
2. **Search for "Email Writer Assistant"**:
   - Type "Email Writer Assistant" in the search bar and find the extension.

3. **Add the Extension**:
   - Click the **Add to Chrome** button to install the extension.

4. **Pin the Extension**:
   - After installation, pin the extension to your toolbar for easy access. Click the puzzle piece icon in your browser toolbar and click the pin icon next to **Email Writer Assistant**.

## Usage

1. **Activate the Extension**:
   - Click the extension icon in your toolbar to open the interface.
   
2. **Enter the Email Content**:
   - Paste or type the content of the email you want to reply to in the **Original Email Content** field.

3. **Select the Tone** (Optional):
   - Choose a tone for your reply (Professional, Casual, Friendly) from the dropdown menu.

4. **Generate Reply**:
   - Click the **Generate Reply** button to get an AI-generated response based on the email content and tone selected.

5. **Copy to Clipboard**:
   - After the reply is generated, click the **Copy to Clipboard** button to copy the reply and use it in your email draft.

## Permissions
The extension requests the following permissions:

- **activeTab**: To interact with the current tab you are viewing and generate responses within Gmail.
- **storage**: To store user preferences (such as tone) for later use.
- **host_permissions**:
  - **`https://localhost:8080/*`**: Allows communication with a local server or API endpoint to generate email replies.
  - **`*://mail.google.com/*`**: Grants access to Gmail pages to read email content and insert generated replies.


## Backend
The backend of this extension is built using **Spring Boot**, a powerful Java-based framework for building web applications and microservices. The backend handles the AI-powered email reply generation and tone selection logic.

The backend is deployed using **Koyeb**, a modern platform for deploying and scaling applications. Koyeb provides seamless deployment, automatic scaling, and global load balancing, ensuring the backend is always available and responsive.



## Contributing
We welcome contributions! Please follow these steps if you would like to contribute:

- Fork the repository.
- Create a new branch (git checkout -b feature-branch).
- Commit your changes (git commit -am 'Add new feature').
- Push to the branch (git push origin feature-branch).
- Submit a pull request.


## License
This extension is licensed under the https://engineerick-portfolio.vercel.app/ License.
