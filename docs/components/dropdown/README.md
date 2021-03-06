# Dropdowns

> Dropdowns are toggleable, contextual overlays for displaying lists of links and more. They’re made interactive with the included Bootstrap dropdown JavaScript plugin.

Simple usage:
```html
<b-dropdown text="Dropdown" variant="success" class="m-md-2">
    <b-dropdown-header>This is a heading</b-dropdown-header>
    <b-dropdown-item>Action</b-dropdown-item>
    <b-dropdown-item>Another action</b-dropdown-item>
    <b-dropdown-divider></b-dropdown-divider>
    <b-dropdown-item>Something else here...</b-dropdown-item>
    <b-dropdown-item-button>Action using button</b-dropdown-item-button>
</b-dropdown>
```

### Accessibility

Providing a unique `id` prop ensures ARIA compliance by automatically adding
the appropriate `aria-*` attributes in the rendered markup.

Dropdowns support keyboard navigation, emulating native select behaviour.
