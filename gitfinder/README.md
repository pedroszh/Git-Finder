# GitHub User Finder

Este projeto é uma aplicação React que permite pesquisar e visualizar informações de perfis do GitHub utilizando a API pública do GitHub. O usuário pode buscar um nome de usuário, e a aplicação exibe dados do perfil como avatar, login, localização, número de seguidores e pessoas que o usuário segue.

## Funcionalidades

- **Pesquisa de usuários do GitHub**: Insira um nome de usuário do GitHub para buscar informações do perfil.
- **Exibição de dados do usuário**: A aplicação mostra:
  - Avatar do usuário
  - Login do GitHub
  - Localização (se não estiver disponível, será exibido "Location not provided")
  - Número de seguidores
  - Número de pessoas que o usuário segue
- **Indicador de carregamento**: Enquanto os dados estão sendo buscados, um componente de carregamento (Loader) é exibido.
- **Tratamento de erros**: Se o nome de usuário não for encontrado, uma mensagem de erro é exibida.

## Tecnologias Utilizadas

- **React**: Biblioteca principal usada para construir a interface do usuário.
- **TypeScript**: Utilizado para adicionar tipagem estática e melhorar a manutenção do código.
- **GitHub API**: API pública do GitHub usada para obter as informações dos usuários.

## Como Executar o Projeto

1. Clone este repositório:

```bash
git clone https://github.com/usuario/repo-nome.git
