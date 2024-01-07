# PDFKit Invoices

## Prerequisites

- [Node.js](http://nodejs.org/) (with npm or Yarn)

## Getting Started

There are two important fields in this this repository:

- [`index.js`](index.js) is the main entry point. It defines the data structure used to create the invoices.
- [`createInvoice.js`](createInvoice.js) exports a function that can be used to create invoice PDFs.

To get started, use the following commands:

```bash
git clone https://github.com/PSPDFKit-labs/pdfkit-invoice.git

npm install  # Install dependencies

npm start  # This will create an invoice.pdf file in the root of the project.
```

To learn more about this project, make sure to read the accompanying [blog post](https://pspdfkit.com/blog/2019/generate-invoices-pdfkit-node)

## Contributing

Please ensure
[you have signed our CLA](https://pspdfkit.com/guides/web/current/miscellaneous/contributing/) so that we can
accept your contributions.
