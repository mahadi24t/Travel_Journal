# Travel Journal 🌍

A beautiful, responsive travel journal built with React and Vite that showcases your travel experiences with stunning visuals and clean design.

## ✨ Features

- **Responsive Design**: Works perfectly on desktop, tablet, and mobile devices
- **Interactive Entries**: Each travel entry includes images, location details, and descriptions
- **Google Maps Integration**: Direct links to view locations on Google Maps
- **Clean UI**: Modern, minimalist design with smooth animations
- **Easy to Customize**: Simple data structure makes adding new entries effortless

## 🚀 Demo

![Travel Journal Preview](https://mahadi24t.github.io/Travel_Journal/)

Check out the live demo: [Travel Journal Demo](https://mahadi24t.github.io/Travel_Journal/) 

## 📸 Screenshots

*Add screenshots of your travel journal here*

## 🛠️ Tech Stack

- **Frontend**: React 18
- **Build Tool**: Vite
- **Styling**: CSS3 with Flexbox/Grid
- **Icons**: Custom icons (GPS, Globe)
- **Deployment**: Vercel/Netlify ready

## 🏃‍♂️ Quick Start

### Prerequisites

- Node.js (v14 or higher)
- npm or yarn

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/travel-journal.git
   cd travel-journal
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Start the development server**
   ```bash
   npm run dev
   ```

4. **Open your browser**
   Navigate to `http://localhost:5173`

## 📝 Adding Your Own Travel Entries

1. **Open the data file**
   ```bash
   src/data.js
   ```

2. **Add a new entry**
   ```javascript
   {
     id: 4, // Increment the ID
     img: {
       src: "your-image-url",
       alt: "Location description"
     },
     title: "Your Location Title",
     country: "Country Name",
     googleMapsLink: "https://maps.app.goo.gl/your-link",
     dates: "Start Date - End Date",
     text: "Your amazing travel experience description..."
   }
   ```

3. **Save the file** - Your new entry will automatically appear!

## 🎨 Customization

### Colors
The color scheme can be customized in `src/index.css`:
```css
:root {
  --primary-color: #2B283A;
  --secondary-color: #918E9B;
  --accent-color: #F55A5A;
  --background-color: #FFFFFF;
}
```

### Fonts
Update the font family in `src/index.css`:
```css
body {
  font-family: 'Your-Font-Name', sans-serif;
}
```

### Layout
The responsive layout uses CSS Grid and Flexbox. Modify breakpoints in `src/index.css`.

## 📁 Project Structure

```
travel-journal/
├── public/
│   └── vite.svg
├── src/
│   ├── assets/
│   │   ├── earth.png
│   │   ├── gps.png
│   │   └── placeholder.png
│   ├── data.js
│   ├── App.jsx
│   ├── App.css
│   ├── index.css
│   └── main.jsx
├── components/
│   ├── Header.jsx
│   └── Entry.jsx
├── index.html
├── package.json
├── vite.config.js
└── README.md
```

## 🚀 Deployment

### Deploy to Vercel

1. **Install Vercel CLI**
   ```bash
   npm i -g vercel
   ```

2. **Deploy**
   ```bash
   vercel --prod
   ```

### Deploy to Netlify

1. **Build the project**
   ```bash
   npm run build
   ```

2. **Deploy the `dist` folder** to Netlify

## 🧪 Available Scripts

- `npm run dev` - Start development server
- `npm run build` - Build for production
- `npm run preview` - Preview production build
- `npm run lint` - Run ESLint

## 🤝 Contributing

Contributions are welcome! Here's how you can help:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 🐛 Issues

Found a bug or have a suggestion? Please open an issue on GitHub.

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 🙏 Acknowledgments

- Built with [React](https://reactjs.org/)
- Powered by [Vite](https://vitejs.dev/)
- Icons from various sources
- Inspired by Scrimba's React course

## 📞 Contact

- GitHub: [mahadi24t](https://github.com/mahadi24t)
- Email: mahaditm249@gmail.com
- LinkedIn: [Md. Mahadi Hasan
](https://www.linkedin.com/in/mahadi24/)

---

Made with ❤️ by [Md. Mahadi Hasan]
