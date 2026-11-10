| Conceito                                    | O que é?                                                                    | Pensa nele como...                                                            |
| ------------------------------------------- | --------------------------------------------------------------------------- | ----------------------------------------------------------------------------- |
| **Pacote (Package)**                        | Uma pasta que agrupa objetos relacionados.                                  | Uma pasta de um projeto no teu computador.                                    |
| **Transação**                               | Um atalho para uma funcionalidade do SAP.                                   | Um ícone no ambiente de trabalho que abre uma aplicação específica.           |
| **Task (Tarefa)**                           | Um registo das alterações feitas por uma pessoa.                            | A tua área de trabalho pessoal dentro de um projeto.                          |
| **Ordem de Transporte (Transport Request)** | Um contentor que junta alterações para serem enviadas para outros sistemas. | Uma encomenda pronta para ser enviada.                                        |
| **Workbench Request**                       | Tipo de transport request usada para transportar objetos desenvolvidos.     | Uma encomenda com código e desenvolvimentos para entregar noutro ambiente.    |
| **Customizing Request**                     | Tipo de transport request usada para transportar configurações.             | Uma encomenda com definições e parametrizações para entregar noutro ambiente. |
| **Namespace**                               | Uma regra de nomenclatura.                                                  | O código de país num número de telefone ou o domínio num endereço web.        |

---


# Como tudo se relaciona

Imagina que queres criar uma nova funcionalidade.


1. Crias ou alteras um objeto SAP

2. O objeto fica dentro de um Pacote

3. As alterações ficam registadas numa Task

4. A Task faz parte de uma Ordem de Transporte (do tipo workbench requesta)

5. A Ordem é enviada para os outros sistemas SAP (Qualidade ou Produção)

---

# Exemplo do Mundo Real

Imagina uma empresa a construir uma nova funcionalidade.

### Pacote

É a pasta do projeto.


Projeto: Gestão de Veículos

### Objeto SAP

São os ficheiros do projeto.

ex: 
- Tabela

- Programa

- Classe

### Task

Regista o trabalho realizado por um programador.


ex: Pedro altera uma tabela.

### Ordem de Transporte

Agrupa todas as alterações que precisam de ser enviadas.

ex:

- Nova tabela

- Novo programa

- Novas configurações


---