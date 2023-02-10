https://www.freecodecamp.org/news/how-to-create-a-react-app-with-a-node-backend-the-complete-guide/

NOTE:

There are TWO package.jsons. One in server and one in client.

Adding the proxy in the below goes into the CLIENT package.json, not server. Hadn't done this and it didn't work.

"proxy": "http://localhost:3001",