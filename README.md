# GetStartReactNative
Tutorial para se inicializar rapidamente, do zero, um projeto React Native CLI

Primeiro vamos instalar os programas e dependencias, para isso usaremos a ferramenta Chocolatey. Ele é uma ferramenta capaz de instalar e atualizar programas via linha de comandos no powerShell, facilitando a instalação e configuração de toda area de trabalho.

Lembrete, todos os comandos devem ser executados no powerShell adm.
Caso queira ver o tutorial de instalação do choco = https://chocolatey.org/install
Caso queira ir direto nos comandos:
  - Instalar o choco: Set-ExecutionPolicy Bypass -Scope Process -Force; [System.Net.ServicePointManager]::SecurityProtocol = [System.Net.ServicePointManager]::SecurityProtocol -bor 3072; iex ((New-Object System.Net.WebClient).DownloadString('https://community.chocolatey.org/install.ps1'))
  - Instalar o Visual Studio Code: choco install vscode
  - Instalar o node: choco install nodejs

Com tudo instalado, vamos a configuração da maquina para rodar os script. Primeiro precisamos liberar a execução de scripts em linha de comando, para isso no powerShell adm execute:
  - Vereficar se os script estão restritos: Get-ExecutionPolicy
  - Se estiver restrito, usar o comando: Set-ExecutionPolicy unrestricted
  Com isso já podemos executar os comandos no Visual Studio Code.
  
Agora vamos iniciar um projeto React, tendo a pasta já criada e selecionada no Visual Studio Code, seguiremos o tutorial do React = https://reactnative.dev/docs/environment-setup

  - Instalando as dependencias: npm install -g expo-cli
  - Criando um proejeto, onde Awesome é o nome do projeto: expo init AwesomeProject
  - Entrando na pasta do projeto: cd AwesomeProject
  - Executando o projeto no navegador: npm start

Pronto, seu ambiente de trabalho está preparado para programar em React!
