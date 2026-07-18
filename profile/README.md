# Quartz Systems
 
We're Quartz Systems, a small software and hardware development company focusing on Information Technology infrastructure. We build the tools we wish existed — network operating systems, management consoles, and the cloud plumbing that ties them together.
 
🌐 [quartz.systems](https://quartz.systems)
 
## 🚧 Projects We're Currently Working On
 
### 🔥 [QuartzFire](https://github.com/quartzsystems/quartz-fire)
A VyOS-based next-generation firewall OS. QuartzFire extends the VyOS platform with a full NGFW component stack — application identification (`qfappd`), SSL inspection, geolocation-based filtering, and a modern web management interface — built into a reproducible ISO pipeline.
 
**Tech:** VyOS/Debian · Rust · TypeScript · Python
 
### ☁️ [Quartz Command](https://github.com/quartzsystems/quartz-command)
The cloud console for Quartz Systems products. A TypeScript/Next.js frontend on a Rust + PostgreSQL backend, with fully separated user and admin auth realms, Argon2id password hashing, and hardened session handling shared with the QuartzFire security model.
 
**Tech:** Rust (axum, sqlx) · Next.js · Tailwind CSS · PostgreSQL
 
### 📡 [Quartz CloudSDK WebUI](https://github.com/quartzsystems/quartz-systems-cloudsdk)
A web management interface for [Telecom Infra Project](https://telecominfraproject.com/) CloudSDK (OpenWiFi) deployments. Installs alongside the CloudSDK on the same Linux host, terminates TLS itself, and proxies the CloudSDK API server-side so privileged tokens never reach the browser. Ships as both `.deb` and `.rpm`.
 
**Tech:** Rust (axum, rustls) · Next.js · Debian/RPM packaging
 
---
 
<sub>All projects share the Quartz Systems design system and a common security model. Feedback and issues welcome.</sub>
