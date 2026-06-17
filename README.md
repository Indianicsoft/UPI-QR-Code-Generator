# UPI QR Code Generator

A lightweight open-source UPI QR code generator built with vanilla HTML, CSS, and JavaScript. Jua

Complete Payment Gateway is Closed-Source!

## Features
- Generate UPI payment QR codes instantly
- Vanilla JS only
- Easy to embed in any website
- Mobile-friendly and responsive
- No framework required 

## Demo
Add a screenshot or GIF here.

## Usage
```html
<script src="upi-qr-lib.js"></script>
<script>
  const uri = UPIQRGenerator.buildUPIUri({
    upiId: "merchant@okaxis",
    name: "Demo Store",
    amount: 499,
    note: "Payment for order"
  });
</script>
```

## Installation
1. Clone the repository.
2. Open `index.html` in your browser.
3. Use the JS file in your project.

## Contributing
Pull requests and issues are welcome.

## License
MIT
