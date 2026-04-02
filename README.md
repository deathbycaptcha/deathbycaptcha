<div align="center">

<img src="https://static.deathbycaptcha.com/img/user/dbc-logo.png" alt="DeathByCaptcha" width="220" />

# DeathByCaptcha

### The Professional Bypass Captcha Service & Captcha Solver for Bots

[![Website](https://img.shields.io/badge/Website-deathbycaptcha.com-blue?style=for-the-badge&logo=googlechrome&logoColor=white)](https://deathbycaptcha.com)
[![API Docs](https://img.shields.io/badge/API-Documentation-orange?style=for-the-badge&logo=readthedocs&logoColor=white)](https://deathbycaptcha.com/api)
[![Support](https://img.shields.io/badge/Support-Contact%20Us-green?style=for-the-badge&logo=headset&logoColor=white)](https://deathbycaptcha.com/contact)
[![Pricing](https://img.shields.io/badge/Pricing-See%20Plans-red?style=for-the-badge&logo=creditcard&logoColor=white)](https://deathbycaptcha.com/)

</div>

---

## What is DeathByCaptcha?

**DeathByCaptcha** is a professional **bypass captcha service** trusted by developers, automation engineers, and researchers worldwide since 2008. Our platform acts as a **captcha solver for bots** and automated workflows, providing a fast, reliable, and accurate CAPTCHA-solving API over both **HTTP REST** and **persistent TCP sockets**.

- ✅ **21+ CAPTCHA types** supported — image, reCAPTCHA v2/v3, Turnstile, Amazon WAF, GeeTest, hCaptcha, and more
- ✅ **HTTP & Socket API** — choose the transport that fits your use case
- ✅ **Official client libraries** in 9+ languages — drop-in, production-ready
- ✅ **24/7 human & automated solving** — sub-15-second average response time
- ✅ **Token-based auth** for CI/CD and headless environments
- ✅ **99.9% uptime SLA** and battle-tested in high-volume production workloads

---

## Official API Client Libraries

| Language | Repository | Install | Docs |
|:---:|---|---|---|
| <img src="https://skillicons.dev/icons?i=python" width="22"/> **Python** | [deathbycaptcha-api-client-python](https://github.com/deathbycaptcha/deathbycaptcha-api-client-python) | `pip install deathbycaptcha` | [README](https://github.com/deathbycaptcha/deathbycaptcha-api-client-python#readme) |
| <img src="https://skillicons.dev/icons?i=go" width="22"/> **Go** | [deathbycaptcha-api-client-go](https://github.com/deathbycaptcha/deathbycaptcha-api-client-go) | `go get github.com/deathbycaptcha/deathbycaptcha-api-client-go/v4` | [README](https://github.com/deathbycaptcha/deathbycaptcha-api-client-go#readme) |
| <img src="https://skillicons.dev/icons?i=nodejs" width="22"/> **Node.js** | [deathbycaptcha-api-client-nodejs](https://github.com/deathbycaptcha/deathbycaptcha-api-client-nodejs) | `npm install deathbycaptcha` | [README](https://github.com/deathbycaptcha/deathbycaptcha-api-client-nodejs#readme) |
| <img src="https://skillicons.dev/icons?i=php" width="22"/> **PHP** | [deathbycaptcha-api-client-php](https://github.com/deathbycaptcha/deathbycaptcha-api-client-php) | `composer require deathbycaptcha/deathbycaptcha` | [README](https://github.com/deathbycaptcha/deathbycaptcha-api-client-php#readme) |
| <img src="https://skillicons.dev/icons?i=java" width="22"/> **Java** | [deathbycaptcha-api-client-java](https://github.com/deathbycaptcha/deathbycaptcha-api-client-java) | Maven / Gradle | [README](https://github.com/deathbycaptcha/deathbycaptcha-api-client-java#readme) |
| <img src="https://skillicons.dev/icons?i=dotnet" width="22"/> **.Net (C#, VB)** | [deathbycaptcha-api-client-dotnet](https://github.com/deathbycaptcha/deathbycaptcha-api-client-dotnet) | NuGet package | [README](https://github.com/deathbycaptcha/deathbycaptcha-api-client-dotnet#readme) |
| <img src="https://skillicons.dev/icons?i=cpp" width="22"/> **C++** | [deathbycaptcha-api-client-cpp](https://github.com/deathbycaptcha/deathbycaptcha-api-client-cpp) | CMake / vcpkg | [README](https://github.com/deathbycaptcha/deathbycaptcha-api-client-cpp#readme) |
| <img src="https://skillicons.dev/icons?i=c" width="22"/> **C (C11)** | [deathbycaptcha-api-client-c11](https://github.com/deathbycaptcha/deathbycaptcha-api-client-c11) | CMake | [README](https://github.com/deathbycaptcha/deathbycaptcha-api-client-c11#readme) |
| <img src="https://skillicons.dev/icons?i=perl" width="22"/> **Perl** | [deathbycaptcha-api-client-perl](https://github.com/deathbycaptcha/deathbycaptcha-api-client-perl) | `cpanm DeathByCaptcha` | [README](https://github.com/deathbycaptcha/deathbycaptcha-api-client-perl#readme) |

> All libraries implement the same `Client` interface with `HTTP` and `Socket` transports,
> support authentication via `username`/`password` **or** `authtoken`, and are **thread-safe**.

---

## Supported CAPTCHA Types

| # | Type | Description |
|:---:|---|---|
| 0 | 🖼️ **Image CAPTCHA** | Classic text-in-image challenges |
| 1 | 🔁 **reCAPTCHA v2** | Google checkbox & invisible reCAPTCHA |
| 3 | 🎮 **FunCaptcha / Arkose Labs** | Interactive game-based challenges |
| 4 | 📊 **reCAPTCHA v3** | Score-based invisible reCAPTCHA |
| 5 | 🔐 **hCaptcha** | Privacy-focused CAPTCHA |
| 6 | 🔑 **KeyCaptcha** | Puzzle-based CAPTCHA |
| 7 | 🧩 **GeeTest v3** | Slide & behavior-based CAPTCHA |
| 8 | 🧩 **GeeTest v4** | Next-gen GeeTest challenges |
| 9 | 🧸 **Capy Puzzle** | Jigsaw puzzle CAPTCHA |
| 10 | ☁️ **Cloudflare Turnstile** | Cloudflare's privacy-preserving challenge |
| 11 | 🛡️ **Amazon WAF** | AWS bot protection token |
| 12 | 🤖 **Cyber SiARA** | Behavioral CAPTCHA |
| 13 | 🔒 **MT Captcha** | MTCaptcha enterprise challenges |
| 14 | 😊 **Friendly Captcha** | Eco-friendly PoW CAPTCHA |
| 15 | ✂️ **Cutcaptcha** | Click-based image CAPTCHA |
| 16 | 🇨🇳 **Tencent CAPTCHA** | Tencent TDC slider |
| 17 | 🚦 **atbCAPTCHA** | AT&T bot challenge |
| 18 | 🍋 **Lemin Cropped CAPTCHA** | Cropped puzzle CAPTCHA |
| 19 | 🚪 **Imperva / Incapsula** | Imperva WAF challenge |
| 20 | 🟣 **DataDome** | DataDome bot protection |
| 21 | 🎵 **Audio CAPTCHA** | Voice/audio challenges |

---

## Quick Start

```python
# Python — solve a reCAPTCHA v2 in 3 lines
import deathbycaptcha
client = deathbycaptcha.HttpClient("your_username", "your_password")
result = client.decode(None, 120, {
    "type": "1",
    "googlekey": "6Le-wvkSAAAAAPBMRTvw0Q4Muexq9bi0DJwx_mJ-",
    "pageurl": "https://example.com"
})
print(result["text"])  # reCAPTCHA token
```

```go
// Go — bypass captcha service with automatic polling
client := deathbycaptcha.NewHttpClient("your_username", "your_password")
result, _ := client.Decode(nil, 120, map[string]string{
    "type":      "1",
    "googlekey": "6Le-wvkSAAAAAPBMRTvw0Q4Muexq9bi0DJwx_mJ-",
    "pageurl":   "https://example.com",
})
fmt.Println(*result.Text) // reCAPTCHA token
```

```js
// Node.js — captcha solver for bots
const dbc = require("deathbycaptcha");
const client = new dbc.HttpClient("your_username", "your_password");
const result = await client.decode(null, 120, {
    type: 1,
    googlekey: "6Le-wvkSAAAAAPBMRTvw0Q4Muexq9bi0DJwx_mJ-",
    pageurl: "https://example.com",
});
console.log(result.text); // reCAPTCHA token
```

---

## How It Works

```
Your App  ──►  DBC API (HTTP or Socket)  ──►  Solving Engine  ──►  Token / Text
                    ▲                                                    │
                    │◄───────────────────────────────────────────────────┘
                                     (< 15 sec avg)
```

1. **Submit** — send the CAPTCHA (image bytes, sitekey + pageurl, or audio)
2. **Poll** — the client automatically polls until the solution is ready
3. **Use** — inject the token or text into your automation

---

## Resources

| Resource | Link |
|---|---|
| 🌐 Website | https://deathbycaptcha.com |
| 📖 API Documentation | https://deathbycaptcha.com/api |
| 💰 Pricing | https://deathbycaptcha.com/ |
| 🔑 Dashboard / Login | https://deathbycaptcha.com/login#login-form |
| 📬 Contact & Support | https://deathbycaptcha.com/contact |
| 🤖 AI Agents API Metadata | [deathbycaptcha-agent-api-metadata](https://github.com/deathbycaptcha/deathbycaptcha-agent-api-metadata) |

---

<div align="center">

**© 2008 – 2026 DeathByCaptcha · Trusted bypass captcha service for developers worldwide**

[![Python](https://img.shields.io/badge/Python-client-3776AB?logo=python&logoColor=white)](https://github.com/deathbycaptcha/deathbycaptcha-api-client-python)
[![Go](https://img.shields.io/badge/Go-client-00ADD8?logo=go&logoColor=white)](https://github.com/deathbycaptcha/deathbycaptcha-api-client-go)
[![Node.js](https://img.shields.io/badge/Node.js-client-339933?logo=nodedotjs&logoColor=white)](https://github.com/deathbycaptcha/deathbycaptcha-api-client-nodejs)
[![PHP](https://img.shields.io/badge/PHP-client-777BB4?logo=php&logoColor=white)](https://github.com/deathbycaptcha/deathbycaptcha-api-client-php)
[![Java](https://img.shields.io/badge/Java-client-ED8B00?logo=openjdk&logoColor=white)](https://github.com/deathbycaptcha/deathbycaptcha-api-client-java)
[![.NET](https://img.shields.io/badge/.NET-client-512BD4?logo=dotnet&logoColor=white)](https://github.com/deathbycaptcha/deathbycaptcha-api-client-dotnet)
[![C++](https://img.shields.io/badge/C++-client-00599C?logo=cplusplus&logoColor=white)](https://github.com/deathbycaptcha/deathbycaptcha-api-client-cpp)
[![C](https://img.shields.io/badge/C11-client-A8B9CC?logo=c&logoColor=black)](https://github.com/deathbycaptcha/deathbycaptcha-api-client-c11)
[![Perl](https://img.shields.io/badge/Perl-client-39457E?logo=perl&logoColor=white)](https://github.com/deathbycaptcha/deathbycaptcha-api-client-perl)

</div>
