# Bytebank
## Projeto de estudos - Orientação a objeto

>>> Status do projeto: Finalizado.

Projeto para simular um modelo para conta corrente e clientes do banco fictício Bytebank.
O projeto tem o objetivo de desenvolver habilidades como:

- Desenvolver conceitos relacionados a classe da orientação a objetos, assim como propriedades e métodos e compreender seu comportamento
- Trabalhar com namespaces
- Conceito de encapsulamento e modificadores de acesso
- Construtores e membro estático

## Features

- Instanciar a classe ContaCorrente e Cliente
- Métodos para depositar, sacar e transferir.


# Utilizando o programa
```sh
No editor de código foi:
1 -Instanciada a classe, após ser escrito todo o código dela:
ContaCorrente conta3 = new ContaCorrente();
2- Definimos na instância seus atributos:
conta3.Numero_agencia = 18;
conta3.Conta = "1011-H";
conta3.SetSaldo(200);
3 - Definimos o cliente titular da conta e a conta recebe esse valor:
Cliente cliente = new Cliente();
cliente.Nome = "vinicius";
cliente.Cpf = "111111111";
cliente.Profissao = "dev";
conta3.Titular = cliente;
4 - Por fim já temos nossa conta, podemos imprimir suas informações com:
Console.WriteLine(conta3.GetSaldo());
Console.WriteLine(conta3.Numero_agencia);
Console.WriteLine(conta3.Conta);
Console.WriteLine(conta3.Titular.Nome);
Console.WriteLine(conta3.Titular.Cpf);
Console.WriteLine(conta3.Titular.Profissao);
```
# Utilizando métodos
```sh
Podemos transferir para outra conta com:
contaAtual.Transferir(valor, contaDeDestino);
Podemos depositar com:
contaAtual.Depositar(valor);
Podemos sacar com:
contaAtual.Sacar(valor);
Para conferir o saldo atualizado após o método:
Console.WriteLine(contaAtual.GetSaldo());
```
