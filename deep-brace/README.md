# Deep Brace - Crypto Wallet Management Platform

A modern, feature-rich crypto wallet management platform built with Next.js 14, featuring multi-wallet support, enhanced security, and seamless user experience.

## 🚀 Features

### Core Functionality (60% ProjectDapp replication)
- **Hero banner** with animated crypto visuals
- **Featured apps grid** showcasing different crypto applications
- **Wallet connection module** with multi-wallet support
- **Responsive dark-mode layout** with smooth transitions
- **Navigation structure**: Home → Apps → Wallet Demo

### Modern Enhancements (40% upgrades)
- **Tech Modernization**: Next.js 14 with App Router, Vite build tooling
- **UI/UX Improvements**: Framer Motion animations, dark/light mode toggle
- **Multi-wallet Support**: Phantom, MetaMask, WalletConnect integration
- **EmailJS Integration**: Contact forms, wallet reports, newsletter signups
- **Enhanced Features**: Token gallery, recent activity dashboard, PDF reports

## 🛠️ Tech Stack

- **Framework**: Next.js 14 (App Router)
- **Build Tool**: Vite
- **Styling**: Tailwind CSS + CSS Modules
- **State Management**: Zustand
- **Wallet Integration**: @thirdweb-dev/react
- **Email Service**: EmailJS SDK
- **Animations**: Framer Motion
- **Icons**: Lucide React
- **Deployment**: Vercel/GitHub Pages/Cloudflare Pages

## 📦 Installation

1. **Clone the repository**
   ```bash
   git clone <repository-url>
   cd deep-brace
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Set up environment variables**
   Create a `.env.local` file in the root directory:
   ```env
   NEXT_PUBLIC_THIRDWEB_CLIENT_ID=your-thirdweb-client-id
   NEXT_PUBLIC_EMAILJS_SERVICE_ID=your-emailjs-service-id
   NEXT_PUBLIC_EMAILJS_TEMPLATE_ID=your-emailjs-template-id
   NEXT_PUBLIC_EMAILJS_PUBLIC_KEY=your-emailjs-public-key
   ```

4. **Run the development server**
   ```bash
   npm run dev
   ```

5. **Open your browser**
   Navigate to [http://localhost:3000](http://localhost:3000)

## 🔧 Configuration

### ThirdWeb Setup
1. Visit [thirdweb.com](https://thirdweb.com)
2. Create a new project
3. Get your client ID
4. Add it to your environment variables

### EmailJS Setup
1. Visit [emailjs.com](https://emailjs.com)
2. Create an account and verify your email
3. Create a new email service (Gmail, Outlook, etc.)
4. Create email templates for:
   - Contact form submissions
   - Wallet connection reports
   - Newsletter signups
5. Get your service ID, template ID, and public key
6. Add them to your environment variables

## 📁 Project Structure

```
deep-brace/
├── src/
│   ├── app/
│   │   ├── (home)/page.tsx          # Homepage
│   │   ├── apps/
│   │   │   ├── page.tsx             # Apps directory
│   │   │   └── brace/
│   │   │       └── page.tsx         # Wallet demo
│   │   ├── layout.tsx               # Root layout
│   │   └── globals.css              # Global styles
│   ├── components/
│   │   ├── Navigation.tsx           # Navigation component
│   │   ├── WalletConnector.tsx      # Multi-wallet support
│   │   └── ContactForm.tsx          # EmailJS integration
│   └── lib/
│       └── emailService.ts          # EmailJS configuration
├── public/
│   └── crypto-icons/                # Optimized assets
└── package.json
```

## 🎨 Customization

### Styling
- Modify `src/app/globals.css` for global styles
- Update Tailwind configuration in `tailwind.config.ts`
- Customize component styles in individual component files

### Components
- Add new components in `src/components/`
- Update navigation in `src/components/Navigation.tsx`
- Modify wallet functionality in `src/components/WalletConnector.tsx`

### Pages
- Create new pages in `src/app/`
- Follow the existing routing structure
- Use the Navigation component for consistency

## 🚀 Deployment

### Vercel (Recommended)
1. Connect your GitHub repository to Vercel
2. Add environment variables in Vercel dashboard
3. Deploy automatically on push to main branch

### Other Platforms
- **GitHub Pages**: Use `npm run build && npm run export`
- **Cloudflare Pages**: Similar to Vercel deployment
- **Netlify**: Connect repository and configure build settings

## 🔒 Security Features

- **Wallet Connection Safeguards**: Secure wallet connection flow
- **EmailJS Environment Variables**: Secure API key management
- **Content Security Policy**: XSS protection
- **Rate Limiting**: Prevent spam and abuse
- **Input Validation**: Form validation and sanitization

## 📱 Responsive Design

The application is fully responsive and optimized for:
- **Desktop**: Full-featured experience
- **Tablet**: Optimized layouts
- **Mobile**: Touch-friendly interface

## 🎯 Performance Optimizations

- **Image Optimization**: WebP format with lazy loading
- **Code Splitting**: Automatic route-based splitting
- **Bundle Optimization**: Tree shaking and minification
- **Caching**: Static generation and ISR
- **CDN**: Global content delivery

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🆘 Support

For support and questions:
- Create an issue in the GitHub repository
- Contact through the contact form on the website
- Email: support@deepbrace.com

## 🙏 Acknowledgments

- **ProjectDapp**: Original inspiration and reference
- **ThirdWeb**: Wallet integration and blockchain tools
- **EmailJS**: Email service integration
- **Framer Motion**: Animation library
- **Tailwind CSS**: Utility-first CSS framework

---

**Deep Brace** - The future of crypto wallet management 🚀
