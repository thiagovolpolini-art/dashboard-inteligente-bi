📊 InsightBI — Dashboard Inteligente para Excel e CSV

Aplicação web completa para análise automática de arquivos Excel e CSV, executada diretamente no navegador.

O projeto identifica métricas, datas, categorias, tendências, rankings e indicadores relevantes, transformando planilhas em um dashboard moderno e interativo.

🚀 Demonstração

https://thiagovolpolini-art.github.io/dashboard-inteligente-bi/

✨ Funcionalidades

Upload de arquivos .xlsx, .xls e .csv

Leitura de planilhas com SheetJS

Identificação automática de:

Métricas numéricas

Datas e períodos

Categorias

Relacionamentos entre colunas

Tendências e agrupamentos

Geração automática de KPIs

Dashboard executivo

Gráficos interativos

Comparativos entre períodos

Ranking das principais categorias

Filtros por:

Busca geral

Categorias

Período

Intervalo numérico

Tabela dinâmica com paginação

Ordenação de colunas

Exportação dos dados filtrados para Excel

Exportação do dashboard para PDF

Modo claro e modo escuro

Layout responsivo para computador, tablet e celular

Processamento local dos dados

🛠️ Tecnologias utilizadas

HTML5

JavaScript

Tailwind CSS

Chart.js

SheetJS / XLSX

HTML2Canvas

jsPDF

Todas as bibliotecas são carregadas por CDN, portanto o projeto não precisa de instalação de dependências.

📁 Estrutura do projeto

dashboard-inteligente-bi/
├── index.html
└── README.md

▶️ Como usar

Baixe ou clone este repositório.

Abra o arquivo index.html no navegador.

Clique na área de upload.

Selecione um arquivo Excel ou CSV.

Aguarde a análise automática.

Utilize os filtros, gráficos, KPIs e a tabela para explorar os dados.

📊 Formatos aceitos

.xlsx
.xls
.csv

Para melhores resultados, utilize arquivos com:

Cabeçalhos na primeira linha

Colunas com nomes claros

Datas padronizadas

Valores numéricos corretamente preenchidos

Poucas células mescladas

Ausência de linhas totalmente vazias entre os dados

🔒 Privacidade

Os arquivos são processados diretamente no navegador.

Os dados carregados não são enviados para servidores externos pela aplicação.

As bibliotecas visuais são carregadas pela internet por meio de CDN, mas o conteúdo da planilha permanece no dispositivo do usuário.

🌐 Publicação no GitHub Pages

Abra o repositório no GitHub.

Clique em Settings.

Acesse Pages.

Em Source, selecione Deploy from a branch.

Escolha a branch main.

Selecione a pasta / (root).

Clique em Save.

Depois da publicação, o GitHub disponibilizará o endereço do site.

💻 Executar localmente

Não é necessário instalar Node.js, Python ou qualquer servidor.

Basta abrir:

index.html

Como as bibliotecas são carregadas por CDN, é necessário estar conectado à internet para que todos os recursos sejam carregados.

📈 Exemplos de dados

A aplicação pode ser utilizada para analisar:

Vendas

Faturamento

Despesas

Estoque

Clientes

Produtos

Campanhas de marketing

Resultados financeiros

Indicadores operacionais

Pesquisas e formulários

Dados acadêmicos

⚠️ Limitações

Arquivos muito grandes podem consumir bastante memória do navegador.

Planilhas com múltiplas linhas de cabeçalho podem exigir ajustes antes do upload.

Células mescladas ou estruturas muito complexas podem afetar a identificação automática.

O desempenho depende do computador ou celular utilizado.

🔮 Melhorias futuras

Salvamento de dashboards

Escolha manual de cores dos gráficos

Mais tipos de visualizações

Importação de múltiplos arquivos

Relacionamento entre diferentes planilhas

Criação de medidas personalizadas

Exportação de imagens

Integração com APIs

Assistente com inteligência artificial

👨‍💻 Autor

Desenvolvido por Thiago Volpolini.

GitHub: thiagovolpolini-art

Portfólio: thiagovolpolini.com

📄 Licença

Este projeto pode ser utilizado para estudos, portfólio e projetos pessoais.

⭐ Caso este projeto tenha sido útil, deixe uma estrela no repositório.
