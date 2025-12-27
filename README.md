# Customer Support Ticket Triage System

This project is a simple Python program that helps manage customer support tickets.
It reads customer messages, finds the type of problem, decides how urgent the issue is, and sets a response time for the support team.
This project was done as part of a Week 1 internship assignment.

# What this project does

Reads customer support tickets from a CSV file  
Cleans the ticket text  
Classifies the issue type (Login, Payment, Delivery, etc.)  
Assigns priority levels (P0 to P3)  
Calculates SLA (time limit to respond)  
Generates a final report in CSV format  

# Priority and SLA

P0 – Very urgent issue → 2 hours  
P1 – High priority issue → 6 hours  
P2 – Medium priority issue → 24 hours  
P3 – Low priority issue → 48 hours  

SLA means *Service Level Agreement*.  
It defines how fast the support team should respond to a ticket.

# Tools and Technologies Used

- Python  
- Pandas  
- Google Colab  
- GitHub  

# Files in this repository

- `Week1_Customer_Support_Triage.ipynb` – Main Python notebook  
- `final_ticket_report.csv` – Output file with classified tickets  
- `README.md` – Project explanation  

# How to run the project

1. Open the notebook in Google Colab  
2. Upload the dataset (CSV file)  
3. Run all cells step by step  
4. The final report will be generated automatically  

# Conclusion

This project shows how basic Python and logic can be used to automate customer support ticket handling and improve response time.
