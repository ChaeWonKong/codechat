# ⌨️ CodeChat ⌨️

## Description

### 🙋‍ Exchange code reviews by chatting while reading codes at the same time
![code-editing]("./ezgif.com-gif-maker.gif")

## Dev stack
- React
- socket.io-client
- Express.js
- Socket.io

## Features
- [x] New User
- [x] Get User Number
- [x] Get New Message
- [x] User Connection
- [ ] User Disconnection
- [ ] User Reconnection

## Getting Started

### Prerequisites
| Require                              | Description                                                               |
| ------------------------------------ | ------------------------------------------------------------------------- |
| [Git](https://git-scm.com/)          | We follow the [GitHub Flow](https://guides.github.com/introduction/flow/) |
| [Node.js](nodejs.org)                | 10.10 LTS or above                                                        |
| [Yarn](https://yarnpkg.com/lang/en/) | Recommend [stable version](https://github.com/yarnpkg/yarn/releases)      |

#### Install Node, Yarn

The project manages the version of node through `nvm`

```bash
$ curl -o- https://raw.githubusercontent.com/creationix/nvm/v0.34.0/install.sh | bash
$ command -v nvm
$ nvm install
$ which node
$ npm install -g yarn
```

In the project root as follows are performed through the `.nvmrc`

```
$ nvm use
Found '/Users/user/Github/higherlowerkor/.nvmrc' with version <10.10.0>
```
### env
fill out `.env` for your socket.io-server
```
REACT_APP_SERVER_URL=${your socket.io server url}
```

### Yarn CLIs

#### Install project
```bash
$ nvm use
...
$ yarn
```
#### Build project
```bash
$ yarn build
```
#### Test project
```bash
$ yarn test
```
#### Start project
```bash
$ yarn start
```
## References
This project was inspired by this site
- https://stresscompany.net/

## License

MIT