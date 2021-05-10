# This is a very rudimentary FAQ-bot for Golden Shoe.

It utilises Google's dialogflow API to bring an easy to edit, dynamic chatbot for FAQ/customer service purposes.

The API is integrated to a Django frontend, with a GCP database in the backend - the whole thing is driven by GCP App Engine.

Currently, it can only answer very simple questions -

## Basic Conversation

It'll communicate with things like "Hi" and "How are you", stuff like that - and some fun questions, feel free to play around.

## Actual FAQ

Since Google's language interpretation is **sheer magic**, the language doesn't need to be exact. For example, the "returns" question will yield the same result if the specific, hard-coded language is followed ("can i return an item") but will also understand _"May I return an item?"_. How incredible is that!

As this is just a proof of concept, I haven't scaled up the intents and Q+A protocol. However, to do would be extremely easy - it's essentially just a matter of busy work and tedium, everyone's two favourite activities.

## Currently Available Queries:

### Question:
why haven't i received my shoes/how long does delivery take/when will my shoes arrive/delivery

### Question:
can i pay with/payments/what can i pay with/how can i pay/what method of payments do you accept

### Question:
can i return an item/how do i return an item/returns/how do i make a return

### Question:
who is the worlds greatest graduate developer
