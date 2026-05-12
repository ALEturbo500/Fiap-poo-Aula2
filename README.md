# Fiap-poo-Aula2

🧠 Pergunta de Reflexão
Reflita:
Se nós podemos simplesmente fazer passageiro.saldo = passageiro.saldo + 100 diretamente no código principal, 
por que dá tanto trabalho criar um método específico chamado adicionarSaldo(valor) para fazer isso? 
Quais seriam os riscos para a nossa startup de mobilidade se deixássemos qualquer programador alterar o saldo diretamente?

Resposta: Criar o método adicionarSaldo(valor) deixa o sistema mais seguro e organizado, porque ele controla como o saldo pode ser alterado. Assim, podemos validar regras, como impedir valores negativos ou registrar movimentações. Se qualquer programador pudesse mudar o saldo diretamente, poderiam acontecer erros, fraudes ou inconsistências, como usuários ficando com saldo negativo ou recebendo créditos indevidos, o que seria um grande risco para a startup.
