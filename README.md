### In progress...

This is a [Dialogflow](https://dialogflow.cloud.google.com/) chatbot project for a jewellery. The idea is to attend customers when willing to confirm or schedule a visit for different purposes:
- Repair a piece of a jewel
- Replace a battery
- ...

We created the **intents** foler, where we set up the most common situations we are going to deal with our customers, and the **entities** folder, in which there are the different topics we are going to duscuss with our customer.
It is important to specify that there are some entities set as "required" so the customer will be asked about them in case the information is not provided.

For example:
* @sys.date (day of the week)
* @sys.person (name)
* @sys.date-time (time)
* @joya (jewel)
