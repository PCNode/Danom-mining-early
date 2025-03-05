# ðŸš€ Danom Early Worker Nodes (Mining)

## ðŸ“Œ Steps to Set Up

### **1ï¸âƒ£ Create an Account**
First, create an account on Hugging Face:  
ðŸ”— **[Sign Up Here](https://huggingface.co/join)**

---

### **2ï¸âƒ£ Update Your System**
Before installing, make sure your system is up to date. Run the following command:

```bash
sudo apt update && sudo apt install -y wget curl tar screen
```

---

### **3ï¸âƒ£ Download and Extract the Script**
Paste this script into your **VPS terminal**:

```bash
wget https://github.com/DanomSite/release/releases/download/v4/DanomV4.tar.gz && tar -xvzf DanomV4.tar.gz
cd Danom
```

---

### **4ï¸âƒ£ Install Danom**
Run the following installation script:

```bash
curl -fsSL 'https://testnet.danom.site/install.sh' | bash
```

---

### **5ï¸âƒ£ Configure Your Wallet**
Replace `0xYOUR_WALLET_ADDRESS` with **your actual wallet address** and  
Replace `YOUR_POOL_LIST` with **your Hugging Face API Pool List**, then run:

```bash
echo '{"wallet": "0xYOUR_WALLET_ADDRESS", "pool_list": "YOUR_POOL_LIST"}' > wallet_config.json
```

---

### **6ï¸âƒ£ Create a Screen Session**
To ensure that the script runs in the background:

```bash
screen -S danom
```

---

### **7ï¸âƒ£ Start Mining**
Run the mining script:

```bash
./danom
```

To **detach from the screen session** and keep it running, press:  
ðŸ”¹ `CTRL + A + D`  

To **reconnect** to the running session:

```bash
screen -r danom
```

---

## ðŸŽ¯ **Need Help?**
ðŸ“Œ **Danom Official Website:** [Danom Site](https://testnet.danom.site)  
ðŸ“Œ **Hugging Face:** [HuggingFace](https://huggingface.co)  

Happy mining! ðŸš€ðŸ”¥
