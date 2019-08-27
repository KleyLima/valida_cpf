# valida_cpf

1 - função de verificação e retirada de quaisquer formatações com a seguinte assinatura: *retira_formatacao(num_cpf)*
2 - função de validação do número do CPF sem formatação com a seguinte assinatura: *valida_cpf(num_cpf)*

essas funções devem estar num arquivo com a seguinte nomenclatura: validacpf_<nome>.py (onde <nome> é o primeiro nome de cada um de vocês)

MAIS IMPORTANTE: *TDD (Test Driven Development)*
podem utilizar o unittest (https://docs.python.org/2/library/unittest.html#basic-example) para implementação de testes.

os testes devem contemplar ambas as funções.
exemplos de testes: 

123.456.789-01 -> saida da retirada de formatacao deve ser igual a 12345678901
11111111111 -> todos os digitos repetidos não devem ser aceitos

*COMECEM PELOS TESTES!!!*
