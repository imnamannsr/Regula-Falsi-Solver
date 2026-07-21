# Regula Falsi Numerical Solver

An interactive, high-precision web tool built to visualize root-finding using the Regula Falsi (False Position) numerical method.

🔗 **Live Tool:** [https://imnamannsr.github.io/Regula-Falsi-Solver/](https://imnamannsr.github.io/Regula-Falsi-Solver/)

---

## Origin & Context

This project originated as an offline classroom exercise during a mathematics lecture, where the goal was to write a script that calculates an approximate function root within a given interval `[a, b]`. 

To better visualize how the secant line repeatedly narrows down the bounds, I converted the core algorithm into an interactive web dashboard.

---

## Key Features

* **Dynamic Function Parser:** Evaluates mathematical expressions with functions like `log10(x)`, `sin(x)`, `pow(x, n)`, and custom operators.
* **Convergence Matrix:** Displays step-by-step iteration logs (bounds, root approximations, and functional evaluations) up to 12 decimal places.
* **Real-time Plotting:** Uses Chart.js to map functional curves and plot calculated roots.
* **High Precision:** Configurable tolerance thresholds down to $10^{-10}$ with a 10,000 max-iteration safety ceiling.

---

## How to Run Locally

Because this project is built as a single-page web app using Tailwind CSS and Chart.js via CDN, no local build tools or dependencies are required:

1. Clone or download this repository.
2. Open `index.html` directly in any web browser.
