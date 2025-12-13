# AGUARIO Website - Image Assets Guide

## Hero Background Image

The hero section currently uses a gradient background. To add a custom image:

1. **Recommended image**: Aerial view of Magdalena River, Canal del Dique, or regional landscape
2. **Dimensions**: 1920x1080px minimum
3. **Format**: JPG or WebP for best performance
4. **File name**: `hero-bg.jpg`
5. **Location**: Place in `c:\Users\gumba\Documents\Aguario\`

### Suggested Image Sources:

- Unsplash.com (search: "colombia river", "wetlands", "bridge river")
- Pexels.com (search: "rural infrastructure", "river landscape")
- Local photography of the region

### To implement:

Once you have the image, the CSS is already configured to use it. The gradient will serve as a fallback.

## Service Icons

The website currently uses Font Awesome icons for all services. These are already implemented and working:

- 🛣️ Infrastructure: `fa-road`
- 💧 Environment: `fa-water`
- ❤️ Social Development: `fa-heart`
- 🏢 Institutional: `fa-building`
- 🚜 Agriculture: `fa-tractor`
- 💻 Technology: `fa-laptop-code`

No additional images needed for services - the icons are vector-based and scale perfectly on all devices.

## Optional Enhancements

If you want to add photos to the projects section or about section:

1. Create an `images` folder: `c:\Users\gumba\Documents\Aguario\images\`
2. Add project photos with descriptive names (e.g., `proyecto-remolino.jpg`)
3. Update the HTML to include `<img>` tags in the project cards

## Performance Tips

- Optimize images before uploading (use TinyPNG.com or similar)
- Use WebP format for better compression
- Keep images under 500KB for fast mobile loading
