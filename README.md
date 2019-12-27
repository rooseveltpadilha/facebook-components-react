# Atividade para criação de ambiente e montagem de componentes fb new style
Atividade realizada para criação de estrutura do ReactJS. Uso do webpack, babel, webpack dev server, ReactJS.

- Passos realizados:

* yarn init -y

* yarn add @babel/core @babel/preset-env @babel/preset-react webpack webpack-cli

* yarn add react react-dom

- Inicio da config:

1. Criação de um arquivo babel.config.js

2. Faço a atualização do arquivo para isso:

```
module.exports = {
  presets: [
    "@babel/preset-env",
    "@babel/preset-react"
  ]
};
```

- Agora iniciamos a configuração do webpack:

1. Crio o webpack.config.js

2. Crio a pasta src, e dentro crio um index.js.

3. Adiciono o entry com o path do node.

4. Crio a pasta public para add no output (transpilação do code), aí temos que adicionar o path.

5. Adicionamos o file name, os modules e as rules no arquivo de configuração do webpack.

6. Adiciono o test, depois o exclude e o babel-loader para os arquivos JS. (yarn add babel-loader -D).

7. Instalar o webpack-dev-server e configura o package.json.

8. Faço o import do react e o render do react-dom. Depois crio a div no index.html do /public e faço a exportação no index.js.

9. Crio o componente com a criação de um novo arquivo e faço o import no index juntamente com a implementação dele na tag principal do render.

10. Instalar o yarn add style-loader e css-loader.

11. Faço a adição no package.json.

12. Fiz a configuração do loader de imagens e ainda fiz a criação de um novo componente para trabalhar com state.

