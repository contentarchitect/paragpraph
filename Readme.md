# Paragraph

This library for Content Architect block editor. It is used to add paragraph blocks to the editor.

## Properties
- Ability to edit text with the place toolbar on it.
- Forming text with bold, italic, strikethrough, code, ordered list, unordered list, link, underline buttons on the toolbar.
- To be able to assign class to selection with text class options.
- To be able to style the text with class options.

## Usage
To install to your page:

```js
<script src="unpkg.com/@contentarcihect/editor"></script>
<script src="unpkg.com/@contentarcihect/paragraph"></script>

<script>
ContentArchitect.Blocks.register(Paragraph)
</script>
```

Use this code after your editor code installation. That's all. Now you can use paragraph block on your editor.

- `ContentArchitect` comes from `@contentarchitect/editor`, 
- `Paragraph` comes from `@contentarchitect/paragpraph`