# 23122206 M.Abdullah
# Intelligent Agents Assignment

## AI Study Preparation & Paper Prediction Agent

**Student Name:** Muhammad Abdullah  
**Roll Number:** 23122206 
**Section:** A
**Semester:** 6

---

## Project Overview

This repository contains my **Intelligent Agents assignment** along with a small Python-based example of TRAVELAGENT that demonstrates a simple decision-making.

The main project focuses on an **AI Study Preparation & Paper Prediction Agent**. The purpose of this agent is to analyze study material, lecture notes, course guides, and previous examination papers to identify recurring topics and question patterns AND CAN PREDICT LIKELY GUESS PAPER.

Based on this information, the agent can help students prioritize important topics and prepare a more focused study plan.

The predicted topics are treated as **evidence-based recommendations**, not as a guarantee of the exact examination paper.

---

## Repository Contents

| File | Description |
|---|---|
| `AI_Study_Preparation_Agent.pdf` | Complete Intelligent Agents assignment report |
| `M_Abdullah_Lab1.ipynb` | Google Colab notebook containing the Travel Agent example |
| `README.md` | Project documentation and instructions |

---

## Basic Travel Agent Example

As a small practical example, I created a simple rule-based Travel Agent.

The agent checks whether a customer's payment has been completed.

- If the payment is complete, the system generates a receipt.
- If the payment is incomplete, the system asks the customer to complete the payment first.

### Python Code

```python
payment_done = True      
customer = "Ali"
amount = 25000

if payment_done:
    print(f"Receipt generated for {customer}: PKR {amount}")
else:
    print("Payment not done. Please complete payment first.")        
