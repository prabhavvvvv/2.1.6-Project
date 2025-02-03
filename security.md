# 2.1.6 Debugging Project 
## Partners: Aditya, and Prabhav

### Initial Errors from email
- Camila gotma malicious email fromm "update@fishtankmontors.com," leading to her being provided false information that could have killed all the fish

### Code errors
1. Alkanity.py -> The range of the values from v1 and v2 were reveresed (17, 12) - it should be 12-17 rather than 17-12 
2. Magnesium.py -> The index was out of the range for for num levels, so we had to subtract the num levels by 1 each time
3. Temperature.py -> The previous num readings was divided by 0, which is not possible. Instead, we divided by the num of readings, which was evidently 6.
