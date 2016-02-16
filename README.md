
Utilização do SoupUI para Testes em Web Services .NET
SoupUI - Ferramenta de Teste para Web Services, trata-se de um
projeto Open Source que pode ser obtido no site: https://www.soapui.org/.

Existe uma versão profissional que se chama SoupUI NG Pro que pode ser
obtida pelo mesmo site.

SoupUI é uma das mais populares ferramentas de testes para testes de Web Services. 
É capaz de testar qualquer tipo de Web Service, a saber:
- SOAP Web Services
- RESTful Web Services 
- HTTP based services

Para gerar um projeto de teste no SoupUI para um Web Service SOAP deve se ter
o URL do WSDL que o descreve, por exemplo: http://10.15.1.110/GCSServer/Service.asmx?WSDL
Nele está especificado o Web Service CalculatorWebServiceSoup. Web Service aonde se
realizou o teste unitário com NUnit.

Assim como no teste unitário realizado como no NUnit, o SoupUI lhe permite realizar 
testes nos métodos disponibilizados no Web Service, para o exemplo:
  - Add
  - Division
  - Multiply
  - Subtract

Com em no NUnit pode-se realizar testes com os respectivos "Assertions". Para isto basta criar 
o que o SoupUI chama de TestSuit, dentro dele especificar o que o SoupUI chama de TestCases.
Para cada TestCase cria-se os TestSteps que para o exemplo do Web Service CalculatorWebServiceSoup 
seria um teste para cada  operação da calculadora, a saber: Add,Division,Multiply,Subtract.

A versão Open Source ainda permite o teste de carga para verificar o funcionamento do WebService
poderá ter em ambiente de produção.
Também é possível realizar o teste de Segurança, como por exemplo: SQL Injection, XPath Injection.
