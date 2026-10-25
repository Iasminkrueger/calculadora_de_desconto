# N2 - E4 — Calculadora de Desconto

Este projeto consiste em um aplicativo de Calculadora de Desconto desenvolvido com Flutter.

O aplicativo permite informar o preço de um produto e a porcentagem de desconto para calcular e exibir o valor final.

O projeto-base do aplicativo já estava implementado. Nesta atividade, foram completados os testes automatizados solicitados.

## Preparar no Windows

### Pré-requisitos

- Flutter instalado e configurado no Windows.
- Visual Studio Code.
- Um emulador Android ou dispositivo compatível, caso queira executar o aplicativo no Android.

### Configuração do projeto

1. Baixe e extraia o ZIP do projeto.
2. Abra a pasta `IasminKrueger_N2_E4` no Visual Studio Code.
3. No menu superior, clique em **Terminal > Novo Terminal**.
4. No terminal, confirme que você está na pasta principal do projeto, onde estão os arquivos `pubspec.yaml`, `lib/` e `test/`.
5. Execute o comando abaixo para instalar as dependências:

flutter pub get

Após a conclusão, o projeto estará preparado para executar os testes e compilar o aplicativo.

## Executar o aplicativo

Para iniciar o aplicativo, abra um emulador Android ou conecte um dispositivo compatível e execute:

flutter run

O aplicativo será iniciado no dispositivo selecionado.

### Exemplo de utilização

1. Informe `200` no campo do valor do produto.
2. Informe `10` no campo do desconto.
3. Pressione **Calcular**.
4. O resultado esperado é `Valor final: R$ 180.00`.

## Testes automatizados

Os testes estão localizados na pasta `test/`.

- `discount_calculator_test.dart`: contém três testes unitários para verificar os cálculos de desconto.
- `widget_test.dart`: verifica a interface e o resultado apresentado ao usuário.

Para executar todos os testes, abra o terminal na pasta principal do projeto e execute:

flutter test

O resultado esperado é:

All tests passed!

A atividade foi testada com sucesso, com quatro testes aprovados: três testes unitários e um teste de interface.

## Gerar o APK

Para gerar o arquivo de instalação Android na versão de lançamento, execute:

flutter build apk --release

O arquivo será gerado em:

`build/app/outputs/flutter-apk/app-release.apk`

## Gerar o AAB

Para gerar o pacote Android App Bundle, execute:

flutter build appbundle

O arquivo será gerado em:

`build/app/outputs/bundle/release/app-release.aab`

## Evidências

As capturas de tela das etapas realizadas estão organizadas na pasta `evidencias/`:

- `app.png`: aplicativo aberto e funcionando.
- `testes.png`: resultado dos testes automatizados.
- `apk.png`: arquivo APK gerado.
- `aab.png`: arquivo AAB gerado.