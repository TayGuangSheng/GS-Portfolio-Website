# Adding Projects

Add new projects in `assets/js/projects-data.js`.

1. Put the project screenshot or image in `assets/img/portfolio/`.
2. Open `assets/js/projects-data.js`.
3. Copy one project block, paste it before the closing `];`, and edit the fields.

Example:

```js
{
  title: "New Project Name",
  category: "Web Design",
  type: "Web Design / Personal",
  image: "assets/img/portfolio/New Project Image.png",
  imageAlt: "Screenshot of New Project Name",
  description: "One short sentence explaining what the project does and why it matters.",
  projectUrl: "https://github.com/TayGuangSheng/new-project",
  previewUrl: "assets/img/portfolio/New Project Image.png"
}
```

Notes:

- `category` controls the filter button. New categories appear automatically.
- `image` is the card image.
- `previewUrl` is the image opened by the plus button. Usually this can match `image`.
- `projectUrl` is opened by the link button.
- Keep commas between project blocks.
