# Que bom que você está aqui 😬🤙

Quero contar algumas coisas sobre mim, desde que comecei a estudar programação online em 2019.

## O que eu já sei 💪

Possuo domínio de **HTML** e **CSS** para iniciar um projeto hoje mesmo.  

Também já criei algumas funções e recursos básicos em **Javascript**, mas ainda tenho muito o que aprender 👨‍💻.  

No momento estou praticando **React.JS** no projeto [Caosfonia](https://github.com/aaamenezes/caosfonia).

## O que eu ainda quero descobrir 🔍

Também tenho interesse em conhecer **Node**, **Flutter** e **Banco de dados**. E num futuro não tão distante, quero me aprofundar em **UX/UI**.

Minhas área de interesse são:

🖥️ Desenvolvimento Web  
📱 Desenvolvimento Mobile  
🖌️ Front-end  
📁 UX/UI Design  

<!--

## Os projetos que mais gostei de ter realizado foram:

...

-->

## Por onde já passei 💼

Atualmente sou Desenvolvedor Front-end na [Vnda - Tecnologia em Ecommerce](https://www.vnda.com.br/). É minha primeira experiência como dev.  
Atuo com **HTML5**, **CSS3** (usando o pré-processador **SASS**) e **Liquid** (uma linguagem de template criada pela [Shopify](https://shopify.github.io/liquid/)).

Decidi seguir na área de desenvolvimento após adquirir experiência em suporte de TI 🛠️ e Marketing Digital 📣. Nesta última, onde iniciei e estruturei o setor da Marketing Digital da [WK JobHub](https://www.wkrh.com.br/), trabalhei com:

💬 Redes sociais  
📝 [Blog](https://wkrh.com.br/blog/) (postagens feitas de 06/2018 a 07/2020)  
🔍 SEO  
🌎 WordPress  
👨‍💻 CSS  

No trabalho voluntário que fiz na ONG Associação 101 Viralatas 🐶🐱 de Viamão/RS ([Facebook](https://www.facebook.com/ONG101viralatas/) / [Instagram](https://www.instagram.com/101viralatas/)), tive uma boa vivência com edição de vídeo usando o Adobe Premiere e tratamento básico de imagens com Photoshop.

## Estudos e qualificações 👨‍🎓

<!-- 👨‍💻 Graduando em Sistemas para Internet (SENAC) - 1º semestre   -->
📣 Brand Design - Gestão de Marca (4ED)  
📣 Técnico em Publicidade (ETCR)  
🖌️ Design Gráfico (Alfamídia)  
📈 Graduado em Administração com ênfase em Marketing (PUCRS)  
🖥️ Técnico em Redes de Computadores (SENAI)  

## Meus principais hobbies 🏖️

⚽ Jogar futebol  
🍻 Sair com amigos  
📚 [Ler](https://www.skoob.com.br/usuario/1298580)  
✍️ [Escrever](https://medium.com/@aaamenezes)  
🎸 Tocar violão  
🎮 Jogar vídeo game  (Atualmente, estou jogando Silent Hill do PS2)

Quer conversar sobre algum projeto, pedir alguma ajuda, ou apenas falar sobre como é prazeroso usar o `{display: grid;}`?

Pode me contatar por e-mail `1992menezes@gmail.com` ou qualquer rede abaixo:

[![linkedin](https://img.shields.io/badge/%20-Linkedin-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/aaamenezes) [![instagram](https://img.shields.io/badge/%20-Instagram-E47AAE?style=for-the-badge&logo=instagram&logoColor=white)](https://www.instagram.com/aaamenezes/) [![twitter](https://img.shields.io/badge/%20-Twitter-1DA1F2?style=for-the-badge&logo=twitter&logoColor=white)](https://twitter.com/aaamenezes) [![medium](https://img.shields.io/badge/%20-Medium-292929?style=for-the-badge&logo=medium&logoColor=white)](https://medium.com/@aaamenezes)

Muito prazer!

---

# Diário de bordo de aprendizados
Daqui para baixo, você poderá acompanhar um Diário de Bordo de coisas que aprendo ao longos dos dias:

## Gerador de acordes musicais para artistas

**Segunda-feira, 09/11/2020**

Estou registrando hoje, mas iniciei esse projeto há algumas semanas já.  

Estou criando meu segundo projeto para treinar o que estou aprendendo em React, o [Caosfonia](https://github.com/aaamenezes/caosfonia).

## Gerador de números das Mega-Sena com React.JS

**Sábado, 03/10/2020**

Minha primeira aplicação em React.JS, um gerador de números da Mega-Sena.  

Falei bastante dessa experiência numa postagem no meu [LinkedIn](https://www.linkedin.com/posts/aaamenezes_react-reactjs-js-activity-6718598035879858176--0o0).

## SPA
**Quinta-feira, 10/09/2020**

Criei uma SPA pela primeira vez usando React.JS.

## [AOS](https://github.com/michalsnik/aos) (Animate on Scroll)
**Terça-feira, 01/09/2020**

Conheci e utilizei no site de um cliente a biblioteca AOS para aplicar animações e deixar o front mais atraente para os visitantes.  

Alguns efeitos legais dessa biblioteca podem ser conferidos [aqui](https://michalsnik.github.io/aos/) e [aqui](https://codepen.io/michalsnik/pen/WxNdvq).

## jQuery Mask Plugin
**Sexta-feira, 14/08/2020**

O site de um cliente tem um campo para o usuário informar seu número de telefone. Porém alguns usuários não forneciam o código de área, e isso dificultava alguns contatos.  

Então apliquei o jQuery Mask Plugin para formatar o campo, exibindo os parênteses assim que o usuário digitasse o primeiro dígito.

## Tratamento de input:date
**Quinta-feira, 13/08/2020**

Montei um script JS para que o usuário não possa escolhar datas que sejam iguais a hoje ou passadas. Caso isso aconteça, o campo muda para a data de amanhã e uma mensagem de alerta surge pedindo para que ele escolha uma data futura.

Quando uma data válida é escolhida, o alerta some.

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
