CryptoViz - Interactive Cryptography Visualizer
Try: https://awaissahab.github.io/cryptoviz/ An educational web application that visualizes cryptographic algorithms step-by-step, making complex encryption concepts accessible to beginners.

Features
🎯 7 Cryptographic Algorithms
Caesar Cipher - Classical substitution cipher with shift values 1-25
Vigenère Cipher - Polyalphabetic cipher using a keyword
XOR Cipher - Bitwise encryption using XOR operation
AES-256-GCM - Modern symmetric encryption (educational simulation)
Base64 Encoding - Binary-to-text encoding scheme
ROT13 - Self-inverse substitution cipher
Binary Encoding - Text to binary conversion
📚 Detailed Step-by-Step Visualization
Each algorithm shows 4-6 detailed steps including:

Original Input - Display of plaintext/ciphertext
Key Processing - How the key is prepared and used
Transformation Details - Character-by-character or byte-by-byte breakdown
Visual Mappings - Alphabet substitution tables, binary conversions, etc.
Final Result - The encrypted/decrypted output
🎨 Rich Visual Components
Alphabet Mapping Tables - Visual substitution maps showing letter transformations
Character-by-Character Breakdown - See exactly how each letter changes
Binary Visualizations - Byte values and binary representations
Data Tables - Detailed operation tables for complex algorithms
Progress Indicators - Step-by-step progress tracking
💡 Educational Tips
Each step includes contextual tips explaining:

Historical context (e.g., Caesar cipher used by Julius Caesar)
Mathematical concepts (e.g., why XOR is self-inverse)
Real-world applications (e.g., where Base64 is used)
Security implications (e.g., why AES-256 is unbreakable)
🔒 Security Features
Input Validation - Caesar cipher validates shift values (1-25)
Error Handling - Clear error messages for invalid inputs
Local Processing - All operations run in browser, no data sent to servers
Robust Copy - Multiple fallback methods for copying results
🎨 Design
Clean Dark Theme - Easy on the eyes with zinc color palette
Responsive Layout - Works on desktop, tablet, and mobile
Smooth Animations - Steps animate in with fade and slide effects
Color-Coded Categories - Classical (amber), Modern (blue), Encoding (purple)
How to Use
Select an Algorithm - Click on any algorithm card
Choose Mode - Toggle between Encrypt and Decrypt
Enter Input - Type your plaintext or ciphertext
Enter Key (if required) - Provide the encryption key
Click Process - Watch the step-by-step transformation
Copy Result - Click the copy button to copy the output
Technical Details
Framework: React 18 with TypeScript
Styling: Tailwind CSS
Build Tool: Vite
All Processing: Client-side only (no server required)
Educational Value
This tool helps beginners understand:

How encryption transforms data
The difference between classical and modern cryptography
Why certain algorithms are secure
How keys work in encryption
The mathematics behind cryptographic operations
Browser Compatibility
Works in all modern browsers with:

Clipboard API support (with fallbacks)
ES6+ JavaScript
CSS Grid and Flexbox
Privacy
All cryptographic operations are performed locally in your browser. No data is ever sent to any server.

+++ README.md (修改后)

CryptoViz - Complete Cryptography Learning Platform
🎉 What's New!
I've successfully integrated the Academy section into the main CryptoViz application. Now you have a complete cryptography learning platform in a single HTML file!

📋 Features
🔐 Crypto Tool (Interactive)
Caesar Cipher encryption/decryption
Step-by-step visualization with animations
Alphabet mapping tables
Character-by-character breakdown
Educational tips and explanations
Input validation (shift 1-25)
Copy to clipboard functionality
Dark/Light mode toggle
📚 Academy (Learning Section)
Complete cryptography course with 6 chapters:

Introduction to Cryptography (Beginner)

What is cryptography
Why we need it (Confidentiality, Integrity, Authentication, Non-repudiation)
Basic terminology (plaintext, ciphertext, encryption, decryption)
Visual flow diagrams
History of Cryptography (Beginner)

Timeline from 1900 BC to present
Caesar Cipher, Vigenère, Enigma Machine
Modern era (DES, RSA, AES, Bitcoin)
Interactive timeline visualization
Symmetric Encryption (Intermediate)

How symmetric encryption works
DES, 3DES, AES, ChaCha20 comparison
Detailed AES-256 encryption process
Visual diagrams
Asymmetric Encryption (Advanced)

Public-key cryptography concept
RSA, ECC, Diffie-Hellman explained
Complete RSA mathematical example
Visual comparison of public vs private keys
Hashing & Digital Signatures (Advanced)

Hash function properties
MD5, SHA-1, SHA-256 comparison
Visual examples of hash changes
Complete digital signature workflow
Real-World Applications (Intermediate)

HTTPS/SSL/TLS explained
Password storage with hashing
Cryptocurrency and blockchain
Email encryption, messaging apps
🎨 Design Features
W3Schools-inspired theme with green accents (#04AA6D)
Dark/Light mode with localStorage persistence
Navigation tabs to switch between Tool and Academy
Sidebar navigation in Academy for easy chapter switching
Visual diagrams for every concept
Step-by-step breakdowns with numbered indicators
Concept cards highlighting key ideas
Fully responsive (mobile, tablet, desktop)
Previous/Next buttons for sequential learning
🚀 How to Use
Open the file: Simply open cryptoviz-single.html in any modern web browser
Navigate: Use the tabs at the top to switch between:
🔐 Crypto Tool - Interactive encryption/decryption
📚 Academy - Learn cryptography theory
In Academy:
Click chapters in the sidebar to navigate
Use Previous/Next buttons for sequential learning
Read through visual diagrams and explanations
In Crypto Tool:
Select algorithm (currently Caesar Cipher)
Choose Encrypt or Decrypt mode
Enter your text and key
Click "Encrypt Now" or "Decrypt Now"
Watch the step-by-step visualization
Copy the result
📱 Responsive Design
The application is fully responsive:

Mobile: Stacked layout, full-width buttons, touch-friendly (44px+ targets)
Tablet: Optimized spacing and typography
Desktop: Side-by-side layouts, sidebar navigation
💾 Data Privacy
All operations run locally in your browser
No data is sent to any server
Theme preference saved in localStorage
Completely offline-capable
🎓 Educational Value
Perfect for:

Students learning cryptography
Developers understanding encryption
Security professionals refreshing concepts
Anyone curious about how cryptography works
📝 Technical Details
React 18 via CDN
Babel Standalone for JSX
Tailwind CSS via CDN
Single HTML file - no build process needed
No dependencies to install
Works offline after initial load
🎯 What You Can Learn
After completing the Academy, you'll understand:

✅ What cryptography is and why it matters
✅ The history and evolution of encryption
✅ How symmetric encryption works (AES, DES)
✅ How asymmetric encryption works (RSA, ECC)
✅ What hashing is and how it's used
✅ How digital signatures work
✅ Real-world applications (HTTPS, passwords, blockchain)
✅ The mathematics behind RSA (simplified)
✅ Why certain algorithms are secure
🌟 Key Highlights
Visual Learning: Every concept has visual diagrams
Step-by-Step: Complex processes broken down into simple steps
Interactive: Try the Caesar cipher yourself
Comprehensive: From basics to advanced topics
Beautiful: Clean, professional design
Accessible: Works on any device
Free: No cost, no sign-up, no ads
📖 Navigation Guide
Crypto Tool Tab
Header with logo and theme toggle
Introduction section
Mode selector (Encrypt/Decrypt)
Input fields for text and key
Process button
Step-by-step visualization
Result display with copy button
Academy Tab
Header with logo and theme toggle
Sidebar with chapter list
Main content area with:
Chapter title
Visual diagrams
Concept cards
Step indicators
Information boxes
Previous/Next navigation buttons
🔧 Customization
You can easily customize:

Colors: Change CSS variables in the <style> section
Content: Edit chapter content in the chapters array
Algorithms: Add more to the algorithms array
Styling: Modify Tailwind classes
📊 File Structure
cryptoviz-single.html (1332 lines)
├── HTML structure
├── CSS styles (inline)
│   ├── Theme variables
│   ├── Component styles
│   └── Academy-specific styles
├── React application
│   ├── Theme hook
│   ├── Crypto utilities
│   ├── Step components
│   ├── Academy content (6 chapters)
│   └── Main App component
└── ReactDOM render
🎉 Ready to Use!
The file is complete and ready to use. Just open it in your browser and start learning cryptography!

Student of Emerson University Multan

Built with ❤️ for education
