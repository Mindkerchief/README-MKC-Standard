# ![logo][logo-thumbnail] README-MKC-Standard ![github-readme][app-badge]

A markdown template of README.md for GitHub repositories, specifically for desktop and smartphone applications. It focuses on simple, consistent design and well-structured content. This template tries to avoid HTML syntax and maintain markdown syntax throughout the template to keep the code cleaner and maintainable. A set of images/screenshot resolutions and other standards are recommended below to maintain a consistent layout while trying to make screenshots readable.

## Table of Contents
- [Standards](#standards)
- [Usage](#usage)
- [License](#license)

## Standards
### Content Structure
The following are recommendations on how to effectively write and structure text content:
- Avoid using AI-generated descriptions. You can use it for inspiration or structuring but try to create your own words to maintain the personality.
- Use proofreading services to identify errors in grammar, punctuation and spelling just in case.
- Be consistent on how you compose sentences, like using the same starting words, where to use declarative/imperative sentences and sentence complexity.
- Read your sentences several times to judge whether they need to be reconstructed or complete trash.
- Template sections can be changed, removed, added and rearranged to fit to preferred style.
- When changing or adding a section title, keep the section title as short as possible with a maximum of three words.

The following are sentence template recommendation if encountered:
- Project Badge: <https://img.shields.io/badge/ `Environment-Type-COLOR>` | ![github-readme](https://img.shields.io/badge/Windows-File_Management_System-4483BE)
- Project Description: `A <app-environment> application that...`
- Installation: `Download the latest release of <app-name>.`
- Acknowledgments: `<contributor>: For <contribution>.`
- License: `This project is licensed under the <licence-name> License`

### Image Handling
The following are recommendations on how to consistently handle images/screenshots:
- The width resolution is recommended to be followed to maintain a consistent design and avoid images from stacking vertically.
- The height resolution can vary, but is it recommended to keep every image/screenshot resolution identical in a single row.
- If there is a large gap between images/screenshots in a single row, try to order them from tallest to smallest.

### Logo Resolution
- **Thumbnail** - `25x25`

### Landscape Resolution
- **Single** - `width: 640px`
- **Double** - `width: 400px`
- ~~**Triple** - `width: 264px` not recommended.~~

### Portrait Resolution
- **Single** - `width: 264px`
- **Double** - `width: 264px`
- **Triple** - `width: 264px`

### Markdown Syntax Conventions
The following are recommendations on how to properly write markdown syntax:
- Do not include another `#` as a section.
- Use `##` for the section header.
- Use `###` for section sub-header.
- Use `[<reference-description>]: <link>` for link reference.
- Use `![<alternative-description>][<link-reference>]` for images.
- Use `&nbsp;` for spacing between images.
- Use single spacing between sections.
- Use single spacing between references that belong to different sections or purposes.

## Usage
### Single Landscape
![screenshot-landscape][single-landscape] &nbsp;
- Ideal for promotional image and application main screen.
- Recommended for desktop/smartphone (landscape) screenshots.

### Double Landscape
![screenshot-landscape][double-landscape] &nbsp;
![screenshot-landscape][double-landscape]
- Ideal for main features to keep them in one place.
- Recommended for desktop/smartphone (landscape) screenshots.

### Triple Portrait
![screenshot-portrait][triple-portrait] &nbsp;
![screenshot-portrait][triple-portrait] &nbsp;
![screenshot-portrait][triple-portrait]
- Ideal for main features to keep them in one place.
- Recommended for smartphone (portrait) screenshots.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

<!-- Reference -->
[logo-thumbnail]: https://github.com/Mindkerchief/README-MKC-Standard/blob/e6aa6e5d50a7de43b5c7d51e576a6eff42c26573/assets/logo-thumbnail.png
[app-badge]: https://img.shields.io/badge/GitHub-README-FFFFFF

[single-landscape]: https://github.com/Mindkerchief/README-MKC-Standard/blob/e6aa6e5d50a7de43b5c7d51e576a6eff42c26573/assets/screenshot-single-landscape.png
[double-landscape]: https://github.com/Mindkerchief/README-MKC-Standard/blob/e6aa6e5d50a7de43b5c7d51e576a6eff42c26573/assets/screenshot-double-landscape.png
[triple-portrait]: https://github.com/Mindkerchief/README-MKC-Standard/blob/e6aa6e5d50a7de43b5c7d51e576a6eff42c26573/assets/screenshot-triple-portrait.png
