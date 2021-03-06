﻿# SAMU
Está aplicação tem como objetivo aumentar a acessibilidade do deficiente auditivo aos principais serviços de atendimentos de urgência!

## Fluxos da aplicação
#### Abrir chamado para o SAMU
<img src="wiki/fluxo_abrir_chamada.png" height="300"/>

#### Fluxo quando houver atendimento pendente
<img src="wiki/atendimento_pendente.png" height="300"/>

#### Fluxo quando último atendimento pendente estiver finalizado
<img src="wiki/atendimento_finalizado.png" height="300"/>

#### Mudança de status(apenas no aplicativo administrativo)
<img src="wiki/adm_alterar_status.png" height="300"/>


## Como usar
* [Pegue uma key map][map-key]
* Crie um arquivo secret.properties contendo a key gerada
```xml
mapsApiKey=AIzaXXXXXXXXXXXXXXXX
```

## Development Tools
* Android Studio v3.1.4
* Android SDK Build Tools v28.0.0
* MinSdkVersion 21
* CompileSDKVersion 28
* Kotlin Version 1.2.70

## Dependências
* Android Support Tools v28.0.0
* Koin 0.9.1
* Retrofit v2.4.0
* Glide v4.8.0
* Play Services(maps e location) v15.0.1
* Firebase messaging v16.0.3
* EventBus v3.1.1

## TODO
* [Administrativo] Melhorar listagem dos chamados
* [Administrativo] Bloquear dispositivos com atividades de má conduta
* [Cliente] Usuário ver histórico de chamados
* [Administrativo e Cliente] Exibir horários das mudanças de estado
* [Administrativo e Cliente] Launcher(icone) personalizado


[map-key]: https://developers.google.com/maps/documentation/android-sdk/signup