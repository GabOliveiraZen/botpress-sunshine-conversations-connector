# Sunshine Conversations Botpress Channel

This main purpose of this project is to enable Sunshine Conversations v2 API on Botpress, in order to support multi-conversations

## Requirements

1. Sunshine Conversations account (you can create one [here](https://app.smooch.io/signup))
1. Botpress installed
1. Sunshine Conversations v2 API


## Installation

1. Install [Botpress](https://botpress.com/download)
1. Clone this repository `git clone https://github.com/GabOliveiraZen/botpress-sunshine-conversations-connector.git`
1. Generate a `channel-sunshine-conversations.tgz` file containing all files in the repository
1. Move the `tgz` file to the `modules` folder on your Botpress instance 
1. Set up your bot and activate the channel by setting the `enabled` flag as `true` in `channel-sunshine-conversations.json` in the `Code Editor`
1. Set up Sunshine Conversations credentials by filling the `appId`, `keyId` and `secret` fields
