# Setting up the `.env` File
<div style="text-align: justify">

## Table of Contents
1. [What is a `.env` file?](#1-what-is-a-env-file)
2. [Which OpenAI Key should I use?](#2-which-openai-key-should-i-use)
3. [How to get an OpenAI Key (for private users)](#3-how-to-get-an-openai-key-for-private-users)
4. [How to set up the `.env` file](#4-how-to-set-up-the-env-file)

## 1. What is a `.env` file?

A `.env` file is a small text file that helps your project work by storing important information, like passwords or special codes (called API keys). These codes are needed so the project can connect to services like OpenAI. This makes it easier and safer for you to use the project, even if you do not have technical experience.

## 2. Which OpenAI Key should I use?

If you are using this project as part of an organization, such as a university or research group, you should first check if your organization already has an OpenAI API key available. In this case, please contact your project administrator, supervisor, or the person who gave you access to this project and ask them for the correct API key and, if needed, the assistant IDs.

If you are working on this project as a private individual and your organization does not provide a key, you will need to create your own OpenAI account and get a personal API key. This is a simple process and is explained in the next section below. Please note that using your own key may require you to sign up for a subscription or pay for usage, depending on OpenAI’s pricing. Always keep your API key private and do not share it with others.

## 3. How to get an OpenAI Key (for private users)

To use OpenAI features in this project, you need a personal key from OpenAI. This key is like a password that allows you to use their services.

1. Visit [https://platform.openai.com/signup](https://platform.openai.com/signup) and sign up for an account, or log in if you already have one.
2. Click your profile icon in the top right and choose **"View API keys"**.
3. Click **"Create new secret key"**.
4. Copy the key that appears (it starts with `sk-`). **Keep this key private and do not share it.**

## 4. How to set up the `.env` file

1. In the folder where you received this project, create a new file named `.env` (just `.env`, nothing else).
2. Open the `.env` file and copy in the following lines. Replace the example text with your real information:

   ```
   OPENAI_API_KEY=<your-openai-api-key>
   ASSISTANT_ID=<your-assistant-id>
   APPENDER_ASSISTANT_ID=<your-appender-assistant-id>
   ```
   It's done. The assistent is ready to use. 
</div>