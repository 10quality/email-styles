# Email Styles

Light weight CSS framework for emails.

Need professional looking emails? Stylize your emails for Gmail, Hotmail, Outlook and more with *Email Styles* CSS framework.

-  [Usage](#usage)
    -  [Basic Structure](#basic-structure)
-  [License](#license)

## Usage

To use the framework, simply copy the content of the minified version, located at `dist/style.min.css`, in your emails template `head` section:

```html
<html>
    <head>
      <!-- COPY CONTENT FROM style.min.css HERE!!!!!! -->  
    </head>
</html>
```

### Basic Structure

This is the recomended structure to use with the framework:
```html
<html>
    <head>
      <!-- COPY CONTENT FROM style.min.css HERE!!!!!! -->  
    </head>
    <body>

        <div class="container">

            <div class="header">
                <!-- Your logo or company name here -->  
            </div>

            <div class="content">
                <!-- Email content here -->  
            </div>

            <div class="footer">
                <!-- Copyright and links info here -->  
            </div>

        </div>

    </body>
</html>
```

Then use the provided CSS classes.

See [DEMO](http://codepen.io/amostajo/pen/RRkygo).

## License

The MIT License (MIT)

Copyright (c) 2016 [10Quality](http://www.10quality.com/).