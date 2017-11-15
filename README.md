# Django Rasa Core Server

[Rasa Core](https://core.rasa.ai) uses yaml files to design conversation flow. I wanted a better way to visualize and handle large data sets during bot training and this is where this project comes handy.

## Training your models

After designing your knowledge base, you need to train for it to take effect. The following command does the magic (Not magic really but it simply wraps what Rasa core does [here](https://core.rasa.ai/tutorial_basics.html#put-the-pieces-together))

    python manage.py train

## Todo list

- Django admin modelling of NLU training
- Django admin modelling of Rasa core dialog flows i.e stories etc
- Alternate API server to handle requests
- Wrapping of Rasa Core and Rasa NLU to this project