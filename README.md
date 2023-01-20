<h1 align="center">
  <img alt="Logo" src="./public/Capa.svg" alt="SpaceTraveling">
</h1>
<p align="center">Aplicação onde o seu principal objetivo é adicionar alguns trechos de código para que a aplicação de upload de imagens funcione corretamente</p>


<p align="center">
 <a href="#sobre-o-projeto">Sobre o Projeto</a> •
 <a href="#tecnologias">Tecnologias</a> •
 <a href="#configurações-necessárias">Configurações necessárias</a>
</p>

## Sobre o projeto

O projeto tem como objetivo o estudo e desenvolvimento de uma aplicação onde o objetivo é adicionar alguns trechos de código para que a aplicação de upload de imagens funcione corretamente. em uma aplicação já implementada. Ela deve realizar requisições para sua própria API Next.js que vai retornar os dados do FaunaDB (banco de dados) e do ImgBB (serviço de hospedagem de imagens).

O projeto foi desenvolvido como desafio das aulas do Chapter IV [Ignite da Rocketseat](https://rocketseat.com.br/)

Link do >> [Desafio](https://www.notion.so/Desafio-02-Upload-de-imagens-4cf1c3b1c1ad4a66961b6e48558cc3b8)

---

## Tecnologias

Abaixo as tecnologias utilizadas para construção da aplicação

- [ReactJS](https://reactjs.org/)
- [React Query](https://react-query-v3.tanstack.com)
- [React Hook Form](https://react-hook-form.com)
- [ImgBB](https://pt-br.imgbb.com)
- [FaunaDB](https://fauna.com)
- [API do Next.js](https://nextjs.org/docs/api-routes/introduction)

---

## Configurações necessárias

### **Requisitos**

Necessário realizar as instalações:

- [Git](https://git-scm.com/)
- [Yarn](https://classic.yarnpkg.com)


### **Clone do projeto**

```bash
# Execute o comando git clone para realizar o clone do repositório
$ git clone https://github.com/diogomfc/desafio-upload-de-imagens.git
# Entre na pasta do repositório clonado
$ cd desafio-upload-de-imagens
```

### **Iniciando o projeto**

```bash
# Execute yarn para instalar as dependências
$ yarn

# Na raiz do projeto crie uma copia do arquivo .env.local.example
# Altere o nome da copia para .env.local
# Preencha as variáveis ambiente de acordo com as instruções
$ cp .env.local.example .env.local


# Para iniciar a aplicação
$ yarn dev

```
