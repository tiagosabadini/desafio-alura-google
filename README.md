
<h1 align="center">
  <br>
  <a href="#"><img src="https://raw.githubusercontent.com/tiagosabadini/desafio-alura-google/main/Ta-Pago-Logo.png" alt="Tá Pago!" width="200"></a>
  <br>
  Tá Pago!
  <br>
</h1>

<h4 align="center">Ajudando a manter o treino dos seus alunos em dia :muscle:</h4>

<p align="center">
  <a href="https://gemini.google.com">
    <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/8/8a/Google_Gemini_logo.svg/120px-Google_Gemini_logo.svg.png"
         alt="Gemini">
  </a>
</p>

<p align="center">
  <a href="#motivacao">Motivação</a> •
  <a href="#funcionalidades">Funcionalidade</a> •
  <a href="#como-testar">Como testar</a> •
  <a href="#creditos">Credits</a> •
</p>

<h2 id="#motivacao">Motivação</h2>
Já conversei com diversos educadores físicos e já presenciei situações em que muitos deles tinham dificuldades em
fazer a cobrança dos seus serviços com seus alunos. O fato de não terem acesso a um sistema de pagamentos que automatize esse processo, exige que muitos façam a cobrança diretamente aos seus alunos o que gera, para muitos, um certo constrangimento.

O Tá Pago! é uma ideia antiga baseada nessas dores, mas hoje vi a possibilidade de fazer essa implementação de forma muito simples
e que, de fato tem uma aplicação real. Este projeto é direcionado para educadores físicos que atuam como: 
  * Personal Trainer;
  * Professores de artes marciais;
  * Professores de dança;
  * Instrutores de qualquer natureza que precisem ter acesso a uma forma de cobrança amigável para que possam focar 100% da sua energia em seus negócios: tornar a vida de seus alunos mais saudável.

<h2 id="#funcionalidades">Funcionalidade</h2>
O sistema aciona os alunos com mensalidades próximas do seu vencimento, com vencimento na data corrente e com mensalidades vencidas.
O acesso é feito a partir de um banco de dados e o Gemini terá o contexto modelado para falar com um aluno específico para cada momento.
O modelo dará instruções ao aluno de como proceder com o pagamento ou alucidará dúvidas que o mesmo possa ter.

<h2 id="#como-testar">Como Testar</h2>
Faça o download do arquivo `App.ipynb` e envie para o <a href="https://gemini.google.com">Google Colab</a>. Crie sua variável (secret) com o nome `GOOGLE_API_KEY` e rode o modelo. 
Para fazer configurações de cenários específicos, modifique os parâmetros do objeto `config` na seção *Enviando a mensagem template inicial*.

<h2 id="#creditos">Créditos</h2>
Desenvolvido por [Tiago Sabadini](https://github.com/tiagosabadini) para o [Desafio da Imersão Alura + Google](https://cursos.alura.com.br/imersao).
