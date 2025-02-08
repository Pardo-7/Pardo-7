# 🌊 Fuente - The Future of E-commerce in Suriname

![Fuente Logo](logo_full.jpeg)

Fuente is a modern e-commerce platform designed specifically for Suriname, enabling seamless online shopping with Bitcoin payments. Built with cutting-edge technologies, Fuente provides a smooth and decentralized shopping experience for consumers, businesses, and service providers. 🛒⚡

---

## 🚀 Features

✅ **Multi-App System:** Includes separate apps for admin, businesses, consumers, drivers, invoicing, and core services.  
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
 git clone https://github.com/yourusername/fuente.git
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
