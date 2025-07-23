# Tutorial Introdutório sobre React Hooks  

React Hooks são funções especiais introduzidas no React 16.8 que permitem que você use **estado** e **outros recursos do React** sem escrever classes.
Eles simplificam a lógica de componentes, promovem a reutilização de código e facilitam o gerenciamento de efeitos colaterais.  

Neste tutorial, vamos explorar os principais Hooks do React, incluindo **`useForm`** (biblioteca popular para formulários), suas funcionalidades básicas e onde encontrar a documentação oficial para se aprofundar.  

Links oficiais:
- 🔗 **[Documentação Completa do React Hooks](https://react.dev/reference/react)**  
- 🔗 **[React Hook Form (useForm)](https://react-hook-form.com/)**  

---


## 1. Principais React Hooks

### 1.1. useState

**Resumo:** Permite adicionar estado a componentes funcionais.
Ele retorna um par de valores: o estado atual e uma função para atualizá-lo.

🔗 [Documentação Oficial](https://react.dev/reference/react/useState)

### 1.2. useEffect

**Resumo:** Executa efeitos colaterais em componentes funcionais, como chamadas de API, subscriptions ou manipulação do DOM.
Substitui `componentDidMount`, `componentDidUpdate` e `componentWillUnmount`.

🔗 [Documentação Oficial](https://react.dev/reference/react/useEffect)

### 1.3. useContext

**Resumo:** Permite acessar o contexto do React sem precisar aninhar vários `Consumer`.
É útil para compartilhar dados globais (como temas, autenticação, etc.) em toda a aplicação.

🔗 [Documentação Oficial](https://react.dev/reference/react/useContext)

### 1.4. useReducer

**Resumo:** Uma alternativa ao `useState` para gerenciar estados complexos.
Segue o padrão Redux, onde ações despachadas modificam o estado através de um reducer.

🔗 [Documentação Oficial](https://react.dev/reference/react/useReducer)

### 1.5. useRef

**Resumo:** Retorna um objeto mutável (`ref`) que persiste durante todo o ciclo de vida do componente.
Pode ser usado para acessar elementos do DOM diretamente ou armazenar valores mutáveis sem causar rerenders.

🔗 [Documentação Oficial](https://react.dev/reference/react/useRef)

### 1.6. useMemo

**Resumo:** Memoriza um valor calculado, evitando recálculos desnecessários em rerenders.
Ideal para otimizar performance em operações pesadas.

🔗 [Documentação Oficial](https://react.dev/reference/react/useMemo)

### 1.7. useCallback

**Resumo:** Memoriza uma função, evitando recriações desnecessárias em rerenders. Útil quando funções são passadas como props para componentes filhos.  

🔗 [Documentação Oficial](https://react.dev/reference/react/useCallback)

### 1.8. useLayoutEffect

**Resumo:** Similar ao `useEffect`, mas é executado sincronamente após todas as mutações do DOM. Útil para ler o layout do DOM antes do navegador pintar a tela.  

🔗 [Documentação Oficial](https://react.dev/reference/react/useLayoutEffect)

### 1.9. useImperativeHandle

**Resumo:** Permite personalizar a instância exposta quando um componente pai usa `ref` em um componente filho. Menos comum, mas útil em casos específicos.  

🔗 [Documentação Oficial](https://react.dev/reference/react/useImperativeHandle)

### 1.10. useDebugValue

**Resumo:** Usado para exibir labels personalizadas para Hooks personalizados no React DevTools, facilitando a depuração.

🔗 [Documentação Oficial](https://react.dev/reference/react/useDebugValue)

### 1.11. useForm (React Hook Form)

**Resumo:** **Não é um Hook nativo do React**, mas sim parte da biblioteca **React Hook Form**, uma das melhores soluções para gerenciamento de formulários.
Ele simplifica validação, manipulação de erros e submissão de formulários com alta performance.  

🔗 [Documentação Oficial](https://react-hook-form.com/)

