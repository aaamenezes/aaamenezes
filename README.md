# Que bom que você veio 😬🤙

Quero contar algumas coisas sobre mim, desde que comecei a estudar programação online em 2019.

## O que eu já sei 💪

Possuo domínio de HTML e CSS para iniciar um projeto hoje mesmo.  

Também já criei algumas funções e recursos básicos em Javascript, mas ainda tenho muito o que aprender 👨‍💻.

## O que eu ainda quero descobrir 🔍

Meus próximos passos serão estudar React, Node e Banco de dados. E num futuro não tão distante, quero me aprofundar em UX/UI.

Minhas área de interesse são:

🖥️ Desenvolvimento Web  
📱 Desenvolvimento Mobile  
🖌️ Front-end  
📁 UX Design  

<!--

Os projetos que mais gostei de ter realizado foram:

...

-->

## Por onde já passei 💼

Atualmente sou Desenvolvedor Front-end na [Vnda - Tecnologia em Ecommerce](https://www.vnda.com.br/). É minha primeira experiência como dev.

Decidi seguir na área de desenvolvimento após adquirir experiência em suporte de TI 🛠️ e Marketing Digital 📣. Nesta última, onde iniciei e estruturei o setor da Marketing Digital da [WK JobHub](https://www.wkrh.com.br/), trabalhei com:

💬 Redes sociais  
📝 Blog  
🔍 SEO  
🌎 WordPress  
👨‍💻 CSS  

No trabalho voluntário que fiz na [ONG Associação 101 Viralatas](https://www.facebook.com/ONG101viralatas/) 🐶🐱 de Viamão/RS, tive uma boa vivência com edição de vídeo usando o Adobe Premiere e tratamento básico de imagens com Photoshop.

## Estudos e qualificações 👨‍🎓

👨‍💻 Graduando em Sistemas para Internet (SENAC) - 1º semestre  
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
