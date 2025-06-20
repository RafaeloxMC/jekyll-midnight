---
layout: post
title: "Formatting Examples for Jekyll Midnight Theme"
date: 2025-06-20 15:00:00 +0000
author: "Jekyll Midnight"
tags: [jekyll, midnight-theme, formatting, markdown]
excerpt: "Explore various Markdown formatting options supported by the Jekyll Midnight theme, including text styles, lists, blockquotes, tables, and syntax highlighting."
---

# Formatting Examples with Jekyll Midnight Theme

This theme supports various **Markdown formatting options**:

## Text Formatting

-   **Bold text** using `**bold**` or `__bold__`
-   _Italic text_ using `*italic*` or `_italic_`
-   **_Bold and italic_** using `***text***`
-   ~~Strikethrough~~ using `~~text~~`
-   `Inline code` using backticks

## Lists

**Unordered lists:**

-   **Primary item**
-   _Secondary item_
-   Regular item
    -   **Nested bold item**
    -   _Nested italic item_

**Ordered lists:**

1. **First important step**
2. _Second step with emphasis_
3. Regular third step

## Blockquotes

> **Important Note**: This is a blockquote with **bold text** and _italic text_.
>
> > **Nested Quote**: You can also nest blockquotes for **emphasis**.

## Tables

| **Feature**      | **Status**       | _Description_          |
| ---------------- | ---------------- | ---------------------- |
| **Dark Mode**    | ✅ **Enabled**   | _Default dark theme_   |
| **Responsive**   | ✅ **Active**    | _Works on all devices_ |
| **Fast Loading** | ✅ **Optimized** | _Quick page loads_     |

## Syntax Highlighting

**Syntax highlighting** is enabled by default using the **`rouge` gem**. You can use **fenced code blocks** in your Markdown files to highlight code snippets. For example:

**Ruby example:**

```ruby
# A simple Ruby method
def hello_world
  puts 'Hello, world!'
end

# Call the method
hello_world
```

**JavaScript example:**

```javascript
// A simple JavaScript function
function greetUser(name) {
	console.log(`Hello, ${name}!`);
}

// Call the function
greetUser("World");
```

**Python example:**

```python
# A simple Python function
def calculate_area(radius):
    return 3.14159 * radius ** 2

# Call the function
area = calculate_area(5)
print(f"Area: {area}")
```
