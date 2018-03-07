## TopAppBar

### Markup

```html
<m-top-app-bar>
  <m-icon
    icon="menu"
    slot="navigation"/>
  <span>Title</span>
  <m-icon
    icon="file_download"
    slot="actions"/>
</m-top-app-bar>
```

### Props & events

| Prop | Type | Default | Description |
|------|------|---------|-------------|
| collapsed | Boolean | false | collapsed bar when short too |
| short | Boolean | false | short bar |

| Event | Description |
|------|------|
| navigation | will be dispatched when navigation item is clicked |

### Slots

| Slot | Description |
|------|-------------|
| default | top app bar title |
| navigation | navigation section icons |
| actions | actions section icons |

### Reference

- https://github.com/material-components/material-components-web/tree/master/packages/mdc-top-app-bar