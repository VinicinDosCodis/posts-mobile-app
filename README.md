Um aplicativo React Native em TypeScript que consome dados de uma API pública e exibe em tela. Desenvolvido como parte de um desafio acadêmico.

Funcionalidades
✅ Consumo de API REST (JSONPlaceholder)

✅ Listagem de posts com scroll

✅ Indicadores de carregamento

✅ Tratamento de erros

✅ Atualização por pull-to-refresh

✅ Layout responsivo

Tecnologias
React Native

TypeScript

Expo

React Native Safe Area Context

Fetch API

Como Executar
Clone o repositório:

bash
git clone https://github.com/seu-usuario/nome-do-repositorio.git
Instale as dependências:

bash
cd nome-do-repositorio
npm install
Inicie o servidor:

bash
npx expo start
Abra o Expo Go no celular e escaneie o QR Code.

Estrutura
text
App.tsx           # Componente principal
package.json      # Dependências
tsconfig.json     # Configuração TypeScript

API Utilizada
Fonte: JSONPlaceholder (https://jsonplaceholder.typicode.com)

Endpoint: /posts

Dados: Posts simulados com ID, título, corpo e ID do usuário

Objetivo de Aprendizado
Este projeto foi desenvolvido para praticar:

Consumo de APIs REST em React Native

Gerenciamento de estado com useState e useEffect

Renderização de listas com FlatList

Tratamento de estados (loading, error, success)

Estilização de componentes
