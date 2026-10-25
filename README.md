# Calculadora de Desconto

Este projeto consiste em um aplicativo de Calculadora de Desconto desenvolvido com Flutter e Dart para uma atividade acadêmica.

O aplicativo permite informar o preço de um produto e a porcentagem de desconto para calcular e exibir o valor final.

Nesta atividade, foram completados e executados os testes automatizados solicitados para verificar os cálculos e o funcionamento da interface.

## Preparar o projeto no Windows

Pré-requisitos

Flutter instalado e configurado no Windows.

Visual Studio Code.

Emulador Android ou dispositivo compatível, caso queira executar o aplicativo no Android.

Configuração

Baixe e extraia o ZIP do projeto.

Abra a pasta IasminKrueger_N2_E4 no Visual Studio Code.

No menu superior, clique em Terminal > Novo Terminal.

Confirme que o terminal está na pasta principal do projeto, onde estão os arquivos pubspec.yaml, lib/ e test/.

Execute:

flutter pub get

Esse comando instala as dependências necessárias para executar o projeto.

## Executar o aplicativo

Com um emulador Android aberto ou um dispositivo compatível conectado, execute:

flutter run

Exemplo de utilização

Informe 200 no campo do valor do produto.

Informe 10 no campo do desconto.

Pressione o botão Calcular.

O resultado esperado é Valor final: R$ 180.00.

## Testes automatizados

Os testes estão localizados na pasta test/.

discount_calculator_test.dart: contém três testes unitários para verificar os cálculos de desconto.

widget_test.dart: verifica o funcionamento da interface do aplicativo.

Para executar os testes, abra o terminal na pasta principal do projeto e execute:

flutter test

O resultado esperado é a aprovação dos quatro testes: três testes unitários e um teste de interface.

Resultado obtido durante a execução:

+4: All tests passed!

## Gerar o APK

O APK é o arquivo de instalação do aplicativo Android.

Para gerar a versão de lançamento, execute:

flutter build apk --release

O arquivo será gerado em:

build/app/outputs/flutter-apk/app-release.apk

## Gerar o AAB

O AAB é um pacote do aplicativo Android usado principalmente para publicação e distribuição pela Google Play.

Para gerar o arquivo, execute:

flutter build appbundle

O arquivo será gerado em:

build/app/outputs/bundle/release/app-release.aab

## Evidências

A pasta evidencias/ deve conter capturas de tela que comprovem as etapas realizadas:

app.png: aplicativo aberto e funcionando, com o resultado do cálculo visível.

testes.png: terminal mostrando a aprovação dos testes automatizados.

apk.png: Explorador de Arquivos mostrando o arquivo app-release.apk.

aab.png: Explorador de Arquivos mostrando o arquivo app-release.aab.

As imagens devem estar salvas na pasta evidencias/ do projeto.

## Estrutura do projeto

lib/: código-fonte do aplicativo.

test/: testes automatizados.

evidencias/: capturas de tela das etapas realizadas.

android/: arquivos necessários para a plataforma Android.

pubspec.yaml: configuração do projeto e suas dependências.

pubspec.lock: registro das versões das dependências utilizadas.

README.md: instruções e informações sobre o projeto.