# Passo a passo para configurar máquina para Automação com Selenium

## Vamos começar a escrever os testes?

### Pre Requisitos

- Possuir browser Google chrome instalado em sua máquina
- Possuir Java JDK 11 ou superior instalado e configurado

### 1. Fazer download do chromedriver
- Verifique a versão do seu browser Google chrome
- Faça o download do chromedriver para a versão do seu Google chrome e seu S.O em [link para download](https://chromedriver.chromium.org/downloads)
- Extrair e escolher a pasta onde ele ficará.

### 2. Fazer download da sua IDE preferida. Para utilizar Selenium Webdriver + Cucumber, preferimos o Eclipse

  - Entrar no [Site do Eclipse](https://www.eclipse.org/downloads/packages/release/2021-09/r) e baixar a versão que corresponde ao seu sistema operacional (Windows, Mac ou Linux);
  ![image](https://user-images.githubusercontent.com/21202785/133531907-283a76b1-76cb-41c9-aeef-9b22a4a9d90f.png)

  - Após o download, extrair e escolher a pasta onde ele ficará.
  - Na etapa seguinte, iremos instalar o plugin Cucumber, para isso abra o Eclipse
  - Agora vá em Help > Marktplace
  - Em find vamos preencher "Cucumber" e pressionar _Enter_
  - Agora é so pressionar em _Install_
  - Ihulll nosso eclipse foi configurado com sucesso!!

### 3. Agora Vamos Importar o nosso projeto base

- Clone o projeto base [LINK AQUI](https://github.com/ailanasmaciel/base-project.git) _Tutorial: [Como clonar um projeto](https://docs.github.com/pt/github/creating-cloning-and-archiving-repositories/cloning-a-repository-from-github/cloning-a-repository)_
- Agora que temos o projeto em nossa maquina o nosso proximo passo será importar o projeto no Eclipse
- Agora abra o Eclipse e clique em File > Import > General > Projects from Folder or Archive
- Selecione o diretorio do projeto que clonamos e clique em Finish
- Aguarde o download das bibliotecas e pronto!!

### 4. Agora Vamos Testar?
- Em src/test/java/utils abra o arquivo DriverUtils e coloque o local do seu chromedriver Ex: "local/chromedriver.exe"
![image](https://user-images.githubusercontent.com/21202785/133542163-f4164c7d-4888-4586-af16-09003f7b6b2c.png)
- Agora abra o arquivo "RunnerTest" em src/test/java/runners e execute como abaixo:
- ![image](https://user-images.githubusercontent.com/21202785/133542477-923b978c-84f9-4ed9-bb84-00daf4ff7e62.png)
- Se o Google chrome abrir seu ambiente está configurado com sucesso!!
