# cs767
Producing the lambda_function.py and interactive_model.json for "Say Hello Alexa"

1. A new intent must be created that can handle raw-text inputs from the user. We called this intent 'AskDeepPavov' which has an intent slot "raw_input" (Source: ). The interactive_model.json can be retrieved from the JSON editor in the Alexa Developer Console -> Build tab.
2. Go to Console -> Code tab to create a handler class for the 'AskDeepPavov' intent. This handler will make Alexa repeat what you said with "You Said (your input)." (Found code to do this on Stack Overflow)
3. Save and build model.
4. Test in "Test" tab.
