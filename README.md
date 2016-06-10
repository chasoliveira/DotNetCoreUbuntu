# DotNetCoreUbuntu
Veja aqui os comandos para a instalação do DotNet Core no Ubuntu 16.04

Abaixo segue instruções usadas no vídeo:

Instalação das dependências para o Linux
	Endereço do pacotes
		http://packages.ubuntu.com/

Comandos

	sudo sh -c 'echo "deb http://security.ubuntu.com/ubuntu trusty-security main universe" > /etc/apt/sources.list'
	sudo apt-get update
	sudo apt-get install clang-3.5

	sudo sh -c 'echo "deb http://cz.archive.ubuntu.com/ubuntu xenial main universe" > /etc/apt/sources.list'
	sudo apt-get update
	sudo apt-get install liblttng-ust0

	sudo sh -c 'echo "deb http://cz.archive.ubuntu.com/ubuntu xenial main" > /etc/apt/sources.list'
	sudo apt-get update
	sudo apt-get install liblldb-3.6

	sudo sh -c 'echo "deb http://security.ubuntu.com/ubuntu trusty-security main" > /etc/apt/sources.list'
	sudo apt-get update

	sudo apt-get install libicu52

	Instação do  DotNet Core
	sudo apt-get install dotnet-sharedframework-microsoft.netcore.app-1.0.0-rc2-3002702

	sudo sh -c 'echo "deb [arch=amd64] https://apt-mo.trafficmanager.net/repos/dotnet/ trusty main" > /etc/apt/sources.list.d/dotnetdev.list'

	sudo apt-key adv --keyserver apt-mo.trafficmanager.net --recv-keys 417A0893

	sudo apt-get update

	sudo apt-get install dotnet-dev-1.0.0-preview1-002702
