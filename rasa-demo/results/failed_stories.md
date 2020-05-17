## happy path 1 (/tmp/tmp1yef9246/f52b0b14a39c4bfdb44691d3baa791f1_conversation_tests.md)
* greet: hello there!   <!-- predicted: ask_detail: hello there! -->
    - utter_greet   <!-- predicted: utter_goodbye -->
* mood_great: amazing   <!-- predicted: ask_date: amazing -->
    - utter_happy   <!-- predicted: utter_goodbye -->


## happy path 2 (/tmp/tmp1yef9246/f52b0b14a39c4bfdb44691d3baa791f1_conversation_tests.md)
* greet: hello there!   <!-- predicted: ask_detail: hello there! -->
    - utter_greet   <!-- predicted: utter_goodbye -->
* mood_great: amazing   <!-- predicted: ask_date: amazing -->
    - utter_happy   <!-- predicted: utter_goodbye -->
* goodbye: bye-bye!   <!-- predicted: ask_detail: bye-bye! -->
    - utter_goodbye


## sad path 1 (/tmp/tmp1yef9246/f52b0b14a39c4bfdb44691d3baa791f1_conversation_tests.md)
* greet: hello   <!-- predicted: ask_detail: hello -->
    - utter_greet   <!-- predicted: utter_goodbye -->
* mood_unhappy: not good   <!-- predicted: ask_detail: not good -->
    - utter_cheer_up   <!-- predicted: utter_goodbye -->
    - utter_did_that_help
* affirm: yes   <!-- predicted: ask_detail: yes -->
    - utter_happy   <!-- predicted: utter_goodbye -->


## sad path 2 (/tmp/tmp1yef9246/f52b0b14a39c4bfdb44691d3baa791f1_conversation_tests.md)
* greet: hello   <!-- predicted: ask_detail: hello -->
    - utter_greet   <!-- predicted: utter_goodbye -->
* mood_unhappy: not good   <!-- predicted: ask_detail: not good -->
    - utter_cheer_up   <!-- predicted: utter_goodbye -->
    - utter_did_that_help
* deny: not really   <!-- predicted: ask_detail: not really -->
    - utter_goodbye


## sad path 3 (/tmp/tmp1yef9246/f52b0b14a39c4bfdb44691d3baa791f1_conversation_tests.md)
* greet: hi   <!-- predicted: ask_detail: hi -->
    - utter_greet   <!-- predicted: utter_goodbye -->
* mood_unhappy: very terrible   <!-- predicted: ask_detail: very terrible -->
    - utter_cheer_up   <!-- predicted: utter_goodbye -->
    - utter_did_that_help
* deny: no   <!-- predicted: ask_date: no -->
    - utter_goodbye


## say goodbye (/tmp/tmp1yef9246/f52b0b14a39c4bfdb44691d3baa791f1_conversation_tests.md)
* goodbye: bye-bye!   <!-- predicted: ask_detail: bye-bye! -->
    - utter_goodbye


## bot challenge (/tmp/tmp1yef9246/f52b0b14a39c4bfdb44691d3baa791f1_conversation_tests.md)
* bot_challenge: are you a bot?   <!-- predicted: ask_detail: are you a bot? -->
    - utter_iamabot   <!-- predicted: utter_goodbye -->


