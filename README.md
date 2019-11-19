# Avaliação de Segurança e versionamento

Avaliação pode ser feita em dupla e com consulta.

Você deverá clonar esse documento, responder as questões e versioná-lo de volta no seu repositório. Ao final deverá me mandar o link.


## Nomes:

Aluno1: Lucas de Castro Andrade.     

Aluno2: Carlos Alexandre da Silva.

## Usage

```python
1 - Explique com suas palavras o que é SQL Injection:
R: É basicamente um ataque direto ao servidor SQL sem que haja a necessidade de uma verificação de login, o invasor consegue adentrar no servidor 
apenas com um codigo que lhe permite pular suas etapas de verificação.

```

```python
2 - Ao ser contratado para uma empresa como consultor
de segurança, ao analisar o código qual seria a primeira falha de segurança
que você procuraria?
R: Verificar se existe uma "cadeia" de users, ou seja, verificar se possuem usuários distintos para determinada área ou se estão todos usando o root.

```

```python
3 - Escreva um exemplo de injeção de SQL que você  tentaria:
R: ! or 1 = 1 --

```
```python
4 - O que você faria para resolver o problema de senhas
 em texto plano no banco de dados
do seu cliente
R: Utizaria o metodo hash para deixar as senhas com uma especie de criptografia, porem "aleatoria", sendo assim mais dificil de ser quebrada.

```

```python
5  a) O que é XSS request forgery:
R: É basicamente uma página clone fake, com intuito de pegar os dados de login de algum usuário para dar acesso ao invasor. 
    
b) Como você resolveria essa falha?

Inseriria um tokken para a autenticação do usuário, assim ele necessitaria de um segundo passo para login, por exemplo:
    
 <input type=hidden name="csrf_token" value:"hashGerada">
```
