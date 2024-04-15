# ChatGPT App

**Learning Objective:** The purpose of the app is to apply AsyncTask to call Open AI LLM (ChatGPT 3.5 Turbo) model in the background and display response to the Android App.
**Open AI model used**- gpt-3.5-turbo

**Steps involved:**
1. Obtain an OpenAI secret key from https://platform.openai.com/api-keys.
2. Refer https://platform.openai.com/docs/api-reference for the api endpoint you want to use, and do a similar  HTTP POST request from the app.
3. Display the response of the API on UI.

**Testing:**

1. Set value for API secret in the MainActivity.java class
2. If possible, test the app on an android device. You might come across some errors while testing on emulator because of different environment settings.

# Screenshots:

Main Activity:

<img width="215" alt="image" src="https://github.com/RavirajWadnerkar/ChatGPTUIApp/assets/47893967/030406dd-1537-4973-b466-0f1ef07d9ac7">

Entering a prompt: 

<img width="235" alt="image" src="https://github.com/RavirajWadnerkar/ChatGPTUIApp/assets/47893967/fff162d8-894f-4b56-bca7-626324324928">

Response is displayed:

<img width="236" alt="image" src="https://github.com/RavirajWadnerkar/ChatGPTUIApp/assets/47893967/f25a40e8-c0c8-48e1-af95-2d8c763d0169">


