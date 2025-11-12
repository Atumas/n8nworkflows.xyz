# n8nworkflows.xyz

Standalone and versionable archive of n8n workflows from the official [n8n.io/workflows](https://n8n.io/workflows) website. This repository allows you to preserve, version, and reuse workflow templates in minimal format, ready to be imported offline.

[n8nworkflows.xyz](https://n8nworkflows.xyz)

---

## 📋 Table of Contents

- [Repository Structure](#-repository-structure)
- [Archived Workflow Format](#-archived-workflow-format)
- [Usage](#-usage)
- [Workflows Summary](#-workflows-summary)
- [License](#-license)

---

## 📁 Repository Structure

```
n8nworkflows.xyz/
├── archive/
│   └── workflows/
│       ├── workflow-name-id-1/
│       │   ├── readme.md
│       │   ├── workflow.json
│       │   ├── metadata.json
│       │   └── workflow-name-id-1.webp
│       ├── workflow-name-id-2/
│       │   └── ...
│       └── ...
└── README.md
```

Each workflow is isolated in its own folder to facilitate navigation, versioning, and individual import.

---

## 📄 Archived Workflow Format

Each workflow folder contains **exactly 4 files**:

| File | Description |
|:---|:---|
| **`readme.md`** | Complete workflow description in Markdown (original template's `readme` field) |
| **`workflow.json`** | Raw workflow export in JSON format, ready to be imported into n8n |
| **`metadata.json`** | Metadata: author (`user_*`), tags, creation date, public link to `https://n8n.io/workflows/<workflowId>` |
| **`<slug-and-id>.webp`** | Workflow screenshot (hero image from Supabase `worklowscreenshot` bucket) |

---



## 📚 Workflows Summary (6 workflows)

- [.DS_Store](https://github.com/nusquama/n8nworkflows.xyz/blob/main/workflows/.DS_Store)
- [AI-Powered n8n Release Notes Summary Notifications via Gmail with GPT-5-Mini-10236](https://github.com/nusquama/n8nworkflows.xyz/tree/main/workflows/AI-Powered%20n8n%20Release%20Notes%20Summary%20Notifications%20via%20Gmail%20with%20GPT-5-Mini-10236)
- [Extract Information from a Logo Sheet using forms, AI, Google Sheet and Airtable-2650](https://github.com/nusquama/n8nworkflows.xyz/tree/main/workflows/Extract%20Information%20from%20a%20Logo%20Sheet%20using%20forms,%20AI,%20Google%20Sheet%20and%20Airtable-2650)
- [Learn Workflow Logic with Merge, IF & Switch Operations-5996](https://github.com/nusquama/n8nworkflows.xyz/tree/main/workflows/Learn%20Workflow%20Logic%20with%20Merge,%20IF%20&%20Switch%20Operations-5996)
- [readme.md](https://github.com/nusquama/n8nworkflows.xyz/blob/main/workflows/readme.md)
- [Simple Eval for Legal Benchmarking-4712](https://github.com/nusquama/n8nworkflows.xyz/tree/main/workflows/Simple%20Eval%20for%20Legal%20Benchmarking-4712)

---

## 🔗 Useful Links

- 🌐 [n8nworkflows.xyz website](https://n8nworkflows.xyz)
- 📖 [Official n8n Documentation](https://docs.n8n.io)
- 💬 [n8n Community](https://community.n8n.io)
- 🐙 [n8n on GitHub](https://github.com/n8n-io/n8n)

---

## 📝 License

This repository archives public workflows from [n8n.io/workflows](https://n8n.io/workflows). Each workflow retains its original license. Refer to individual metadata for more information.

The archiving code and repository structure are licensed under [MIT](LICENSE).

---

## ⚠️ Disclaimer

This project is **independent** and not officially affiliated with n8n. It is a personal initiative aimed at facilitating access to and preservation of public n8n workflows.

---

**Made with ❤️ for the n8n community**

