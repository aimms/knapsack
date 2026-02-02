# Knapsack Problem 

[![Downloads](https://img.shields.io/github/downloads/aimms/knapsack/total?style=for-the-badge&logo=github&labelColor=000081&color=1847c9)](https://github.com/aimms/knapsack/releases)
![AIMMS Version](https://img.shields.io/badge/AIMMS-24.5-white?style=for-the-badge&labelColor=009B00&color=00D400)
![WebUI Version](https://img.shields.io/badge/WebUI-24.10.3.3-white?style=for-the-badge&labelColor=009B00&color=00D400)
![Excel Integration](https://img.shields.io/badge/AXLL-24.0.0.2-white?style=for-the-badge&labelColor=009B00&color=00D400)

This repository contains a functional AIMMS example for the classic **Knapsack Problem**. It demonstrates how to select an optimal subset of items to maximize total value without exceeding the maximum weight capacity of the knapsack.

## 🎯 Business Problem

The knapsack problem is a fundamental optimization challenge used in resource allocation, portfolio selection, and loading scenarios. This model helps address:
- **Value Maximization:** Selecting items that provide the highest accumulated return.
- **Capacity Constraints:** Respecting strict weight limits of the container.
- **Quantity Management:** Handling variants where items can be unique (Binary), limited (Bounded), or unlimited (Unbounded).

## 📖 How to Use This Example

To get the most out of this model, we highly recommend reading our detailed step-by-step guide on the AIMMS How-to website:

👉 **[Read the Full Article: Knapsack Problem Guide](https://how-to.aimms.com/Articles/390/390-knapsack-problem.html)**

### Prerequisites
- **AIMMS:** You will need AIMMS installed to run the model. [Download the Free Academic Edition here](https://www.aimms.com/support/licensing/) if you are a student.
- **WebUI:** This model is optimized for the AIMMS WebUI for a modern, browser-based experience.

### Technical Highlights
- **Dynamic Solving:** A single algebraic model that handles three types of solve (Classic, Unbounded, and Bounded) by dynamically modifying variable bounds.
- **Data Integration:** Uses the **AXLL library** for seamless Excel import and export of item data.
- **Randomization:** Includes procedures to randomize data sets for testing and playful exploration.
- **WebUI:** This model features advanced UI widgets, including Sliders, Multiselectors, and data-dependent CSS styling for an interactive experience.

## 🚀 Getting Started

1. **Download the Release:** Go to the [Releases](https://github.com/aimms/knapsack/releases) page and download the `.zip` file from the latest version.
2. **Open the Project:** Launch the `.aimms` file.
3. **Run the Model:** Use the WebUI workflow to randomize data, import from Excel, and solve using different knapsack variants.

## 🤝 Support & Feedback

This example is maintained by the **AIMMS User Support Team**.
- Found an issue? [Open an issue](https://github.com/aimms/knapsack/issues).
- Questions? Reach out via the [AIMMS Community](https://community.aimms.com).

---
*Maintained by the AIMMS User Support Team. We optimize the way you build optimization.*
