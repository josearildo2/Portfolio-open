# Portfolio aberto

Portfólio feito em Vue JS, TailwindCSS e DaisyUI.

## Tecnologias utilizadas no projeto

[Vue.JS](https://vuejs.org/) <br>
[TailwindCSS](https://tailwindcss.com/) <br> 
[DaisyUI](https://daisyui.com/) <br>
[FontAwesome-Icons](https://fontawesome.com/icons) .

## Como iniciar o projeto

Clone o repositório

```sh
git clone -b https://github.com/josearildo2/Portfolio-open.git portfolio
```

## Acesse a pasta do projeto e instale as dependências

```sh
cd portfolio
npm install
```

### Compile e starte o projeto localmente

```sh
npm run dev
```

### Compile e builde para caso queira subir para produção

```sh
npm run build
```

### Dicas do projeto

A maioria das alterações que podem ser feitas no projeto serão nos arquivos Portfolio.vue (/src/views/) e variaveis.js (/src/assets/) tentei padronizar algumas
variáveis utilizando o export padrão do vue. <br>

A imagem que será exibida na Navbar terá que ser upada dentro da pasta images (/src/images/) e com um nome padrão: "default.png". Ela irá substituir a imagem
padrão que está na pasta.

### Dicas para deploy em nuvem

O Netlify pode ser uma das melhores opções no momento, sendo muito fácil de subir um site estático através do repositório em seu GitHub. <br>

Primeiro, configure um repositório privado em seu github e suba o clone do projeto, alterando os arquivos principais: <b>Portfolio.vue | variaveis.js</b>
com suas informações de currículo. O Netlify oferece um login via Github que facilita ainda mais o deploy, basta vincular ambos e já estará acessando o site. <br>

Agora, acesse a parte de projetos e adicione um novo projeto, importando um já existente do seu GitHub e escolha o Portfolio, lembrando que o Netlify usará a branch
Main para fazer o deploy. <br>

Configurando o build settings para subir o projeto: <br>
Base directory: .
Package directory: ./
Build command: npm run build
Publish directory: ./dist
Functions directory: ./ <br>

Com isso o projeto irá executar o comando de instalação e deploy automaticamente.