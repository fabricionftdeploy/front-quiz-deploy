<h1 align="center">FastLash 👁️</h1>
<img src="assets/inicial.png" width="100%$">

<h2>Sobre o projeto 🔎</h2>
Fastlash é um site de agendamento de extensão de cílios, desenvolvido com o intuito de facilitar ..
<br><br>

<h2>Tecnologias utilizadas 💻</h2>
<ul>
  <li>Java + Spring Boot;</li>
  <li>Javascript + React;</li>
  <li>HTML + CSSS;</li>
  <li>Banco de dados MySQL.</li>
</ul>
<br>

<h2>Dependências Maven utilizadas ♦️</h2>
<ul>
  <li>Spring Web;</li>
  <li>Spring Data JPA;</li>
  <li>Spring Security;</li>
  <li>MySQL Driver;</li>
  <li>Lombok;</li>
  <li>DevTools;</li>
  <li>Java JWT;</li>
  <li>ModelMapper.</li>
</ul>

<h2>Dependências React utilizadas 🔷</h2>
<ul>
  <li>react</li>
  <li>react-dom;</li>
  <li>axios;</li>
  <li>react-router-dom;</li>
</ul>
<br>
 
<h2>Mecânica de funcionamento do site :hammer: </h2> 

<strong>1</strong> - O cliente cria sua conta passando seus dados de contato e endereço;<br>
<img src="assets/camisa.png" width="300px">

<strong>2</strong> - Com sua conta criada, o cliente loga e adquire a possibilidade de adicionar/remover itens do seu carrinho;<br>
<img src="assets/carrinho.png" width="300px">

<strong>3</strong> - Com ao menos um item no carrinho, o cliente ganha direito a fazer um pedido, passando a forma de pagamento e o parcelamento;<br><br>
<img src="assets/form.png" width="300px">

<strong>4</strong> - Com um pedido confirmado, o mesmo é gerado, salvo e exibido instantaneamente no menu administrativo;<br>
<img src="assets/pedido.png" width="300px">

<strong>5</strong> - O administrador ao receber o pedido, pode aceitá-lo ou recusá-lo. Caso aceite, ele deverá através de algum dos dados de comunicação do cliente estabelecer contato com o mesmo, para lhe passar a cobrança selecionada. Caso rejeite, deverá devolver uma mensagem explicando o motivo.<br>
<img src="assets/pedido-adm.png" width="500px">
<br><br>
 
<h2>Ações do cliente</h2> 
<ul>
  <li>Agendar seu atendimento, passando todas suas informações pessoais, de endereço e fisionomia.</li>
</ul>
<br>
 
<h2>Ações do administrador</h2>
<ul>
  <li>Vizualizar todos agendamentos;</li>
  <li>Defifnir/editar o procedimento de cada agendamento;</li>
  <li>Agendar cada procedimento na agenda;</li>
  <li>Vizualizar todos procedimentos na agenda;</li>
  <li>Definir o status de cada agendamento (pendente, agendado, concluído).</li>
</ul>
<br>
 
<h2>Segurança do site :lock:</h2> 
O projeto possui um sistema de tokens JWT, o que faz com que somente usuários com papel de administrador possam acessar/controlar o menu administrativo. Além disso, o sitestema também conta com conceitos de DTO's e criptografia, para uma maior proteção às suas entidades.
<br><br>

<h2>Passo a passo para rodar o front-end em seu PC</h2>
<ul>
  <li>Possua o node.js instalada em seu PC;</li>
  <li> Baixe ou clone o projeto em seu PC;</li>
  <li>Abra a pasta front-end em alguma IDE (recomendo o Vs Code);</li>
  <li>Logo após, abra o terminal de comando da IDE e selecione a pasta raiz do front-end, que no caso é a própria "front-end", para isso utilize o comando "cd" seguido do caminho onde está a sua pasta front-end em seu PC. Exemplo: "C:\Users\fabri\OneDrive\Área de Trabalho\PROJETOS\fastlash\front-end"</li>
  <li>Já com a pasta raiz selecionada, rode o comando "npm install" para instalar todas as dependências necessárias;</li>
  <li>Feito isso, rode o comando "npm run dev" e voa lá, o site subirá para o ar na porta 5173 (pode ser outra, caso a 5173 já esteja em uso em seu PC).</ul>
<br>

<h2>Passo a passo para rodar o back-end em seu PC</h2>
<ul>
  <li>Possua uma JDK 17 ou superior instalada em seu PC;</li>
  <li> Baixe ou clone o projeto em seu PC;</li>
  <li> Abra a pasta back-end em alguma IDE (recomendo o Intelij);</li>
  <li>Configure algum banco de dados MySQL, seja ele local ou de algum serviço externo (recomendo os do site RailWay) dentro do applications.properties. Para isso você precisa do host, nome, porta, usuario e senha do banco de dados;</li>
  <li>Dê build ou compile no projeto usando alguma IDE (recomendo Intelij), para baixar todas as dependências;</li>
  <li>Por fim, dê start na classe principal do projeto (FutshopApplication) e pronto, ele já funcionará.</li>
</ul>
<br>

Obs: É necessário que ambas as partes tenham sido inciadas da forma correta para tudo funcionar normalmente. Atente-se a configuração dos Allowed COR'S no back-end, as vezes a porta que você está rodando o front-end não está definida lá, o que faz com que a política de COR'S bloqueie o uso das rotas pelo front-end. 
<br><br>
 
<h2>Link video 📺</h2>
Estará aqui quando postado
<br><br>

<h2>Link site :zap:</h2>
estará aqui quando estiver no ar
<br><br>

<h2>Autor :raising_hand:</h2>

| [<img src="assets/perfil.jpg" width=115><br><sub>Fabrício Ferreira Tavares</sub>](https://github.com/fabricionft) | 
| :---: | 
