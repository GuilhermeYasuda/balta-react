# 📝 Todo App - React + TypeScript

Repositório desenvolvido durante o curso **"Criando um App com React, TypeScript, Hooks, Context e Forms"** do [balta.io](https://balta.io).

Uma aplicação completa de gerenciamento de tarefas construída com as tecnologias mais modernas do ecossistema React.

## 🎯 Sobre o Projeto

Este projeto é um aplicativo de TODO funcional que demonstra os principais conceitos de React intermediário, incluindo:
- Uso de **React Hooks** (useState, useContext, etc.)
- **Context API** para gerenciamento de estado global
- **React Hook Form** com validação usando **Yup**
- **React Router** para navegação entre páginas
- **TypeScript** para type-safety
- Estrutura escalável e bem organizada

## 🚀 Tecnologias Utilizadas

- **React** v19.2.5 - Biblioteca para construção de UIs
- **TypeScript** v4.9.5 - Superset JavaScript com tipagem estática
- **React Router DOM** v7.15.0 - Roteamento de páginas
- **React Hook Form** v7.75.0 - Gerenciamento de formulários
- **Yup** v1.7.1 - Validação de esquemas
- **React Testing Library** - Testes de componentes
- **UIKit** - Framework CSS para estilização

## ✨ Funcionalidades

- ✅ Criar novas tarefas
- ✅ Listar todas as tarefas
- ✅ Marcar tarefas como concluídas
- ✅ Deletar tarefas
- ✅ Validação de formulários com Yup
- ✅ Navegação entre páginas com React Router
- ✅ Gerenciamento de estado com Context API

## 📁 Estrutura do Projeto

```
src/
├── components/          # Componentes React reutilizáveis
│   ├── App.tsx         # Componente principal com roteamento
│   ├── Navbar.tsx      # Barra de navegação
│   ├── Home.tsx        # Página inicial
│   ├── TodoList.tsx    # Lista de tarefas
│   ├── TodoListItem.tsx # Item individual de tarefa
│   └── AddTodo.tsx     # Formulário para adicionar tarefas
├── contexts/           # Context API
│   ├── TodoContext.tsx     # Provedor do contexto
│   └── TodoContextType.tsx # Tipos do contexto
├── models/             # Modelos de dados
│   └── Todo.tsx        # Interface/tipo de tarefa
├── services/           # Serviços/lógica de negócio
│   └── TodoService.tsx # Operações com tarefas
└── index.tsx          # Ponto de entrada da aplicação
```

## 🛠️ Como Instalar e Rodar

Este projeto foi criado com [Create React App](https://github.com/facebook/create-react-app).

### 📦 Instalação

1. **Clone ou acesse o repositório:**
```bash
cd c:\Cursos\balta-react\todo
```

2. **Instale as dependências:**
```bash
npm install
```

## 📖 Scripts Disponíveis

### `npm start`
Executa a aplicação em modo de desenvolvimento.
Abra [http://localhost:3000](http://localhost:3000) para visualizar no navegador.

A página será recarregada ao fazer edições.
Erros de lint também aparecerão no console.

### `npm test`
Inicia o test runner em modo interativo.
Veja a seção sobre [executar testes](https://facebook.github.io/create-react-app/docs/running-tests) para mais informações.

### `npm run build`
Constrói a aplicação para produção na pasta `build`.
Agrupa corretamente o React em modo produção e otimiza o build para melhor performance.

O build é minificado e os nomes dos arquivos incluem hashes.
Sua aplicação está pronta para ser deployada!

Veja a seção sobre [deployment](https://facebook.github.io/create-react-app/docs/deployment) para mais informações.

## 📚 Conceitos Aprendidos

Este projeto implementa e demonstra:

### React Hooks
- `useState` - Gerenciamento de estado em componentes funcionais
- `useContext` - Acesso a dados do contexto
- `useEffect` - Efeitos colaterais e ciclo de vida

### Context API
- Criação de um contexto global para tarefas
- Provider e Consumer pattern
- Compartilhamento de estado entre componentes

### React Hook Form
- Integração com formulários
- Validação de campos
- Integração com Yup para schemas de validação

### React Router
- Configuração de rotas
- Navegação entre páginas
- Componentes de rota

### TypeScript
- Interfaces e tipos customizados
- Type safety em componentes React
- Tipos para props e estado

## 🎓 Sobre o Curso

Este projeto foi desenvolvido durante o curso **"Criando um App com React, TypeScript, Hooks, Context e Forms"** do balta.io.

📎 **Link do Curso:** [https://balta.io/player/assistir/5f734df2-005b-f737-069c-124200000000](https://balta.io/player/assistir/5f734df2-005b-f737-069c-124200000000)

## 📚 Saiba Mais

Você pode aprender mais em:
- [Documentação do Create React App](https://facebook.github.io/create-react-app/docs/getting-started)
- [Documentação do React](https://reactjs.org/)
- [Documentação do TypeScript](https://www.typescriptlang.org/docs/)
- [React Router Documentation](https://reactrouter.com/)
- [React Hook Form](https://react-hook-form.com/)
- [Yup Documentation](https://github.com/jquense/yup)

## 📝 Licença

Este projeto é um projeto educacional para fins de aprendizado.
