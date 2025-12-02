---
layout: default
title: Basic HTML Styling
---

# Basic HTML Styling

[← Back to Course Home](../../)

## Introduction to Inline Styling

While CSS is the standard way to style web pages, you can add basic styles directly to HTML elements using the `style` attribute.

## The Style Attribute

The `style` attribute allows you to apply CSS properties directly to an element:

```html
<p style="color: blue;">This text is blue.</p>
```

## Common Style Properties

### Text Color

Change the color of text:

```html
<p style="color: red;">Red text</p>
<p style="color: #0066cc;">Blue text using hex code</p>
<p style="color: blueviolet;">Purple text</p>
```

### Background Color

Set the background color:

```html
<p style="background-color: yellow;">Highlighted text</p>
```

### Font Size

Adjust text size:

```html
<p style="font-size: 20px;">Larger text</p>
<p style="font-size: 12px;">Smaller text</p>
```

### Font Family

Change the font:

```html
<p style="font-family: Arial;">Text in Arial</p>
<p style="font-family: 'Courier New';">Text in Courier New</p>
```

### Text Alignment

Align text horizontally:

```html
<p style="text-align: center;">Centered text</p>
<p style="text-align: right;">Right-aligned text</p>
```

## Multiple Styles

Combine multiple style properties using semicolons:

```html
<p style="color: white; background-color: navy; font-size: 18px; padding: 10px;">
    Styled paragraph with multiple properties
</p>
```

## Example: Changing Color

As shown in the course repository:

```html
<p style="color: blueviolet;">This text appears in blue-violet color</p>
```

## Practical Example

```html
<html>
<head>
    <title>Styling Example</title>
</head>
<body>
    <h1 style="color: darkblue; text-align: center;">Welcome</h1>
    <p style="color: green; font-size: 16px;">
        This is a styled paragraph.
    </p>
</body>
</html>
```

## Limitations of Inline Styles

While inline styles are useful for learning, they have limitations:
- Hard to maintain across multiple pages
- Can't reuse styles easily
- Mix presentation with content

**Note:** For larger projects, use external CSS files instead!

## Practice Exercise

Style a paragraph with:
1. A custom text color
2. A background color
3. A specific font size
4. Center alignment

## Next Steps

Ready to add interactivity? Learn about [JavaScript Basics](basicJavaScript) →

---

**Navigation:** [Home](../../) | [Previous: Images](images) | [Next: JavaScript Basics](basicJavaScript)
