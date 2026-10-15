# Calculadora (Android / Java)

Aplicativo de calculadora desenvolvido em Java no Android Studio — UEMG Unidade Passos, Sistemas de Informação.

## Funcionalidades

- Botões numéricos de 0 a 9 (até 7 dígitos por número)
- As 4 operações básicas: soma (+), subtração (-), multiplicação (X) e divisão (/)
- Botão **=** para calcular e **CE** para limpar
- Divisão inteira (ex.: `7 / 2 =` → `3`)
- Exibe **ERROR** em divisão por zero ou quando o resultado passa do limite da tela
- Após o **=**, o resultado pode ser usado na próxima operação

## Como executar

1. Abra a pasta do projeto no Android Studio.
2. Aguarde a sincronização do Gradle.
3. Execute no emulador ou em um dispositivo (Android 7.0 / API 24 ou superior).

## Estrutura principal

- `app/src/main/java/br/edu/uemg/calculadora/MainActivity.java` — lógica da calculadora
- `app/src/main/res/layout/activity_main.xml` — layout da tela
