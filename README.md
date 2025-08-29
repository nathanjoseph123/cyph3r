# cyph3r

*cyph3r* is a lightweight messaging app and  server for Windows.  
It allows you to ping connected clients, forward messages and files securely, and display notifications. Built with Python and packaged as a standalone Windows executable using PyInstaller.

---

## Features

- Ping clients to check who is online
- Forward messages and files between clients
- Display  notifications using Plyer
- customizable background
- Custom app icon and GUI
- Secure and easy-to-use interface
- modify ip address and port of both server and client
---

## Installation

server(cyph3r): Download the latest release https://nullroot1.itch.io/cyph3r

*IMPORTANT*📌
---
How to use the server alone for development 
---
-immediately after connecting send allass.?? Nickname  i.e if i want my nickname to be john i will send allass.?? john
-incase you are use the server alone to build your stuff the server sends out a ping (pqpwpopopo) to all it's clients to know who's alive so ensure to filter it out
​- message  sent to the server should be in this format Nickname/alias : message i.e john : hello world

---

client(whispher/Шепот): Download the latest release https://nullroot1.itch.io/whisper

---

*Windows:*

1. Download whisper.exe or cyph3r.exe from the above.
2. Double-click to run. No installation required.

---
*linux:*
1. Download whisper.exe or cyph3r.exe from the link above.
2. Use wine to run . No installation required.

---
## Usage

1. Launch the application.
2. The main window button will be red if connected to the server else red.
3. Use the interface to send messages or files.
4. Notifications will appear when events occur (e.g., new file received).

---

## Dependencies (for running from source)

If running from source, install required packages:

```bash
pip install -r requirements.txt
