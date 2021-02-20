# Chat MultiCast em Java

## Autor
* Augusto Coutinho Freitas

## Orientador
* Hugo de Paula

## Instruções de utilização

O projeto esta com algum problemas pois eu nao soube usar o Observable list para ir adicionando as mensagens recebidas.

* CRIAR SALA - Pensei em que o Usuario poderia Escolher o nome da Sala e o programa geraria um ip disponivel.

* LISTAR SALAS - Quando se cria uma sala, ela é adicionada ao um arrayList, onde a minha ideia seria salvar em um arquivo.txt para quando o usuario entrar na aplicaçao, mostrar as salas disponiveis.(Nao implementado por falta de tempo).

* ENTRA NA SALA - teria uma tableView com todas as sala disponiveis, o usuario so teria que selecionar uma sala para poder acessa-la.

* LISTAR MEMBROS DA SALA - Nao implementado.

* SAIR DA SALA - Quando o usuario clicar no btn_sairSala possuir o ActionEvent - mSocket.leaveGroup(ipDaSala);

* ENVIAR MENSAGEM - O projeto esta eviando a msg para o Multicastpeer e recebendo de volta, mas estou com problema ao ultilizar o TableView com o ObsarvableList.
