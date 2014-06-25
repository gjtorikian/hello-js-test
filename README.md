To try this locally:

1. Clone the repo.
2. Run `npm install mime`.
3. Run something like [ngrok](https://ngrok.com/) to map your dev environment out to the world: `ngrok 8888`.
4. Set up a new GitHub application. Set the callback to the mapping ngrok gives you, like `http://51c2456e.ngrok.com`.
5. Update the `github` key in *index.html* with your client ID.
6. Register your app with https://auth-server.herokuapp.com
7. Run `node static.js`
