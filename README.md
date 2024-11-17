Here's the README content provided as code:  

```markdown
# **Terminal GPT (tgpt) 🚀**

![GitHub Go Version](https://img.shields.io/github/go-mod/go-version/aandrew-me/tgpt)  
![GitHub Release](https://img.shields.io/github/v/release/aandrew-me/tgpt)  
![Arch Linux Package](https://img.shields.io/archlinux/v/extra/x86_64/tgpt)  
![Chocolatey Version](https://img.shields.io/chocolatey/v/tgpt)

> **A versatile, cross-platform AI-powered command-line interface for chatting and generating images directly from your terminal!**

<p align="center">
  <img src="tgpt.svg" alt="tgpt logo" width="200">
</p>

---

## 🌟 **Key Features**
- **Providers Supported**: Works with popular AI providers like OpenAI, Blackbox AI, Phind, and more.
- **No API Key Needed**: Some providers like DuckDuckGo don't require an API key.
- **Image Generation**: Generate stunning visuals using Blackbox AI.
- **Interactive Modes**: Enjoy both standard and multiline interactive chat modes.
- **Advanced Options**: Customize AI behavior with options like temperature, model selection, and more.

---

## 📚 **Usage**

```bash
tgpt [Flags] [Prompt]
```

### **Command Flags**
| Flag              | Description                                    |
|-------------------|------------------------------------------------|
| `-s, --shell`     | Generate and execute shell commands. (Experimental) |
| `-c, --code`      | Generate code snippets. (Experimental)         |
| `-q, --quiet`     | Output response without loading animation      |
| `-w, --whole`     | Return response as a complete text block       |
| `-img, --image`   | Generate images from text input                |
| `--provider`      | Set the AI provider. Default: `phind`          |
| `--model`         | Specify the AI model (provider-dependent)      |
| `--key`           | Set API key for services like OpenAI           |
| `--temperature`   | Adjust creativity (higher values are more random) |
| `--max_length`    | Set the maximum response length                |

---

### **Providers**
| Provider         | Features                                       |
|------------------|------------------------------------------------|
| **Phind**        | Default provider; developer-friendly.          |
| **OpenAI**       | Supports multiple models with API key.         |
| **DuckDuckGo**   | Offers GPT-4o-mini and other models.           |
| **Blackbox AI**  | Tailored for coding-related tasks.             |
| **Groq**         | Requires free API key; supports LLaMA2-70b.    |
| **KoboldAI**     | Creative and novel-style text generation.      |

---

## ✨ **Examples**

```bash
# Simple Prompt
tgpt "Explain quantum mechanics in simple terms."

# Use a Specific Provider
tgpt --provider openai --key "sk-xxx" "Write a Python script to reverse a string."

# Interactive Mode
tgpt -i
```

---

## 🚀 **Installation**

### **GNU/Linux and macOS**
```bash
curl -sSL https://raw.githubusercontent.com/aandrew-me/tgpt/main/install | bash -s /usr/local/bin
```

### **Windows**
- **Scoop**:  
  ```bash
  scoop install https://raw.githubusercontent.com/aandrew-me/tgpt/main/tgpt.json
  ```
- **Chocolatey**:  
  ```bash
  choco install tgpt
  ```

### **FreeBSD**
```bash
pkg install tgpt
```

---

## 🔧 **Updating**
```bash
tgpt -u
```

---

## 🌐 **Proxy Support**
**Configuration Options**:
- Environment Variables:  
  Set `http_proxy`, `HTTP_PROXY`, or equivalent for socks5.
- Configuration File:  
  Place your proxy settings in a file at `~/.config/tgpt/proxy.txt`.

Example (`proxy.txt`):
```
http://127.0.0.1:8080
```

---

## 📥 **Uninstallation**
```bash
sudo rm $(which tgpt)
```

---

## 🎥 **Demo**

<p align="center">
  <img src="https://user-images.githubusercontent.com/66430340/233759296-c4cf8cf2-0cab-48aa-9e84-40765b823282.gif" alt="Demo gif" width="700">
</p>

---

### 🙌 **Contributing**
We welcome contributions! Feel free to open issues or pull requests to improve tgpt.

---

### 📝 **License**
This project is licensed under the [MIT License](https://opensource.org/licenses/MIT).
```

