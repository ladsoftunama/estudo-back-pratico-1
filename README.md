# Desafio pratico back-end 1

![img](https://github.com/ladsoftunama/ladsoftunama/blob/main/imagens/image_readme.png?raw=true)
Faça **_3 rotas de api_** com mecanicas de uso de **_passagem de parametro_** na url

```Javascript
const { nome_do_parametro_url } = req.query;
```

### Passos iniciais

Clone esse projeto para sua maquina:

```bash
git clone url_do_projeto
```

Para inciar pacotes essenciais do projeto desse repositorio execute:

```bash
npm install
```

Para Executar o projeto desse repositorio execute:

```bash
npm run dev
```

### Estrutura de pastas

    |-- pages/
      |-- api/
        |-- rota1.js
        |-- rota2.js
        |-- rota3.js

### Exemplo de passagem de parametro

Exemplo de estrutura basica api next:
Passagem de parametro via **url**

```Javascript
export default function handler(req, res) {
  const { nome_do_parametro_url } = req.query;
  res.status(200).json({ message: "Esta é uma rota de API" });
}
```

### Material de apoio

- [Conteudo 1](https://github.com/ladsoftunama/Cronograma/blob/main/cronograma-back-end/aula-1/README.md)
