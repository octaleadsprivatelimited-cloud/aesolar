# AE Solar - Solar Panel Installation Website

A professional, responsive website for a solar panel installation company operating in East Godavari, Andhra Pradesh, India.

## 🌟 Features

- **Multi-page Website**: Home, Services, About, Calculator, Contact
- **Responsive Design**: Mobile-first approach, works on all devices
- **SEO Optimized**: Meta tags, structured data, and semantic HTML
- **Cost Calculator**: Solar installation cost calculator with PM Solar Scheme subsidies
- **Modern UI/UX**: Professional design with smooth animations
- **Contact Forms**: Lead generation forms with validation
- **Service Areas**: Coverage across East Godavari district - cities, towns, and villages

## 🚀 Tech Stack

- **Frontend**: React.js with TypeScript
- **Styling**: Tailwind CSS
- **Routing**: React Router DOM
- **Animations**: Framer Motion
- **Icons**: Lucide React
- **Build Tool**: Create React App

## 📱 Service Areas

**Major Cities:**
- Rajahmundry (Rajamahendravaram)
- Kakinada
- Amalapuram

**Towns:**
- Tuni, Peddapuram, Pithapuram, Mandapeta, Razole, Ramachandrapuram, Mummidivaram, Kothapeta, Samalkot, Yeleswaram, Gollaprolu, Tallarevu, Uppalaguptam, Malikipuram, Allavaram, Katrenikona, I. Polavaram, Devipatnam, Maredumilli, Y. Ramavaram, Addateegala, Rajanagaram, Anaparthy, Kadiam, Sankhavaram, Kotananduru, Alamuru, Atreyapuram, Ravulapalem, Kapileswarapuram, Karapa, Thondangi, Sakhinetipalli, Ainavilli, Ambajipeta

**Villages:**
- We serve all villages across East Godavari district

## 🏗️ Installation & Setup

### Prerequisites
- Node.js (v14 or higher)
- npm or yarn

### Setup Steps

1. **Install dependencies**
   ```bash
   npm install
   ```

3. **Start development server**
   ```bash
   npm start
   ```

4. **Build for production**
   ```bash
   npm run build
   ```

## 📁 Project Structure

```
src/
├── components/          # Reusable UI components
│   ├── Navbar.tsx      # Navigation bar
│   ├── Footer.tsx      # Footer component
├── pages/              # Page components
│   ├── Home.tsx        # Homepage
│   ├── Services.tsx    # Services page
│   ├── About.tsx       # About company
│   ├── Calculator.tsx  # Cost calculator
│   └── Contact.tsx     # Contact page
├── types/              # TypeScript type definitions
├── utils/              # Utility functions
├── App.tsx             # Main app component
└── index.tsx           # Entry point
```

## 🎨 Customization

### Colors
The website uses a custom color palette defined in `tailwind.config.js`:
- Primary: Solar yellow (#eab308)
- Secondary: Blue (#1e40af)
- Accent: Green (#059669)

### Content
Update the following files to customize content:
- Company information: `src/components/Footer.tsx`
- Contact details: `src/pages/Contact.tsx`
- Service areas: Update city arrays in multiple components

## 📊 SEO Features

- Meta tags for all pages
- Open Graph tags for social media
- Twitter Card support
- Schema.org structured data
- Location-based meta tags
- Business information markup

## 📱 Responsive Design

- Mobile-first approach
- Breakpoints: sm (640px), md (768px), lg (1024px), xl (1280px)
- Touch-friendly interface
- Optimized for all screen sizes

## 🚀 Deployment

### Build for Production
```bash
npm run build
```
The build folder will contain all production-ready files.

## 📞 Contact Information

- **Service Areas**: Rajahmundry, Kakinada, Amalapuram, Tuni, Peddapuram, and all towns and villages in East Godavari district

## 🔧 Configuration

### Environment Variables
Create a `.env` file for environment-specific configurations:
```env
REACT_APP_COMPANY_NAME=AE Solar
```

### Tailwind Configuration
Customize colors, fonts, and animations in `tailwind.config.js`

## 📈 Performance Optimization

- Lazy loading for images
- Optimized bundle size
- CSS purging with Tailwind
- Responsive images
- Minified production build

## 🔒 Security

- HTTPS enforcement
- XSS protection
- CSRF protection
- Secure form handling
- Input validation

## 📋 Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers

## 🤝 Contributing

For contributions and collaboration, please contact us directly.

## 📄 License

This project is licensed under the MIT License.

## 🆘 Support

For support and questions, please use the contact form on the website.

---

**AE Solar** - Powering the future with solar energy! ☀️
