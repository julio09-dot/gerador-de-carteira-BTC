# Att lopal


## 💻 Tecnologias Usadas

Esse projeto foi desenvolvido com as seguintes tecnologias:

- [NodeJS](https://nodejs.org)
- Lib bip32
- Lib bip39
- Lib bitcoinjs-lib
- [Electrum](https://electrum.org/)

## 👽 Projeto

A Carteira foi criada na rede Testnet uma rede válida apenas para testes mesmo, e que é separada da rede Mainnet a rede principal do BITCOIN.
Usamos o token Faucet para realizar as transações nas carteiras, um token sem valor, utilizado apenas para validar o correto funcionamento dos endereços

Deixarei algumas imagens para um melhor entendimento de como ocorreu toda a atividade, desde a elaboração do script até as transações realizadas nos endereços criados a partir do código...



![image](https://github.com/Carloscam98/gerador-de-carteira-BTC/assets/114948535/f7b84d5d-ec82-4394-8455-b2cbd3e6b393)

O código é simples, mas funcional.


Após salvar o script, adentrei a pasta src via Terminal e rodei por duas vezes o seguinte comando 

```
node .\createWallet.js

```

Gerando assim, duas carteiras, com os seguintes endereços no qual destaquei em amarelo:

![ultima foto](https://github.com/Carloscam98/gerador-de-carteira-BTC/assets/114948535/58a1bff6-2b57-4297-80b9-d51d5f974936)

##


A seguir, deixarei duas imagens da interface gráfica do ELECTRUM, o software gerenciador de carteiras usado para efetuar as transações

![saldo na carteira electrum](https://github.com/Carloscam98/gerador-de-carteira-BTC/assets/114948535/ae9a3036-10b6-445a-ab5a-b2d8b78446f5)
![btc enviado pelo carlitos](https://github.com/Carloscam98/gerador-de-carteira-BTC/assets/114948535/f345dee6-7ac6-4f42-bea8-59a0bc58d367)


Não posso deixar de pontuar a alteração necessária que deve ser feita na aba propriedades do app para seu correto funcionamento na atividade

![electrum alter](https://github.com/Carloscam98/gerador-de-carteira-BTC/assets/114948535/a134d872-0552-4ff4-8ad7-55a60da21731)

##

Usei o site https://coinfaucet.eu/en/btc-testnet/ para enviar tBTC para minha carteira.  

![btc enviados pelo site](https://github.com/Carloscam98/gerador-de-carteira-BTC/assets/114948535/e5fe81fe-2199-44c8-b288-1d2e14a79960)

##

E por fim, acompanhei as transações na blockchain pelo site https://live.blockcypher.com/btc-testnet/  

![btcs transacionados](https://github.com/Carloscam98/gerador-de-carteira-BTC/assets/114948535/3383ef1a-4dd5-4be9-b37b-3513fcad9063)

##

Note que os endereços das imagens de exemplo, são os endereços gerados pelo nosso gerador de carteiras, constatando assim, a eficiência da nossa ferramenta elaborada ! 


