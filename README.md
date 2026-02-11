# Evilginx 2.0 Phishlets Repository

A curated collection of **Evilginx 2.0 phishlets** designed for **security research, red-team simulations, and authorized penetration testing labs**.

This repository aims to provide well-structured, tested, and easy-to-deploy phishlets that help security professionals understand modern phishing techniques and improve defensive strategies.

⚠️ **Disclaimer:**
These phishlets are provided strictly for **educational purposes and authorized security assessments**. Do **not** use them against targets without explicit permission. Unauthorized phishing is illegal and unethical.

---

## 📌 Features

* Ready-to-use Evilginx 2.0 phishlets
* Clean and readable configurations
* Lab-tested setups
* Organized for quick deployment
* Continuously updated

---

## 📂 Repository Structure

```
.
├── phishlets/
│   ├── service-name.yaml
│   ├── example.yaml
│
├── lures/
│   ├── sample-configs
│
└── README.md
```

**phishlets/** → Contains YAML configurations for supported services.
**lures/** → Optional lure examples for testing workflows.

---

## ⚙️ Requirements

Before using these phishlets, ensure you have:

* A properly configured **Evilginx 2.x** server
* A registered domain
* DNS configured correctly
* Valid SSL certificates (handled automatically by Evilginx)
* A controlled lab or authorized engagement

Official Evilginx repository:
👉 [https://github.com/kgretzky/evilginx2](https://github.com/kgretzky/evilginx2)

---

## 🚀 Quick Start

### 1. Clone the Repository

```bash
git clone https://github.com/its-ashu-otf/evilginx-2.0-phishlets.git
cd evilginx-phishlets
```

### 2. Move Phishlets

```bash
cp phishlets/* /path/to/evilginx/phishlets/
```

### 3. Launch Evilginx

```bash
sudo evilginx
```

### 4. Enable a Phishlet

```
phishlets
phishlets enable <phishlet-name>
```

### 5. Create a Lure

```
lures create <phishlet-name>
lures get-url <id>
```

---

## 🧪 Recommended Usage

Use these phishlets for:

* Red team exercises
* Phishing awareness simulations
* Adversary-in-the-middle research
* Detection engineering
* Blue team training

**Tip:** Always isolate your lab infrastructure to avoid accidental exposure.

---

## 🤝 Contributing

Contributions are welcome.

If you want to submit a phishlet:

1. Ensure it is tested.
2. Follow the existing YAML style.
3. Add notes if the target service has special behaviors (JS redirects, CAPTCHA, etc.).
4. Open a Pull Request.

---

## 🔐 Legal Notice

The author assumes **no liability** for misuse of this material.
You are responsible for complying with all applicable laws and regulations.

---

## ⭐ Support

If this repository helped you:

* Star the repo
* Share it with fellow security researchers
* Contribute improvements


