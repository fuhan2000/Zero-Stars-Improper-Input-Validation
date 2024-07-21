# Zero-Stars-Improper-Input-Validation

## What I have learned from Hacksplained’s Zero Stars (Improper Input Validation).

- Typically, the Rating on the OWASP Juice Shop is from 1 to 5. When you click "Submit" in Ref 1, Burp Suite will display a "rating" of 1.

<img src="https://i.imgur.com/nXAM10Y.png" width="400" />

*Ref 1: "rating":1*

- If you change the rating to 0 (as in Ref 2),

<img src="https://i.imgur.com/CUlrm3O.png" width="400" />

*Ref 2: "rating":0*

- You will see "Thank you for your feedback" as in Ref 3. If there had been proper input validation, this problem would not have occurred.

<img src="https://i.imgur.com/IxZVn5Z.png" width="400" />

*Ref 3: Thank you for your feedback*
