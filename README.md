# upfi

upfi é uma aplicação desenvolvida para a submissão do desafio do Chapter IV da trilha de ReactJS no Ignite, cujo objetivo era trabalhar com o upload de imagens.

<p align="center">
  <img src="https://user-images.githubusercontent.com/26419930/127943786-448d7306-6697-4692-8e37-a2e3e646a3bd.png" alt="upfi"/>
</p>

## Tecnologias

- Next.js
- FaunaDB
- Chakra UI
- API do ImgBB
- API do Next.js
- React Query
- React Hook Form

## Execução

1. Clone o repositório

```sh
git clone https://github.com/abigailarruda/upfi.git
```

2. Crie um arquivo <code>.env.local</code> na raiz do projeto, utilizando o exemplo a seguir:

```bash
NEXT_PUBLIC_IMGBB_API_KEY= # Chave da API no ImgBB
FAUNA_API_KEY= # Chave do FaunaDB
```

3. Instale as dependências

```sh
yarn
```

4. Execute a aplicação

```sh
yarn dev
```
