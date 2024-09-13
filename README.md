# Customize File Upload Input in HTML Using CSS & JavaScript
### Create a custom file upload input in HTML and style it using CSS. We also use JavaScript to handle file selection and display the selected file name.


## Full Tutorial
[On Youtube](https://youtu.be/tFaIFb3CI6U)


## Explanation

### Hiding the File Input:
In the HTML, the <input type="file"> is hidden using style="display: none;". This hides the native file input so that we can replace it with our custom UI.

### Custom Button:
The button is styled as the trigger for the file input. When the button is clicked, JavaScript simulates a click on the hidden file input using fileInput.click().

### Display File Name:
After a file is selected, the JavaScript change event updates the fileName span with the name of the selected file.


## Requirements

+ Text Editor
+ Browser 

## Contributing

If you'd like to contribute, please fork the repository and submit a pull request. Any contributions are welcome.

## License

This project is open-source and available under the MIT License.