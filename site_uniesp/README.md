# SITE UNIESP

Neste projeto, criei uma simples solução para fornecer informações e abas de navegação, ajudando os usuários que estão ingressando na UNIESP a terem um norte.

## Estrutura de Pastas


## Arquivos Principais

### `pages/inicial/`
Página inicial do site, contendo informações de boas-vindas e links para outras seções.

### `pages/faculdade/`
Página com informações detalhadas sobre a faculdade, incluindo cursos oferecidos e estrutura.

### `pages/dpolgpd/`
Página dedicada à DPOLGPD, com informações relevantes sobre o departamento.

### `pages/noticias/`
Seção de notícias, com as últimas atualizações e artigos relacionados à UNIESP.

### `pages/admin/`
Administração de notícias, contendo subpáginas para gerenciamento de notícias.

#### `pages/admin/AdminNoticias/`
Seção de administração de notícias, permitindo gerenciar os artigos publicados.

#### `pages/admin/CadastrarNoticias/`
Página para cadastro de novas notícias, com formulário para inserir informações.

#### `pages/admin/EditarNoticia/`
Página para edição de notícias existentes, permitindo atualizar o conteúdo.

### `componentes/navbar/`
Componente da barra de navegação, que facilita a navegação entre diferentes seções do site.

### `componentes/banner-ad/`
Componente de banners e anúncios, utilizado para destacar informações importantes.

### `public/imagens/`
Pasta contendo imagens públicas que são utilizadas em várias partes do site.

## Bibliotecas Utilizadas

- **Vite@latest**: Utilizado como ferramenta de construção rápida, moderna e leve para desenvolvimento frontend. Escolhido por sua eficiência e velocidade no desenvolvimento de projetos React.
- **json-server**: Utilizado para criar uma API REST fake para desenvolvimento e testes. Permite simular um backend simples para facilitar o desenvolvimento frontend.
- **react-router-dom**: Biblioteca de roteamento para React, utilizada para criar a navegação entre páginas da aplicação. Permite gerenciar e implementar a navegação de maneira fácil e eficiente.
- **axios**: Biblioteca para fazer requisições HTTP. Utilizada para se comunicar com APIs e manipular dados de maneira simples e eficiente.
- **React Hooks**: Utilizados para gerenciar o estado e os efeitos colaterais no React. Hooks como `useState`, `useEffect`, e outros permitem uma abordagem mais funcional para desenvolvimento de componentes React.

## Como Executar o Projeto

Instruções passo a passo sobre como configurar e executar o projeto:

1. Clone o repositório:
    ```sh
    git clone https://link-do-repositorio.git
    ```
2. Navegue até o diretório do projeto:
    ```sh
    cd SITE_UNIESP
    ```
3. Instale as dependências:
    ```sh
    npm install
    ```
4. Instale as bibliotecas necessárias:
    ```sh
    npm i axios
    npm i json-server
    ```
5. Inicie o servidor JSON:
    ```sh
    npm run server
    ```
6. Execute o projeto:
    ```sh
    npm run dev
    ```

## Contribuições

Explique como outros desenvolvedores podem contribuir para o projeto, incluindo diretrizes para pull requests e issues.

## Licença

Inclua informações sobre a licença do projeto, se aplicável.

---

