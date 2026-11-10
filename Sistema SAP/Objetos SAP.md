

Os objetos SAP são os diferentes componentes utilizados para construir funcionalidades dentro do sistema.

Cada objeto tem uma responsabilidade específica. Alguns são utilizados para armazenar dados, outros para implementar regras de negócio e outros para permitir a interação com o utilizador.

À medida que fores aprendendo SAP, vais encontrar estes objetos repetidamente e perceber como trabalham em conjunto.

---

## Uma Funcionalidade SAP É Feita de Várias Peças

Imagina que queres criar um sistema para gerir colaboradores.

Primeiro precisas de guardar informação:

	Nome
	
	Data de Nascimento
	
	Nº Funcionário

Depois precisas de permitir que alguém consulte essa informação.

Depois precisas de permitir pesquisas.

Depois precisas de criar regras de negócio.

Cada necessidade é resolvida por um objeto diferente.

---

## Primeiros Objetos a Conhecer

### Domain

Define as características técnicas de um valor.

Exemplo:

	Número inteiro
	
	8 caracteres
	
	Data
	
	Texto

Pergunta que responde:

	"Que tipo de valor pode ser guardado?"

---

### Data Element

Define o significado de um valor.

Exemplo:

	Employee ID
	
	Start Date
	
	Employee Name

Pergunta que responde:

	"O que representa este campo?"

---

### Table

Guarda os dados.

Exemplo:

	Funcionário 1000
	
	Funcionário 1001
	
	Funcionário 1002

Pergunta que responde:

	"Onde os dados ficam armazenados?"

---

### Search Help

Ajuda o utilizador a encontrar valores.

Exemplo:

	Pesquisar colaborador pelo nome
	
	e devolver o ID

Pergunta que responde:

	"Como ajudar o utilizador a encontrar um valor?"

---

### Program / Class

Contêm a lógica da aplicação.

Exemplo:

	Calcular antiguidade
	
	Validar dados
	
	Gerar relatórios

Pergunta que respondem:

	"O que o sistema deve fazer?"

---

### Transaction

Permite executar uma funcionalidade.

Exemplo:

	VA03
	
	SE11
	
	ME23N

Pergunta que responde:

	"Como o utilizador acede à funcionalidade?"

---

## Como Tudo se Liga?

	Domain
	
	↓ é usado por um
	
	Data Element
	
	↓ é atribuído ao campo de uma
	
	Table
	
	↓ pode ser associada à uma
	
	Search Help
	
	↓ Pode ser usada num
	
	Program / Class
	
	↓ Pode estar ligado a uma
	
	Transaction
	
	↓ é efetuada por um
	
	User

---

## O Que Devo Aprender Primeiro?

1. Domain

2. Data Element

3. Table

4. Search Help

5. Program

6. Class

7. Transaction

Quando perceberes a função destes objetos, os restantes tornam-se muito mais fáceis de compreender.

---

A única alteração adicional que eu faria seria trocar o título **"Os Objetos Mais Comuns"** para **"Primeiros Objetos a Conhecer"**, porque reforça a ideia de percurso de aprendizagem em vez de catálogo de referência. Isso está mais alinhado com o objetivo do _SAP Practical Guide_.