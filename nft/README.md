# NFT

Исходный код контракта на FunC: [ton-blockchain/nft-contract](https://github.com/ton-blockchain/nft-contract).

[Стандарт TEP-62 NFT](https://github.com/ton-blockchain/TEPs/blob/master/text/0062-nft-standard.md), [Стандарт данных для токенов TEP-64](https://github.com/ton-blockchain/TEPs/blob/master/text/0064-token-data-standard.md) и [Расширение стандарта лицензионных платежей NFT TEP-66](https://github.com/ton-blockchain/TEPs/blob/master/text/0066-nft-royalty-standard.md).

В этом пакете реализованы эталонные контракты на NFT коллекцию и отдельные объекты, в том числе с учетом роялти и метаданных. Тесты проверяют поведение коллекции и отдельных цифровых объектов в эталонных наборах.

Скрипты в `scripts/` предоставляют рабочие точки входа для развертывания, проверки состояния и управления коллекцией или отдельными объектами: `deploy.tolk`, `info.tolk` и `manage.tolk`. Запускайте их с помощью команды `acton script nft/scripts/<name>.tolk`.
