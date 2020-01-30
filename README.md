# Instruções básicas para setup de ambiente java.

## Instalando o JDK:

**1. Download java development kit**

[Java SE Downloads]("https://www.oracle.com/technetwork/java/javase/downloads/index.html")

Obs.: Escolha a versão desejada, aceite o termo de licença e faça o download do instalador.

**2. Execute o instalador.**

**3. Configure as seguinte variáveis de ambiente:**

Path: *Adicione uma nova entrada com o caminho da pasta bin onde o jdk foi instalado.*

Conteúdo: [C:\Program Files\Java\jdk-13.0.2\bin]

Exemplo(Win):

![path](/assets/images/path.JPG)

JAVA_HOME: *Adicione uma nova variável com este nome, conforme imagem abaixo:*

Exemplo(win):

![java_home](/assets/images/java_home.JPG)

**4. Testando a instalação**

Abra uma janela de comando ou terminal:
win+R cmd

Digite o comando java -version e pressione enter

Exemplo de output:

![java version](/assets/images/java_version.JPG)

Digite o comando javac e pressione enter

Exemplo de output:

![java c](/assets/images/java_c.JPG)

## Instalando o Mavem:

## Instalando o Gradle:

## Visual Studio Code Setup:

**1. Configure a variavel java home nos settings do visual studio code**

Exemplo:

![java home](/assets/images/Settings_vs_code.JPG)

**1.1 Edite o arquivo settings.json adicionando o caminhando da instalação do JDK**

Exemplo:

![java home](/assets/images/setting_json_edit.JPG)

**2. Instale as extensions abaixo**

- Java Extension Pack
- Spring Boot Tools
- Spring Initializr Java Support
- Spring Boot Dashboard
- Jetty
- CheckStyle