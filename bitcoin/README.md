# Actions on Google Webhook example for bitcoin-info codelab (using Node.js)

This webhook example for bitcoin-info codelab sets up everything you need to build your fulfillment
business logic for your API.AI bitcoin agent. 
It could fetch the current price, market cap or the total amount of bitcoins. 

#### Demo
* Check it live as Assistant App [Bitcoin Info](https://assistant.google.com/services/a/id/66888e9b751b325a/) or on the [web](https://ido-green.appspot.com/bots.html)
* Read more about it [here](https://greenido.wordpress.com/2017/06/14/a-bitcoiner-info-action/)
* (!) Psst... Want to get a cool intro to bitcoin? Checkout this [short video](https://www.youtube.com/watch?v=TN7cmfoH06w) I made.

![bitcoin logo](https://greenido.files.wordpress.com/2015/07/screenshot-2015-07-13-11-45-37.png?w=307&h=289)

## Setup Instructions

### Pre-requisites
 1. Dialogflow account: [https://dialogflow.com](https://dialogflow.com)
 2. Google Cloud project: [https://console.cloud.google.com/project](https://console.cloud.google.com/project) or you can use this [glitch template](https://glitch.com/edit/#!/aog-template) to have your webhook hosted on Glitch.
 
See the developer guide and release notes at [https://developers.google.com/actions/](https://developers.google.com/actions/) for more details.

### Steps
1. Create a new agent in API.AI [https://api.ai](https://api.ai). You can also take this repo as a zip and import it to API.AI
2. Deploy this action to your preferred hosting environment
 (we recommend [Google Cloud Functions](https://cloud.google.com/functions/docs/tutorials/http)).
3. Set the "Fulfillment" webhook URL to the hosting URL.
4. In any relevant intents (*price* and *total*), enable the Fulfillment for the response.
5. Build out your agent and business logic by adding function handlers for API.AI actions.
6. For each API.AI action, set a new key/value pair on the actionMap, reflecting
 the action name and corresponding function handler on the actionMap in **index.js**.
1. Make sure all domains are turned off.
1. Enable Actions on Google in the Integrations.
1. Provide an invocation name for the action.
1. Authorize and preview the action in the [web simulator](https://developers.google.com/actions/tools/web-simulator).

For more detailed information on deployment, see the [documentation](https://developers.google.com/actions/samples/).

## References and How to report bugs
* Actions on Google documentation: [https://developers.google.com/actions/](https://developers.google.com/actions/).
* If you find any issues, please open a bug here on GitHub.
* Questions are answered on [StackOverflow](https://stackoverflow.com/questions/tagged/actions-on-google).

## How to make contributions?
Please read and follow the steps in the CONTRIBUTING.md.

## License
See LICENSE.md.

## Terms
Your use of this sample is subject to, and by using or downloading the sample files you agree to comply with, the [Google APIs Terms of Service](https://developers.google.com/terms/).

## Google+
Actions on Google Developers Community on Google+ [https://g.co/actionsdev](https://g.co/actionsdev).

[![Analytics](https://ga-beacon.appspot.com/UA-65622529-1/bitcoin-info-action/)](https://github.com/igrigorik/ga-beacon)
