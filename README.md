# Developer Portfolio Website

A modern, responsive portfolio website built with React, TypeScript, and Tailwind CSS. This portfolio template is designed for junior developers to showcase their projects and skills to potential employers.

![Portfolio Preview](https://images.unsplash.com/photo-1517245386807-bb43f82c33c4?auto=format&fit=crop&q=80&w=2940&ixlib=rb-4.0.3)

## Features

- 🎨 Modern and clean design
- 📱 Fully responsive for all devices
- 🌙 Dark theme with professional color scheme
- ⚡ Built with performance in mind
- 🔧 Easy to customize and maintain
- 📦 Minimal dependencies

## Prerequisites

Before you begin, ensure you have the following installed on your system:
- [Node.js](https://nodejs.org/) (LTS version recommended)
- npm (comes with Node.js)

## Getting Started

1. Clone the repository:
   ```bash
   git clone [your-repository-url]
   cd developer-portfolio-website
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Start the development server:
   ```bash
   npm run dev
   ```

4. Open your browser and visit `http://localhost:5173`

## Customization

### Personal Information
Edit the following in `src/App.tsx`:
- Name and title in the hero section
- About Me section content
- Skills list
- Contact information
- Social media links

### Projects
Update the `projects` array in `src/App.tsx` with your own projects:
```typescript
const projects = [
  {
    title: "Your Project Title",
    description: "Project description...",
    image: "project-image-url",
    github: "github-repo-url",
    live: "live-demo-url"
  },
  // Add more projects...
];
```

### Styling
- The website uses Tailwind CSS for styling
- Modify colors, spacing, and other design elements in the Tailwind classes
- Update the color scheme by modifying the slate color classes

## Building for Production

1. Build the project:
   ```bash
   npm run build
   ```

2. Preview the production build:
   ```bash
   npm run preview
   ```

The built files will be in the `dist` directory, ready for deployment.

## Deployment

The website can be deployed to any static hosting service:
- Netlify
- Vercel
- GitHub Pages
- Firebase Hosting

Most services can deploy directly from your repository, or you can upload the contents of the `dist` directory after building.

## Technologies Used

- React
- TypeScript
- Tailwind CSS
- Vite
- Lucide React (for icons)

## License

This project is open source and available under the [MIT License](LICENSE).

## Support

If you find any issues or have questions, please open an issue in the repository.

---

Remember to update this README with your specific project details, repository URL, and any additional instructions specific to your implementation.
