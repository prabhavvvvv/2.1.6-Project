# 2.1.6 Debugging Project 
# Partners: Aditya, and Prabhav

## Initial Errors from email
- Camila gotma malicious email fromm "update@fishtankmontors.com," leading to her being provided false information that could have killed all the fish

## Code errors
1. Alkanity.py -> The range of the values from v1 and v2 were reveresed (17, 12) - it should be 12-17 rather than 17-12
   ## Before:
   ![image](https://github.com/user-attachments/assets/318bec5b-64bf-4173-8b21-f44200987c4d)
   ## After:
   ![image](https://github.com/user-attachments/assets/1fed41ac-46b3-422b-ab43-6c128c9b68ba)


2. Magnesium.py -> The index was out of the range for for num levels, so we had to subtract the num levels by 1 each time
   ## Before:
   ![image](https://github.com/user-attachments/assets/1cdb986a-88dd-4400-ab74-c42d6b7b672e)
   ## After:
   ![image](https://github.com/user-attachments/assets/8c1fd9bd-4669-4b5f-a826-7f7d6907dd65)


3. Temperature.py -> The previous num readings was divided by 0, which is not possible. Instead, we divided by the num of readings, which was evidently 6.
   ## Before:
   ![image](https://github.com/user-attachments/assets/f0d4a542-a211-41ca-8745-ec177d42107f)
   ## After:
   ![image](https://github.com/user-attachments/assets/93aae658-8af0-4be5-a482-39e0c2c8c1e6)

   

