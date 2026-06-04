# Markdown basics tutorial

This README gives a quick introduction to Markdown, the lightweight syntax used to write formatted text in `README.md` files.

## What Markdown is

Markdown lets you write plain text and turn it into headings, lists, links, code blocks, and more with simple symbols.

## Common elements

### Headings

Use `#` for headings. More `#` symbols mean a smaller heading.

```md
# H1
## H2
### H3
```

### Bold and italic

```md
**bold text**
*italic text*
```

### Lists

Unordered lists use `-`, `*`, or `+`.

```md
- Item one
- Item two
  - Nested item
```

Ordered lists use numbers.

```md
1. First step
2. Second step
3. Third step
```

### Links and images

```md
[OpenAI](https://openai.com)
![Alt text](image.png)
```

### Code

Inline code uses backticks.

```md
Use `git status` to check changes.
```

For longer examples, use a fenced code block:

```js
function greet(name) {
  return `Hello, ${name}!`;
}
```

### Quotes and separators

```md
> This is a blockquote.

---
```

## Small practice example

```md
# My notes

## Today

- Learn Markdown
- Write a README

## Reminder

> Keep it short and readable.
```

## Tips

- Keep paragraphs short.
- Use headings to organize content.
- Prefer clear examples over long explanations.
- Preview your Markdown to check formatting.

That is enough to start writing clean README files and simple documentation.
