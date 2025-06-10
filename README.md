# DT Money

**DT Money** é uma aplicação desenvolvida como parte do curso de React da Rocketseat. O projeto tem como objetivo criar uma aplicação de gerenciamento de finanças pessoais, permitindo que os usuários cadastrem suas receitas e despesas, visualizem seus saldos e acompanhem seus gastos de forma simples e eficiente.

## Funcionalidades

- Cadastro de receitas e despesas
- Visualização do saldo total
- Filtro por tipo de transação (receita/despesa)
- Interface intuitiva com gráficos para melhor visualização do fluxo de caixa
- Responsividade para uso em dispositivos móveis

## Tela do Projeto

Aqui está o design do projeto, conforme a [página do Figma](https://www.figma.com/design/ZlZS03YXPkNiG0dFiGDnzS/DT-Money--Community-?node-id=42078-424&t=do2B0DrB5Ku65wlu-0).

![Imagem do projeto](link-da-imagem)

## Tecnologias Usadas

Este projeto foi desenvolvido com as seguintes tecnologias:

- **React.js** - Biblioteca JavaScript para construção da interface.
- **TypeScript** - Superset do JavaScript que traz tipagem estática.
- **Styled-components** - Biblioteca para escrever CSS dentro do JavaScript.
- **Context API** - Para o gerenciamento de estado global da aplicação.
- **JSON Server** - Utilizado para simular uma API RESTful local.
- **Vite** - Ferramenta de bundling e desenvolvimento rápido.
  
## Como rodar o projeto

### Pré-requisitos

Antes de começar, você precisará ter o Node.js e o npm (ou yarn) instalados na sua máquina.

- [Instalar o Node.js](https://nodejs.org/)

### Passos para rodar

1. Clone o repositório:
    ```bash
      git clone https://github.com/thauanyAA/dtmoney.git
      cd dtmoney
    ```

2. Instale as dependências:
  Com npm:
    ```bash
      npm install
    ```
  Ou com yarn:
    ```bash
      yarn install
    ```

3. Inicie o servidor de desenvolvimento:
  Com npm:
    ```bash
    npm run dev
    ```

  Ou com yarn:
    ```bash
    yarn dev
    ```

4. Acesse a aplicação em seu navegador:
    ```bash
    http://localhost:3000
    ```

### Estrutura do Projeto
A estrutura de diretórios deste projeto segue a convenção típica para aplicações React com TypeScript:

```php
dt-money/
├── src/
│   ├── assets/            # Imagens e outros arquivos estáticos
│   ├── components/        # Componentes reutilizáveis
│   ├── context/           # Context API para gerenciar estado global
│   ├── hooks/             # Custom hooks
│   ├── services/          # Funções para interagir com a API
│   ├── styles/            # Arquivos de estilos globais
│   └── App.tsx            # Componente principal da aplicação
├── public/                # Arquivos públicos como index.html
├── package.json           # Arquivo de configuração do projeto
└── README.md              # Este arquivo
```

### Contribuindo
Se você deseja contribuir para o desenvolvimento do DT Money, fique à vontade para abrir um Pull Request. Siga as etapas abaixo para colaborar:

1. Faça um fork do repositório.

2. Crie uma nova branch para sua feature (git checkout -b minha-feature).

3. Faça as mudanças desejadas e adicione testes, se necessário.

4. Faça o commit das suas alterações (git commit -am 'Adiciona nova feature').

5. Faça o push para sua branch (git push origin minha-feature).

6. Abra um Pull Request para que possamos revisar suas mudanças.

## Licença

Este projeto está licenciado sob a Licença MIT - veja o arquivo [LICENSE](LICENSE) para mais detalhes.


Desenvolvido com 💙 durante o curso de React da Rocketseat.