# Local Volatility Surface Estimation Using Nonparametric Methods

## Description

This project demonstrates the **estimation of local volatility surfaces** for **options pricing** using **nonparametric methods**. In the context of **quantitative analysis** (quant analysis), this process is essential for improving the **pricing accuracy** of options and understanding the underlying **market behavior**. By using **nonparametric techniques**, such as **Kernel Density Estimation (KDE)**, we can create a **flexible model** that doesn't rely on a fixed formula (like the **Black-Scholes model**), making it better suited for real-world market conditions.

### How Does This Project Align with Quantitative Analysis?

In quantitative finance, **accurate pricing** of **derivatives** (like options) is crucial for managing **financial risk** and making informed **investment decisions**. One of the challenges is accounting for the fact that **market volatility** can change over time and is often **non-linear**. This project addresses that challenge by:

- **Estimating the local volatility** at different levels of **strike prices** and **maturities**.
- **Modeling the volatility surface** to account for changes in the **term structure** (how volatility evolves over time) and the **volatility smile** (how volatility differs for options with different strikes).
- Using **nonparametric methods** like **Kernel Density Estimation (KDE)**, which doesn't rely on rigid assumptions about the volatility model, allowing for a more **realistic** and **flexible** approach.

### Key Features:
- **Nonparametric Estimation**: We use **Kernel Density Estimation (KDE)** to **estimate the local volatility** without assuming a specific model, which gives us a more flexible way to model the **volatility surface**.
- **Implied Volatility Extraction**: We extract **implied volatility** from **European call options** by using the **Black-Scholes model** and **Brent's method** to find the volatility implied by the market prices of the options.
- **Visualizations**: We create **visual representations** of both the **implied volatility surface** and the **local volatility surface**, making it easier to understand how volatility behaves at different strikes and maturities.

### Keywords for Quantitative Analysis:
- **Local Volatility Surface (LVS)**: A key concept in **option pricing** that shows how volatility changes with respect to **strike price** and **time to maturity**.
- **Nonparametric Methods**: Techniques that don't assume a specific functional form (such as Black-Scholes), offering more flexibility in modeling real-world data.
- **Kernel Density Estimation (KDE)**: A nonparametric way to estimate the probability distribution of a random variable, in this case, **local volatility**.
- **Implied Volatility**: The **market's expectation of future volatility**, calculated from current option prices. It is crucial for pricing and **risk management**.
- **Volatility Smile**: A pattern where **implied volatility** tends to be higher for both **in-the-money** (ITM) and **out-of-the-money** (OTM) options compared to **at-the-money** (ATM) options. This reflects real market behavior and is key for traders and analysts.

### Why This Matters for Quantitative Analysis:
1. **Accurate Option Pricing**: The project helps in improving option pricing by better modeling volatility, a core aspect of any quantitative finance strategy.
2. **Risk Management**: By understanding how volatility behaves under different conditions (e.g., strikes, maturities), quants can better manage risk in **portfolios** and **derivative instruments**.
3. **Real-World Relevance**: This project moves beyond theoretical models and provides practical insights into how volatility surfaces behave in **real markets**, which is crucial for anyone working in **quantitative finance**, **trading**, or **financial modeling**.

---

### Example Visualizations

Below are visualizations of the **local volatility surface** and **implied volatility surface**, which help visualize the relationships between **strike price**, **maturity**, and **volatility**.

<p align="center"
Local Volatility Surface <br/>
<img src="https://i.imgur.com/vXfPLxb.png" height="80%" width "80%" alt="Disk Sanitization Steps">
<br />
This 3D plot shows how volatility varies across different strikes and maturities.

<p align="center"
Implied Volatility Surface <br/>
<img src="https://i.imgur.com/ueVueQT.png" height="80%" width "80%" alt="Disk Sanitization Steps">
<br />
This shows the implied volatility based on market prices for different options.  
  
---

### How This Project Helps You:
This project is a useful tool for anyone working in **quantitative finance** or **financial engineering**. It provides a detailed, flexible approach to **pricing options**, which can be crucial for traders, **risk managers**, and financial analysts. By modeling the **local volatility surface**, it helps create a more realistic picture of how **market volatility** behaves, improving the decision-making process for **derivatives pricing** and **risk management** strategies.

---

## Installation and Setup

1. Clone this repository:
    ```bash
    git clone https://github.com/yourusername/Local-Volatility-Surface-Estimation.git
    cd Local-Volatility-Surface-Estimation
    ```

2. Install dependencies:
    ```bash
    pip install -r requirements.txt
    ```

---

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.


