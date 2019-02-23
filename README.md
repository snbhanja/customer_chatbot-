# customer_chatbot-
customer_chatbot built with RASA stack

# Setup instructions are in setup.txt file.

# Steps to run:
python nlu_model.py

Create the dialogue model. Comment out the run_customer_bot() method inside the __main__. Then run below command.
python dialogue_management_model.py

Now uncomment the run_customer_bot() method at __main__ and comment out the train_dialogue() method. Then run below again.
python dialogue_management_model.py
