# PhonePe-Transaction-Analysis

## Objectives
- Analyze total transaction volume and amount over time  
- Compare successful vs failed transactions  
- Identify services with high failure rates  
- Understand common reasons for payment failures  
- Provide actionable insights to improve payment reliability  


## Dataset Overview
The dataset contains PhonePe transaction records including:

- **User Information:** User ID, join date  
- **Transaction Details:** Transaction ID, amount, date  
- **Service Type:** Insurance, Loans, Money Transfer, Recharge & Bills  
- **Payment Status:** Successful / Failed  
- **Failure Reasons:** Server error, incorrect PIN, insufficient balance, bank declined  


## Tools Used
- **Excel** – Data cleaning, validation, and preprocessing  
- **Tableau** – Dashboard creation and visual analysis  


## Dashboards

### 1️⃣ Overall Dashboard
- Total transaction amount  
- Total number of transactions  
- Successful vs failed transaction ratio  
- Failed transaction reasons  
- Date-level filtering  

![Overall Dashboard](screenshots/overall-1.png)

---

### 2️⃣ Insurance Dashboard
- Insurance transaction trends  
- Success vs failure distribution  
- Failure reason analysis  

![Insurance Dashboard](screenshots/Insurance-2.png)

---

### 3️⃣ Loans Dashboard
- Loan transaction volume over time  
- Loan category comparison  
- Failed transaction breakdown  

![Loans Dashboard](screenshots/Loans-3.png)

---

### 4️⃣ Money Transfer Dashboard
- Monthly transaction trend  
- Success vs failure comparison  

![Loans Dashboard](screenshots/Money-transfer-4.png)

---

### 5️⃣ Recharge & Bills Dashboard
- Recharge vs bill payment comparison  
- Monthly transaction volume  

![Loans Dashboard](screenshots/Bill&Recharge-5.png)


## Key Insights
- A significant share of failed transactions is caused by **server errors and incorrect payment details**
- **Loans and Insurance services** contribute the highest transaction values
- Certain services show repeated failure spikes during specific periods
- Improving reliability in high-failure services can directly increase successful transactions

