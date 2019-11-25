# SlackAPI Reshuffle template

SlackAPI template for Reshuffle which includes a simple example bot. Uses [bolt](https://github.com/slackapi/bolt) under the hood, which is a succinct and powerful wrapper for the Slack API.

### Setting up the bot

The bot used in this example is Hubot, provided originally as a SlackAPI example. The instructions for setting up the bot can be found [here](https://github.com/slackapi/bolt/tree/master/examples/hubot-example) and are completely applicable. To respond to the challenge use your Reshuffle apps URL, and then redeploy your app with the tokens/secrets provided by Slack (see instructions below).

### Required environment variables

For the SlackAPI to function, the following values need to be set in your `.env`:

> Note: You'll need to deploy without these once to respond to the challenge.

```bash
SLACK_BOT_TOKEN=
SLACK_SIGNING_SECRET=
HUBOT_ANSWER_TO_THE_ULTIMATE_QUESTION_OF_LIFE_THE_UNIVERSE_AND_EVERYTHING=
```

## Running locally

To run your express server locally run:

```bash
npm install
npm start
```

> Note: Developing locally with SlackAPI is not officially supported at this time.

## Running remotely

Deploy your app to the Reshuffle cloud to run it remotely. Simply run:

```bash
npx reshuffle deploy
```

from the projects root directory
