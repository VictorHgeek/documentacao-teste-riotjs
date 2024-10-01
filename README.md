# documentacao-teste-riotjs
Cenário 1 - Inserir item<br>
Given acesse o site https://todomvc.com/riotjs<br>
When clicar sobre campo de inserção<br>
And inserir valor "olá mundo"<br>
And clicar enter<br>
Then deverá inserir "olá mundo"<br>

Cenário 2 - Check de item<br>
Given acesse o site https://todomvc.com/riotjs<br>
And clicar sobre campo de inserção<br>
And inserir valor "olá mundo"<br>
And clicar enter<br>
When clicar sobre checkbox<br>
Then deverá ficar com check<br>

Cenário 3 - Validação dos itens<br>
Given acesse o site https://todomvc.com/riotjs<br>
And clicar sobre campo de inserção<br>
And inserir valor "olá mundo"<br>
And clicar enter<br>
And clicar sobre checkbox<br>
When clicar sobre All Completed<br>
Then deverá conter item com check<br>

Cenário 4 - Limpeza de item<br>
Given acesse o site https://todomvc.com/riotjs<br>
And clicar sobre campo de inserção<br>
And inserir valor "olá mundo"<br>
And clicar enter<br>
And clicar sobre checkbox<br>
When clicar sobre Clear completed<br>
Deverá limpar o item<br>

<table>
  <tr>
    <th>Campo</th>
    <th>Descrição</th>
  </tr>
  <tr>
    <td>ID do Bug</td>
    <td>BUG-001</td>
  </tr>
  <tr>
    <td>Data</td>
    <td>01/10/2024</td>
  </tr>
  <tr>
    <td>Testador</td>
    <td>Victor Hugo</td>
  </tr>
  <tr>
    <td>Resumo</td>
    <td>O botão "Enviar" na página de formulário não responde ao clique.</td>
  </tr>
  <tr>
    <td>Passos para Reproduzir</td>
    <td>
      1. Acesse a página de formulário.<br>
      2. Preencha todos os campos obrigatórios.<br>
      3. Clique no botão "Enviar".
    </td>
  </tr>
  <tr>
    <td>Resultado Esperado</td>
    <td>O formulário deve ser enviado e uma mensagem de sucesso deve ser exibida.</td>
  </tr>
  <tr>
    <td>Resultado Obtido</td>
    <td>O botão não responde e não há feedback para o usuário.</td>
  </tr>
  <tr>
    <td>Severidade</td>
    <td>Alta</td>
  </tr>
  <tr>
    <td>Sistema Operacional</td>
    <td>Windows 10</td>
  </tr>
  <tr>
    <td>Navegador</td>
    <td>Chrome 115</td>
  </tr>
  <tr>
    <td>Versão da Aplicação</td>
    <td>1.0.0</td>
  </tr>
  <tr>
    <td>Anexos</td>
    <td>Screenshot do erro</td>
  </tr>
  <tr>
    <td>Observações Adicionais</td>
    <td>O problema ocorre apenas no navegador Chrome.</td>
  </tr>
</table>
