# Dead of Winter

## Sobre o Projeto

Este é um projeto de desenvolvimento frontend que visa criar uma versão digital do aclamado jogo de tabuleiro **Dead of Winter**. [cite_start]Utilizando a expertise em **React**, **TypeScript** e **Vite**, o objetivo é replicar a experiência do jogo de forma interativa e fiel às regras originais[cite: 1, 2].

[cite_start]O jogo aborda temas de sobrevivência em um inverno apocalíptico, onde os jogadores devem colaborar para atingir um objetivo comum da colônia, ao mesmo tempo que cumprem seus próprios objetivos secretos[cite: 97, 98].

## Funcionalidades Planejadas

-   [cite_start]**Modos de Jogo**: Suporte para os modos **Padrão** e **Cooperativo**, incluindo suas variantes[cite: 48, 51].
-   [cite_start]**Fases do Jogo**: Implementação completa das fases de **Preparação**, **Jogadores** e **Colônia**[cite: 59, 104].
-   **Mecânicas Principais**:
    -   Gerenciamento de **Sobreviventes** e seus atributos.
    -   [cite_start]Uso de **Dados de Ação** para realizar ações como atacar e explorar[cite: 133, 138, 183].
    -   [cite_start]Resolução de **Cartas de Crise** e **Encruzilhadas**[cite: 127, 112].
    -   [cite_start]Gerenciamento de recursos como comida e lixo[cite: 170, 214].
    -   [cite_start]Controle da **Moral da Colônia** e **Rodadas** de jogo[cite: 102, 103, 239].
    -   [cite_start]Votação de **Exílio** e suas consequências[cite: 24].

## Tecnologias Utilizadas

-   **React**: Biblioteca principal para a construção da interface do usuário.
-   **TypeScript**: Adiciona tipagem estática para um código mais robusto e previsível.
-   **Vite**: Ferramenta de build rápida e moderna para o ambiente de desenvolvimento.

## Como Executar o Projeto

Para configurar o projeto em seu ambiente local, siga os passos abaixo:

1.  Clone o repositório:
    ```bash
    git clone [URL_DO_REPOSITORIO]
    ```
2.  Navegue até o diretório do projeto:
    ```bash
    cd dead-of-winter-digital
    ```
3.  Instale as dependências:
    ```bash
    npm install
    ```
4.  Inicie o servidor de desenvolvimento:
    ```bash
    npm run dev
    ```

O projeto estará disponível em `http://localhost:5173`.

## Estrutura do Projeto

A arquitetura do projeto segue a convenção de **componentes** baseados em responsabilidades:

src/
├── components/
│   ├── ui/ (Componentes de interface genéricos)
│   ├── game/ (Componentes específicos do jogo)
│   └── common/ (Lógica e estado compartilhados)
├── pages/ (Páginas principais da aplicação)
├── hooks/ (Hooks personalizados)
├── types/ (Definições de tipos)
├── utils/ (Funções utilitárias)
└── main.tsx
