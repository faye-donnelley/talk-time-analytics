# Talk Time Analytics using Deepgram

[![Remix on Glitch](https://img.shields.io/badge/Glitch-remix-blue?logo=glitch)](#remix-on-glitch)

Analyzing the talk time of participants in a classroom, meeting, or phone call
can help you improve participant engagement, sales presentations, and support
response. This app aims to demonstrate how to use Deepgram API to compute talk
time per speaker. We then display the calculated talk time in a pie chart.

If you launch Glitch directly from a link in Deepgram Console, Deepgram creates and implements a temporary API key for you named 'talk-time-demo'. This key will expire 8 hours after creation. If you need to make immediate changes to an app's access to your Deepgram account, you can do so my managing your Deepgram API keys in the Deepgram Console under Settings > API Keys

Actions taken in Glitch are subject to [Glitch’s Terms of Service and Privacy Policy](https://glitch.com/legal).


## Prerequisites

You will need:

- A [free Deepgram account](https://console.deepgram.com/signup?utm_source=DEVREL&utm_medium=github&utm_content=talk-time-analytics)
- A Deepgram [API key](https://developers.deepgram.com/getting-started/create-api-key)

## Getting started

You can run this application by remixing it on Glitch or by running it on your local computer.

### Remix on Glitch

Glitch comes with an online editor, so you'll have all the necessary tools to explore your own app instance. 

To remix this application on Glitch, go to the following URL:

> https://glitch.com/edit/#!/remix/dg-uc-talk-time-analytics

When accessing this URL in your browser, the project will be forked and deployed.

#### Configure the settings

Your application will need to know more about you before it can run successfully. Edit the environment variables (`.env`) to reflect the settings you want to use:

- `PORT`: The port on which you want to run the application. We generally set this to port 3000.
- `DG_KEY`: The API Key you created earlier in this tutorial.

Once these variables are set, the application should run automatically.

### Run on localhost

You can also run this project on your local computer. To do so, you will need
to clone the repository, configure the settings, install the dependencies, and
start the server.

#### Clone the repository

Either clone or download the repository to your local machine, in a new directory.

```bash
# Clone this repo
git clone https://github.com/deepgram-devs/talk-time-analytics.git

# Move to the created directory
cd talk-time-analytics
```

#### Configure the settings

Your application will need to know more about you before it can run. Copy the
`.env-example` file into a new file named `.env` and edit this new file to
reflect the settings you want to use:

- `PORT`: The port you wish to run the application on. Leaving this as port 3000
is acceptable.
- `DG_KEY`: The Deepgram API key you created earlier in this tutorial.

#### Install the dependencies

In the directory where you downloaded the code, run the following command to
bring in the dependencies needed for this project.

```bash
npm install
```

#### Start the server

With the configuration done and the dependencies in place, your application
is ready to go! Run it with:

```bash
npm start
```

## Development and contributing

Interested in contributing? We ❤️ pull requests!

To make sure our community is safe for all, be sure to review and agree to our
[Code of Conduct](./CODE_OF_CONDUCT.md). Then see the
[Contribution](./CONTRIBUTING.md) guidelines for more information.

## Getting help

We love to hear from you, so if you have questions or comments, or find a bug in the
project, let us know! You can either:

- [Open an issue](https://github.com/deepgram-devs/talk-time-analytics/issues/new) in this repository
- Tweet at us! We're [@DeepgramDevs on Twitter](https://twitter.com/DeepgramDevs)

## Further reading

Check out the Developer Documentation at [https://developers.deepgram.com/](https://developers.deepgram.com/).
