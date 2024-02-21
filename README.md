# COMUNICAÇÃO CLIENT x SERVER

## OBJETIVO GERAL
Entender um pouco a história do computador, surgimento da internet e entender como funciona toda a comunicação quando você acessa uma página web ou utiliza um aplicativo.

### Primeiros Computadores ### 

Leia mais: https://introducao-a-informatica.webnode.page

# 1ª Geração (1940 - 1952)
- Programação através de fios
- Utilização de linguagem de máquina
- Harvard Mark I (1944)
- Colossus (1946)
- ENIAC (1946)

# 2ª Geração (1953-1964)
- Tecnologia:Transistor e Memórias Magnéticas
- Primeiras Linguagens de Programação: Assembly,Fortran,Cobol
- Primeiros sistemas operacionais
- Dispositivo de E/S:cartões perfurados e fitas magnéticas

# 3ª Geração (1965-1971)
- Tecnologia:Circuitos Integrados(CI)
- IBM/360(mainframe)
- Multiprogramação
- Surgimento do UNIX
- Grande variaçao na capacidade de memória
- Avanço nos periféricos de entrada e saída
- Dispositivos de E/S:terminal de vídeo,teclado,disco magnético

# 4ª Geração (1972-1980)
- Tecnologia:Microprocessadores
- Microprocessador Intel 4004 (1971)
- Circuitos de Escala Ultra Grande - ULSI (1981)
- Inicio da utilização do disquete como unidade de armazenamento.
- Surgimento de grande quantidade de linguagens de programação.

# 5ª Geração (1980- Atualmente)
- Surgimento dos PC's
- Surgimento do DOS
- Expansão da Internet
- Inteligência Artificial
- Sistemas Operacionas de Interface Gráfica
- Arquiteturas Paralelas

### Como surgiu a Internet ###

- Telégrafo e Código Morse
- Em 1858, um cabo telegráfico foi instalado no Atlântico para permitir a comunicação entre a Europa e a América, mas só funcionou durante três semanas
- Guerra Fria e Corrida Espacial 
- DARPA (Defense Advanced Research Projects Agency)
- Joseph Carl Robnett Licklider teoriza sobre uma rede mundial de comunicação na década de 1960
- Arpanet: Sistema de comunicação em pacotes (checkpoints), enviados um a um e que permitia múltiplos destinos
- 1ª conexão estabelecida em 29/10/1969 entre a Universidade da California (UCLA) e o Instituto de Pesquisa de Stanford (SRI)
- Criação do Protocolo TCP/IP por Vinton Cerf e Robert Kahn
- Em 1989, Tim Berners-Lee viu a oportunidade de unir hipertexto com TCP/IP e criar a World WideWeb (WWW)
- Primeiro navegador chamado WorldWideWeb

### Grandes Nomes da Tecnologia ###

# Grace Murray Hopper
- Marinha dos Estados Unidos
- Uma das primeiras programadoras do Mark I em 1944
- Criadora da linguagem de programação de alto nível Flow Matic (Base do COBOL)
- Termo “bug” na computação

# Joseph Carl Robnett Licklider
- Recrutado pela DARPA depois de teorizar sobre uma rede “galática” de computadores
- Plantou a “semente” da comunicação entre dois pontos distintos através do computador

# Robert E. Kahn
- Primeira apresentação pública da ARPANet
- Apresentou o primeiro e-mail
- Criador do Protocolo TCP/IP

# Tim Berners Lee
- Inventor do WWW
- Diretor do World Wide Web Consortion (W3C)
- Diversas homenagens, incluindo título de cavaleiro dados pela Rainha Elizabeth II
- Popularizou o HTTP e HTML

Marc Andreessen
- Criou o navegador Netscape Navigator feito a partir do Mosaic.
- Tornou o navegador amigável ”, com recursos gráficos
- Deteve 90% da internet na época , mas sendo superado

### Client e Server em desenvolvimento web ###

Um servidor é um recurso dentro de um sistema computacional, capaz de processar aplicações, armazenar dados e prestar serviços, enquanto o cliente é um computador que solicita esses serviços e recursos.

# Falando sobre navegadores
- São programas criadas por empresas , utilizados para abrir executar arquivos
- Seguem padrões W3C, porém , sempre tem uma diferença ou outra de interpretação
- Também chamados de “browsers”
- Iniciou com o MOSAIC, passou para o Netscape, e hoje temos uma variedade de navegadores disponíveis
- São gratuitos

# Aplicações Web
- São soluções criadas que possuem a internet como meio de comunicação entre Client x Server não sendo necessário a sua instalação
- Facebook, Instagram, Youtube são aplicações web sendo acessados pelo navegador. Ex: www.youtube.com
- Não são Aplicações Web quando acessado através de um aplicativo instalado no seu dispositivo

# Hardwares e Softwares em Servidores

__Softwares__
- Sistemas Operacionais: Windows Server, Ubuntu, Fedora, Oracle Linux, Debian, CentOS
- Monitoramento
- Servidores Web: Apache HTTP Server Project, NGINX
__Hardwares__
- Armazenamento (disco rígidos, SSDs)
- Memória
- Processadores

# Tipos de Servidores
- Arquivos
- Segurança (Firewall)
- Streaming
- E-mail
- Web
 _________            _____________________           _________
| Clients | ------>  |         DNS         | ------> | Servers |
 ---------            (Domain Name Service)           ---------

Obs: Servidor Web sem internet, chamamos de Intranet

### Linguagens de Programação ###
Linguagem de Programação é uma linguagem escrita e formal que especifica um conjunto de instruções e regras usadas para gerar programas (software).

# As cinco primeiras segundo RedMonk
1. Javascript
2. Python
3. Java
4. PHP
5. C#

# Linguagens Server-Side
- PHP
- Ruby
- C#
- JavaScript
- Java

# Linguagem Client-Side
- JavaScript: executa dos dois lados. Mas como? Ele usa o V8 por meio do navegador e do Node.Js
- V8 é o mecanismo JavaScript e WebAssembly de código aberto e de alto desempenho do Google, escrito em C++. É usado no Chrome e no Node.js.
  Veja mais em: https://v8.dev/

# HTML é linguagem de programação? Não!
- Apesar do nome (Linguagem de Marcação de HiperTexto), HTML não é linguagem de programação
- HTML é um arquivo de marcação
- Textos delimitados por nomes que o navegador consegue interpretar
- Cada nome destes delimitadores, tem uma função e comportamento específico

# Exemplo de HTML
<p>
Eu
curto demais a <strong><i>DIO!</i></strong>
</p>
Resultado:
Eu curto demais a DIO! (negrito e itálico)
