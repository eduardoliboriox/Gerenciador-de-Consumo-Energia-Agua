# 🧮 Consumption Manager – Energy, Water, and Bills

A simple and functional web application to record, calculate, and track real **electricity**, **water**, and **monthly bills** consumption. Developed with **Python + Flask**, featuring a responsive interface with **Bootstrap 5**.

Check out the live application via the link at the end of this README.md.

---

## 🚀 Features

### 🔌 Energy Simulator

* Calculates consumption using current and previous readings
* Applies tariff per kWh
* Allows inclusion of fixed fees
* Displays consumption summary and total cost

### 💧 Water Simulator

* Calculates consumed units
* Shows estimated total
* Simple and responsive interface

### 🧾 Real Bills

* Records electricity and water bills
* Stores amount, reference period, and reported consumption
* Organized interface with cards

### 📊 History

* Lists previous records
* Allows viewing past data
* Presented in a clean, modern table

---

## 🛠️ Technologies

* **Python 3**
* **Flask**
* **HTML5**
* **Bootstrap 5**
* **Custom CSS**
* **Jinja2 Templates**

---

## 📂 Project Structure

```
water-energy-manager/
├─ static/
│   ├─ logo.png    - no logo
│   └─ style.css   
├─ templates/ 
│   ├─ agua.html
│   ├─ base.html
│   ├─ contas.html
│   ├─ energia.html
│   ├─ historico.html
│   └─ index.html
├─ app.py
├─ consumos.json
├─ ping.py
├─ Profile  
├─ README.md
├─ README.EN.md
├─ requirements.txt
```

---

## 📁 How to Run

```bash
pip install -r requirements.txt
python app.py
```

---

## 🔗 Access the System (Deployment)

The system is available online via Render.
Countermeasures are applied even in the free version to prevent inactivity shutdown. If it closes, wait 50 seconds and reopen.

➡️ **[https://water-energy-manager.onrender.com](https://water-energy-manager.onrender.com)**

---

## 👨‍💻 Author

* Developed by **Eduardo Libório**
* 📧 [eduardosoleno@protonmail.com](mailto:eduardosoleno@protonmail.com)

---
