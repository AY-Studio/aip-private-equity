# Hero Video Background Guide

The hero section now includes a video background. You'll need to add your video file(s) to make it work.

## Video Requirements

### Technical Specifications
- **Format**: MP4 (primary) and WebM (fallback for better browser support)
- **Resolution**: 1920x1080 (Full HD) minimum
- **Duration**: 10-30 seconds (will loop seamlessly)
- **File Size**: Under 5MB for optimal loading (compress if necessary)
- **Frame Rate**: 24-30 fps
- **Aspect Ratio**: 16:9

### Content Suggestions for Private Equity Firm
- Modern office buildings/cityscapes
- Business meetings and collaboration
- Corporate environments
- Financial data visualizations
- Professional handshakes/partnerships
- Technology and innovation themes
- Abstract corporate motion graphics

## Where to Find Professional Stock Videos

### Free Sources
1. **Pexels Videos** - https://www.pexels.com/videos/
   - Search: "business", "office", "corporate", "finance", "cityscape"

2. **Pixabay** - https://pixabay.com/videos/
   - High-quality free videos
   - Search: "business meeting", "corporate", "financial"

3. **Coverr** - https://coverr.co/
   - Free videos specifically for website backgrounds
   - Search: "business", "corporate"

4. **Videvo** - https://www.videvo.net/
   - Mix of free and paid options

### Premium Sources (Higher Quality)
1. **Envato Elements** - https://elements.envato.com/
2. **Shutterstock** - https://www.shutterstock.com/video
3. **Adobe Stock** - https://stock.adobe.com/video
4. **Storyblocks** - https://www.storyblocks.com/

## Installation Steps

1. **Download your chosen video** in both MP4 and WebM formats (if possible)
   - If you only have MP4, that's fine - the WebM is optional

2. **Optimize the video** (recommended)
   - Use a tool like HandBrake (free) to compress the video
   - Target: Under 5MB for best performance
   - Keep quality high but file size reasonable

3. **Name your video files**:
   - `hero-video.mp4`
   - `hero-video.webm` (optional)

4. **Place the video files** in the same directory as `index.html`:
   ```
   aip/
   ├── index.html
   ├── styles.css
   ├── script.js
   ├── hero-video.mp4    ← Add here
   └── hero-video.webm   ← Add here (optional)
   ```

5. **Test the website** - Open `index.html` in a browser to see the video background

## Video Compression Tips

If your video is too large:

### Using HandBrake (Free, Cross-platform)
1. Download HandBrake: https://handbrake.fr/
2. Open your video file
3. Use the "Web" preset
4. Adjust quality slider to 22-24 (lower = smaller file)
5. Export

### Using FFmpeg (Command line)
```bash
# Compress MP4
ffmpeg -i input.mp4 -vcodec h264 -acodec aac -b:v 2M hero-video.mp4

# Convert to WebM
ffmpeg -i input.mp4 -c:v libvpx-vp9 -b:v 2M hero-video.webm
```

## Fallback

If no video is provided, the hero section will show the gradient background (current blue gradient). The site will work perfectly fine without the video.

On mobile devices, the video is automatically hidden to save bandwidth and improve performance.

## Recommended Search Terms

When searching for stock videos, try these terms:
- "corporate office timelapse"
- "business people working"
- "modern city skyline"
- "financial district"
- "team collaboration"
- "boardroom meeting"
- "data visualization motion"
- "abstract business motion graphics"
- "professional handshake"
- "stock market graphs"

## Performance Notes

- Video is set to `autoplay`, `muted`, and `loop`
- Uses `playsinline` for iOS compatibility
- Disabled on mobile to save bandwidth
- Dark overlay ensures text remains readable
- Fallback gradient shows if video doesn't load
