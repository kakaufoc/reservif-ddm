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
 Essa entidade é necessária para cadastrar o cliente (quem realiza a reserva) e seus dados, possuindo os campos id, email, nome, telefone e senha. 
 <br><br>
 
- `idUsuário`: É um atributo do tipo INT. É o responsável por criar um **Id único** para o usuário, que no caso é o cliente que fará a reserva (**CHAVE PRIMÁRIA**).
- `email`: É um atributo do tipo VARCHAR com um tamanho de 45 caracteres. É o responsável por armazenar o e-mail que o usuário cadastrou.
- `nome`: É um atributo do tipo VARCHAR com um tamanho de 45 caracteres. É o responsável por armazenar o nome do usuário.
- `telefone`: É um atributo do tipo VARCHAR com um tamanho de 45 caracteres. É o responsável por armazenar o número de telefone do usuário.
- `senha`: É um atributo do tipo VARCHAR com um tamanho de 45 caracteres. É o responsável por armazenar a senha que o usuário cadastrou.
- `created_at`: É um atributodo tipo DATE. É o responsável por armazenar a data em que o usuário realizou o cadastro.
  
