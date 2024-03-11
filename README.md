
## QR Code Generator by Irene Annah

This is a simple QR code generator implemented in JavaScript, Html and Css

## Live link 
This project had been deployed on Netlify app, below is the link

## How to Use
Clone this repository to your local machine.
Open the index.html file in your web browser.
Enter the desired text or URL into the input field.
Click the "Generate QR Code" button.
Your QR code will be generated and displayed on the screen.
Script Explanation
The QR code generator is implemented in the script.js file. Here's a brief overview of how it works:

The script listens for a click event on the "Generate QR Code" button.
When the button is clicked, it retrieves the value entered into the input field.
If the input value is not empty and different from the previous value, it generates a QR code using the entered text or URL.
The QR code is generated using the https://api.qrserver.com API.
Once the QR code image is loaded, it is displayed on the screen.
The script also listens for keyup events in the input field. If the input field becomes empty, it hides the QR code.
Dependencies
This project does not have any external dependencies.

## License
This project is licensed under the MIT License - see the LICENSE file for details.
