---
layout: default
title: HTML Links
---

# HTML Links

[← Back to Course Home](../../)

## What are Links?

Links (hyperlinks) allow users to navigate between web pages. They are created using the `<a>` (anchor) tag.

## Basic Link Syntax

```html
<a href="https://www.example.com">Click here</a>
```

### Components:
- `<a>` - The anchor tag
- `href` - The URL or path to link to
- Link text - The clickable text between the tags

## Types of Links

### External Links

Links to other websites:

```html
<a href="https://www.google.com">Visit Google</a>
```

### Internal Links

Links to other pages in your site:

```html
<a href="about.html">About Us</a>
<a href="/contact.html">Contact</a>
```

### Anchor Links

Links to specific sections on the same page:

```html
<a href="#section2">Jump to Section 2</a>

<!-- Later on the page -->
<h2 id="section2">Section 2</h2>
```

## Link Attributes

### `target` Attribute

Control where the link opens:

```html
<!-- Open in new tab -->
<a href="https://www.example.com" target="_blank">Open in new tab</a>

<!-- Open in same window (default) -->
<a href="https://www.example.com" target="_self">Open here</a>
```

### `title` Attribute

Add a tooltip to your link:

```html
<a href="https://www.example.com" title="Visit Example Site">Click here</a>
```

## Styling Links

You can style links using the `style` attribute:

```html
<a href="page.html" style="color: blue; text-decoration: none;">Styled link</a>
```

## Example

See a working example with links in action:
- [Links Example](../../Samples/LinksImagesAndTitle.html)

## Video Tutorial

Watch this tutorial about HTML links:
- [HTML Links Tutorial](https://youtu.be/c3Tg5QCxEbA?si=H2UKvBKIUJyFq0NN)

## Practice Exercise

Create:
1. A link to an external website
2. A link that opens in a new tab
3. A link to another page in your site
4. An anchor link to a section on the same page

## Next Steps

Learn about [HTML Images](images) →

---

**Navigation:** [Home](../../) | [Previous: Attributes](attributes) | [Next: Images](images)
