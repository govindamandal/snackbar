# snackbar
This repository is for showing alert message.

## Add a new way of showing alert message in your website.
## Example:

```html
<!DOCTYPE html>
<html lang="en-US">
  <head>
    <title>Snackbar Demo</title>
    <link rel="stylesheet" href="snackbar.css" type="text/css" />    
  </head>
  <body>
    <button type="button" onclick="showSnackbar()"></button>
    <script src="snackbar.js"></script>
    <script type="text/javascript">
       showSnackbar = () => {
          // Success message
          snackbar.success('Success: Welcome to snackbar!');
          
          // Warning message
          snackbar.warning('Warning: You have error in message!');
          
          // Success message
          snackbar.error('Warning: You don\'t have permission to access this!');
       }
    </script>
  </body>
</html>
```
