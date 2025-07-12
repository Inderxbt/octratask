# # Octra

# Wallet generation Guide

---

## 🔹 Step 1:

```bash
curl -fsSL https://bun.sh/install | bash
source ~/.bashrc
bun --version
````

---

## 🔹 Step 2:

```bash
bun install
```

---

## 🔹 Step 3:

```bash
bun run build
```

---

## 🔹 Step 4:

```bash
bun start
```

> click the **“PORTS”** tab open link under forwarded address in browser

---

**Wallet Generated, Back up private key**

Go to https://faucet.octra.network/

Paste Wallet address & claim faucet

Join Discord - https://discord.gg/gfAazqK9Xb

---

# Quest1 & Quest2 - Send Tokens & ENCRYPT / DECRYPT BALANCE

### Step 1

Open in Codespace

1. Go to 👉 [https://github.com/octra-labs/octra_pre_client](https://github.com/octra-labs/octra_pre_client)
2. Click the green `Code` button  
3. Select → `Open with Codespaces` → `+ New codespace`
4. Wait for the environment to fully load

### Step 2

In the Codespace terminal run this command 

```bash
pip install -r requirements.txt
````

---

```bash
cp wallet.json.example wallet.json
```

### Step 3 
Then open the file: wallet.json

Paste your test wallet details 


```
{
  "priv": "private key here",
  "addr": "octxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx",
  "rpc": "https://octra.network"
}
```

---

### 🔹 Step 4 : Send a test transaction

Replace address with any address from explorer - https://octrascan.io/

```bash
python cli.py send --to oct9AEtCF44sWQVaQm91A2c4EKXWBXYFECXMQVCdtvhLXXF --amount 0.01
```

---

### 🔹 Step 5 :
• Use Command 1 For Send tx
• Use Command 3 For Multi send
• Use Command 4 For Encrypt
• Use Command 5 For Decrypt

Keep doing transactions, you can also use other commands like `6` & `7` for private Transfer & Claim , Use Address From Explorer: https://octrascan.io/

---
