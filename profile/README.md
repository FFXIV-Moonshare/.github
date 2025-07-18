# 🌙 Moonshare

**Moonshare** ist ein einfaches, modulares File-Sharing- und Kommunikationssystem für Final Fantasy XIV, entwickelt als Dalamud-Plugin. Es ermöglicht Spielern, sich über eine WebSocket-Verbindung zu verbinden und Dateien oder Informationen direkt mit anderen Spielern auszutauschen – schnell, leichtgewichtig und serverbasiert.

---

## 🚀 Features

- 🔌 **WebSocket-basierte Verbindung zwischen Spielern**
- 📂 **Dateifreigabe-System** (in Entwicklung)
- 🧑‍🤝‍🧑 **Verbindung über eindeutige UserIDs**
- 💬 **Nachrichtenübertragung und Sessions**
- 💡 Integriert in Dalamud mit eigenem UI-Window
- 🛡️ Geplante Erweiterung um Rechte-/Zugriffsmanagement und Authentifizierung

---

## 🧰 Installation

### Voraussetzungen

- Dalamud-Plugin-System (XIVLauncher)
- WebSocketSharp (für den Server)
- .NET 6+ (für das Servermodul)

### Plugin Installation

Das Plugin befindet sich derzeit in der Entwicklung und ist **noch nicht öffentlich über das Dalamud-Repo** verfügbar. Du kannst es manuell bauen und in deinen Plugin-Ordner legen:

1. Klone dieses Repository
2. Baue das Projekt in Visual Studio mit dem Dalamud-Paketreferenzsystem
3. Füge das Plugin in deinen Dalamud Plugins-Ordner ein
4. Starte FFXIV mit XIVLauncher und aktiviere „Moonshare“

### Server starten

```bash
dotnet run --project MoonshareServer
