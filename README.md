# ![LOGO](logo.png) Cnab Online **flow**ground Connector

## Description

A generated **flow**ground connector for the Cnab Online API (version 1.0.0).

Generated from: https://api.apis.guru/v2/specs/cnab-online.herokuapp.com/1.0.0/swagger.json<br/>
Generated at: 2019-05-07T17:40:05+03:00

## API Description

Processe arquivos de retorno CNAB

## Authorization

This API does not require authorization.

## Actions

### Faz o upload de um arquivo

> Processa um arquivo CNAB para obter informacoes sobre o mesmo. Retorna um ID temporario para o mesmo.

*Tags:* `file`

### Retorna as informacoes basicas de um arquivo previamente processado

*Tags:* `file`

#### Input Parameters
* `fileId` - _required_ - ID Temporario gerado no endpoint file

### Retorna todas as linhas e seus respectivos campos (de forma nao processada, apenas indicando os campos reconhecidos)

*Tags:* `file`

#### Input Parameters
* `fileId` - _required_ - ID Temporario gerado no endpoint file

### Retorna as informacoes de baixa de boletos e outros tipos de ocorrencias

*Tags:* `file`

#### Input Parameters
* `fileId` - _required_ - ID Temporario gerado no endpoint file

## License

**flow**ground :- Telekom iPaaS / cnab-online-herokuapp-com-connector<br/>
Copyright © 2019, [Deutsche Telekom AG](https://www.telekom.de)<br/>
contact: flowground@telekom.de

All files of this connector are licensed under the Apache 2.0 License. For details
see the file LICENSE on the toplevel directory.
