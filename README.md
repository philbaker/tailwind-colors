# Tailwind colors

Find a Tailwind color class name, hex or rgb value based on another value.

Colors are from [Customizing colors](https://tailwindcss.com/docs/customizing-colors) and are accurate as of Tailwind v3.3.2

## Options

### Class to hex (ch or class-to-hex)
```bash
$ node index.mjs ch "red-100"
#fee2e2
```

### Class to RGB (cr or class-to-rgb)
```bash
$ node index.mjs cr "red-100"
rgb(254, 226, 226)
```

### Hex to class (hc or hex-to-class)
```bash
$ node index.mjs hc "#fee2e2"
:red-100
```

### RGB to class (rc or rgb-to-class)
```bash
$ node index.mjs rc "rgb(254, 226, 226)"
:red-100
```
