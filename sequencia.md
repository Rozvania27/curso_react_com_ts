# 1 - Boas vindas

# 2 - Nossos cursos

# 3 - Ebook gratuito dos principais conceitos

# 4 - Discord para networking

# 5 - Setup (1_setup)

Instalação Node/npm

npm create vite@latest 1_setup

Alteração do projeto

# 6 - Fundamentos (2_fundamentos)

- 6.1 Criação de componente
- 6.2 Expressões no JSX
- 6.3 Componente dentro de componente
- 6.4 Props
- 6.5 Desestruturação de props
- 6.6 useState
- 6.7 Múltilplos estados e alteração de dados com form
- 6.8 Eventos
- 6.9 Passando Funções de Manipulação de Eventos como Props
- 6.10 Eventos de form
- 6.11 Renderização condicional
- 6.12 Expressão ternária
- 6.13 Render nulo
- 6.14 Listas e Chaves
- 6.15 Estilos por atributo
- 6.16 Estilos globais
- 6.17 Exercícios

* Exercício 1: Componente Funcional Básico

Enunciado:
Crie um componente funcional chamado Greeting que aceita uma prop name e renderiza uma mensagem de boas-vindas. Por exemplo, se a prop name for "João", o componente deve renderizar "Olá, João!".

- Exercício 2: Manipulação de Eventos e Estado

Enunciado:
Crie um componente chamado Counter que renderiza um botão e um texto indicando o número de vezes que o botão foi clicado. Por exemplo, se o botão foi clicado 3 vezes, o texto deve mostrar "Você clicou 3 vezes no botão". Inicialize o contador com 0 e incremente-o a cada clique no botão.

- Exercício 3: Renderização Condicional e Listas

Enunciado:
Crie um componente chamado TaskList que aceita uma prop tasks, que é um array de objetos com id e text. Renderize uma lista ordenada de tarefas, mostrando o texto de cada tarefa. Se não houver tarefas, exiba a mensagem "Não há tarefas a mostrar".

# 7 - Curso React do zero a maestria

# 8 - Avançando em hooks e outros conceitos

- 8.1 useEffect
- 8.2 useContext
- 8.3 useReducer
- 8.4 Custom hooks
- 8.5 Slots e children props
- 8.6 Sincronizando Estado com Props
- 8.7 Performance e Hooks: useMemo e useCallback
- 8.8 Exercícios

- Exercício 1: Uso de useEffect para Sincronização de Dados

Enunciado:
Você precisa exibir informações de um usuário que são recebidas via props em um componente. Crie um componente que use o hook useEffect para sincronizar as informações do usuário com o título do documento (o título da aba no navegador).

- Exercício 2: Memorizando Cálculos com useMemo

Enunciado:
Suponha que você tenha um componente que realiza um cálculo pesado, como uma função de fibonacci que é chamada com um número específico. Use o hook useMemo para evitar que o cálculo seja refeito desnecessariamente.

- Exercício 3: Criação e Uso de um Custom Hook

Enunciado:
Crie um custom hook chamado useOnlineStatus que rastreia se o usuário está online ou offline. Use este hook em um componente para exibir o status atual do usuário.