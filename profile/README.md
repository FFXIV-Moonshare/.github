# 🌙 Moonshare

**Moonshare** is a lightweight, modular file sharing and communication system for **FINAL FANTASY XIV**, built as a Dalamud plugin.  
It allows players to connect to each other over WebSocket and exchange files or messages directly — fast, secure, and server-backed.

---

## 🚀 Features

- 🔌 **WebSocket-based peer connections**
- 📂 **File sharing system** *(in development)*
- 🧑‍🤝‍🧑 **UID-based player linking**
- 💬 **Message and session exchange**
- 💡 Fully integrated with Dalamud via a custom UI window
- 🛡️ Planned extensions: authentication, permission management, access control

---

## 🧰 Installation

### Requirements

- Dalamud Plugin System via XIVLauncher
- .NET 8 or higher (for running the backend server)

---

### Plugin Installation

> 🚧 **Note:** Moonshare is currently under active development and is **not yet available through the official Dalamud plugin repo**. You can build and install it manually:

1. Clone this repository  
2. Open the solution in Visual Studio (with Dalamud references configured)  
3. Build the plugin project  
4. Place the output DLL in your Dalamud `DevPlugin` folder  
5. Launch FFXIV with XIVLauncher and enable **Moonshare** via `/xlplugins`

---

### Starting the Server

To run the server locally (e.g., for testing your plugin build):

```bash
dotnet run --project MoonshareServer
