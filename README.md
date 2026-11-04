# EasyEMI

A small web app for planning loan repayments: work out a monthly EMI, compare loan options, and check whether refinancing an existing loan saves money. Amounts are in rupees (₹).

## Pages

| Page | What it does |
| --- | --- |
| Dashboard (`dash.html`) | Home page linking to the tools |
| EMI Calculator (`emiplan.html`) | Sliders for loan amount, interest rate and years; shows monthly EMI, total payment and total interest, with a chart |
| Take a Loan (`takeloan.html`) | Compare loan options side by side |
| Refinancing (`finance.html`) | Compare a current loan with a refinance offer, with a total-payment chart |

## Tech stack

- Node.js + Express 5, serving static pages (`app.js`)
- HTML, CSS and plain JavaScript (`public/`)
- Tailwind CSS, Chart.js and Bootstrap Icons from CDNs

## Run it

Requires Node.js.

```sh
npm install
node app.js
```

Then open http://localhost:3000.

## Credits

Built by Team Vortex:

- Aditya Gorane ([@AdiGo112](https://github.com/AdiGo112))

## License

MIT. See [LICENSE](LICENSE).
