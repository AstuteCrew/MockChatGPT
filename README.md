# Sample Chat GPT example with token and prompts limitation


Backend: NodeJs
Frontend: React
Database: MongoDB
Docker

The summary of the project is, This is an Web Application that like ChatGPT. The LLM used in this app is Mistral, which is connected to using an API key from Hugging Face. The users are signed up -> logged in -> and they can see the Chat interface. The users are allowed with only 2000 tokens perday max limit and 2 questions per 2 minutes which can be adjusted. The whole project is containerized. The database is connected to my mongoserver please feel free to change it in .env file, same with the hugging face key.To start the project run node server.js in backend folder,cd into frontend and run npm start.

you can see UI in localhost:3001


