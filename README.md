# Semana OmniStack 11
### Repo to store files about Omnistack Course

URL: https://rocketseat.com.br/week/aulas/11.0
Dica: Anotações https://notion.so
Dica: Layout de aplições mobile -> figma.com

### Setup:
```shell
brew install node
brew install yarn
brew install npm
```

### VSCode:
    Extensions:
        Dracula Official, Material Theme

### Backend Init:
    mkdir aulas/backend && cd aulas/backed
    npm init (vai criar o package.json)
    npm install express

### Entendendo o React:
    Abordagem SPA (single page application)

### Projeto com React
    npx create-react-app frontend
    npm init react-app frontend
    cd frontend && npm start

#### Arquivo App.js
    Trocar texto frontend/src/App.js em <p> colocar Hello World

### React Native
    expo: faz apps para android e IOS, tem diversas libs prontas para ambos os sistemas


### Entendendo o React:
    Abordagem SPA (single page application)

### Projeto com React
    npx create-react-app frontend
    npm init react-app frontend
    cd frontend && npm start

#### Arquivo App.js
    Trocar texto frontend/src/App.js em <p> colocar Hello World

### React Native
    expo: faz apps para android e IOS, tem diversas libs prontas para ambos os sistemas

### Database knex / dir backend
    npm install knex
    npm install sqlite3
    npx knex init
    npx knex migrate:make create_ongs
    npx knex migrate:latest
    npx knex migrate:make create_incidents
    npx knex migrate:latest

### React frontend connect to backend
    npm install axios
    npm install -g expo-cli
    expo init mobile
    cd mobile
    yarn start
    # No celular, baixar o app Expo

### Routes React Navigation
   npm install @react-navigation/native
   # npm install react-native-reanimated react-native-gesture-handler react-native-screens react-native-safe-area-context @react-native-community/masked-view
   expo install react-native-gesture-handler react-native-reanimated react-native-screens react-native-safe-area-context @react-native-community/masked-view
   npm install
   npm install @react-navigation/stack
   expo install expo-constants

### Expo Mail Composer and Whastapp
  expo install expo-mail-compose


### Conector backend no mobile
  npm install axios
  npm install intl
  
