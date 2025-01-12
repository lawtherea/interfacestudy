Exercício do módulo de interfaces do curso de Java do Nélio Alves, na Udemy.

📝 Enunciado do Exercício
Uma empresa deseja automatizar o processamento de seus contratos. O processamento de um contrato consiste em gerar as parcelas a serem pagas para aquele contrato, com base no número de meses desejado.
A empresa utiliza um serviço de pagamento online para realizar o pagamento das parcelas. Os serviços de pagamento online tipicamente cobram um juro mensal, bem como uma taxa por pagamento. Por enquanto, o serviço contratado pela empresa é o do PayPal, que aplica juros simples de 1% a cada parcela, mais uma taxa de pagamento de 2%.
Fazer um programa para ler os dados de um contrato (número do contrato, data do contrato, e valor total do contrato). Em seguida, o programa deve ler o número de meses para parcelamento do contrato, e daí gerar os registros de parcelas a serem pagas (data e valor), sendo a primeira parcela a ser paga um mês após a data do contrato, a segunda parcela dois meses após o contrato e assim por diante. Mostrar os dados das parcelas na tela.

🔑 Conceitos Aplicados no Programa
💡 Encapsulamento:
Os dados do contrato e das parcelas foram encapsulados nas classes Contract e Installment, garantindo uma estrutura organizada e protegida.
💡 Polimorfismo:
Foi aplicado na interface OnlinePaymentService, que é implementada pela classe PaypalService. Essa abordagem permite trocar ou estender o serviço de pagamento de forma flexível.
💡 Herança e Reuso:
Embora o foco não fosse diretamente na herança, a reutilização de código foi promovida ao usar classes e métodos bem estruturados, como o ContractService, que centraliza a lógica do processamento.
💡 Trabalhando com Datas:
A API de datas do Java (LocalDate e DateTimeFormatter) foi utilizada para calcular as datas de vencimento das parcelas de maneira clara e eficiente.
💡 Coleções:
Usei uma lista (ArrayList) para armazenar as parcelas geradas, demonstrando a importância de estruturas dinâmicas no gerenciamento de dados.
