# Product & Checkout E-Commerce Template

Product & Checkout E-Commerce Template is an HTML/ CSS template including some pages which are product, cart, address, shipping and payment detail pages. This template has been prepared by using Sass/SCSS and LiquidJS.

**Pages**
- Product Detail
- Cart
- Address 
- Shipping
- Payment

## [Demo website](https://product-checkout-e-commerce-template.vercel.app/)

# Project Structure

css/main.css file is created from main.scss file which is inside the scss folder. 
main.scss file is used to import the other scss files. CSS codes of the pages are included in the scss/pages and scss/components/pages folders. CSS codes of the header are included in the scss/global folder. CSS codes of the common components of the website are included in the scss/components.

LiquidJS is used as a template engine.
Files of the template are in the views folder.
Files in the views/pages folder are extended from the file called views/master.liquid. HTML codes of the common components of the website are included in the views/components which is in the views folder.

## Installation

```bash
git clone https://github.com/hey-fk/product-checkout-e-commerce-template
cd product-checkout-e-commerce-template
npm install or yarn install
```

## Start the server

```bash
gulp
```

Now enter [`localhost:3000`](http://localhost:3000) in the address bar of your browser.

## Dist Folder

```bash
gulp dist
```

Production files will be prepared in /dist folder.

## Deploy Vercel

Build Command
```bash
gulp dist
```

Output Directory
```bash
dist
```

## Contributing

Did you found a bug or got an idea for a new feature? Feel free to use the [issue tracker](https://github.com/hey-fk/product-checkout-e-commerce-template/issues) to let me know. Or make directly a [pull request](https://github.com/hey-fk/product-checkout-e-commerce-template/pulls).

## Credits

Design: [Furniture Store - E-commerce Freebie by Huzefa Bagwala](https://dribbble.com/shots/15009361-E-Commerce-Website-Furniture)

## License

This template is released under the MIT License.