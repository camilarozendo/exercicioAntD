<p align="center">
  <img src="https://camo.githubusercontent.com/a4e71a0942263821f4cb9213b2808af909e46967d9ed3ccee6e7e122f276efd6/68747470733a2f2f696d672e69636f6e73382e636f6d2f65787465726e616c2d74616c2d72657669766f2d726567756c61722d74616c2d72657669766f2f39362f65787465726e616c2d726561646d652d69732d612d656173792d746f2d6275696c642d612d646576656c6f7065722d6875622d746861742d6164617074732d746f2d7468652d757365722d6c6f676f2d726567756c61722d74616c2d72657669766f2e706e67" width="100" />
</p>
<p align="center">
    <h1 align="center">Exercício Ant Design</h1>
</p>
<p align="center">
    <em>Exercício para a disciplina de Técnicas Avançadas de CSS do curso de Desenvolvimento Web Front-End - PUC Minas</em>
</p>
<p align="center">
	<img src="https://img.shields.io/github/license/camilarozendo/exercicioAntD?style=default&color=0080ff" alt="license">
	<img src="https://img.shields.io/github/last-commit/camilarozendo/exercicioAntD?style=default&color=0080ff" alt="last-commit">
	<img src="https://img.shields.io/github/languages/top/camilarozendo/exercicioAntD?style=default&color=0080ff" alt="repo-top-language">
	<img src="https://img.shields.io/github/languages/count/camilarozendo/exercicioAntD?style=default&color=0080ff" alt="repo-language-count">
<p>
<p align="center">
	<!-- default option, no dependency badges. -->
</p>
<hr>

## 🔗 Quick Links

> - [ Overview](#-overview)
> - [ Features](#-features)
> - [ Repository Structure](#-repository-structure)
> - [ Getting Started](#-getting-started)
>   - [ Installation](#-installation)
>   - [ Running exercicioAntD](#-running-exercicioAntD)
>   - [ Tests](#-tests)
> - [ Contributing](#-contributing)
> - [ License](#-license)

---

## 📍 Overview

Esta aplicação React é um exercício que tem como objetivo a utilização do framework Ant Design para a construção da interface do usuário.

---

## 🔮 Features

#### Ant Design:
* O código faz uso extensivo dos componentes do Ant Design para criar a interface do usuário. Alguns desses componentes incluem 'Layout', 'Menu', 'Card', 'Breadcrumb', 'Typography', entre outros.
* O tema da aplicação é personalizado usando tokens do Ant Design, como 'colorBgContainer', que é utilizado para definir o fundo de alguns elementos da interface.

#### Menu Lateral e Breadcrumb:
* Um menu lateral é criado usando o componente 'Menu' do Ant Design, com ícones e opções de navegação.
* O componente 'Breadcrumb' é utilizado para exibir uma trilha de navegação no topo da página.

#### Conteúdo Principal:
* O conteúdo principal da página está dentro do componente 'Content' do Ant Design.
* Uma Breadcrumb é exibida acima do conteúdo principal para indicar a localização do usuário na aplicação.

#### Cards no Conteúdo Principal:
* O conteúdo principal contém uma seção com quatro cartões ('Card') organizados em uma linha com estilos de flexbox. Cada cartão possui um estilo específico, incluindo altura fixa.

#### useState:
* O estado local é gerenciado usando o hook 'useState'. Um exemplo disso é o estado 'collapsed', que controla se o menu lateral está recolhido ou expandido.

#### Responsividade:

* O layout é projetado para ser responsivo, ajustando-se à altura da visualização (`minHeight: '100vh'`) e utilizando o componente 'Sider' para criar um menu lateral recolhível.

#### Footer:

* Um rodapé ('Footer') exibe informações de crédito, indicando que a aplicação foi criada por Ant UED.

Em resumo, a aplicação é um exemplo de utilização do framework Ant Design para criar uma interface de usuário React. Ela incorpora componentes comumente utilizados, como menus, cartões e breadcrumb, proporcionando uma estrutura organizada e estilizada para uma aplicação web.

## 🧩 Repository Structure

```sh

└── exercicioAntD/
   ├── package-lock.json
   ├── package.json
   ├── public/
   │   ├── index.html
   │   ├── logo.png
   │   └── manifest.json
   └── src/
      ├── App.css
      ├── App.js
      ├── App.test.js
      ├── index.js
      ├── logo.svg
      ├── reportWebVitals.js
      └── setupTests.js

```

---

## 🚀 Getting Started

***Requirements***

Ensure you have the following dependencies installed on your system:

* **Node.js**

### ⚙️ Installation

1. Clone the exercicioAntD repository:

```sh
git clone https://github.com/camilarozendo/exercicioAntD
```

2. Change to the project directory:

```sh
cd exercicioAntD
```

3. Install the dependencies:

```sh
npm install
```

### 👩‍💻 Running exercicioAntD

Use the following command to run exercicioAntD:

```sh
node app.js
```

###  🧪 Tests

To execute tests, run:

```sh
npm test
```

---


##  🤝 Contributing

Contributions are welcome! Here are several ways you can contribute:

- **[Submit Pull Requests](https://github/camilarozendo/exercicioAntD/blob/main/CONTRIBUTING.md)**: Review open PRs, and submit your own PRs.
- **[Join the Discussions](https://github/camilarozendo/exercicioAntD/discussions)**: Share your insights, provide feedback, or ask questions.
- **[Report Issues](https://github/camilarozendo/exercicioAntD/issues)**: Submit bugs found or log feature requests for exercicioAntD
<details closed>
    <summary>Contributing Guidelines</summary>

1. **Fork the Repository**: Start by forking the project repository to your GitHub account.
2. **Clone Locally**: Clone the forked repository to your local machine using a Git client.
   ```sh
   git clone https://github.com/camilarozendo/exercicioAntD
   ```
3. **Create a New Branch**: Always work on a new branch, giving it a descriptive name.
   ```sh
   git checkout -b new-feature-x
   ```
4. **Make Your Changes**: Develop and test your changes locally.
5. **Commit Your Changes**: Commit with a clear message describing your updates.
   ```sh
   git commit -m 'Implemented new feature x.'
   ```
6. **Push to GitHub**: Push the changes to your forked repository.
   ```sh
   git push origin new-feature-x
   ```
7. **Submit a Pull Request**: Create a PR against the original project repository. Clearly describe the changes and their motivations.

Once your PR is reviewed and approved, it will be merged into the main branch.

</details>

---

##  📄 License

MIT License

Copyright (c) [2023] [Camila Rozendo]

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

---


[**Return**](#-quick-links)

---