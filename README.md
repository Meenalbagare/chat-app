# Chat-app
## Description
A chat app developed for Software Engineering course UE21CS341A at PES University.

## Contributors
- [Melvin J](https://github.com/melvinjjoseph)
- [Meenal Bagare](https://github.com/Meenalbagare)
- [Meghana Anand](https://github.com/MeghanaAnand09)
- [L Sai Tejas](https://github.com/saiii009)

## Installation
- Clone the repository
- Install the go dependencies
```bash
go mod tidy
```
- Install the react dependencies
```bash
cd client
npm install
```
## Configuration
- Create a .env file in the root directory
- Add the following environment variables
```bash
REDIS_CONNECTION_STRING=enter your redis connection string here
REDIS_PASSWORD=enter your redis password here
```
## Usage
- Run the http server
```bash
go run main.go --server=http
```
- Run the websocket server
```bash
go run main.go --server=websocket
```
- Run the react app
```bash
cd client
npm start
```
- Open the app at http://localhost:3000