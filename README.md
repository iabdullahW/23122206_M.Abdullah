# 23122206 Muhammad Abdullah


Intelligent Agents Assignment

AI Study Preparation & Paper Prediction Agent

This repository contains my Intelligent Agents assignment and a small Python demonstration of a basic decision-making travel agent.

The main assignment presents an AI Study Preparation & Paper Prediction Agent. The proposed agent analyzes study material, lecture notes, course guides, and past papers to identify recurring topics and help students create a prioritized study plan. The prediction is treated as an evidence-based estimate rather than a guarantee of the exact examination paper.

Repository Contents

AI_Study_Preparation_Agent_Professional.pdf — Complete assignment report.

travel_agent_ai.ipynb — Google Colab notebook containing the basic Python agent.

travel_agent_ai.py — Standalone Python version of the same example.

README.md — Project overview and instructions.

Basic Travel Agent Example

The Python example demonstrates a simple decision rule:

If payment is completed, the system generates a receipt.

If payment is not completed, the system displays a payment-pending message.

payment_done = True
customer = "Ali"
amount = 25000
if payment_done:
    print(f"Receipt generated for {customer}: PKR {amount}")
else:
    print("Payment not done. Please complete payment first.")

This is intentionally a very small rule-based example. In intelligent-agent terms, the payment status is the percept/input, the if/else statement performs the decision, and the printed result is the action/output.

Run in Google Colab

After uploading this repository to GitHub, replace YOUR_USERNAME below with your GitHub username:

https://colab.research.google.com/github/YOUR_USERNAME/intelligent-agents-assignment/blob/main/travel_agent_ai.ipynb

You can also open the .ipynb file on GitHub and choose Open in Colab if that option is available.

Run Locally

Make sure Python 3 is installed, then run:

python travel_agent_ai.py

No external Python packages are required.

Suggested Repository Link

After creating the GitHub repository, your link should look like:

https://github.com/YOUR_USERNAME/intelligent-agents-assignment

Submission

For the Google Docs submission list, paste the public GitHub repository link. If your instructor also requests the Colab notebook link, include the Colab URL shown above after replacing YOUR_USERNAME.
