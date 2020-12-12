## happy path 1
* greet: नमस्ते
    - utter_greet   <!-- predicted: utter_welcome -->
* ask_date: BITSAT कब है
    - utter_dates   <!-- predicted: utter_bio -->
* bio_eligibility: बायोलॉजी के छात्र एलिजिबल हैं?
    - utter_bio   <!-- predicted: utter_foreign -->
* goodbye: ओके  बाई
    - utter_goodbye   <!-- predicted: utter_foreign -->


## happy path 2
* greet: हेलो
    - utter_greet   <!-- predicted: utter_welcome -->
* ask_iterations:एडमिशन से पहले कितनी पुनरावृत्तियाँ होंगी
    - utter_iterations   <!-- predicted: utter_bio -->
* ask_edit: अपने एप्लीकेशन फॉर्म में बदलाव कैसे करूँ
    - utter_edit   <!-- predicted: utter_foreign -->
* bio_eligibility:क्या मैं बायो के साथ बिट्सैट दे सकता हूं
    - utter_bio   <!-- predicted: utter_foreign -->
* goodbye: बाई
    - utter_goodbye   <!-- predicted: utter_foreign -->


## happy path 3
* greet: हेलो
    - utter_greet   <!-- predicted: utter_welcome -->
* ask_fee:शुल्क कितना है
    - utter_fee   <!-- predicted: utter_bio -->
* ask_mail:क्या मैं अपना आवेदन पोस्ट कर सकता हूं?
    - utter_mail   <!-- predicted: utter_foreign -->
* goodbye: बाई-बाई!
    - utter_goodbye   <!-- predicted: utter_foreign -->


## happy path 4
* greet: हे
    - utter_greet   <!-- predicted: utter_welcome -->
* foreign citizens: अंतर्राष्ट्रीय छात्रों की प्रक्रिया
    - utter_foreign   <!-- predicted: utter_bio -->
* ask_edit: एप्लीकेशन फॉर्म की गलतियां कैसे ठीक करूँ
    - utter_edit   <!-- predicted: utter_bio -->
* ask_mail:मेल द्वारा फॉर्म भेजें
    - utter_mail   <!-- predicted: utter_fee -->
* thank: ठीक है शुक्रिया
    - utter_welcome   <!-- predicted: utter_foreign -->


## say goodbye
* goodbye: बाई!
    - utter_goodbye   <!-- predicted: utter_welcome -->


