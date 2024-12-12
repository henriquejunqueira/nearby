# Nearby App

## Repositório do app desenvolvido no NLW da Rocketseat utilizando React Native

### Arquitetura de arquivos React Native:

#### Raiz do projeto:

- `tsconfig.json`: Configuração do TypeScript, definindo como o código será transpilado e os caminhos de importação;
- `package.json`: Lista todas as dependências e scripts do projeto, incluindo pacotes como `react`, `react-native`, `expo`, e `typescript`;
- `app.json`: Arquivo de configuração do Expo. Contém informações sobre o nome do aplicativo, ícone, splash screen, versão, etc;
- `.gitignore`: Define quais pastas e arquivos devem ser ignorados em um commit;
- `src/`: É usada para armazenar o código do aplicativo;
- `src/app/index.tsx`: É o componente principal do app;
- `src/app/_layout.tsx`: Responsável pela configuração das rotas da aplicação;

### Comandos utilizados:

#### Criando o projeto:

- `$ npx create-expo-app --template`
- ` ? Choose a template: › - Use arrow-keys. Return to submit.`
- `Default`
- `Blank`
- `Blank (TypeScript)`
- `❯ Navigation (TypeScript) - File-based routing with TypeScript enabled`
- `Blank (Bare)`

#### Executando o app:

- `$ npx expo start`

### Instalando fonte Rubik:

- `$ npx expo install expo-font @expo-google-fonts/rubik`

### Instalando biblioteca de ícones tabler:

- `$ npm install @tabler/icons-react-native`

### Instalando biblioteca para renderizar svg:

- `$ npx expo install react-native-svg`

### Instalando biblioteca React Native Bottom Sheet:

- `$ npm i @gorhom/bottom-sheet`

### Instalando as dependências do Bottom Sheet:

- `$ npx expo install react-native-reanimated react-native-gesture-handler`

### Instalando a biblioteca de mapas:

- `$ npx expo install react-native-maps`
