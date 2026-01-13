# 💰 Loan Calculator

A simple and responsive **Loan Calculator** built with **HTML, CSS, and JavaScript**.  
It helps users calculate their monthly loan payments based on loan amount, interest rate, and repayment period.

---

## 🚀 Features
- Clean and modern UI with gradient background 🎨
- Calculates **monthly payment** using the amortization formula
- Handles **zero-interest loans** correctly
- Displays **total payment** and **total interest** for better insights
- Responsive design for desktop and mobile

---

## 📂 Project Structure
Loan-Calculator/ │── index.html  
# Main HTML file │── style1.css
# External CSS (optional, inline styles included)
│── README.md  

# Project documentation

---

## 🧮 Formula Used
Monthly Payment is calculated using the standard loan amortization formula:

\[
M = \frac{P \cdot r \cdot (1+r)^n}{(1+r)^n - 1}
\]

Where:
- \(M\) = Monthly Payment  
- \(P\) = Loan Amount  
- \(r\) = Monthly Interest Rate (Annual Rate ÷ 12 ÷ 100)  
- \(n\) = Number of Months  

If interest rate = 0, then:
\[
M = \frac{P}{n}
\]

---

## 📸 Demo Screenshot
*(Add a screenshot of your calculator UI here once hosted or tested locally)*

---

## 🛠️ How to Run
1. Clone or download this repository.
2. Open `index.html` in your browser.
3. Enter loan details and click **Calculate**.
4. View monthly payment, total payment, and interest.

---

## 🔮 Future Improvements
- Add currency selection (₹, $, €, etc.)
- Include loan amortization schedule table
- Dark mode toggle 🌙
- Save calculations to local storage

---

## 👨‍💻 Author
**Ashish Kumar**  
Full Stack Developer passionate about building interactive and visually impressive web apps.  

---
