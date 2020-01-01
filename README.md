# Google Calendar Bulk Delete
Want to delete lots of events from your calendar based on a specific property? The website doesn't support it. This node app does! It is a typed and promisified version of the Google Calendar NodeJS [quickstart guide](https://developers.google.com/calendar/quickstart/nodejs), which also includes an additional function to delete events based on ID.

How to use:
- You need [NodeJS](https://nodejs.org/)
- Clone the repo, `npm install` to install the dependencies
- You need to generate a credentials.json (step 1) and place it in the repo folder (generated from https://developers.google.com/calendar/quickstart/nodejs)
- You need to generate a token.json file by running `npm start`: contains your access and refress tokens
- Programmatically choose IDs to delete

// TODO
Finish index.ts
- add bad token checking: e.g. insufficient scope, expired token, corrupted token
- Custom search string, to search through descriptions of events, returning array of event objects
- Make react native app with functionality