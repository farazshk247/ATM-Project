# Lab 8 - ATM Client

CSCI 2020U: Software Systems Development and Integration

## Overview

In this lab, you'll need to implement the functionality of these functions:

In `ATMThread.java`:

- `processWITH(String)` this function withdraws money from a user's account
    - In reality, this deducts the amount passed by the user from the `balances` hashmap

In `ATMClient.java`:

- `withdrawMoney()` this function reads user input and sends a request to the server to withdraw $x$ amount of money
- `createNewAccount()` this function creates a new account on the server

## Tasks

See each subdirectory for instructions on what to do.

```dir
src/main/java/org/example
   client/
      README.md
      ATMClient.java
      ATMGUI.java
   server/
      README.md
      ATMServer.java
      ATMThread.jva
```
>The auto grader will not check for correctness, this will be manually done.

## How to Submit

### Assignment Dropbox (Canvas)
- **Available:** Opens **2 days before** the lab session at **12:00 AM**  
  - Example: Lab on Monday → assignment opens Saturday at 12:00 AM
- **Due:** **End of your lab section**  
  - Example: 11:10 AM–12:30 PM lab → due at **12:30 PM**
- **Available Until:** **Start of the next lab session**  
  - Example: Next lab starts at **11:10 AM**
- Ensure the **assignment URL is updated** to this year’s version

---

## Grading

### In-Person Only

#### On Time (by the end of your lab section)
1. Submit your **assignment URL** to Canvas
2. Show your **completed lab assignment** to your **lab TA** for grading

---

#### Late (finished after the end of the lab session)
1. Submit your **assignment URL** to Canvas
2. **Do not make any changes** to your repository after your last commit
3. **Commits made after the Dropbox deadline will invalidate your submission**  
   - Your grade will be **0 (zero)**
4. Attend your **next lab session** and:
   - Show your TA the output of:
     ```bash
     git status
     ```
     (This proves no changes were made after the Dropbox deadline.)
   - Show your **completed lab assignment** to your lab TA for grading


The TA can provide oral feedback if you do not receive full marks for any lab assignment, but it is most
appropriate to ask the TA for this feedback in a timely fashion (i.e. ask now, not at the end of the term).
