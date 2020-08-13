### Olá 😬🤙

Você já deve saber meu nome, porque leu ali ao lado ⏪ certo? (ou olhou agora para ler). Então queria contar outros coisas sobre mim.

Possuo domínio de HTML e CSS para iniciar um projeto hoje mesmo. Também já criei algumas funções e recursos básicos em Javascript, mas ainda tenho muito o que aprender 👨‍💻.

Meus próximos passos serão estudar React, Node e Banco de dados. E num futuro não tão distante, quero me aprofundar em UX/UI.

Minhas área de interesse são:

🖥️ Desenvolvimento Web  
📱 Desenvolvimento Mobile  
🖌️ Front-end  
📁 UX Design  

Estudo programação majoritariamente online 💻 desde 2019.

<!--

Os projetos que mais gostei de ter realizado foram:

...

-->

Atualmente sou Desenvolvedor Front-end na [Vnda - Tecnologia em Ecommerce](https://www.vnda.com.br/).

Decidi seguir na área de desenvolvimento após adquirir experiência em suporte de TI 🛠️ e Marketing Digital 📣. Nesta última, trabalhei com:

💬 Redes sociais  
📝 Blog  
🔍 SEO  
🌎 WordPress  
👨‍💻 CSS  

Sou graduado em Administração com ênfase em Marketing (PUCRS), técnico em Publicidade (ETCR) e técnico em Redes de Computadores (SENAI).

No trabalho voluntário que tive na ONG Associação 101 Viralatas 🐶🐱 (Viamão/RS), tive uma boa vivência com edição de vídeo usando o Adobe Premiere e tratamento básico de imagens com Photoshop.

Meus principais hobbies são:

⚽ Jogar futebol  
🍻 Sair com amigos  
📚 Ler  
✍️ [Escrever](https://medium.com/@aaamenezes)  
🎸Tocar violão  
🎮 Jogar vídeo game  

Quer conversar sobre algum projeto, pedir alguma ajuda, ou apenas falar sobre como é prazeroso usar `display:grid`?

Então pode me contatar no meu [e-mail](mailto:1992menezes@gmail.com) (1992menezes@gmail.com) ou no [Linkedin](https://www.linkedin.com/in/aaamenezes).

Muito prazer!

# Diário de bordo de aprendizados
Daqui em diante, você poderá acompanhar um Diário de Bordo de coisas que aprendo ao longos dos dias:

## Validação de campos de formulário
**Quarta-feira, 12/08/2020**

Utilizei Javascript para fazer a formatação de um campo de telefone com parênteses e um ponto separando os dígitos.

```
let inputTelefone = document.getElementById('telefone-whatsapp')

inputTelefone.addEventListener('blur', function() {

  let number = inputTelefone.value
  number = number.replace('(', '')
  number = number.replace(')', '')
  number = number.replace('.', '')
  number = number.replace(' ', '')
  number = number.replace('-', '')
  
  number = `(${number.substring(0,2)}) ${number.substring(2,7)}.${number.substring(7,11)}`
  inputTelefone.value = number
})
```

## Babel
**Terça-feira, 21/07/2020**  

Instalei e executei pela primeira ver o Yarn, gerando o bundle.js a partir do arquivo main.js.

Grande recurso para executar em todos os navegadores.

## Ajax, Promises e Axios
**Sábado, 18/07/2020**  

Aprendi a fazer requisições à API do Github (https://api.github.com/users/[nome_usuario]), buscar informações dos usuários e montar uma página HTML com essas informações.

## Storage do browser com Javascript
**Sábado, 18/07/2020**  

No [projeto de Lista de tarefas](https://github.com/aaamenezes/Lista-de-tarefas-com-Bootstrap) utilizei o comando `localStorage.setItem` para armazenar as tarefas da lista no banco de dados do navegador.

## Comandos de Javascript
**Sexta-feira, 17/07/2020**  

Apliquei alguns comandos de Javascript para desenvolver o [projeto de Lista de tarefas](https://github.com/aaamenezes/Lista-de-tarefas-com-Bootstrap):

```
document.createElement
document.createTextNode
.setAttribute
.appendChild
.removeChild
```

## SwiperJS
**Sexta-feira, 03/07/2020**  

Instalei o SwiperJS para realização de um [desafio](https://github.com/aaamenezes/vnda-frontend-challenge-junior).

## Funções em Python
**Terça-feira, 30/06/2020**  

Usei funções em Python pela primeira vez para reaproveitar código, facilitar a leitura e diminuir o número de linhas de um pequeno projeto para a faculdade

## Modulos
**Sábado, 20/06/2020**

Aprendi uma introdução sobre os módulos do Javascript, como separar, exportar e importar funções em diferentes arquivos.

## Javascript: setInterval()
**Quarta-feira, 17/06/2020**

Em vez de esperar um evento na DOM para executar uma função (evento esse que nem sabia qual era), deixei o setInterval() executar ela a cada 1 segundo.  

Como era um script pequeno e para aprendizado, não pesou a execução.
