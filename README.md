# Cotion: Real-Time Document Collaboration Platform

## Introduction
Cotion is a modern workspace solution offering real-time collaboration with rich document management features. Designed for teams and individuals, it simplifies content creation through an intuitive interface, secure authentication, and seamless file handling while maintaining full mobile responsiveness.

### Key Features
- **Real-Time Database** 🔗  
- **Rich Text Editor** 📝 (block-based formatting, nested documents)  
- **Light/Dark Mode** 🌓  
- **Infinite Nested Documents** 🌲  
- **Soft Delete & Recovery** 🗑️ 🔄📄  
- **Authentication** 🔐 (Clerk integration)  
- **File Management** (upload/delete/replace)  
- **Dynamic Icons** 🌠 (real-time updates)  
- **Collapsible Sidebar** ↕ ➡🔀⬅  
- **Web Publishing** 🌐  
- **Mobile Optimization** 📱  
- **Landing Page** 🛬  
- **Custom Document Covers** 🖼️  

## Installation
### Prerequisites
- Node.js v18+
- npm v9+
- [Convex](https://convex.dev) account
- [Clerk](https://clerk.dev) account

### Setup
1. Clone the repository:
```
git clone https://github.com/Chamod07/Cotion.git
cd Cotion
```

2. Install dependencies:
```
npm install
```
3. Configure environment variables (create `.env.local`):
```
NEXT_PUBLIC_CONVEX_URL="your_convex_deployment_url"
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY="your_clerk_pub_key"
CLERK_SECRET_KEY="your_clerk_secret"
NEXT_PUBLIC_CLERK_SIGN_IN_URL=/sign-in
NEXT_PUBLIC_CLERK_AFTER_SIGN_IN_URL=/
```
4. Start the development server:

```
npm run dev
```


## Usage
### Getting Started
1. Sign up/in via Clerk authentication
2. Create documents with `+ New` button
3. Use slash (`/`) commands in the editor to:
- Insert headers, lists, code blocks
- Upload images/files
- Toggle live-publish mode
4. Right-click documents for:
- Nested child creation
- Cover image customization
- Soft deletion/recovery

### Key Commands
| Action                | Command          |
|-----------------------|------------------|
| Start dev server      | `npm run dev`    |
| Build for production  | `npm run build`  |
| Deploy to Convex      | `npx convex dev` |

## Contributing
We welcome contributions! Please follow these steps:
1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit changes with descriptive messages
4. Push to branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

**Issue Tracking**:  
- Report bugs via [GitHub Issues](https://github.com/yourusername/docucollab/issues)
- Use labels for `bug`, `enhancement`, or `documentation`

## License
Distributed under MIT License. See `LICENSE` for details.  
Permissions include commercial use, modification, and distribution.  
**Limitations**: License must be included in all copies/modifications.  
**No Liability**: Software provided "as is" without warranty.

---

**[⬆ Back to Top](#cotion-real-time-document-collaboration-platform)**

