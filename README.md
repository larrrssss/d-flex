# d-flex

CSS file for easy positioning

## Documentation

To start with `d-flex` you have to add the `d-flex` class to your parent elemen. Example a `div`:

```html
<div class="d-flex"></div>
```

After adding the class, your element is now flexified. You can start adding following classes:

| Class             | Description                                                                                    |
| ----------------- | ---------------------------------------------------------------------------------------------- |
| `.column`         | Change the parent flex direction to column                                                     |
| `.text-right`     | Makes the `text-align` be `right`                                                              |
| `.fill`           | Adds `flex: 1`; to the element to fill up the space                                            |
| `.child-grow`     | Makes each direct child fill up according to their content                                     |
| `.child-fill`     | Makes each direct child be equal width and fill up the parent's width/height depending on axis |
| `.justify-center` | Justifies the d-flex content into the center                                                   |
| `.align-center`   | Moves the content into the center                                                              |