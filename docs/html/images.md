---
layout: default
title: HTML Images
---

# HTML Images

[← Back to Course Home](../../)

## Adding Images to Web Pages

Images make web pages more interesting and informative. Use the `<img>` tag to embed images.

## Basic Image Syntax

```html
<img src="image.jpg" alt="Description of image">
```

### Required Attributes:
- `src` - The path or URL to the image file
- `alt` - Alternative text (shown if image can't load, important for accessibility)

## Image Attributes

### Width and Height

Control the image size:

```html
<img src="photo.jpg" alt="My Photo" width="300" height="200">
```

### Using Pixels

```html
<img width="120" height="120" src="logo.png" alt="Company Logo">
```

## Image Sources

### Online Images

Link to images on the web:

```html
<img src="https://example.com/image.jpg" alt="Online Image">
```

### Local Images

Link to images in your project:

```html
<!-- Image in same folder -->
<img src="photo.jpg" alt="Local Image">

<!-- Image in subfolder -->
<img src="images/photo.jpg" alt="Image in subfolder">
```

## Best Practices

1. **Always include `alt` text** - Helps with accessibility and SEO
2. **Specify dimensions** - Prevents page layout shifts
3. **Optimize file size** - Compress images for faster loading
4. **Use appropriate formats**:
   - JPEG for photos
   - PNG for graphics with transparency
   - SVG for logos and icons

## Styling Images

Add borders, spacing, and other styles:

```html
<img src="photo.jpg" alt="Styled photo"
     style="border: 2px solid black; border-radius: 10px;">
```

## Example

See images in action:
- [Images Example](../../Samples/LinksImagesAndTitle.html)

## Video Tutorial

Learn more about HTML images:
- [HTML Images Tutorial](https://youtu.be/A1C4RqH1o2I?si=eq-cogBwL_tevK0y)

## Practice Exercise

Add to your HTML file:
1. An image from the web
2. A local image with width and height
3. An image with descriptive alt text
4. A styled image with a border

## Next Steps

Learn about [Basic Styling](styling) →

---

**Navigation:** [Home](../../) | [Previous: Links](links) | [Next: Styling](styling)
