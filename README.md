# Dextra
arquivo de analise de testes automatizado

Nos arquivos enviados contem o seguinte conteúdo

Os testes realizados foram feitos utilizando a ferramenta Selenium IDE versão 3.4.4 utilizando o navegador Google Chrome versão 70.

plano de teste dextra parte 1.side: Foi realizado os seguintes processos

- Preencher o cadastro com o seguinte e-mail: teste@hotmail.com (Validar a mensagem de e-mail já cadastrado)
- Inserir uma senha com 2 caracteres e válidar as mensagens: "Senha Fraca" e "Senha precisa ter entre 6 a 50 caracteres."
- Inserir um CPF inválido e validar a mensagem: "Campo inválido"

foi criado o cenário de testes valida_cpf, valida_email, valida_senha.

plano de teste dextra parte 2.side: Foi realizado o processo de cadastro de uma pessoa ficticia e também foi realizada a compra de 2 itens celulares Moto G6 conforme .gif enviado. validando conforme solicitado.
PARTE 2
- Ainda no formulário de cadastro, preencha todas as informações corretamente e realize um cadastro com sucesso. Ao termino desse passo você deverá ser redirecionado para a home.
        - Após logado no sistema, faça uma busca pelo texto "Moto G6".
	- Adicione dois produtos a sua cesta.
	- Valide que o total da compra é inferior a 5 mil reais.
	- Valide que a compra pode ser dividida em até 10x sem juros.
  
