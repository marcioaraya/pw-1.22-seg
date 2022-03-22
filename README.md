# pw-1.22-seg
## Disciplina Padrões Web - Faculdade Senac  DF - 1.2022 - 2ADS/2GTI/2TSI/2BDD
  
Neste repositório vamos disponibilizar os códigos elaborados nas aulas da disciplina **Padrões Web** ministradas no primeiro semestre de 2022 para as turmas 2ºADS, 2ºGTI, 2ºTSI e2BDD do turno matutino da **Faculdade de Tecnologia e Inovação Senac DF**.
  
Para baixar o conteúdo deste repositório para seu computador, vamos usar o **git**.  
  
### Para instalar o **git**:
1. Faça o download a partir da página https://git-scm.com/. Está disponível para Windows, Linux e MacOS. Se utilizar Linux pode ser que já esteja instalado, digite **git** na linha de comando para verificar. No Windows vai instalar um aplicativo **Git Bash** que será usado para digitar os comandos do **git**.  
2. Após instalar o **git**, faça esta configuração básica (coloque os seus dados no lugar de **Fulano de Tal**):  
```
git config --global user.name "Fulano de Tal"
git config --global user.email fulanodetal@exemplo.br
```

### Clonando este repositório
Para baixar os códigos para seu computador acesse o botão verde "Code". Há três opções para baixar os arquivos:
1. Clonar o repositório utilizando o git.  
2. Usar o aplicativo Git Desktop.  
3. Baixar com arquivo compactado no formato zip.  

Vamos usar a primeira opção. 
Acesse a pasta onde você deseja clonar este repositório e digite o comando abaixo (não é necessário estar logado no Github):
```
git clone https://github.com/marcioaraya/pw-1.22-seg.git
```
Este comando irá criar uma pasta com o nome do repositório **pw-1.22-seg**. Caso deseje, pode alterar o nome da pasta que será criada, basta acrescentar o nome escolhido depois do comando. Por exemplo, o comando abaixo irá criar uma pasta com nome **padroes_web**:
```
git clone https://github.com/marcioaraya/pw-1.22-seg.git padroes_web
```
  
4. Para atualizar a cópia do repositório em seu computador com a versão mais recente dos arquivos no repositório no Github, use o comando:
```
git pull
```
  
### Comandos no Git Bash

No Git Bash, os comandos utilizados são os que seriam utilizados no Linux:
- ls: listar nomes de arquivos e pastas
- ll: lista dos arquivos com detalhes
- cd (change directory): altera o diretório (pasta) corrente.
- mkdir (make directory): permite criar um diretório (pasta).
- clear: limpa a tela.
- rm: apaga arquivo.

Para consultar as opções de cada comando, pode usar a opção "--help". Por exemplo:
```
mkdir --help
```
