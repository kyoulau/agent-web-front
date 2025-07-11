# NLW Agents

Projeto desenvolvido durante o evento **NLW Unite** da Rocketseat, trilha de React.

## 🚀 Sobre o Projeto

A aplicação "NLW Agents" é uma interface web para a criação e gerenciamento de salas de eventos.

## 🛠️ Tecnologias Utilizadas

O projeto foi construído utilizando um conjunto de tecnologias modernas para o desenvolvimento web:

- **React + TypeScript**: Biblioteca para construção de interfaces de usuário com tipagem estática para maior segurança e manutenibilidade do código.
- **Vite**: Ferramenta de build extremamente rápida que oferece uma experiência de desenvolvimento otimizada com Hot Module Replacement (HMR).
- **React Router DOM**: Para gerenciamento de rotas e navegação na aplicação.
- **TanStack Query (React Query)**: Utilizada para data fetching, caching, e gerenciamento de estado de servidor, simplificando a lógica de requisições assíncronas.
- **Tailwind CSS**: Framework CSS utility-first para a criação de designs customizados de forma rápida e eficiente.
- **Biome**: Ferramenta de alta performance para formatação e linting de código, garantindo consistência e qualidade.

## 🎨 Padrões de Projeto

- **Componentização**: A interface é dividida em componentes reutilizáveis, seguindo as melhores práticas do React.
- **Data Fetching com Hooks**: As chamadas à API são abstraídas através do hook `useQuery` do TanStack Query, centralizando a lógica de busca e cache de dados.
- **Estilização com Variantes**: Componentes de UI, como botões, utilizam `class-variance-authority` para gerenciar variantes de estilo de forma organizada e escalável.

## ⚙️ Setup e Configuração

Siga os passos abaixo para rodar o projeto localmente.

### Pré-requisitos

- Node.js (versão 18 ou superior)
- npm ou um gerenciador de pacotes compatível

### Instalação

1.  Clone o repositório:
    ```bash
    git clone <url-do-repositorio>
    ```
2.  Navegue até o diretório do projeto:
    ```bash
    cd web-agent
    ```
3.  Instale as dependências:
    ```bash
    npm install
    ```

### Rodando o Projeto

Para iniciar o servidor de desenvolvimento, execute o comando:

```bash
npm run dev
```

A aplicação estará disponível em `http://localhost:5173` (ou outra porta, se a 5173 estiver em uso).

### Qualidade de Código

O projeto utiliza **Biome** para garantir a formatação e a qualidade do código. Se você utiliza o VS Code, é recomendado instalar a extensão do Biome para que a formatação e a correção de lint sejam aplicadas automaticamente ao salvar os arquivos.
