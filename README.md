# 🧠 D0mainz – Suspicious Domain Generator

![banner](https://img.shields.io/badge/Made_by-Jull3Hax0r-green?style=flat-square)  
![Whitehat](https://img.shields.io/badge/Use-Whitehat-green.svg)
![Python](https://img.shields.io/badge/Made%20with-Python-FFD43B.svg)
**Only for education/Protection** ⚠️ Use responsibly

---

## 🔍 What is this?

**D0mainz** is a command-line tool that generates realistic phishing-style domain variants from a given base domain and checks if they are available.  
Perfect for **security researchers**, **blue teams**, **bug bounty hunters**, or **brand protection audits**.

> Example: from `facebook`, D0mainz might generate:
> - `login-facebook.com`
> - `facebook-support.net`
> - `secure-facebook.xyz`  
> Then checks if those are available or already registered ✅

---

## 🚀 Features

- ✅ Generate domain variants using phishing-style prefixes
- 🌐 Check real-time DNS availability (no 3rd party APIs)
- 📊 "Fake Score" that estimates how suspicious a domain looks
- 🎨 Terminal UI with colors and ASCII banner via `rich` and `pyfiglet`
- 💾 Export **available** and **taken** domains to separate `.txt` files
- 🧪 Educational, ethical, and safe for research
<table>
<tr>
<td><img src="https://jull3.se/domain.png" width="100%"></td>
<td><img src="https://jull3.se/domain1.png" width="100%"></td>
</tr>
</table>


--

## 💻 Usage

### 1. Clone the repo
```bash
git clone https://github.com/Jull3Hax0r/domainz.git
cd domainz
./domainz



