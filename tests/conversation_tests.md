#### This file contains tests to evaluate that your bot behaves as expected.
#### If you want to learn more, please see the docs: https://rasa.com/docs/rasa/user-guide/testing-your-assistant/



## path1
* greet: hey
  - utter_greet
* category: Student
  - utter_ask_id
* id: 123dsr345
  -utter_tell_id
  - action_fetch_name
* goodbye: bye
  - utter_goodbye