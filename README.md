# Med Spa Landing Page - Static Variants

This folder contains static HTML variants of the med spa landing page for A/B testing purposes.

## Overview

These static variants were created as standalone HTML files that don't require the Vite/React build process. Each variant maintains the same core content but presents it with different layouts, typography, spacing, and messaging to test which resonates best with your target audience.

## Variants

### Variant A: Standard Layout
- **File**: `variant-a.html`
- **Container Width**: 1200px
- **Focus**: Classic layout following the original structure
- **Key Features**: Standard text and heading sizes, grid-based layouts

### Variant B: Refined Messaging
- **File**: `variant-b.html`
- **Container Width**: 1100px
- **Focus**: Different headline ("Attract High-Value Clients & Boost Revenue")
- **Key Features**: Two-column service layout, larger padding in service boxes

### Variant C: Premium Luxury Focus
- **File**: `variant-c.html`
- **Container Width**: 1300px
- **Focus**: Upscale positioning with stronger luxury-focused language
- **Key Features**: Added stats highlight section, redesigned case study section, larger fonts

### Variant D: Minimalist Approach
- **File**: `variant-d.html`
- **Container Width**: 1000px
- **Focus**: Cleaner, more minimal aesthetic with sharper corners
- **Key Features**: Split-section layout for About Us, process section, different color treatment

## Image Sources

All images used in these variants are placeholder images from [Unsplash](https://unsplash.com/), a source for freely-usable images. In a production environment, you should:

1. Replace these placeholder images with your own professional photography
2. Ensure you have proper licensing for any stock photos you use
3. Optimize images for web performance

### Current Image Sources:

- Hero background: [Luxury spa interior](https://images.unsplash.com/photo-1540555700478-4be289fbecef) 
- Case studies/testimonials: 
  - [Case study 1](https://images.unsplash.com/photo-1540555700478-4be289fbecef)
  - [Case study 2](https://images.unsplash.com/photo-1583417267826-aebc4d1542e1)
  - [Case study 3](https://images.unsplash.com/photo-1501854140801-50d01698950b)
- Testimonial profile photos:
  - [Dr. Sarah Johnson](https://images.unsplash.com/photo-1649972904349-6e44c42644a7)
  - [Jennifer Martinez](https://images.unsplash.com/photo-1581091226825-a6a2a5aee158)
  - [Michael Chang](https://images.unsplash.com/photo-1519389950473-47ba0277781c)

## Viewing the Variants

To view these variants:

1. Start a local HTTP server in this directory:
   ```
   cd /path/to/static-variants
   python -m http.server 8000
   ```

2. Open your browser and navigate to:
   ```
   http://localhost:8000
   ```

3. Click on any variant HTML file to view it.

## Customization

To customize these variants:

- **Global styles**: Edit the shared `styles.css` file for changes that apply to all variants
- **Variant-specific styles**: Edit the inline `<style>` section within each variant's HTML file
- **Content**: Modify the HTML directly within each variant
- **Images**: Replace the Unsplash URLs with paths to your own images

## A/B Testing

These variants are designed to be used in A/B testing to determine which design and messaging resonates best with your audience. Consider testing:

1. Different headlines and value propositions
2. Layout variations
3. Call-to-action button text and placement
4. Color schemes and typography

For optimal A/B testing, use a tool like Google Optimize, Optimizely, or VWO to track conversions across variants.
