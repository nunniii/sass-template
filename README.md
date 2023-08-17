
# Presets for use in sass

### Main preset:

```scss
    @charset "UTF-8";

    * {
        margin: 0;
        padding: 0;
        box-sizing: border-box;
    }
```

### Fonts: 

```scss
    @mixin font-{FONT NAME} {
        @import url('URL FONT');

        font-family: {CALLING THE FONT};
    }
```

**available fonts:**
- Poppins;
- Inter;
- Baskerville;
- Montserrat;
- Lora;
- Inconsolata;


### Colors

```scss
    ${COLOR}: rgb(R, G, B);
```

**available colors:**

The available colors were based on tailwindcss presets: [dos/list-of-colors](https://tailwindcss.com/docs/background-color)

