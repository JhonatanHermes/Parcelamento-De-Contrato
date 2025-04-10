# Parcelamento de Contrato

Este projeto é um exercício em Java para simular o parcelamento de um contrato com base na data, valor e número de parcelas. Ele utiliza conceitos de orientação a objetos, datas e formatação.

## 📚 Tecnologias usadas

- Java 8+
- Orientação a Objetos (POO)
- Manipulação de datas com `LocalDate` e `DateTimeFormatter`
- Interface `OnlinePaymentService` com implementação via PayPal

## 💡 Como funciona

O usuário deve informar:
- Número do contrato
- Data do contrato
- Valor total
- Número de parcelas

O programa então calcula o valor de cada parcela com acréscimos de juros mensais e taxa de pagamento. Em seguida, exibe as datas e valores de cada parcela.

