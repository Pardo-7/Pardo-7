<img src="https://github.com/illuminodes/fuente/blob/mera/public/assets/img/logo_full.jpeg?raw=true" alt="Logo" width="300px" style="margin-bottom: 1rem">

Fuente is a modern and open-source e-commerce platform, enabling seamless online shopping with Bitcoin payments. Built with cutting-edge technologies, Fuente provides a smooth and decentralized shopping experience for consumers, businesses, and service providers. 🛒

---

## 🚀 Features

✅ **Multi-App System:** Includes separate apps for admin, businesses, consumers, drivers, and core services.  
✅ **Bitcoin Payments:** Easily transact using Bitcoin for a seamless and borderless payment experience.  
✅ **Decentralized & Secure:** Powered by Rust, Yew, and Nostr for speed, security, and resilience.  
✅ **Interactive UI:** Styled with TailwindCSS for a sleek and modern interface.  
✅ **Geo-Enabled Services:** Integrated with Leaflet for mapping and location-based features.  
✅ **QR Code Payments:** Leverages BitcoinQR for simple cryptocurrency transactions.  
✅ **Notifications:** Uses ToastifyJS for real-time alerts and updates.  
✅ **Efficient Testing:** Ensured reliability with Rust’s built-in testing framework.  

---

## 🛠 Tech Stack

Fuente is built using the latest web technologies to ensure performance and scalability:

- **🦀 Rust** - High-performance, memory-safe programming language [(Download Rust)](https://www.rust-lang.org/learn/get-started)
- **🌿 Yew** - Rust-based framework for building interactive web apps [(Yew Docs)](https://yew.rs/docs/)
- **⚡ Nostr** - Decentralized protocol for secure communication [(Nostr Protocol)](https://nostr.com/)
- **🎨 TailwindCSS** - Utility-first CSS framework for styling [(Tailwind Docs)](https://tailwindcss.com/docs)
- **🗺️ Leaflet** - Interactive maps and location services [(LeafletJS)](https://leafletjs.com/)
- **💰 BitcoinQR** - Simple Bitcoin QR code generator for payments [(BitcoinQR GitHub)](https://github.com/bitcoinerlab/bitcoinqr)
- **🔔 ToastifyJS** - Elegant toast notifications [(ToastifyJS Docs)](https://apvarun.github.io/toastify-js/)
- **👾 Lucide Yew** - Flexible icon family for interfaces [(Lucide Yew Docs)](https://docs.rs/lucide-yew/latest/lucide_yew/)

---

## 🏗 Project Architecture

Fuente is structured as a **Cargo workspace** that manages multiple apps, each with its own dependencies and configurations. The main apps include:

- `admin/` - Dashboard for managing the platform.
- `business/` - Interface for businesses selling products or services.
- `consumer/` - Main shopping application for customers.
- `driver/` - App for delivery drivers.
- `fuente/` - Core shared resources and utilities.

Each app contains:
- `Cargo.toml` - Rust dependencies and settings.
- `manifest.json` - Web app metadata.
- `serviceWorker.js` - PWA functionality for offline capabilities.
- `Trunk.toml` - Configuration for Trunk bundler.
- `build.rs` - Custom build script if needed.
- `src/` - Main application logic.

Fuente does **not** rely on a traditional backend. Instead, it is fully decentralized, using **Nostr** and **IndexedDB** for communication and storage.

---

## 🌐 How Fuente Uses Nostr

Fuente leverages **Nostr** as its primary communication protocol for a trustless and decentralized experience. 

### 🔗 Communication with Relays
- All messages, transactions, and interactions are sent via **Nostr relays**, removing the need for centralized servers.
- Each app (consumer, business, admin, etc.) subscribes to specific events in the network, ensuring seamless interaction.

### 🔑 Authentication
- Users authenticate using **Nostr public/private keys** instead of traditional logins.
- Private keys are securely stored on the client-side, never exposing them to third parties.

### 💰 Payments & Transactions
- Bitcoin payments are processed using **BitcoinQR** and are confirmed via **Nostr events**.
- Transactions are immutable and verifiable, enhancing security and transparency.

### 📦 Data Storage
- No centralized database is used. Instead, **IndexedDB** is leveraged for local storage.
- Users retain control over their data, which can be synchronized across devices via Nostr relays.

Using **Nostr** ensures Fuente remains **censorship-resistant**, **fault-tolerant**, and **decentralized**, making it an ideal solution for borderless commerce.

---

## 📦 Installation & Setup

To run Fuente locally, ensure you have the necessary dependencies installed.

### ✅ Prerequisites

Before starting, install the following:
- [Rust & Cargo](https://www.rust-lang.org/tools/install) 🦀
- [Trunk](https://trunkrs.dev/#install) 🚀
- [WebAssembly Target](https://rustwasm.github.io/wasm-pack/installer/) 🕸️

### 📥 Clone the Repository

```sh
 git clone https://github.com/illuminodes/fuente.git
 cd fuente
```

### 🔥 Run the Application

To start the **Consumer App**, execute:

```sh
trunk serve --config consumer/Trunk.toml
```

For other apps, replace `consumer` with the desired app folder (e.g., `admin`, `business`).

---

## 🧪 Running Tests

Fuente uses Rust's built-in testing framework. Run tests with:

```sh
cargo test
```

This ensures the application is stable and reliable. ✅

---

## 🔗 Useful Links

- 📜 Official Rust Docs: [Rust Documentation](https://doc.rust-lang.org/)
- 🔧 Trunk Guide: [Trunk Docs](https://trunkrs.dev/)
- 🖥️ Yew Framework: [Yew Documentation](https://yew.rs/docs/)
- 🔑 Nostr Protocol: [Nostr](https://nostr.com/)
- 🎨 TailwindCSS: [Tailwind Docs](https://tailwindcss.com/docs)
- 🗺️ Leaflet Maps: [LeafletJS](https://leafletjs.com/)
- ⚡ BitcoinQR: [BitcoinQR GitHub](https://github.com/bitcoinerlab/bitcoinqr)

---

## 📄 License

Fuente is open-source and available under the **MIT License**. See [`LICENSE`](LICENSE) for details.
