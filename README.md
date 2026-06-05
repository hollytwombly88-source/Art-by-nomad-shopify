# Art by Nomad - Shopify Theme

A fully functioning, luxury art gallery Shopify theme inspired by the dark, emotional aesthetic of "Art by Nomad" (Nomad 26). This theme is designed for selling digital art with a sophisticated, gallery-like presentation.

## 🎨 Theme Features

### Design
- **Dark Luxury Aesthetic**: Deep black background with gold and red accents
- **Responsive Design**: Mobile, tablet, and desktop optimized
- **Gallery-Style Layout**: Perfect for showcasing artwork
- **Smooth Animations**: Elegant transitions and hover effects
- **Accessibility**: WCAG compliant with proper focus states and ARIA labels

### Sections
- **Hero Section**: Large hero image with compelling copy and CTA
- **Collections Grid**: 5-column grid showcase of art collections
- **Header**: Sticky navigation with announcement bar
- **Footer**: Multi-column footer with newsletter signup and social links
- **Product Showcase**: Detailed product pages with image gallery
- **Shopping Cart**: Full cart management system
- **Collections Page**: Browse all artwork by collection

## 📋 File Structure

```
Art-by-nomad-shopify/
├── config/
│   ├── settings_data.json       # Theme settings data
│   └── settings_schema.json     # Settings configuration
├── templates/
│   ├── index.json               # Homepage
│   ├── product.liquid           # Product page
│   ├── collection.liquid        # Collection page
│   ├── cart.liquid              # Shopping cart
│   └── page.liquid              # Generic page template
├── sections/
│   ├── header.liquid            # Header with navigation
│   ├── footer.liquid            # Footer section
│   ├── hero.liquid              # Hero section
│   └── collections-grid.liquid  # Collections showcase
├── layout/
│   └── theme.liquid             # Main theme layout
├── assets/
│   ├── theme.css                # Theme styles
│   ├── base.css                 # Base styles
│   └── theme.js                 # Theme JavaScript
├── config.yml                   # Shopify CLI config
├── theme.toml                   # Theme manifest
└── README.md                    # This file
```

## 🚀 Getting Started

### 1. Install Shopify CLI
```bash
npm install -g @shopify/cli@latest
```

### 2. Connect to Your Store
```bash
cd Art-by-nomad-shopify
shopify theme dev
```

This will start a local development server and automatically upload changes to your theme.

### 3. Create a New Theme in Admin
1. Go to your Shopify Admin
2. Navigate to **Sales channels** → **Online store** → **Themes**
3. Click **Add theme** → **Upload theme file**
4. Or use Shopify CLI to connect directly

## 🎯 Customization Guide

### Colors
Edit the CSS variables in `layout/theme.liquid`:

```css
--color-bg: #000000              /* Background */
--color-text: #e8e8e8           /* Text */
--color-accent: #d4af8a         /* Gold accents */
--color-accent-red: #a83e3e     /* Red accents */
```

### Fonts
Update font settings in `config/settings_schema.json` or through Shopify Admin.

### Hero Section
Customize the hero section through Shopify Admin:
1. Go to **Online store** → **Pages** → **Homepage**
2. Click **Edit sections**
3. Configure the Hero Section settings

### Collections
Add your art collections through Shopify Admin:
1. Go to **Products** → **Collections**
2. Create new collections for each series
3. Add products to each collection

## 📱 Responsive Breakpoints

- **Desktop**: 1400px and above
- **Tablet**: 768px to 1024px
- **Mobile**: Below 768px

## 🛒 Shopping Features

### Cart Management
- Add/remove items
- Quantity adjustment
- Real-time cart updates
- Persistent cart data

### Checkout
- Secure Shopify checkout
- Multiple payment methods
- Shipping calculation
- Tax estimation

## 🔐 Security

- Shopify's built-in security
- HTTPS only
- PCI compliance
- Secure payment processing

## ⚙️ Theme Settings

Access theme settings through **Shopify Admin** → **Online store** → **Themes** → **Customize**

### Available Settings
- **Color Scheme**: Customize all theme colors
- **Header Menu**: Set primary navigation
- **Logo Width**: Adjust logo size
- **Announcement**: Display banner message
- **Social Media**: Add social links

## 🎯 SEO Features

- Proper heading hierarchy (H1, H2, H3)
- Meta descriptions for all pages
- Structured data markup
- Alt text for images
- Mobile-friendly design
- Fast page load optimization

## ♿ Accessibility

- ARIA labels on interactive elements
- Keyboard navigation support
- Focus states on all interactive elements
- Semantic HTML
- Color contrast compliance
- Screen reader support

## 📊 Performance Optimizations

- Lazy loading for images
- Minified CSS and JavaScript
- Optimized image serving
- Efficient caching
- Mobile-first responsive design

## 🐛 Troubleshooting

### Cart Not Updating
Clear your browser cache and check that cookies are enabled.

### Images Not Loading
Ensure images are uploaded to Shopify and properly configured in product/collection settings.

### Styles Not Applying
Try clearing the browser cache and reloading. Use `shopify theme develop` for local testing.

## 📚 Resources

- [Shopify Theme Development Docs](https://shopify.dev/themes)
- [Liquid Template Language](https://shopify.dev/api/liquid)
- [Shopify CLI Documentation](https://shopify.dev/themes/tools/cli)

## 🤝 Support

For issues or questions:
1. Check the Shopify documentation
2. Review the code comments in each file
3. Test locally with `shopify theme dev`

## 📄 License

This theme is designed for use with Shopify. Ensure compliance with Shopify's terms of service.

## 🎨 Brand Guidelines

### Typography
- **Headings**: Georgia (Serif)
- **Body**: Quattrocento Sans (Sans-serif)

### Color Palette
- **Primary**: Gold (#d4af8a)
- **Accent**: Red (#a83e3e)
- **Background**: Black (#000000)
- **Text**: Light Grey (#e8e8e8)

### Design Elements
- Clean, minimalist layouts
- Generous white space
- Elegant borders and dividers
- Smooth transitions and animations
- Gallery-style imagery showcase

## ✨ Latest Updates

- Full responsive design
- Mobile menu toggle
- Cart integration
- Newsletter signup
- Social media links
- Accessibility improvements

---

**Art by Nomad Theme** | Created for emotional, story-driven art exhibitions
