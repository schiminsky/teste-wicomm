---
<h1 align="center">🛒 VTEX IO Front-end Test - Wicomm</h1>
<p align="center">
  <strong>Projeto de implementação de Storefront utilizando VTEX IO Framework e React.js</strong>
</p>

---

## 📝 Sobre o Projeto
Este repositório contém o desenvolvimento de um desafio técnico focado na plataforma VTEX IO. O objetivo foi construir uma interface de e-commerce modular, utilizando as melhores práticas de Store Framework, componentização de blocos e estilização avançada.

A arquitetura segue o padrão de SFC (Store Framework Components), garantindo uma loja performática, escalável e de fácil manutenção via Site Editor.

---

## 🛠️ Stacks Utilizadas

<p align="left">
  <img src="https://img.shields.io/badge/VTEX%20IO-F71963?style=for-the-badge&logo=vtex&logoColor=white" />
  <img src="https://img.shields.io/badge/JSONC-000000?style=for-the-badge&logo=json&logoColor=white" />
  <img src="https://img.shields.io/badge/Sass-CC6699?style=for-the-badge&logo=sass&logoColor=white" />
</p>

---

## ✨ Funcionalidades em Destaque
* **Arquitetura Modular**: Separação clara entre blocos de header, footer, home e product page.
* **Navegação por Abas (Tab Layout)**: Implementação de troca dinâmica entre diferentes vitrines de produtos utilizando botões de seleção, otimizando o espaço da Home.
* **Flex Layout**: Uso extensivo de flex-layout para garantir responsividade total em todos os dispositivos.
* **Custom Styles**: Estilização avançada via arquivos SCSS organizados por componentes (Custom Handles), garantindo fidelidade ao layout proposto.
* **Shelf e Sliders**: Configuração de carrosséis de produtos utilizando o slider-layout com navegação fluida.
* **Rich Text**: Construção de banners e conteúdos institucionais dinâmicos.

---

## 📂 Estrutura de Arquivos
```bash
├── store/
│   └── blocks/          # Definição da estrutura da loja
│       ├── home/        # Blocos da Home
│       ├── footer.jsonc # Estrutura do rodapé
│       └── header.jsonc # Estrutura do cabeçalho
└──styles/
   ├── configs/         # Configurações de cores e fontes
   └── scss/            # Estilização avançada (vtex.tab-layout.scss, etc)

 ```

---

## 🚀 Como Executar o Projeto

Para visualizar este projeto em um ambiente de desenvolvimento, você precisará do VTEX Toolbelt instalado.

## 📋 Pré-requisitos
Antes de começar, você precisará ter instalado em sua máquina:
* Ter o **VTEX Toolbelt** instalado globalmente.
* Estar logado em uma conta **VTEX** válida.
* **Node.js** 
* **npm** ou **Yarn**
* Um navegador moderno para visualização (Chrome, Firefox ou Edge)

---

## 🛠️ Passo a Passo
**Clonar o Repositório:**
```bash
  git clone https://github.com/schiminsky/teste-wicomm.git
```
**Instale as dependências e rode (npm):**
```bash
  npm install
  npm install sass
```
**se preferir usar o Yarn:**
```bash
  yarn install
  yarn install sass
```
**Fazer login na conta:**
```bash
vtex login nome-da-conta
```
**Criar ou utilizar um Workspace de teste:**
```bash
vtex use meu-workspace-teste
```
**Instalar dependências e linkar o projeto:**
```bash
vtex link
```

---

## 🧪 Como Testar as Funcionalidades
* **Interatividade**: Teste a troca de vitrines clicando nos botões do tab-layout na página inicial.
* **Responsividade**: Verifique como o flex-layout e os estilos SCSS se comportam em diferentes resoluções.
* **Customização**: Note como os arquivos em styles/scss/ utilizam as classes nativas para aplicar o design system customizado.

---

<p align="center">
Desenvolvido por <strong>Claudio Schiminsky Junior</strong>
</p>

---
