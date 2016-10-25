# captchaReceitaData
[![Travis-CI Build Status](https://travis-ci.org/decryptr/captchaReceitaData.svg?branch=master)](https://travis-ci.org/decryptr/captchaReceitaData)

Repositório de dados de imgs e audios brutos utilizados nos pacotes do tipo captchaReceita

# Instalando

Instale o pacote usando:

```
devtools::install_github("decryptr/captchaReceitaData")
```

# Usando os dados

Os dados podem ser acessados usando

```
list.files(system.file("audio/", package = "captchaReceitaData"))
list.files(system.file("img/", package = "captchaReceitaData"))
```
