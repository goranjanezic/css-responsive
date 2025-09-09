# goja.css

goja.css is a library of various CSS styles.

## Installation

just download the css folder.

## Usage

Example of 'responsive.css' usage. The full example is in the 'Samples/ResponsiveDesign' section.

```html
<!DOCTYPE html>

<html lang="en" xmlns="http://www.w3.org/1999/xhtml">
<head>
    <meta charset="utf-8" />
    <title></title>
    <link rel="stylesheet" href="css/main.css" />
    <link rel="stylesheet" href="../../css/responsive.css" />
    <link rel="stylesheet" href="css/site.css" />
</head>
<body>
    <div class="row">
        <div class="col col-auto">
            <div>1</div>
        </div>
        <div class="col">
            <div>2</div>
        </div>
        <div class="col col-md-40 col-sm-40">
            <div>3</div>
        </div>
        <div class="col">
            <div>4</div>
        </div>
        <div class="col">
            <div>5</div>
        </div>
    </div>
</body>
</html>
```

## Contributing

Pull requests are welcome. For major changes, please open an issue first
to discuss what you would like to change.

Please make sure to update tests as appropriate.

## License

[MIT](https://choosealicense.com/licenses/mit/)
