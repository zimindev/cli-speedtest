# 🚀 `speedtest-cli` — Test Your Internet Speed from the Command Line

`speedtest-cli` is a command-line interface for testing internet bandwidth using [Speedtest.net](https://www.speedtest.net). It can measure download and upload speeds, as well as ping latency — directly from your terminal.

---

## ✅ Features

- Test download/upload speed & ping  
- Select a specific server to test against  
- Share results with a Speedtest.net link  
- Works in scripts and cron jobs  
- Lightweight and easy to use  

---

## 🔧 Installation

### On Debian/Ubuntu:
```bash
sudo apt update && sudo apt install speedtest-cli
```

### On Arch Linux:
```bash
sudo pacman -S speedtest-cli
```

### On macOS (via Homebrew):
```bash
brew install speedtest-cli
```

### Using `pip` (cross-platform):
```bash
pip install speedtest-cli
```

---

## 🚀 Basic Usage

### Run a basic speed test:
```bash
speedtest
```

### Alternative command:
```bash
speedtest-cli
```

---

## 🌐 Output Example

```bash
Retrieving speedtest.net configuration...
Testing from YourISP (192.0.2.1)...
Retrieving speedtest.net server list...
Selecting best server based on ping...
Hosted by ExampleISP (City) [10.00 km]: 12.345 ms
Download: 85.32 Mbit/s
Upload: 15.67 Mbit/s
```

---

## ⚙️ Useful Options

| Option                          | Description                              |
|----------------------------------|------------------------------------------|
| `--simple`                      | Simplified output (ping, download, upload only) |
| `--bytes`                       | Display results in bytes instead of bits |
| `--share`                       | Generate a Speedtest.net shareable URL   |
| `--server [ID]`                 | Use a specific server by ID              |
| `--list`                        | List all available servers               |
| `--timeout [SECONDS]`           | Set timeout for tests                    |
| `--json`                        | Output results in JSON                   |
| `--csv`                         | Output results in CSV format             |

---

## 🎯 Examples

### Simple and fast:
```bash
speedtest --simple
```

### Get a shareable link:
```bash
speedtest --share
```

### List available servers:
```bash
speedtest --list
```

### Test using a specific server:
```bash
speedtest --server 1234
```

### Save output as JSON:
```bash
speedtest --json > result.json
```

---

## 🧩 Alternatives

- `fast` — CLI from Netflix to check download speed only  
- `iperf3` — Advanced network performance tool  
- `nperf` — GUI and CLI alternatives for network testing  

---

## 📚 More Info

- GitHub: [https://github.com/sivel/speedtest-cli](https://github.com/sivel/speedtest-cli)  
- Help: `speedtest --help`  
- API: [https://www.speedtest.net](https://www.speedtest.net)
