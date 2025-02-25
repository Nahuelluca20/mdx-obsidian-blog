# MDX Blog Template

A simple blog template that uses MDX for content creation. It's designed to work seamlessly with Obsidian, allowing you to write your posts in MDX format with the same experience you'd have in Obsidian.

## Features

- Full MDX file support
- Obsidian compatibility
- Support for drag-and-drop images from Obsidian
- Tag system for post categorization
- Sorting by publication date

## How to Use

1. Create your MDX file in the `content/` folder
2. Add the required frontmatter at the beginning of your file:

```mdx
---
title: "Your Post Title"
publishedAt: "2024-03-20"
summary: "A brief summary of your post"
tags: ["tag1", "tag2"]
---
```

3. When using images from Obsidian:
   - Images will be automatically saved in your Obsidian folder
   - Copy these images to the `public/attachments/` folder
   - Image references in your MDX will work automatically

## Project Structure

## Getting Started

```bash
# Install dependencies
bun install

# Start development server
bun run dev
```

## License

MIT
