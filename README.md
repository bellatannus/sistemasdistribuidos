# SistemasDistribuídos
Repositório para trabalhos da disciplina Sistemas Distribuídos 2019/2.

## EquipeFestas :balloon:
<strong>Formalização do Projeto:</strong>

  Sistema de e-commerce para aluguel de equipamentos para festa (CDJ, Controladoras, Caixas de som, fones, máquinas de fumaça, jogos de luzes, projetor, mesas de som, microfones, pedestais de microfone, globos espelhados, lâmpadas negras, lasers...). O empréstimo será feito a partir de um aplicativo, disponível para Android; Cada cliente poderá escolher o tempo que ficará com o(s) equipamento(s), com limite máximo de 5 dias; O valor dos equipamentos é calculado por dia alugado; A forma de pagamento poderá ser cartões de crédito, cartões de débito ou boleto; Um cliente não poderá alugar o(s) mesmo(s) equipamento(s) no mesmo dia que o mesmo  estiver reservado para outro cliente; O(s) equipamento(s) será entregue pelo Entregador para o cliente no dia e hora escolhidos por ele; O Entregador recolherá o(s) equipamento(s) no dia e hora escolhidos pelo cliente.
  
<strong>Componentes:</strong>
  <ul>
    <li> Cliente: interessados em alugar equipamentos de festa
    <li> Servidor
    <li> Aplicação
  </ul>
  
<strong>Testes a serem implementados:</strong>
  <ul>
    <li> Teste de Concorrência: os múltiplos clientes devem poder acessar o sistema ao mesmo tempo, contudo, não é possível alugar um equipamento que já está alugado no dia desejado.
    <li> Teste de Recuperação de Falhas: quando um componente falha, o mesmo volta a executar sem o usuário ter ciência do que aconteceu.
    <li> Demonstração de Funcionalidades: 
      <li> Funcionalidade de CRUD (Criar, ler, atualizar e deletar usuários)
      <li> Login de usuários
      <li> Logout de usuários
      <li> Cadastro de cartão para pagamentos
      <li> Cadastro de endereço de entrega dos equipamentos
      <li> Navegar pelos diferentes tipos, valores e marcas dos equipamentos disponíveis
  </ul>
