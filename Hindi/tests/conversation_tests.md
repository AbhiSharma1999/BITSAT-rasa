#### This file contains tests to evaluate that your bot behaves as expected.
#### If you want to learn more, please see the docs: https://rasa.com/docs/rasa/user-guide/testing-your-assistant/

## happy path 1
* greet: नमस्ते 
  - utter_greet
*ask_date: BITSAT कब है
  - utter_dates
* bio_eligibility: बायोलॉजी के छात्र एलिजिबल हैं?
  - utter_bio
*goodbye: ओके  बाई 
  - utter_goodbye

## happy path 2
* greet: हेलो 
  - utter_greet
* ask_iterations:एडमिशन से पहले कितनी पुनरावृत्तियाँ होंगी 
  - utter_iterations
*ask_edit: अपने एप्लीकेशन फॉर्म में बदलाव कैसे करूँ
  - utter_edit
* bio_eligibility:क्या मैं बायो के साथ बिट्सैट दे सकता हूं
  - utter_bio
* goodbye: बाई 
  - utter_goodbye

## happy path 3
* greet: हेलो 
  - utter_greet
* ask_fee:शुल्क कितना है
  - utter_fee
* ask_mail:क्या मैं अपना आवेदन पोस्ट कर सकता हूं?
  - utter_mail
* goodbye: बाई-बाई!
  - utter_goodbye

## happy path 4
* greet: हे
  - utter_greet
* foreign citizens: अंतर्राष्ट्रीय छात्रों की प्रक्रिया
  - utter_foreign
* ask_edit: एप्लीकेशन फॉर्म की गलतियां कैसे ठीक करूँ 
  - utter_edit
* ask_mail:मेल द्वारा फॉर्म भेजें
  - utter_mail
* thank: ठीक है शुक्रिया
  - utter_welcome


## say goodbye
* goodbye: बाई!
  - utter_goodbye

