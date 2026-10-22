# Minecraft Server Setup (v1.21.5)

This repository contains the configuration for a **Velocity-proxied Minecraft server** with multiple backend servers.

---

## 🚀 Quick Start

### 1. **Open Three Terminals**
You need to run three separate servers: `limbo`, `server`, and `velocity`.

### 2. **Start Each Server**
In each terminal, navigate to the respective directory and start the server:


# Terminal 1: Limbo Server
```bash
cd limbo && java -jar server.jar
```
# Terminal 2: Main Server
```bash
cd server && java -jar server.jar
```

# Terminal 3: Velocity Proxy
```bash
cd velocity && java -jar server.jar
```

### 3. **Joining the Server***
In the ports tab set port 25567 to public and copy its https address
Then change the https:// to wss:// and thats your ip!
