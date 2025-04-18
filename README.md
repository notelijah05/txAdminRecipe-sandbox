# Mythic Framework - txAdmin Recipe

A fully automated **txAdmin recipe** to install and run [Mythic Framework](https://github.com/Mythic-Framework/mythic-framework) — a modern, full-featured FiveM server framework built to streamline roleplay server development.

---

## 📦 About the Recipe

This txAdmin recipe simplifies the process of deploying a Mythic Framework-based FiveM server by:

- Cloning the latest version of the framework from GitHub.
- Setting up all required folder structures (`resources`, `configs`, etc.).
- Automatically importing the framework’s SQL schema into your database.
- Moving optional files like configuration templates and logos.
- Ensuring compatibility with txAdmin deployment validation.

This recipe is ideal for developers or server owners looking to get started with Mythic Framework quickly, without needing to manually configure or move files.

---

## ⚙️ Features

- ✅ Automatic GitHub download of the latest Mythic Framework
- ✅ Database setup and schema import
- ✅ Optional config templates included
- ✅ Resource folder validation for txAdmin
- ✅ Minimal manual configuration post-deployment

---

## 📚 About Mythic Framework

**Mythic Framework** is a modern FiveM roleplay server framework written in TypeScript, Node.js, and Lua. It is designed to be modular, scalable, and developer-friendly, supporting key features like:

- Full support for TypeScript backends
- Built-in support for MariaDB and MongoDB
- Configuration-driven design for environments and resources
- Hot-reload capable development environment using `pnpm` and `vite`

📘 More info and full documentation:  
➡️ [Mythic Framework GitHub](https://github.com/Mythic-Framework/mythic-framework)

---

## 🚀 How to Use This Recipe in txAdmin

1. Open your **txAdmin panel**.
2. Go to the **Recipe Deployer** tab.
3. Use the following URL to deploy this recipe: https://raw.githubusercontent.com/Rhodiniium/txAdminRecipe/main/mythic-stable.yaml
4. Follow the prompts to configure your database credentials and deployment options.
5. After deployment:
   - Ensure dependencies (MongoDB, MariaDB, Node.js, and pnpm) are installed
   - Update your `server.cfg`

---

## 🛠 Requirements

To run the Mythic Framework successfully after deployment, ensure you have the following installed:

- **Node.js** (latest LTS recommended)
- **pnpm** (`npm install -g pnpm`)
- **MongoDB** (running locally or remotely)
- **MariaDB** (or compatible MySQL DB)

---

## ℹ️ Known Issues / First-Time Launch Tip

> **Heads up!**  
If you encounter errors related to **Fuel** or **Inventory** systems when launching the server for the first time, don’t worry — this is normal.

🛠️ **Solution:**  
Simply **restart the server once**, and the issues should be resolved automatically. These errors typically occur only during the very first launch due to initial resource registration or dependency order.

---

## 🧠 Tips

- You can customize `resources.cfg` to match your server setup.

---

## 📬 Feedback & Support

If you encounter any issues with the recipe or want to contribute improvements, feel free to open an issue or PR on the [Mythic txAdmin Recipe GitHub](https://github.com/Rhodiniium/txAdminRecipe).

For questions specific to the Mythic Framework, check out their [GitHub repo](https://github.com/Mythic-Framework/mythic-framework) or Discord community.

---

Happy deploying! 🚀
