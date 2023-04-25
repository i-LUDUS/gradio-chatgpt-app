## Beschrijving

Deze app is een Chatbot-gebruikersinterface die de OpenAI ChatGPT-API gebruikt om reacties op tekstinvoer te geven.
Het wordt gelanceerd met behulp van de Gradio-bibliotheek, waarmee de gebruiker tekstvragen kan invoeren vanuit een mooie interface en antwoorden van de chatbot kan ontvangen.

![image](./chat-screenshot.png)

## Installatie van de afhankelijkheden

Start installlatie van de afhankelijkheden via het commando:
```bash
pip install -r requirements.txt
```

## API Sleutel

De app heeft een OpenAI API-sleutel nodig om te werken.
Om het te specificeren, maakt u een .env-bestand en schrijft u uw OpenAI API-sleutel
```bash
OPENAI_API_KEY=XXXXXXXXX
```

## Start de App

Start de app via het commando:
```bash
gradio mywebgpt.py
```

Vervolgens kunt u uw app zien op de url `http://127.0.0.1:8080/`.
