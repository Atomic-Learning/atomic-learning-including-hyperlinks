Sometimes you might want to include a hyperlink to an external resource in the `content.md` file of a piece of content on the Atomic Learning Platform. This can be achieved using standard Markdown syntax, for example:

```html
[Imperial](https://www.imperial.ac.uk/)
```

This will render as "[Imperial](https://www.imperial.ac.uk/)".

# Referencing Internal Pages

In general, you should not use in-page links to reference other content pages. Instead, you should consider the relationship of the two pages:

- If the other page is required to understand the current page, you should note it as a prerequisite of the page in the `metadata.json` file. This means you can assume a reader is familiar with the content of that page. It will be automatically linked at the bottom of the page on the website, allowing the reader to revisit it if they wish.
- If the other page is not required to understand the current page, but may provide additional context or is a suggestion of what the reader may want to learn about next, it should be included as a related piece of content in the `metadata.json` file. This will automatically create a link at the bottom of the page the reader can follow if they wish.

# Accessibility

Links are more accessible to users using screen readers if the text of the link is descriptive of the content it links to. For example, instead of saying "click [here](https://www.imperial.ac.uk/) to visit Imperial's website", you should say "visit the [Imperial College London website](https://www.imperial.ac.uk/)". This provides context to users who may have used a screen reader to navigate the page, and allows them to understand what the link is for without having to read the surrounding text.