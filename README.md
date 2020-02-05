# cs767
Producing the lambda_function.py and interactive_model.json for "Say Hello Alexa"

1. A new intent must be created that can handle raw-text inputs from the user. We called this intent 'AskDeepPavov' which has an intent slot "raw_input" (Source: http://docs.deeppavlov.ai/en/master/integrations/amazon_alexa.html). The interactive_model.json can be retrieved from the JSON editor in the Alexa Developer Console -> Build tab.
2. Go to Console -> Code tab to create a handler class for the 'AskDeepPavov' intent. This handler will make Alexa repeat what you said with "You Said (your input)." (Found code to do this on Stack Overflow - https://stackoverflow.com/questions/54150434/how-to-check-and-get-alexa-slot-value-with-python-ask-sdk)
3. Install all dependencies via AWS cli and upload zip of code to Lambda function.
4. Add trigger to Alexa and give Alexa developer console arn of Lambda function.
5. Save and build model.
6. Test in "Test" tab.
7. Test using Echoism.io to see how it would react to actual audio input. 
