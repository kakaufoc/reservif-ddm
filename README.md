<h1 align="center"> PROJETO APLICATIVO "RESERVIF" - DDM </h1>
<p align="center">Um trabalho para a disciplina de DESENVOLVIMENTO DE DISPOSITIVOS MÓVEIS - 4º Informática do IFSP-Jacareí</p>
<br>
<p align="center">
<h1>👨‍🏫 Professor responsável </h1> 

Carlos Eduardo Duque Polito 

<h1>🎯 Objetivo do aplicação</h1> 
O objetivo dessa aplicação é desenvolver um aplicativo que facilite a solicitação de reservas de espaços para atividades pedagógicas no IFSP - CAMPUS JACAREÍ. 
<br>

<h1>👥 Público-alvo</h2>
Nosso público alvo é toda a comunidade escolar do IFSP - JCR, todos que desejarem maior facilidade na solicitação de reservas de espaços para atividades pedagógicas no campus. 

<h1><span style='font-size:100px;'>&#128311;</span>Funcionalidades do projeto:</h2>

- `Registro de clientes`: Um sistema de cadastro de clientes onde seus dados serão enviados a um banco de dados.
- `Autenticação de conta`: Uma vez já cadastrado e tendo seus dados autenticados, o usuário poderá realizar seu login no aplicativo. 
- `Reserva de espaços para atividades pedagógicas`: É disponibilizado um formulário onde o usuário poderá inscrever informações sobre o evento que deseja realizar. Caso o horário e local escolhido esteja disponível, o usuário conseguirá solicitar sua reserva para a CAE, que poderá ou não aprovar a solicitação.
- `Edição de eventos e informações sobre o perfil`: Nessas abas o usuário poderá alterar informações sobre seu perfil e poderá também excluir ou editar seus eventos criados.
  
<h1><span style='font-size:100px;'>&#128203;</span> Requisitos não funcionais para o site</h1> 
Para o total funcionamento, a aplicação deve conter:

- `Responsividade`: Capacidade de responder a algo de forma rápida e adequada, adaptando-se às circunstâncias. 
- `Desempenho`: O APP deverá funcionar com o melhor desempenho possível.
- `Segurança`: O APP deve garantir que os dados do cliente estejam em segurança.

<h1><span style='font-size:100px;'>&#128203;</span>Matriz de Requisitos</h1>
<img src="https://github.com/user-attachments/assets/c04a4092-8ba2-4c04-871f-710537e11c3e" width = 1000>

<h1>📊 Relacionamento de Dados </h1> 
<img src="https://github.com/user-attachments/assets/d451428d-7384-4ac6-9034-60d587089bdc" width=1000> 

<h1>📖 Dicionário de Dados</h1> 

Esse projeto contará com as seguintes Entidades e atributos

<h2>Entidade Usuário</h2>
 Essa entidade é necessária para cadastrar o cliente e seus respectivos dados.
 <br><br>
 
- `username`: É um atributo do tipo VARCHAR com um tamanho de 45 caracteres. Ele armazena o nome que o usuário cadastrará.
- `email`: É um atributo do tipo VARCHAR com um tamanho de 45 caracteres. É o responsável por armazenar o e-mail que o usuário cadastrou.
- `senha`: É um atributo do tipo VARCHAR com um tamanho de 45 caracteres. É o responsável por armazenar a senha que o usuário cadastrou.
- `prontuário`: É um atributodo tipo VARCHAR com um tamanho de 9 caracteres. É o responsável por armazenar o prontuário que o usuário cadastrou.

<h2>Entidade Eventos</h2>
 Essa entidade é necessária para cadastrar o evento que o usuário deseja fazer a solicitação. 
 <br><br>
 
- `id_event`: É um atributo do tipo INT responsável por criar uma identidade única para cada evento criado pelos usuários.
- `data_started`: É um atributo do tipo DATE. É o responsável por armazenar a data em que o usário deseja criar o evento.
- `data_end`: É um atributo do tipo DATE. É o responsável por armazenar a data em que o uusário deseja finalizar o evento.
- `descriçãodoevento`: É um atributodo tipo VARCHAR com um tamanho de 250 caracteres. É o responsável por armazenar a descrição do evento que o usuário deseja criar
- `event_name`: É um atributo do tipo VARCHAR com um tamanho de 45 caracteres. É o responsável por armazenar o nome do evento que o usuário deseja criar para a reserva.

<h2>Entidade Salas</h2>
 Essa entidade é necessária para cadastrar as salas disponíveis para realização de eventos. 
 <br><br>
 
- `id_rooms`: É um atributo do tipo INT responsável por criar uma identidade única para cada evento criado pelos usuários.
- `rooms_types`: É um atributo do tipo VARCHAR com um tamanho de 45 caracteres. É o responsável por armazenar o tipo das salas disponíveis para eventos.
- `rooms_names`: É um atributo do tipo VARCHAR com um tamanho de 45 caracteres. É o responsável por armazenar o nome das salas disponíveis para eventos.

<h2>Entidade Eventos Expirados</h2>
 Essa entidade é necessária para cadastrar os eventos que já expiraram. 
 <br><br>
 
- `id_event`: É um atributo do tipo INT responsável por criar uma identidade única para cada evento criado pelos usuários.
- `data_started`: É um atributo do tipo DATE. É o responsável por armazenar a data em que o usário deseja criar o evento.
- `data_end`: É um atributo do tipo DATE. É o responsável por armazenar a data em que o uusário deseja finalizar o evento.
- `descriçãodoevento`: É um atributodo tipo VARCHAR com um tamanho de 250 caracteres. É o responsável por armazenar a descrição do evento que o usuário deseja criar
- `event_name`: É um atributo do tipo VARCHAR com um tamanho de 45 caracteres. É o responsável por armazenar o nome do evento que o usuário deseja criar para a reserva.

<h1>🧍Diagramas UML</h1>
<h2>Tela de Login e Cadastro</h2>
<img src="https://github.com/user-attachments/assets/cb65be56-2ea6-4079-b689-b70429d4490b" width=1000>
<h2>Tela inicial, quartos e reserva</h2>
<img src="https://github.com/user-attachments/assets/3afa9e98-c9fa-416e-a6ac-0a7eca64ab13" width=1000>


  
