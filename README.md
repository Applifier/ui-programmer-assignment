# UI programming assignment

Return your answers as a zip file. Do not fork this repo.

## Chat UI

Implement a chat UI for mobile devices similar to e.g. [Whatsapp](https://www.whatsapp.com/) or [Facebook messenger](https://www.messenger.com/).
You only need to implement the frontend, as the backend is provided for you, along with an [API client](https://applifier.github.io/ui-programmer-assignment-backend/).

You should implement the following views and navigation between them:
- Chat list:
  - List chats in which you are participating.
  - Clicking an item in the chat list will take you to that chat's details view.
- Chat details view:
  - List all messages in the chat. Messages may contain text and emoticons.
  - Functionality to send a new chat message.

You should pay extra attention to the polish of the the UI, including animations and performance. You can find the specs in the `interaction-prototype` and `visual-specs` folders; the original specs are made with [sketch](https://www.sketchapp.com) and [flinto](https://www.flinto.com), but exported files are made available as well.

You can find and use the graphical assets you need in the assets folder.

Technology constraints & considerations:
- Use [React native](https://github.com/facebook/react-native).
- Use the provided API client. You can find installation instructions and documentation here: https://applifier.github.io/ui-programmer-assignment-backend/
- You may use additional libraries, but if you do explain why you did.
- Include instructions how to run the app. Include enough mock data for us to test your UI.
