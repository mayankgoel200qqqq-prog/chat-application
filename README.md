# chat-application
💬 Python Chat Application

A real-time multi-user chat application built using Python sockets and threading. This project allows multiple clients to connect to a server and communicate instantly via a command-line interface.

---

🚀 Features

- 💬 Real-time messaging
- 👥 Multi-client support
- 🔗 Client-server architecture
- 🧵 Multi-threaded communication
- 🖥️ Lightweight CLI-based interface

---

📂 Project Structure

chat-app/
│── server.py
│── client.py
│── README.md

---

🛠️ Requirements

- Python 3.x
- No external libraries required

---

▶️ How to Run

1️⃣ Start the Server

python server.py

2️⃣ Start the Client(s)

Open multiple terminals and run:

python client.py

3️⃣ Enter Nickname

Each user will be prompted to enter a nickname.

---

💡 How It Works

- The server listens for incoming client connections.
- Each client connects and sends a nickname.
- Messages sent by any client are broadcast to all connected users.
- The server handles multiple clients using threading.

---

📸 Example

[User1]: Hello!
[User2]: Hi there!
[User3]: Welcome to the chat 👋

---

🔧 Configuration

By default:

- Host: "127.0.0.1" (localhost)
- Port: "5555"

You can modify these values in both "server.py" and "client.py".

---

📌 Future Improvements

- 🖼️ GUI using Tkinter or PyQt
- 🔐 User authentication system
- 📡 Private messaging
- 🌐 Online hosting (public server)
- 📁 File sharing feature

---

🤝 Contributing

Contributions are welcome! Feel free to fork this repository and submit a pull request.

---

📄 License

This project is licensed under the MIT License.

---

👨‍💻 Author

Developed by Nivaan Ghatwal

---

⭐ Support

If you like this project, give it a ⭐ on GitHub!
