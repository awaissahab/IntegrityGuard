# IntegrityGuard - Client-Side File Integrity & Hash Verification Tool

Try now :  https://awaissahab.github.io/IntegrityGuard/
An all-in-one, browser-based file integrity verification platform that computes, compares, and cross-references file hashes against a trusted software database without uploading data to external servers.

---

## 📋 Features

### 🔍 Multi-Algorithm File Hashing

* **Simultaneous Hash Calculation**: Computes SHA-256, SHA-512, SHA-1, and MD5 simultaneously.
* **Large File Support**: Uses chunked client-side streaming (`FileReader.slice()`) to hash multi-gigabyte files (OS ISOs, archives, installers) smoothly without browser freezes.
* **Drag-and-Drop Interface**: Instant file loading with clear visual drop targets.

### 🛡️ Trusted Signature Database

* **Pre-loaded Repository**: Includes pre-configured hashes for official releases (Ubuntu, Python, Node.js, Git, 7-Zip).
* **Automated Match Detection**: Displays instant verification badges (Valid / Mismatch / Unverified) upon calculation.
* **Custom Signature Management**: Add, search, filter, import, and export custom trusted software signatures via JSON.

### ⚖️ Dual File & Text Comparator

* **File vs. File Comparison**: Compare two local files directly to check identity.
* **File vs. Checksum Hash**: Cross-reference calculated hashes against official vendor checksum strings.
* **Difference Highlighting**: Visual indicators for matching and non-matching signatures.

### ✍️ Raw Text & HMAC Hasher

* **Real-time Input Hashing**: Instant calculations for text inputs.
* **HMAC Support**: Keyed-hash message authentication code generation using SHA-256, SHA-512, MD5, and SHA-1.
* **Flexible Encoding**: Toggle between Hexadecimal and Base64 output formats.

### 📊 Audit Logging & Exporting

* **Scan History Tracking**: Automatically records verified files, match statuses, and timestamps.
* **Report Generation**: Export complete audit logs to JSON, CSV, or TXT formats.

---

## 🎨 Design & Accessibility

* **Adaptive Light & Dark Themes**: Fully styled dynamic UI with persistent theme state (`localStorage`).
* **Responsive Layout**: Designed for desktops, laptops, and tablet displays.
* **Status Badging**: Visual badge indicators for cryptographic verification states.

---

## 🚀 How to Use

1. **Open the App**: Launch `index.html` in any modern web browser or visit the live page.
2. **Select a File**: Drag and drop your file into the main drop area or click to select.
3. **View Calculated Hashes**: SHA-256, SHA-512, SHA-1, and MD5 hashes generate automatically.
4. **Check Verification Status**:
* **Database Match**: The tool alerts you if the hash matches a known trusted release.
* **Direct Comparison**: Paste a vendor checksum into the comparison panel to verify match status.


5. **Manage Hashes & Export**: Add custom entries to the database or export your verification history from the Audit Log.

---

## 💻 Technical Details

* **Processing**: 100% Client-Side (Web Crypto API & CryptoJS streaming)
* **Storage**: LocalStorage for database persistence and theme settings
* **Deployment**: Zero build dependencies — single or multi-file static deployment ready for GitHub Pages

---

## 🔒 Privacy & Security

All hash computations run locally in your browser. Files are processed using local memory streams and are **never uploaded to any server or remote endpoint**.

---

Created with ❤️ by **Awais Khalid**

*Student of Emerson University Multan*
