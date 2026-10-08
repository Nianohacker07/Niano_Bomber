# 💣 Niano_Bomber

**Niano_Bomber** is a powerful SMS bombing script for testing OTP spam protections on Pakistani numbers. Built in Shell (`.sh`) format, it runs easily in **Termux**, **Kali Linux**, and other Linux environments.

> ⚠️ **Strictly for educational and testing purposes only. Misuse is illegal and unethical.**

---------------------------------------------------------------------------------------------------------------------------

## ⚙️ How It Works

- Supports **only Pakistani phone numbers**
- Format: `03XXXXXXXXX`
- You input the number and how many **times** you want the bombing to occur.
  - **One run = 100+ OTPs**
- OTP Sources:
  - 🟣 **Jazz numbers** → Sends **JazzCash** OTPs
  - 🔵 **Other numbers** → Sends:
    1. **3x EasyPaisa** OTPs
    2. Then continuous **Bajao** OTPs

---------------------------------------------------------------------------------------------------------------------------

## 🚀 Setup & Run

### 1. 📥 Clone the Repository

```bash
git clone https://github.com/Nianohacker07/Niano_Bomber.git
cd Niano_Bomber
```

### 2. ✅ Make the Script Executable

```bash
chmod +x bomber.sh
```

### 3. 🔧 Run the Script

```bash
./bomber.sh
```

---------------------------------------------------------------------------------------------------------------------------

## 📲 Input Example

```text
Enter the phone number (Format: 03XXXXXXXXX): 03.......... ( Number should be based on 11 digits)
Enter number of runs (e.g., 1 = ~100 OTPs): 3
```

- This will send ~300 OTPs in total.
- Works **only on Pakistani numbers**

---------------------------------------------------------------------------------------------------------------------------

## 🖥️ Supported Platforms

- ✅ Termux (Android)
- ✅ Kali Linux
- ✅ Ubuntu / Debian / Linux Mint
- ✅ Any Linux distro with Bash

---------------------------------------------------------------------------------------------------------------------------
## ⚠️ Disclaimer

This project is intended for **educational and ethical testing** only. Spamming individuals without consent is **illegal** and punishable by law. The author takes **no responsibility** for any misuse of this tool.


## 👤 Author

- **Zulqarnain Ahmed**
- GitHub: [Nianohacker07](https://github.com/Nianohacker07)
