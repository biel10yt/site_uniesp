# SITE UNIESP

In this project, I created a simple solution to provide information and navigation tabs, helping users who are joining UNIESP to have direction.

## Estrutura de Pastas

- **data/**
    - db.json
- **src/**
    - assets/
      - react.svg
  - components/
    - BannerAd.jsx
    - Navbar.jsx
  - pages/
    - admin/
        - AdminNoticias.jsx
        - CadastroNoticias.jsx
        - EditarNoticias.jsx
    - login/
        - Login.jsx
        - styles.css
    - DpoLgpd.jsx
    - Faculdade.jsx
    - Inicial.jsx
    - Noticias.jsx
    - VisualizaNoticia.jsx
  - App.css
  - App.jsx
  - index.css
  - main.jsx
- **public/**
  - download.png
  - uniesp.jpg
  - VESTIBULAR.gif
- **.gitignore**
- **package.json**
- **README.md**

## Arquivos Principais

### `pages/home/`
Site home page, containing welcome information and links to other sections.

### `pages/faculty/`
Page with detailed information about the college, including courses offered and structure.

### `pages/dpolgpd/`
Page dedicated to DPOLGPD, with relevant information about the department.

### `pages/news/`
News section, with the latest updates and articles related to UNIESP.

### `pages/admin/`
News administration, containing subpages for news management.

#### `pages/admin/AdminNoticias/`
News management section, allowing you to manage published articles.

#### `pages/admin/CadastrarNoticias/`
Page for registering new news, with a form to enter information.

#### `pages/admin/EditarNoticia/`
Page for editing existing news, allowing you to update the content.

### `components/navbar/`
Navigation bar component, which makes it easier to navigate between different sections of the website.

### `components/banner-ad/`
Component of banners and advertisements, used to highlight important information.

### `public/images/`
Folder containing public images that are used in various parts of the site.

## Bibliotecas Utilizadas

- **Vite@latest**: Used as a fast, modern and lightweight build tool for frontend development. Chosen for its efficiency and speed in developing React projects.
- **json-server**: Used to create a fake REST API for development and testing. Allows you to simulate a simple backend to facilitate frontend development.
- **react-router-dom**: Routing library for React, used to create navigation between application pages. Allows you to manage and implement navigation in an easy and efficient way.
- **axios**: Library for making HTTP requests. Used to communicate with APIs and manipulate data in a simple and efficient way.
- **React Hooks**: Used to manage state and side effects in React. Hooks like `useState`, `useEffect`, and others allow for a more functional approach to developing React components.
- **Material-UI (MUI)**: User interface component library. Used to style the React application with ready-made and highly customizable components, providing a consistent and attractive user interface.

## Como Executar o Projeto

Step-by-step instructions on how to set up and run the project:

1. Clone the repository:
    ```
    git clone https://github.com/biel10yt/site_uniesp.git
    ```
2. Navigate to the project directory:
    ```
    cd site_uniesp
    ```
3. Install dependencies:
    ```
    npm install
    ```
4. Install the required libraries:
    ```
    npm i axios
    npm i json-server
    npm i react-router-dom
    npm install @mui/material @emotion/react @emotion/styled
    npm install @mui/icons-material --legacy-peer-deps

    ```
5. Start the JSON server:
    ```
    npm runserver
    ```
6. Run the project:
    ```
    npm run dev
    ```

## Contribuições

- [x] User login
- [x] News page
- [x] Administration page
- [x] About the university and LGPD
- [x] Backend request submission

## Contributing
1. Fork the project.

2. Create a branch for your feature:
```bash
git checkout -b my-feature
```

3. Commit your changes:
```bash
git commit -m "My new feature"
```

4. Push to the main branch:
```bash
git push origin my-feature
```

5. Open a Pull Request.

## Licença

MIT License

Copyright (c) [2024] [Gabriel Soares]

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.


