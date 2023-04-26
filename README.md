## 🌐FXSS-Hunter🌐
<h1 align="center">🚀 Introdução:</h1>

O FXSS-Hunter é uma ferramenta de teste de penetração baseada em Python usada para detectar vulnerabilidades de Cross-Site Scripting (XSS) em sites da web. A ferramenta usa um conjunto predefinido de payloads ou payloads personalizados fornecidos pelo usuário para executar testes automatizados e identificar vulnerabilidades XSS. O programa oferece várias opções, como profundidade de rastreamento da página da web, configuração do método de solicitação HTTP, configuração de proxy e agentes do usuário, entre outras opções.
<h2 align="center">Funcionamento 🛠️</h1>
O FXSS-Hunter é uma ferramenta de segurança que detecta vulnerabilidades de Cross-Site Scripting (XSS) em sites. Ele faz isso enviando payloads maliciosos por meio de solicitações GET ou POST para determinados parâmetros da URL. Quando o payload é refletido de volta na página, é possível determinar se o site é vulnerável a ataques XSS.

O FXSS-Hunter é capaz de detectar vulnerabilidades em vários níveis, desde payloads simples até payloads mais complexos que envolvem codificação Base64 ou Unicode. Ele também tem a capacidade de rastrear várias páginas em um site, permitindo que você descubra mais pontos de entrada para ataques XSS.

A ferramenta é escrita em Python e usa a biblioteca Requests para enviar solicitações HTTP para o site em questão. Ele também usa a biblioteca Beautiful Soup para analisar o HTML da página em busca de refletividade do payload.

<h2 align="center">📥 Instalação</h1>
Para instalar o FXSS-Hunter, siga os seguintes passos:

Clone este repositório para o seu diretório local usando o comando abaixo:
```sh
git clone https://github.com/FoxsBlintersOFC07/FXSS-Hunter.git
```
Navegue até o diretório clonado usando o comando abaixo:
```sh
cd FXSS-Hunter
```
Instale as dependências necessárias usando o comando abaixo:
```sh
pip install -r requirements.txt
```
Execute o programa usando o seguinte comando (sem aspas):
```sh
python FXSS-Hunter.py -u (url_do_alvo)
```

## 📋 Resumo

O FXSS-Hunter é uma ferramenta de teste de penetração útil para identificar vulnerabilidades de Cross-Site Scripting (XSS) em sites da web. Ele usa um conjunto predefinido de payloads ou payloads personalizados fornecidos pelo usuário para executar testes automatizados e identificar vulnerabilidades XSS. A ferramenta oferece várias opções, como profundidade de rastreamento da página da web, configuração do método de solicitação HTTP, configuração de proxy e agentes do usuário, entre outras opções, tornando-a altamente personalizável e fácil de usar. Com o FXSS-Hunter, os usuários podem identificar e corrigir vulnerabilidades de segurança em seus sites da web, protegendo seus dados e seus usuários.
