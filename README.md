# HubLocalTechTestFront

Front end do teste técnico realizado para a empresa HubLocal

### Pré-Requisitos

- Lado [back end](https://github.com/ericmadson/HubLocalTechTesteBack) da aplicação 
- NodeJS => v16.13.0
- NPM => v8.1.0
- Yarn => 1.22.11

### Instalação

Clone o repositório

    git clone https://github.com/ericmadson/HubLocalTechTestFront.git

Navegue até o repositório

    cd HubLocalTechTestFront

Instale as dependências

    yarn

Inicie a aplicação

    yarn dev

## Detalhes

Essa aplicação foi criada segundo os parâmetros definidos pela empresa HubLocal,
seguindo a proposta de:
- Logar/Criar usuários
- Criar/Listar/Deletar/Editar empresas (usuário logado)
- Criar/Listar/Deletar/Editar locais pertencentes a uma
empresa (usuário logado)

## Observações

Ao realizar a deleção, pode acontecer algum erro por causa da entidade possuir outra relacionada.
Ex: Erro ao excluir uma empresa, pois a mesma possui locais cadastrados a ela.

## Techs

Tecnologias utilizadas:
- ReactJS
- Material UI
- Styled Components
- Context API




