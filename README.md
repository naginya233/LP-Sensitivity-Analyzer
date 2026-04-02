# Linear Programming Sensitivity Analyzer

> An Interactive, Web-Based Tool for Linear Programming & Sensitivity Analysis

## 📌 Overview

This project is an advanced, purely frontend-based web application tailored for Operations Research. It visualizes **2D Linear Programming (LP)** problems, computes optimal solutions in real-time, and provides extensive sensitivity analysis including shadow prices and feasible region bounds.

Aimed at students, educators, and researchers, this tool provides an intuitive graphical interface that requires no continuous server backend communication—everything runs smoothly within your browser.

## 🚀 Key Features

- **Interactive Canvas Rendering**: Dynamic, colored rendering of the feasible region, multiple constraints, and the gradient/contour of the Objective Function.
- **Parametric Adjustments (Real-Time)**:
  - **Objective Function Coefficients (C)**: Adjust the value/weight associated with each decision variable via sliding controls.
  - **Right-Hand Side Constraints (b)**: Expand or tighten resource constraints and see the feasible region shrink or grow immediately.
  - **Technical Coefficients (A)**: Hand-tune the precise coefficients matrix without reloading the page.
- **Intelligent Sensitivity Analysis**:
  - Automatically calculates and lists **Slack/Surplus** values or notes if a constraint is **Binding**.
  - Produces real-time **Shadow Prices (λ)** indicating the marginal value of unit changes to active constraints.
- **Smart Insights**: Automatically categorizes constraints and suggests deeper Operations Research insights.

## 💻 Tech Stack

- **HTML5 & Vanilla JavaScript**: Pure client-side calculations and matrix projections.
- **HTML Canvas API**: Used for 2D geometrical rendering.
- **CSS3 Layouts**: Fully responsive interface using Grid, Flexbox, and CSS Multi-col features suited for multi-device support.

## 🛠️ Usage

To use the tool, you only need a modern web browser:

1. Clone this repository to your local machine.
2. Open the file `1.html` in your web browser of choice.
3. Use the sidebar to interactively adjust parameters and observe real-time chart interactions.

## 📝 About the Files

- `1.html`: The monolithic file containing complete logic, interface constraints, styles, and the rendering loop.
- `1.tex`: Associated LaTeX source logic documentation for this homework/task.

## 📄 License

This project was developed as a course/homework submission for Operations Research (OperationsResearch) studies. Open for educational re-use.
