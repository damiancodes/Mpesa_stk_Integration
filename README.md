# Mpesa Integration Project

![STK Push Home Screen](https://github.com/damiancodes/Mpesa_stk_Integration/blob/master/stkpushapp/static/images/payhere.png)

This project implements Mpesa integration with two main components:
- STK Push
- Payhere

## STK Push

The STK Push feature allows users to initiate Mpesa payments directly from their phones.

![STK Push Home Screen](https://github.com/damiancodes/Mpesa_stk_Integration/blob/master/stkpushapp/static/images/payhere.png)

## Successful Transaction

When a transaction is completed successfully, users will see a confirmation screen.

![Successful Transaction](https://github.com/damiancodes/Mpesa_stk_Integration/blob/master/stkpushapp/static/images/success.png)

## Home

The Home feature provides an alternative payment method for users.

![Payhere Interface](https://github.com/damiancodes/Mpesa_stk_Integration/blob/master/stkpushapp/static/images/homestk.png))

## Getting Started

I highly recommend to get used to using Linux if you still on the blue screen....huuh!!

## Configuration
git clone 
cd mpesa_stk_integration
python3 -m venv venv
source venv/bin/activate    for linux and mac users!!!!
pip install django
pip istall requests.
N/B:ensure you have python on your system.

## Usage
python3 manage.py migrate
python3 manage.py runserver
Navigate to http://127.0.0.1:8000/.
Enter payment details and initiate an M-Pesa STK push request.
Confirm the transaction on your mobile phone



## License

MIT Licence.
