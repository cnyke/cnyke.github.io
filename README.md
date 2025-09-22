# Resilience Continuum Website

A mobile-responsive website built with Astro.build and Tailwind CSS, featuring data visualizations and creative content exploring themes of resilience and adaptation.

## Features

- **Mobile-first responsive design** using Tailwind CSS
- **Octopuses page** with interactive Leaflet map for data visualization
- **Mosquitoes page** with data visualization placeholders
- **Graphic Design gallery** with three-column responsive layout
- **Fiction writing** showcase
- **Professional resumé** page
- **About & Contact** page with contact form
- **Lexend font** from Google Fonts throughout
- **Clean navigation** with mobile hamburger menu

## Pages

1. **Index (Octopuses)** - `/` - Features an interactive Leaflet map ready for data connection
2. **Mosquitoes** - `/data-viz-2` - Data visualization page with placeholders for charts
3. **Graphic Design** - `/graphic-design` - Three-column gallery showcase
4. **Fiction** - `/fiction` - Creative writing portfolio
5. **Resumé** - `/resume` - Professional experience and skills
6. **About & Contact** - `/about-contact` - Information and contact form

## Getting Started

### Prerequisites

- Node.js 18+ 
- npm or yarn

### Installation

1. Install dependencies:
```bash
npm install
```

2. Start the development server:
```bash
npm run dev
```

3. Open your browser to `http://localhost:4321`

### Building for Production

```bash
npm run build
```

### Preview Production Build

```bash
npm run preview
```

## Technology Stack

- **Astro.build** - Static site generator
- **Tailwind CSS** - Utility-first CSS framework
- **Leaflet** - Interactive maps library
- **TypeScript** - Type safety
- **Lexend** - Google Fonts typography

## Customization

### Adding Data to Visualizations

1. **Octopus Map**: Edit `src/pages/index.astro` and replace the sample markers with your actual data
2. **Mosquito Charts**: Edit `src/pages/data-viz-2.astro` and replace placeholders with actual chart components
3. **Gallery Images**: Replace placeholder content in `src/pages/graphic-design.astro` with actual images

### Styling

- All styles use Tailwind CSS classes
- Custom color scheme can be modified in `tailwind.config.mjs`
- Font settings are configured in the base layout

### Content

- Update contact information in `src/layouts/BaseLayout.astro` (footer)
- Modify personal information in `src/pages/about-contact.astro`
- Replace placeholder content throughout with actual content

## Mobile Responsiveness

The site is built mobile-first with responsive breakpoints:
- **sm**: 640px and up
- **md**: 768px and up  
- **lg**: 1024px and up
- **xl**: 1280px and up

All components are tested and optimized for mobile devices.

## License

This project is open source and available under the [MIT License](LICENSE).

