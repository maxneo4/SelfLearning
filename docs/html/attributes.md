---
layout: default
title: HTML Attributes
---

# HTML Attributes

[← Back to Course Home](../../index.md)

## What are HTML Attributes?

HTML attributes provide additional information about elements. They are always specified in the opening tag and usually come in name/value pairs like `name="value"`.

## Common Attributes

### The `id` Attribute

The `id` attribute specifies a unique identifier for an element:

```html
<p id="main-paragraph">This paragraph has a unique ID.</p>
```

### The `class` Attribute

The `class` attribute specifies one or more class names for styling:

```html
<p class="important-text">This text has a class.</p>
```

### The `style` Attribute

The `style` attribute adds inline CSS styling:

```html
<p style="color: blue;">This text is blue.</p>
```

### The `title` Attribute

The `title` attribute provides tooltip text:

```html
<p title="This is a tooltip">Hover over me!</p>
```

## Attribute Examples

### Width and Height

Used with images and other elements:

```html
<img width="120" height="120" src="image.jpg" alt="Description">
```

### Multiple Attributes

Elements can have multiple attributes:

```html
<p id="intro" class="highlight" style="font-size: 18px;">
    Welcome text with multiple attributes
</p>
```

## Best Practices

1. Always use lowercase for attribute names
2. Always quote attribute values
3. Use double quotes (") for consistency
4. Use meaningful `id` and `class` names

## Video Tutorial

Learn more about HTML attributes:
- [HTML Attributes Tutorial](https://youtu.be/Qm8NrEjAeq4?si=4jT0b5mJygQ8e9Se)

## Practice Exercise

Create an HTML element with:
1. An `id` attribute
2. A `class` attribute
3. A `style` attribute that changes the color
4. A `title` attribute

## Next Steps

Learn about [HTML Links](links.md) →

---

**Navigation:** [Home](../../index.md) | [Previous: Basics](basics.md) | [Next: Links](links.md)
