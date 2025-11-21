# AIP Capital Website Redesign

A modern, professional website redesign for AIP Capital, built with Bootstrap 5 and designed with institutional investment firm best practices in mind.

## Design Philosophy

This redesign combines the best design patterns from leading investment firms (Castlelake, BC Partners, Bridgepoint Group, and GCM Grosvenor) while maintaining AIP Capital's unique aviation-focused brand identity.

### Key Design Principles

1. **Institutional Credibility**: Clean, professional aesthetic that builds trust with sophisticated investors
2. **Clear Value Proposition**: Immediate communication of AIP's unique positioning in aviation investment
3. **Generous Whitespace**: Modern, uncluttered layout that prioritizes readability and visual hierarchy
4. **Data-Driven Messaging**: Facts-first approach with prominent display of key metrics ($4B AUM, 31+ professionals, 7 offices)
5. **Responsive Design**: Fully optimized for all device sizes

## Design Elements

### Color Palette
- **Primary Navy**: `#0056A7` - Main brand color conveying trust and stability
- **Secondary Navy**: `#1863DC` - Complementary blue for accents
- **Accent Cyan**: `#00c5de` - Energetic accent color for CTAs and highlights
- **Dark Navy**: `#002d5c` - Deep navy for headers and emphasis

### Typography
- **Font Family**: Inter (Google Fonts) - Modern, highly readable sans-serif
- **Hierarchy**: Clear visual hierarchy with varied font sizes and weights
- **Spacing**: Generous line-height (1.7) for optimal readability

### Layout Structure

1. **Hero Section**: Full-height hero with gradient background and clear value proposition
2. **Stats Bar**: Eye-catching metrics displayed prominently with animation
3. **About Section**: Company introduction with core values (Committed, Collaborative, Connected)
4. **Strategies Section**: Three investment approaches in card format with imagery
5. **Platform Section**: Differentiators with icon-based features
6. **Global Reach**: Seven office locations displayed in grid
7. **CTA Section**: Strong call-to-action encouraging investor engagement
8. **Footer**: Comprehensive navigation and contact information

## Features

### User Experience
- **Smooth Scrolling**: Seamless navigation between sections
- **Sticky Navigation**: Fixed header that adapts on scroll
- **Active States**: Navigation highlights current section
- **Mobile-First**: Responsive design optimized for all devices
- **Accessibility**: WCAG compliant with proper semantic HTML

### Animations
- **AOS (Animate On Scroll)**: Subtle fade-in animations for content sections
- **Counter Animation**: Stats numbers animate when scrolled into view
- **Hover Effects**: Interactive cards and buttons with smooth transitions
- **Parallax**: Subtle parallax effect on hero section

### Performance
- **CDN Resources**: Bootstrap and fonts loaded from CDN for optimal performance
- **Lazy Loading**: Images load as needed to improve initial page load
- **Optimized Assets**: Minimal external dependencies

## Technologies Used

- **Bootstrap 5.3.2**: Responsive grid system and components
- **AOS 2.3.1**: Animate On Scroll library for scroll animations
- **Google Fonts (Inter)**: Professional typography
- **Bootstrap Icons**: Scalable vector icons
- **Vanilla JavaScript**: Custom interactions without heavy frameworks

## File Structure

```
aip/
├── index.html          # Main homepage HTML
├── styles.css          # Custom styles and theme
├── script.js           # Interactive functionality
└── README.md          # This file
```

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## Customization

### Changing Colors
Edit the CSS variables in `styles.css`:
```css
:root {
    --primary-navy: #0056A7;
    --accent-cyan: #00c5de;
    /* ... */
}
```

### Adding Content
- **Strategies**: Add new strategy cards in the strategies section
- **Offices**: Add office locations in the global section
- **Values**: Modify core values in the about section

### Images
Replace placeholder images from Unsplash with actual AIP Capital photography:
- Hero background
- Strategy section images
- About section images
- Platform section images

## Next Steps

1. **Add Real Content**: Replace placeholder images with actual AIP Capital photography
2. **Implement Forms**: Add contact forms and investor login functionality
3. **CMS Integration**: Connect to a content management system for easy updates
4. **Analytics**: Add Google Analytics or similar tracking
5. **Additional Pages**: Create About, Strategies, Team, Contact pages
6. **Legal Compliance**: Add necessary disclaimers and legal disclosures
7. **Performance Optimization**: Compress images, minify CSS/JS for production

## Comparison to Reference Sites

### What We Adopted
- **Castlelake**: Clean navigation, video/image hero concepts, substantial whitespace
- **BC Partners**: Navy/cyan color scheme, clear strategy segregation
- **Bridgepoint**: Tiered navigation structure, transparency mechanisms
- **GCM Grosvenor**: Sophisticated typography hierarchy, responsive architecture

### AIP Capital Differentiators
- Aviation-specific imagery and messaging
- Emphasis on "asset manager vs lessor" positioning
- Three distinct business streams (Credit, Investing, Management)
- Phoenix Aviation Capital integration
- Global office presence highlighting

## Credits

Design and development by Claude (Anthropic)
Built for AIP Capital
2024

## License

Proprietary - AIP Capital
