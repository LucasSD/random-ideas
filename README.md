# RandomIdeas App

This is a fullstack application for sharing random ideas. 

This app includes a Node.js/Express REST API that uses MongoDB for a database. The client-side is built with Webpack.
![image](https://github.com/LucasSD/random-ideas/assets/71330905/6489cb15-b019-4951-97d2-5619af258c92)


## Usage

Setup instrucitons pending. 

## REST Endpoints

### Ideas

| Endpoint       | Description    | Method | Body                    |
| -------------- | -------------- | ------ | ----------------------- |
| /api/ideas     | Get all ideas  | GET    | None                    |
| /api/ideas/:id | Get idea by id | GET    | None                    |
| /api/ideas     | Add idea       | POST   | { text, tag, username } |
| /api/ideas/:id | Update idea    | PUT    | { text, tag, username } |
| /api/ideas/:id | Delete idea    | DELETE | username                |

When updating or deleting, the username must match the username of the idea creator.
