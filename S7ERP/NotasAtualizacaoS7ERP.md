# Notas de Atualização - S7ERP

### 11.20I (30/12/2020)

#### Melhoria

 * **Rotina 609**: Criado novo campo "Vl. Tot. Títulos" na Dialog do detalhamento do Desdobramento, que se encontra na aba "Destino" 
 * **Rotina 201**: Implementada usabilidade onde somente deve aparecer os CST IPI, CST PIS, e CST COFINS de Entrada.
 * **Rotina 615**: Adicionado tratamento para que usuário só consiga fazer sangria de um caixa banco onde o mesmo teve movimentação do dia considerando: Usuário, Data e Caixa Banco.
 * **Rotina 506**: Criado na aba “Checkout” o novo parâmetro “Permite Acesso ao Checkout?”. Parâmetro tem como finalidade permitir o usuário a ter acesso ao Frente de Caixa (PDV)
 * **Rotina 103**: Adicionado vídeo da rotina 103

 #### Correção
 
 * **Rotina 113**: Implementada validação que não permite o usuário desmarcar opção "Usa Lote", se o produto selecionado estiver com quantidade diferente de ZERO.
 * **Rotina 301**: Implementada correção do percentual de desconto ao utilizar ***Negociação por Cliente***
 * **Rotina 308**: Tratar o travamento do campo de busca do vendedor, quando se utiliza o parâmetro "Vendedor é usuário logado?", o mesmo não estava respeitando quando o usuário limpava as informações do filtro.
 * **Rotina 201**: Implementada correção ao importar XML, o sistema não estava tratando a nova técnica ***2019.001 Versão 1.20***
 

