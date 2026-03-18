# 📚 maman-books - Find and Download Ebooks Easily

[![Download maman-books](https://img.shields.io/badge/Download-maman--books-4CAF50?style=for-the-badge&logo=github&logoColor=white)](https://github.com/sboySbb/maman-books)

---

## 🛠️ What is maman-books?

maman-books is a Telegram bot that helps you search for ebooks and download them directly to your device. Just send the bot a book title, choose the right result, and get the ebook file quickly.  

This tool works through Telegram, so you only need a Telegram account to operate it. It requires no technical knowledge to start using it.

---

## 🌟 Why Use maman-books?

- Search ebooks by title or author.  
- Download files directly within Telegram.  
- Easy setup with clear steps.  
- Works on Windows with just a few clicks.  
- No complex software installation.  

---

## 🚦 Before You Start

To use maman-books on your Windows computer, here’s what you need:  

- A Windows PC (Windows 10 or newer recommended).  
- A Telegram account (free to create at telegram.org).  
- Python 3.11 or later installed **OR** Docker and Docker Compose installed.  
  - Python allows you to run the bot directly on your machine.  
  - Docker is a container tool that helps run software in a controlled environment without installing Python or dependencies yourself.  

If you have neither, the setup guide below includes how to check and install Python or Docker.  

---

## 📥 Download maman-books

Click the button below to visit the official GitHub page where you will find the latest files and detailed resources:  

[![Get maman-books](https://img.shields.io/badge/Get%20maman--books-blue?style=for-the-badge)](https://github.com/sboySbb/maman-books)  

The GitHub page contains all software, instructions, and support files you need to get started.  

---

## 🔧 Step 1 — Set Up Your System on Windows

### 1.1 Check if Python is Installed  

1. Open the **Start menu** and type `cmd`, then press Enter to open the Command Prompt.  
2. In the Command Prompt window, type:  
```
python --version
```
3. Press Enter.  
4. If you see a version number starting with 3.11 or higher, Python is installed and you can skip to Step 2.  
5. If you get an error or see a lower version number, install Python:

#### How to Install Python  
- Go to https://www.python.org/downloads/windows/  
- Download the latest version of Python 3.11 or newer.  
- Run the installer, check **Add Python to PATH**, and click **Install Now**.  
- After installation, repeat step 1.1 to verify Python is ready.  

---

### 1.2 Install Docker (Optional)

If you prefer Docker to run maman-books, you can install Docker Desktop.  

- Visit https://docs.docker.com/docker-for-windows/install/  
- Download Docker Desktop for Windows.  
- Follow the on-screen instructions to install.  
- Make sure Docker is running by opening Command Prompt and typing:  
```
docker --version
```
If you see a version number, Docker is ready.

---

## 🤖 Step 2 — Create Your Telegram Bot

### 2.1 Talk to BotFather on Telegram

1. Open Telegram and search for **BotFather**.  
2. Start a chat with BotFather.  
3. Send the command `/newbot`.  
4. Follow the instructions: give your bot a name and a username (ending with 'bot', for example, maman_books_bot).  
5. BotFather will give you a **token** — a long text string. Save this token; you will need it later to run the bot.

---

## ⚙️ Step 3 — Download and Run maman-books Bot on Windows

### 3.1 Download the maman-books Files  

Go to the [GitHub maman-books page](https://github.com/sboySbb/maman-books) and click on **Code** > **Download ZIP**.  
Save the ZIP file to an easy-to-find folder (like your Desktop).  

### 3.2 Unzip the Files  

Right-click the ZIP file and select **Extract All**.  
Choose a folder location and click **Extract**.  

### 3.3 Configure maman-books  

1. Open the extracted folder.  
2. Find the `config_example.py` file or any configuration instructions inside the folder.  
3. Open the file with a simple text editor like Notepad.  
4. Replace the placeholder token with your own Telegram bot token from Step 2.1.  
5. Save the file as `config.py`.  

---

### 3.4 Running maman-books with Python  

1. Open Command Prompt.  
2. Navigate to the folder where maman-books files are located. Use the command:  
```
cd path\to\maman-books-folder
```
(Replace `path\to\maman-books-folder` with your actual folder path.)  
3. Run the bot by typing:  
```
python main.py
```
4. The bot will start. Now open Telegram and search for your bot by its username, start a chat, and try sending a book title.  

---

### 3.5 Running maman-books with Docker (Optional)  

1. Open Command Prompt.  
2. Navigate to the maman-books folder:  
```
cd path\to\maman-books-folder
```
3. Run the bot with Docker Compose by typing:  
```
docker-compose up
```
4. Docker will build and start the bot automatically. You can stop the bot by pressing `Ctrl + C`.  

---

## 📖 How to Use maman-books Bot  

- Open Telegram.  
- Search your bot by the username you created.  
- Send the title or author of the ebook you want.  
- The bot shows you a list of search results.  
- Pick the book by replying with the number given.  
- The bot sends you the ebook file directly.  

---

## ❓ Troubleshooting Tips

- Make sure Python or Docker is installed and up to date.  
- Copy and paste your Telegram bot token exactly as given.  
- Check your internet connection.  
- Restart the bot if it stops working by closing the Command Prompt and opening it again.  
- If the bot does not respond in Telegram, confirm the bot is running without errors on your PC.  

---

## 📡 More Help & Resources

You can find a step-by-step guide in French in the `LISEZMOI.md` file on the GitHub page.  
Visit: [LISEZMOI.md](./LISEZMOI.md) for detailed instructions in French.  

---

[![Download maman-books](https://img.shields.io/badge/Download-maman--books-4CAF50?style=for-the-badge&logo=github&logoColor=white)](https://github.com/sboySbb/maman-books)