# Validação de CPF, e-mail e senha

Exercício de formulário no navegador, feito com HTML, CSS e JavaScript puro. A verificação de CPF confere os dígitos verificadores; a de e-mail e senha usa regras locais simples, sem consultar serviços externos.

## Executar

Abra `index.html` em um navegador. Não há instalação ou servidor obrigatório. Os dados digitados são processados apenas na página; este projeto não cria contas nem envia os campos a uma API.

## Regras e limites

- CPF: aceita 11 dígitos com ou sem pontuação, rejeita sequências repetidas e verifica os dois dígitos finais.
- E-mail: validação didática de formato, não comprova existência da caixa postal.
- Senha: ao menos 8 caracteres, uma letra maiúscula e um número; a página não armazena nem autentica senhas.

O arquivo inicial foi renomeado de `idex.html` para `index.html`. Não use esta validação isolada como controle de segurança de um sistema real: entradas precisam de validação também no servidor.
