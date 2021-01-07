## TipCalculator

Calculate Tip     | Calculator
-------------     | -------------
Total Tip in %    |  tip / 100
total_tip_amount  |  bill * tip_as_percent
total_bill        |  bill + total_tip_amount
bill_for_person   |  total_bill / No of People
final_amount      |  round(bill_per_person, 2)
final_amount      |  "{:.2f}".format(bill_per_person)
print             |  print(f"Each person should pay: ${final_amount}")
