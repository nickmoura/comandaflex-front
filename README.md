# ComandaFlex - Frontend

Interface web para gestão de pedidos de mesas no sistema **ComandaFlex**.

Este projeto foi desenvolvido utilizando **React.js** com **Vite**, **TailwindCSS** para o estilo e **React-Toastify** para as notificações.

---

## Tecnologias Utilizadas

- [React.js](https://reactjs.org/)
- [Vite](https://vitejs.dev/)
- [TailwindCSS](https://tailwindcss.com/)
- [React-Toastify](https://fkhadra.github.io/react-toastify/)
- [JavaScript](https://developer.mozilla.org/pt-BR/docs/Web/JavaScript)

---

## Como rodar o projeto

### Pré-requisitos

- Node.js (versão 18 ou superior)
- npm ou yarn instalado

### Instalação

Clone o repositório:

```bash
git clone https://github.com/seu-usuario/comandaflex-frontend.git
cd comandaflex-frontend
````
Instale as dependências:

```bash
npm install
```

Inicie o servidor de desenvolvimento:
```bash
npm run dev
```

Acesse no navegador:
```bash
https://localhost:5173
```

## Estrutura de pastas

```bash
📁 src/
 📁 components/
   ⚛️ PedidoForm.jsx
    ⚛️ PedidoList.jsx
 📁 pages/
   ⚛️ Mesa.tsx
 📁 services/
   ⚛️ pedidoService.jsx
 ⚛️ App.jsx
 ⚛️ main.jsx
 ```

- components/: Componentes reutilizáveis da interface.
- pages/: Páginas principais da aplicação.
- services/: Serviços de comunicação e manipulação de dados.

## Funcionalidades

- Criar novos pedidos.
- Listar pedidos em aberto.
- Armazenamento de pedidos em LocalStorage (em fase inicial).
- Feedback ao usuário através de notificações visuais.
- Layout responsivo e adaptado a dispositivos móveis.

## Próximos Passos
- Integração com API backend.
- Funcionalidades de registro para delivery e para levar.
- Autenticação de usuários (garçons e administradores).
- Sistema de gestão de mesas dinâmicas.
- Dashboard para acompanhamento dos pedidos em tempo real.

## Licença

Este projeto está licenciado sob a licença MIT.

## Autor

Desenvolvido por [Nick](https://www.nickmoura.dev)
