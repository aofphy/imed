# Presentation Guide

## File Structure

```
FF69/
├── presentation.html          # Main presentation file
├── images/                    # All presentation images
│   ├── sut_logo.svg          # University logo
│   ├── hospital_logo.svg     # Hospital logo
│   ├── dr_fundus.svg         # Retina comparison diagram
│   ├── ai_growth_chart.svg   # Publications growth chart
│   ├── chatgpt.svg           # AI model badges
│   ├── claude.svg
│   ├── gemini.svg
│   └── perplexity.svg
└── PRESENTATION_GUIDE.md     # This file
```

## How to Use

### Opening the Presentation

1. **Double-click** `presentation.html` to open in your default browser
2. Or **right-click** → Open With → Choose your preferred browser (Chrome, Firefox, Safari, Edge)

### Navigation

- **Next slide**: Click right arrow (→) or press **Right Arrow** or **Space**
- **Previous slide**: Click left arrow (←) or press **Left Arrow**
- **Slide counter**: Bottom center shows current slide number

### Presentation Features

- ✅ 14 slides total
- ✅ Full-screen, professional layout
- ✅ Smooth transitions between slides
- ✅ All images stored locally (works offline)
- ✅ Responsive design
- ✅ Custom data visualizations
- ✅ Color-coded performance metrics

## Slide Overview

1. **Title** - Project title, authors, institutions
2. **The Problem** - DR screening gap statistics
3. **AI Revolution** - Introduction to LLMs and MLLMs
4. **Can AI Bridge the Gap** - Research approach
5. **Phase 1 Methodology** - Baseline evaluation process
6. **Binary Classification Results** - Performance comparison
7. **Severity Grading Results** - Multi-class accuracy
8. **Phase 1 Conclusion** - Key findings
9. **Phase 2 Methodology** - Fine-tuning approach
10. **Fine-Tuning Details** - Technical implementation
11. **Phase 2 Results** - Performance improvements
12. **Application Prototype** - Demo interface
13. **Conclusion & Future** - Roadmap
14. **Q&A** - Thank you & questions

## Customization

### Updating Images

All images are in the `images/` folder. To replace:

1. Add your new image to the `images/` folder
2. Open `presentation.html` in a text editor
3. Find the slide with the image you want to replace
4. Update the `src="images/old_image.svg"` to your new filename
5. Save and refresh your browser

### Editing Content

1. Open `presentation.html` in any text editor (VS Code, Sublime, Notepad++, etc.)
2. Find the slide you want to edit (search for slide comments like `<!-- Slide 2: The Problem -->`)
3. Edit the HTML content
4. Save and refresh browser to see changes

### Styling

- The presentation uses **Tailwind CSS** for styling
- Colors, fonts, and layout can be customized by editing CSS classes
- Main gradient: `from-sky-700 to-teal-600`

## Technical Details

- **Framework**: Pure HTML + Tailwind CSS + Vanilla JavaScript
- **No dependencies**: Works completely offline
- **Browser compatibility**: All modern browsers (Chrome, Firefox, Safari, Edge)
- **Screen size**: Optimized for 1920×1080 (scales to other sizes)

## Tips for Presenting

1. **Practice navigation** before presenting
2. **Use full-screen mode** (F11 in most browsers)
3. **Test on presentation computer** beforehand
4. **Bring backup** (USB drive + cloud backup)
5. **Have speaker notes** ready (current version doesn't show notes)

## Troubleshooting

### Images not showing?
- Check that `images/` folder is in the same directory as `presentation.html`
- Verify image files exist and aren't corrupted
- Check browser console for errors (F12 → Console tab)

### Fonts look different?
- Presentation uses **Inter** font from Google Fonts
- Requires internet connection to load
- Falls back to system sans-serif if offline

### Slides won't advance?
- Check that JavaScript is enabled in your browser
- Try refreshing the page (Ctrl+R or Cmd+R)
- Use keyboard arrows if clicking doesn't work

## Contact & Support

For questions about this presentation:
- **Project PI**: Asst. Prof. Dr. Itthiphol Phongphaew
- **Institution**: Suranaree University of Technology
- **Funding**: Fundamental Fund (FF) 2025, Science, Research and Innovation Promotion Fund

---

**Version**: 1.0  
**Last Updated**: October 20, 2025  
**Created with**: Claude Code
