Autora: Alice Moreira dos Santos

O projeto foi concebido para resolver o gargalo de comunicação entre a captação de clientes via tráfego pago e a distribuição dessas demandas para os advogados em um escritório de advocacia de pequeno porte.

✅ Lista de verificação | Indicadores de Desempenho (ID) dos Resultados de Aprendizagem (RA)

RA1 - Utilização Frameworks CSS para estilização de elementos HTML e criação de layouts responsivos.
ID 01 - Prototipa interfaces adaptáveis ​​para no mínimo os tamanhos de tela mobile e desktop, utilizando ferramentas de design tradicionais (Figma, Quant UX ou Sketch) ou IA (Stitch).
ID 02 - Implementar layout responsivo com Framework CSS (Bootstrap, Materialize, Tailwind + DaisyUI) usando Flexbox ou Grid do próprio framework.
ID 03 - Implemente layout responsivo com CSS puro, usando Flexbox ou Grid Layout.
ID 04 - Utiliza componentes prontos de um Framework CSS (ex.: cartão, botão) e componentes JavaScript do framework (ex.: modal, carrossel).
ID 05 - Cria layout fluido usando unidades relativas (vw, vh, %, em, rem) no lugar de unidades fixas (px).
ID 06 - Aplicar um Design System consistente (núcleos, tipografia, padrões de componentes) em toda a aplicação.
ID 07 - Utilize Sass (SCSS) com ou sem framework, aplicando variáveis, mixins e funções para modularizar o código.
ID 08 - Aplicação de tipografia responsiva (media queries mobile first) ou tipografia fluida (função clamp() + unidades relativas).
ID 09 - Aplicação de técnicas de responsabilidade de imagens usando CSS (object-fit, containers com unidades relativas).
ID 10 - Otimiza imagens usando formatos modernos (WebP) e carregamento adaptativo (srcset, picture, ou parâmetros do Cloudinary).
RA2 - Realizar tratamento de formulários e aplicar validações customizadas no lado cliente.
ID 11 - Implementa validação HTML nativa (campos obrigatórios, tipos, limites de caracteres) com mensagens de erro/sucesso no lado cliente.
ID 12 - Aplicação de expressões regulares (REGEX) para validações personalizadas (e-mail, telefone, dados, etc.)
ID 13 - Utiliza elementos de seleção em formulários (checkbox, radio, select) para coleta de dados.
ID 14 - Implementa leitura e escrita no Web Storage (localStorage/sessionStorage) para persistir dados localmente.
RA3 - Aplicar ferramentas para otimização do processo de desenvolvimento web.
ID 15 - Configurar ambiente com Node.js e NPM para gerenciamento de pacotes e dependências.
ID 16 - Utilize boas práticas de versionamento no Git/GitHub (branch main ou branch específico, uso de .gitignore).
ID 17 - Mantém um README.md padronizado, conforme template da disciplina, com checklist preenchido.
ID 18 - Organiza arquivos do projeto de forma modular, seguindo padrão de exemplo fornecido.
ID 19 - Configure linters e formatadores (ESLint, Prettier) para manter a qualidade e padronização do código.
RA4 - Aplicar bibliotecas de funções e componentes em JavaScript para aprimorar a interatividade das páginas web.
ID 20 - Utiliza jQuery para manipulação do DOM e interatividade (eventos, animações, manipulação de elementos)
ID 21 - Integra e configura um plugin jQuery relevante (ex.: jQuery Mask Plugin).
RA5 - Efetuar requisições assíncronas para uma API falsa e APIs públicas, permitindo a obtenção e manipulação de dados de forma dinâmica.
ID 22 - Realiza requisições assíncronas para uma API falsa (ex.: JSON Server) para persistir dados de um formulário.
ID 23 - Realiza requisições assíncronas para uma API falsa para exibir dados na página.
ID 24 - Realiza requisições assíncronas para APIs públicas reais (OpenWeather, ViaCEP etc.), exibindo os dados e tratando erros.
🚀 Manual de execução
Clonar ote comgit clone
Fazer checkout no branch developque contém as modificações mais recentes
Abra o projeto no editor Visual Studio Code (VS Code)
Abra um terminal pelo VSCode ou qualquer terminal do seu Sistema Operacional apontando para o diretório raiz do projeto
Instalar as dependências contidas nopackage.json
Comando:npm i
(Opcional) Instale o JSON Server globalmente disponível emhttps://www.npmjs.com/package/json-server
Comando:npm i -g json-server
É opcional porque a dependência já vem cadastrada no arquivo package.jsonpara instalação local na pastanode_modules
Execute uma API Fake (JSON Server) através de um dos seguintes comandos:
Execução via script registrado no package.json:npm run json:server:routes
Ou via Execução explícita:json-server --watch db.json --routes routes.json
O comando para execução do JSON Server deve ser aplicado no diretório raiz do projeto, ou seja, que contém o arquivo db.jsone routes.json.
Por padrão, a aplicação JSON Server executa no endereçolocalhost:3000
Executar o projeto frontend.

📱 Telas da aplicação
