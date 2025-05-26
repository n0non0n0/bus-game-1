# Business game
Feel free to test and make issues to fix. THis game is a vending machine game to get $10,000. Listed HEre is technical details. 
**Discord:** https://discord.gg/f24xzhUD
**Game:** https://lbozo1000.neocities.org/QnVzaW5lc3NfMDFB/sim1
**The same exact Game link, just in case something happens:** https://lbozo1000.neocities.org/QnVzaW5lc3NfMDFB/sim1.htm
------------------------------------------------
## Technical Details
### Business
- The goal is based upon the difficulty, calculated as $200,000 time the difficulty, minus -100,000.
- Each 'turn' is calculated as one day in real life.
- the difficulty is reversed- 3 is the easies, 2 is moderate, and 1 is Hard
### Employees
- Each employee must be 0, or greater
- If the employee amounts are 0, except for the owners which there need to be at least 1, the pay is calculated as 0.
#### Types
- THere are 12 types of employees.
  ##### employees
  
  ##### managers
  
  ##### senior managers
  
  ##### vice director
  
  ##### director
  
  ##### vice president
  
  ##### president
  
  ##### minor executive
  
  ##### major executive
  
  ##### Owner
    - There can be more than one, with a combined share of 100% of the company. When creating the business, the first employee is the     owner.
  ##### The board
  
  ##### chairman

  #### Morale
  - Morale starts at 100
  #### Pay deductions
  ##### Healthcare
  Hard:.04, Moderate/Medium: .07 Easy:.0355
  ##### Cost of Living
  The starting cost of living that will be deducted is 1775.5. For each difficulty increase, the value will increase by $150, then it is divided by 365.
##### Taxes and retirement
|pay(per year)|tax|retirement|
--------------------
|less than 10000|10%,plus 5% per increase in difficulty|7%, plus 2.5% per difficulty level

        } else if (grossPay <= 40000) {
            tax = 0.15 + 0.05 * (maxDV - dV);
            retirement = 0.1 + 0.03 * (maxDV - dV);
            healthcare *= 1.1;
            living -= 300;
        } else if (grossPay <= 80000) {
            tax = 0.18 + 0.05 * (maxDV - dV);
            retirement = 0.11 + 0.02 * (maxDV - dV);
            living -= 400;
        } else if (grossPay <= 110000) {
            tax = 0.22 + 0.05 * (maxDV - dV);
            retirement = 0.125 + 0.03 * (maxDV - dV);
            living -= 500;
        } else {
            tax = 0.25 + 0.1 * (maxDV - dV);
            retirement = 0.15 + 0.04 * (maxDV - dV);
            living = 2100 + ((maxDV - dV) * 600);
        }
  ##### Tax 
  THe tax starts at 10%, with a 1% increase per employee level, then finally multiplied by the difficulty.
  ##### Retirement
  The retirement starts at 5%, increases by 1% per employee level, then also multiplied by the difficulty


  
