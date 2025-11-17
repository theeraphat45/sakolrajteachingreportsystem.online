Next.js backend example for LINE notifications

- Install: `npm install`
- Configure environment variables:
  - `LINE_ACCESS_TOKEN` - channel access token
  - `LINE_GROUP_ID` - destination user/group id for push messages
- Run dev: `npm run dev`
- API route: `POST /api/notify` expects JSON { rooms: [...], date: 'YYYY-MM-DD' }

This example shows how to call LINE Messaging API server-side.
