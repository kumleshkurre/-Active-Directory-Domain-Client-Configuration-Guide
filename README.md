# 🌐 Active Directory Domain Client Configuration

> **PC / Laptop ko Active Directory Domain me join karne ke liye step-by-step guide** 💻🔐
> *(Specially useful for IT Support / Network Engineer projects)*

---

## 🧩 Step 1: Configure Network (IP Address)

### 🔧 open Network Settings 

* **Run Window:** `Windows + R`
* Type : `ncpa.cpl`
* **Enter** press karein

### 🌐  Configure Active Adapter

* Right-click on the active network adapter → Properties
* Select: **Internet Protocol Version 4 (TCP/IPv4)**
* Click: **Properties**

### 🧾 IP Configuration

```text
IP Address        : 10.0.0.2
Subnet Mask       : 255.0.0.0
Preferred DNS     : 10.0.0.1
```

* **Apply → OK**

---

## 📡 Step 2: Check Network Connectivity

### 💻 Open Command Prompt 

```cmd
ping 10.0.0.1
```

```cmd
ping kurrecomputers.local
```

✅ **The ping Reply should be successfully **

---

## 🏢 Step 3: Join PC / Laptop to Domain

### ⚙️ Open System Settings

* **This PC → Right Click → Properties**
* **Advanced system settings**
* **Computer Name tab → Change**

### 🧑‍💼 Join  the Domain 

```text
Domain Name: kurrecomputers.local
```

* **Next** click 
* **Enter Domain Administrator Username & Password** enter 
* **OK → Apply → OK**

---

## 🔁 Step 4: Restart the System

* **Restart the computer** ♻️

Restart ke baad client successfully domain ka part ban jata hai.

---

## ✅ Final Output

🎉 **After the restart, the client system will be successfully joined to the Active Directory domain!**

✔️ Centralized Login
✔️ Group Policy Support
✔️ Domain Security Enabled

---

## 🛠️ Requirements

* Windows Server (AD DS Installed)
* DNS Server prperly  Configured
* Client & Server connected to the same network 

---

## 👨‍💻 Author

**Kumlesh Kurre**
🎓 BCA (Pursuing)
💼 IT Support / Networking Enthusiast
