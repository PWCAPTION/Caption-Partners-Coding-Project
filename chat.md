# Chat API

Build an API (No client app / UI) for a simple chat application. At a minimum we would expect support for some REST but added support for real time data is a big plus.

## Import Notes before getting started

- You may use third party libraries but please refrain from using highly opinionated frameworks e.g. Django, NextJS

Please include the following features in your chat app:

- App has users
- App has conversations
- App has messages
- Messages are associated with a user and a conversation
- Messages have a timestamp
- Conversations have participant (users) and messages
- Users are participants in conversations, they can send and receive messages
- API supports getting a list of conversations that could be consumed by a UI
- Above list of conversations can accept parameters which allow for filtering conversations by user and/or range of time (will omit messages/conversations outside this range)
- API supports sending/receiving messages
- API supports searching conversations for a particular string
- If you have any gaps, omissions, areas needing improvement or otherwise interesting & relevant thoughts please document them in a file named "Notes"

Please consider the following components of a chat app to be extras:

- User Authentication
- Database Integration
- Containerization Workflows
