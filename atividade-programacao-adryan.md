## Atividade – Prompt Mestre em Programação de Computadores  
### Tema: Funções em Python

---

### Prompt Mestre Inicial

**Prompt:**  
Escreva uma função em Python que receba dois números e retorne a soma deles.

---

### Variação 1

**Prompt:**  
Escreva a função em Python e explique passo a passo como funciona.

**Resposta do LLM:**
```python
def soma(a, b):
    return a + b

resultado = soma(5, 3)
print(resultado)
**Explicação:**  
A função chamada `soma` recebe dois parâmetros (`a` e `b`). Dentro da função, ela retorna a soma desses dois valores.  

Depois, a função é chamada passando os valores `5` e `3`, e o resultado é armazenado na variável `resultado`.  

Por fim, o valor é exibido na tela com `print()`.
### Variação 2

**Prompt:**  
Melhore a função para validar se os valores são números antes de somar.

**Resposta do LLM (corrigida):**
```python
def soma(a, b):
    if isinstance(a, (int, float)) and isinstance(b, (int, float)):
        return a + b
    else:
        return "Erro: valores inválidos"

print(soma(5, 3))
### Variação 3

**Prompt:**  
Explique a função em linguagem simples, como se fosse para um iniciante.

**Resposta do LLM:**  
Essa função serve para somar dois números. Você informa os valores, e ela entrega o resultado da soma.  

Se os valores não forem números, ela retorna uma mensagem de erro. Isso ajuda a evitar problemas no programa.

---

### Reflexão

Ao modificar os prompts, é possível perceber que pequenas mudanças nas instruções influenciam diretamente nas respostas geradas.  

A versão com explicação foi a mais útil para o aprendizado, pois facilitou o entendimento do funcionamento da função.  
Já a versão com validação mostrou uma aplicação mais prática e segura do código.  

Isso demonstra que a engenharia de prompt pode ser usada para obter respostas mais completas, adaptadas ao nível de conhecimento e à necessidade do programador.
