# calculator-api
API de Calculadora Spring Boot
API de Calculadora é uma API REST simples construída usando Spring Boot. Esta API fornece operações básicas de uma calculadora, como adição, subtração, multiplicação e divisão.

Requisitos
Java 17 ou superior
Maven
IntelliJ IDEA (ou qualquer outro IDE de sua preferência)

Abra o projeto no IntelliJ IDEA ou no seu IDE preferido.

Execute o aplicativo clicando com o botão direito do mouse na classe principal (por exemplo, CalculatorApiApplication.java) e selecionando 'Run'.

Após executar o aplicativo, a API estará disponível e pode ser acessada através das seguintes URLs:

Adição: http://localhost:8080/add?num1={num1}&num2={num2}
Subtração: http://localhost:8080/subtract?num1={num1}&num2={num2}
Multiplicação: http://localhost:8080/multiply?num1={num1}&num2={num2}
Divisão: http://localhost:8080/divide?num1={num1}&num2={num2}
Substitua {num1} e {num2} pelos números que você deseja calcular.

API Endpoints
GET /add: Retorna a soma de dois números. Exige num1 e num2 como parâmetros de consulta.
GET /subtract: Retorna a subtração de dois números. Exige num1 e num2 como parâmetros de consulta.
GET /multiply: Retorna a multiplicação de dois números. Exige num1 e num2 como parâmetros de consulta.
GET /divide: Retorna a divisão de dois números. Exige num1 e num2 como parâmetros de consulta. Retorna uma exceção se num2 for zero, pois a divisão por zero não é permitida.
Contribuição
As contribuições são sempre bem-vindas. Sinta-se à vontade para enviar pull requests ou abrir issues.
