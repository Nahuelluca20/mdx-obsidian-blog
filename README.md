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

First, run the development server:

```bash
npm run dev
# or
yarn dev
# or
pnpm dev
# or
bun dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

You can start editing the page by modifying `app/page.tsx`. The page auto-updates as you edit the file.

This project uses [`next/font`](https://nextjs.org/docs/app/building-your-application/optimizing/fonts) to automatically optimize and load [Geist](https://vercel.com/font), a new font family for Vercel.

## Learn More

To learn more about Next.js, take a look at the following resources:

- [Next.js Documentation](https://nextjs.org/docs) - learn about Next.js features and API.
- [Learn Next.js](https://nextjs.org/learn) - an interactive Next.js tutorial.

You can check out [the Next.js GitHub repository](https://github.com/vercel/next.js) - your feedback and contributions are welcome!

## Deploy on Vercel

The easiest way to deploy your Next.js app is to use the [Vercel Platform](https://vercel.com/new?utm_medium=default-template&filter=next.js&utm_source=create-next-app&utm_campaign=create-next-app-readme) from the creators of Next.js.

Check out our [Next.js deployment documentation](https://nextjs.org/docs/app/building-your-application/deploying) for more details.

## Local Development

```bash
# Install dependencies
npm install

# Start development server
npm run dev
```

## License

MIT
