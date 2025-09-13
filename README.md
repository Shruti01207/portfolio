# Sunil Kumar - Professional Portfolio

A modern, responsive portfolio website built with React, TypeScript, and Tailwind CSS.

## Features

- **Professional Design**: Clean, modern layout with excellent typography and visual hierarchy
- **Responsive Layout**: Optimized for all devices from mobile to desktop
- **Interactive Elements**: Smooth animations and hover effects
- **Professional Image Upload**: Easy-to-use image upload feature with URL support
- **Comprehensive Sections**: 
  - Professional summary
  - Work experience with detailed descriptions
  - Education background
  - Technical skills organized by category
  - Personal information
  - Contact details with direct links

## Professional Image Feature

The portfolio includes a professional image upload feature that allows:

1. **File Upload**: Upload images directly from your device
2. **URL Input**: Add images via URL (supports any web-accessible image)
3. **Automatic Fallback**: Shows a professional icon if image fails to load
4. **Responsive Design**: Image scales appropriately on all screen sizes

### How to Update the Professional Image

1. Click the camera icon on the profile photo
2. Choose either:
   - **Upload from Device**: Select an image file from your computer
   - **Enter Image URL**: Paste a link to an online image

### Recommended Image Specifications

- **Format**: JPG, PNG, or WebP
- **Size**: 400x400 pixels minimum
- **Aspect Ratio**: Square (1:1) for best results
- **File Size**: Under 2MB for optimal loading speed

## Getting Started

1. Install dependencies:
   ```bash
   npm install
   ```

2. Start the development server:
   ```bash
   npm run dev
   ```

3. Build for production:
   ```bash
   npm run build
   ```

## Customization

### Updating Personal Information

Edit the data in `src/App.tsx`:
- Experience details in the `experiences` array
- Education information in the `education` array
- Contact information in the `Header` component

### Changing Colors and Styling

The portfolio uses Tailwind CSS. Key color classes used:
- Primary: `blue-600`, `blue-700`, `blue-800`, `blue-900`
- Secondary: `teal-600`, `teal-700`
- Accent colors for different skill categories

### Adding New Sections

Create new components in the `src/components/` directory and import them into `App.tsx`.

## Technologies Used

- **React 18** - Modern React with hooks
- **TypeScript** - Type safety and better development experience
- **Tailwind CSS** - Utility-first CSS framework
- **Vite** - Fast build tool and development server
- **Lucide React** - Beautiful, customizable icons

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## Performance

- Optimized images with proper loading
- Minimal JavaScript bundle size
- CSS-in-JS avoided for better performance
- Responsive images with proper sizing

## Deployment

The portfolio is ready for deployment to any static hosting service:
- Netlify
- Vercel
- GitHub Pages
- AWS S3 + CloudFront

Simply run `npm run build` and deploy the `dist` folder.