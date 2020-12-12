#### This file contains tests to evaluate that your bot behaves as expected.
#### If you want to learn more, please see the docs: https://rasa.com/docs/rasa/user-guide/testing-your-assistant/

## happy path 1
* greet: hi
  - utter_greet
*ask_date: when is bitsat
  - utter_dates
*ask_edit: how to change my form
  - utter_edit
*goodbye: okay bye
  - utter_goodbye

## happy path 2
* greet: hello
  - utter_greet
* ask_iterations:how many iterations occur before allocation
  - utter_iterations
* bio_eligibility: Can I give BITSAT with Bio
  - utter_bio
* goodbye: bye-bye!
  - utter_goodbye

## happy path 3
* greet: hello
  - utter_greet
* ask_fee: how much is the fee
  - utter_fee
* ask_mail:can i post my application
  - utter_mail
* goodbye: bye-bye!
  - utter_goodbye

## happy path 4
* greet: heyo
  - utter_greet
* foreign citizens: international students process
  - utter_foreign
* ask_date: when is bitsat scheduled to be held?
  - utter_dates
* ask_mail: send form by mail
  - utter_mail
* thank: okay thanks
  - utter_welcome


## say goodbye
* goodbye: bye-bye!
  - utter_goodbye

