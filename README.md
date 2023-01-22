<p align="left">
  <img src="https://img.shields.io/static/v1?label=REACT&message=BIBLIOTECA&color=blue&style=for-the-badge&logo=REACT"/>
  <img src="https://img.shields.io/static/v1?label=REACT NATIVE&message=BIBLIOTECA&color=blue&style=for-the-badge&logo=REACT"/>
  <img src="https://img.shields.io/static/v1?label=TYPESCRIPT&message=language&color=red&style=for-the-badge&logo=TYPESCRIPT"/>
<img src="https://img.shields.io/static/v1?label=NODEJS&message=SERVER&color=green&style=for-the-badge&logo=nodedotjs"/>

<img src="https://img.shields.io/static/v1?label=prisma&message=SERVER&color=green&style=for-the-badge&logo=prisma"/>

<img src="https://img.shields.io/static/v1?label=sqlite&message=SERVER&color=green&style=for-the-badge&logo=sqlite"/>


<img src="https://img.shields.io/static/v1?label=TAILWINDCSS&message=STYLE&color=purple&style=for-the-badge&logo=TAILWINDCSS"/>
  <img src="https://img.shields.io/static/v1?label=android&message=plataform&color=yellow&style=for-the-badge&logo=android"/>
  <img src="https://img.shields.io/static/v1?label=ios&message=plataform&color=yellow&style=for-the-badge&logo=ios"/>
  <img src="https://img.shields.io/static/v1?label=chrome&message=plataform&color=yellow&style=for-the-badge&logo=google-chrome"/>
</p>


### Tópicos 

:small_blue_diamond: [Sobre o Projeto](#sobre-o-projeto-star)
:small_blue_diamond: [Objetivo](#objetivo-dart)
:small_blue_diamond: [Pacotes Utilizados](#pacotes-utilizados-gear)
:small_blue_diamond: [Pré-requisitos](#pré-requisitos-bookmark_tabs)
:small_blue_diamond: [Como rodar a aplicação](#como-rodar-a-aplicação-arrow_forward)

## Sobre o Projeto :star:

Projeto desenvolvido durante o NLW Setup, um evento online grauito, organizado pela [Rocket Seat](https://lp.rocketseat.com.br/nlw).


## Objetivo :dart:

:trophy: O Habits é um aplicativo desenvolvido para controle dos hábitos do dia a dia, visando melhoria na qualidade de vida, disponível tanto para Web como para Mobile.

O back-end da aplicação foi desenvolvido em nodejs, utilizando SQLite como banco de dados.


## :sunrise_over_mountains: Imagens

### :computer: Web
![](/images/web/summary.png)
![](/images/web/new_habit.png)
![](/images/web/summary_list.png)

### :iphone: Mobile

![](/images/mobile/splash.png)
![](/images/mobile/summary.png)
![](/images/mobile/new.png)
![](/images/mobile/summary_list.png)


## :gear:  Pacotes Utilizados 

### :station: Server
- :white_check_mark:[Prisma](https://www.prisma.io/)
- :white_check_mark:[Fastify](https://www.fastify.io/)
- :white_check_mark:[Dayjs](https://day.js.org/)
- :white_check_mark:[Zod](https://zod.dev/)
- :white_check_mark:[MermaidJs](https://mermaid.js.org/#/)
- :white_check_mark:[Prisma ERD Generator](https://github.com/keonik/prisma-erd-generator#prisma-entity-relationship-diagram-generator)


### :computer: Web
- :white_check_mark:[Radix](https://www.radix-ui.com/)
- :white_check_mark:[Axios](https://axios-http.com/ptbr/docs/intro/)
- :white_check_mark:[Clsx](https://github.com/lukeed/clsx#readme)
- :white_check_mark:[Phosphor Icons](https://phosphoricons.com/)
- :white_check_mark:[Vite](https://vitejs.dev/)
- :white_check_mark:[TailwindCSS](https://tailwindcss.com)
- :white_check_mark:[Dayjs](https://day.js.org/)

### :iphone: Mobile
- :white_check_mark:[Expo](https://expo.dev/)
  - https://docs.expo.dev/versions/latest/sdk/safe-area-context/
  - https://docs.expo.dev/versions/latest/sdk/screens/
  - https://docs.expo.dev/versions/latest/sdk/svg/
  - https://docs.expo.dev/guides/using-custom-fonts/
- :white_check_mark:[Axios](https://axios-http.com/ptbr/docs/intro/)
- :white_check_mark:[Nativewind](https://www.nativewind.dev/)
- :white_check_mark:[React Native Reanimated](https://docs.swmansion.com/react-native-reanimated/)
- :white_check_mark:[Dayjs](https://day.js.org/)
- :white_check_mark:[React Navigation](https://reactnavigation.org/)
  - https://reactnavigation.org/docs/native-stack-navigator/
- :white_check_mark:[Clsx](https://github.com/lukeed/clsx#readme)

## Como rodar a aplicação :arrow_forward:

#### :warning: Pré-Requisitos

- [Git](https://git-scm.com/)

#### :heavy_check_mark: Clonando o Projeto

No terminal, clone o projeto: 

```
https://github.com/dgo-angelo/nlw-setup.git
```

### :station: Server

#### :warning: Pré-Requisitos

- :link: [NodeJs e NPM](https://nodejs.org/en/)


#### :arrow_forward: Executando a aplicação

1) Acessar a pasta ```server``` do projeto
2) Instalar as dependencias
```
npm install
```

3) Executar o comando abaixo, que disponibilizará a api no endereço http://localhost:3333

```
npm run dev
```

4) Acessar a api no endereço http://localhost:3333

### :computer: Web

#### :warning: Pré-Requisitos

- [Vite](https://vitejs.dev/)

#### :arrow_forward: Executando a aplicação

1) Acessar a pasta ```web``` do projeto
2) Instalar as dependencias

```
npm install
```

3) Executar o comando abaixo

```
npm run dev
```

4) Acessar o link que será exibido no terminal

### :iphone: Mobile

#### :warning: Pré-Requisitos

- [Expo](https://expo.dev/)

#### :arrow_forward: Executando a aplicação

1) Acessar a pasta ```mobile``` do projeto
2) Instalar as dependencias

```
npm install
```

3) Executar o comando abaixo

```
npx expo start --clear
```

4) Será exibida uma tela para seleção do dispositivo para execução.

5) Após selecionar o dispositivo, o aplicativo será executado.

<hr/>