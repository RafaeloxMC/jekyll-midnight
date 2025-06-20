---
layout: default
title: Home
description: A clean Jekyll theme for dark mode users
---

# jekyll-midnight

_jekyll-midnight_ is a **clean Jekyll theme** for the average **dark mode user**.

It is designed to be **simple**, **easy to use**, and **visually appealing**, with a focus on **readability** and **user experience**.

## Features

-   **Dark mode** by default
-   **Responsive** design
-   **Clean** and **minimalistic** layout
-   **Easy** to **customize**
-   **Code** syntax highlighting
-   **Fast** loading and optimized
-   **SEO** friendly structure

## Installation

To install _jekyll-midnight_, follow these **simple steps**:

1. **Clone the repository**:
    ```bash
    git clone https://github.com/RafaeloxMC/jekyll-midnight.git
    ```
2. **Navigate** to the cloned directory:
    ```bash
    cd jekyll-midnight
    ```
3. **Install** the dependencies:
    ```bash
    bundle install
    ```
4. **Build** the site:
    ```bash
    bundle exec jekyll build
    ```
5. **Serve** the site locally:
    ```bash
    bundle exec jekyll serve
    ```
6. **Open** your browser and go to `http://localhost:4000` to view your site.

## Formatting Examples

This theme supports various **Markdown formatting options**:

### Text Formatting

-   **Bold text** using `**bold**` or `__bold__`
-   _Italic text_ using `*italic*` or `_italic_`
-   **_Bold and italic_** using `***text***`
-   ~~Strikethrough~~ using `~~text~~`
-   `Inline code` using backticks

### Lists

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

### Blockquotes

> **Important Note**: This is a blockquote with **bold text** and _italic text_.
>
> > **Nested Quote**: You can also nest blockquotes for **emphasis**.

### Tables

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

## Customization

You can **easily customize** the theme by:

-   **Editing** the `_config.yml` file for **site configuration**
-   **Modifying** styles in the `assets/css` directory for **visual changes**
-   **Adding** your own content by creating **new Markdown files**
-   **Customizing** the layout in the `_layouts` directory

### **Key Configuration Options:**

-   **Site title** and **description**
-   **Author information**
-   **Social media links**
-   **Custom CSS** and **JavaScript**

## Contributing

**We welcome contributions!** If you would like to contribute to _jekyll-midnight_:

-   **Open an issue** for bug reports or feature requests
-   **Submit a pull request** with your improvements
-   **Share feedback** on the theme's usability
-   **Help improve** documentation

**All contributions** are **greatly appreciated** and help make this theme **better for everyone**!

---

**Happy blogging** with _jekyll-midnight_! 🌙
