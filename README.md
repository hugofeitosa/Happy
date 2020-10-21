Lista de Conteúdo

Sobre
Tecnologias Utilizadas
Instalação e Execução
Licença
recycle Sobre
O Happy é uma aplicação que conecta pessoas à casas de acolhimento institucional para fazer o dia de muitas crianças mais feliz. Esse projeto possui uma versão browser e mobile. purple_heart

clipboard Tecnologias Utilizadas
Yarn
NodeJs
ReactJs
React-Native
React-Navigation
React-Leaflet
MapBox
TypeScript
Expo
Express
Multer
Sqlite3
TypeORM
Yup

desktop_computer Instalação e Execução
Antes de iniciar, é necessário ter o NodeJs e o Yarn baixado na máquina, bem como o aplicativo Expo no celular para a aplicação mobile

Comando para clonar o repositório:
  #Para clonar o projeto
  git clone https://github.com/hugofeitosa/Happy

Para rodar a parte do servidor:
  #Navegar e baixar as depêndencias
  cd backend
  yarn install

  #Iniciar o servidor com yarn
  yarn dev
Para rodar a aplicação na parte do cliente web:
  #Navegar e baixar as depêndencias web
  cd web
  yarn install
  
  #Iniciar a aplicação
  yarn start
Vá para http://localhost:3333 para ver o website.

Para rodar a aplicação na parte do cliente mobile:
  #Navegar e baixar as depêndencias mobile
  cd mobile
  yarn install
  
  #Iniciar a aplicação
  yarn start
