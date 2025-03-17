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
#### Prerequisites  
- Ensure you have **Python** installed on your system.  
#### Setup  
1. Clone the repository:  
   ```bash
   git clone https://github.com/yourusername/mpesa-integration.git
   cd mpesa-integration
   ```  
2. Create and activate a virtual environment:  
   - For Linux and macOS:  
     ```bash
     python3 -m venv venv
     source venv/bin/activate
     ```  
   - For Windows:  
     ```bash
     python -m venv venv
     venv\Scripts\activate
     ```  
3. Install Django and dependencies:  
   ```bash
   pip install django  
   pip install requests  
   ```  
4. Set up environment variables (API keys, shortcodes, etc.).  
5. Run database migrations:  
   ```bash
   python manage.py migrate
   ```  
6. Start the server:  
   ```bash
   python manage.py runserver
   ```  
Here's the **Usage** section formatted with numbering:  

---

## Usage  
1. Apply database migrations:  
   ```bash
   python3 manage.py migrate
   ```  
2. Start the development server:  
   ```bash
   python3 manage.py runserver
   ```  
3. Open your browser and navigate to:  
   `http://127.0.0.1:8000/`  
4. Enter payment details and initiate an **M-Pesa STK push request**.  
5. Confirm the transaction on your mobile phone.  



## License

MIT Licence.
