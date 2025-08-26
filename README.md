# Gerador e Leitor de QR Code com HTML, CSS e JavaScript
# Descrição do Projeto
Este é um projeto simples e intuitivo para gerar e ler QR Codes, construído inteiramente com HTML, CSS e JavaScript. A aplicação permite aos usuários criar QR Codes a partir de links e também ler QR Codes de imagens enviadas. A geração e leitura são feitas através da integração com a API **qrserver**.

# Funcionalidades
 - **Gerador de QR Code**: Converta qualquer URL ou texto em um QR Code dinâmico, que pode ser visualizado e baixado.

 - **Leitor de QR Code**: Envie uma imagem de QR Code e receba o link ou texto contido nela.

- **terface Simples**: Design minimalista e responsivo, fácil de usar em qualquer dispositivo.

# Tecnologias Utilizadas
`HTML5`: Estrutura base do projeto.

`CSS3`: Estilização e responsividade da interface.

`avaScript`: Lógica da aplicação para interagir com a API e manipular o DOM.

`API qrserver`: Utilizada para gerar e ler os QR Codes.

# Como Utilizar
**Clone o repositório**:

Bash
```
git clone https://github.com/ParreirasJuniorWeb/App_gerador_QRCode_e_leitor_QRCode_em_HTML_CSS_javascript.git
```
# Abra o arquivo:
Simplesmente abra o arquivo 'index.html' em seu navegador web. Não é necessário nenhum servidor local.

# Use a aplicação:

 - **Para Gerar um QR Code**: Insira um link ou texto no campo de entrada e clique no botão para gerar. O QR Code aparecerá abaixo.

 - **Para Ler um QR Code**: Clique no botão de upload, selecione uma imagem com um QR Code do seu dispositivo e o conteúdo do código será exibido na tela.

# Estrutura do Projeto
A estrutura de arquivos do projeto é organizada da seguinte forma:
```
App_gerador_QRCode_e_leitor_QRCode_em_HTML_CSS_javascript/
├── index.html
├── style.css
└── script.js
```
 - `index.html`: Contém a estrutura HTML da página, incluindo o formulário de entrada e os elementos de exibição do QR Code.

 - `style.css`: Responsável pela aparência visual do projeto, com estilos que deixam a interface atraente e responsiva.

 - `script.js`: O cérebro da aplicação, controlando a lógica de geração e leitura dos QR Codes através da API.
