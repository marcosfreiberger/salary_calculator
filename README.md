# :fast_forward: Salary Calculator :rewind:

## 🖥 Preview

<p align = "center">
  <img src = "file:///C:/Users/Freiberger/Downloads/image.jpg" width = "700">
</p>

---

## 📖 About

Create, using React, an application named 'react-salario' that should be able to calculate the net salary from gross salary, considering the 2020 CLT rules.

---

## 🛠 Technologies used

- CSS
- HTML
- Javascript
- Class Components
- React
- Materialize
- Node.js

---

## 🔍Development Tips

- For the horizontal bar, use the Determinate Linear Preloader available on Materialize.

```
  <div class="progress">
      <div class="determinate" style="width: 20%"></div>
      <div class="determinate" style="width: 10%"></div>
  </div>
```

- As the bar shall be a sum of net salary and IRPF and INSS discounts, you can consider the background color as the net salary bar.
- For the other two bars, you will use the determinate class. Remember that the first one declared will be overlapped by the second. So a tip is to add the value to be presented in the latter to the former and set the calculated width to the former.
- For the percentages and currency formatting, use the Intl library.

```
const currencyFormatter = Intl.NumberFormat('pt-BR', { style: 'currency', currency: 'BRL' });
const percentageFormatter = Intl.NumberFormat('pt-BR', { style: 'percent', maximumFractionDigits: 2 });
```

---

## 🚀 How to execute the project

#### Clone the repository

git clone https://github.com/marcosfreiberger/salary_calculator

#### Enter directory

`cd SalaryCalculator`

#### Download dependencies

`yarn`

#### Run the server

`yarn start`

#### That done, open your browser and go to `https://localhost:3000/`

---

Developed with 💙 by Marcos N. Freiberger
