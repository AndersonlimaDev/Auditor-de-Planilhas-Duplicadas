📊 Auditor de Planilhas Duplicadas (Duplicity Checker)
Este é um sistema web frontend-only desenvolvido em HTML, JavaScript puro e Tailwind CSS para identificar e destacar entradas duplicadas em grandes conjuntos de dados de planilhas (CSV, TXT). Ideal para auditoria rápida de pedidos, cadastros ou qualquer lista onde a unicidade é crucial.

✨ Funcionalidades Principais
Entrada Flexível de Dados: Suporta upload de arquivos (CSV/TXT) e colagem de conteúdo diretamente no campo de texto.

Detecção Inteligente: Analisa automaticamente a primeira linha do conteúdo para identificar o delimitador correto (vírgula, ponto e vírgula ou tabulação).

Seleção Dinâmica de Colunas: Após o carregamento dos dados, o usuário pode selecionar quais colunas (ex: ID_Pedido + Data) devem ser combinadas para definir a regra de duplicidade.

Visualização Clara de Resultados: As linhas identificadas como duplicadas são exibidas em uma tabela e destacadas em vermelho para facilitar a inspeção e correção manual.

Performance: Por ser um aplicativo leve baseado em JavaScript, todo o processamento é feito localmente no navegador, garantindo velocidade e privacidade dos dados.

🛠️ Tecnologias Utilizadas
HTML5: Estrutura base da aplicação.

JavaScript (ES6+): Lógica de processamento de dados (parsing, detecção de delimitador e lógica de duplicidade).

Tailwind CSS: Framework utilitário para um design responsivo e moderno (single-file setup via CDN).

🚀 Como Usar
Clone o Repositório:

git clone [https://www.youtube.com/watch?v=X49Wz3icO3E](https://www.youtube.com/watch?v=X49Wz3icO3E)
cd auditor-planilhas

Abra o Arquivo: Simplesmente abra o arquivo index.html em qualquer navegador web moderno.

Carregue os Dados: Utilize o campo de upload ou cole o conteúdo da sua planilha.

Defina a Regra: Selecione as colunas que formam a chave única do seu registro.

Verifique: Clique em "Verificar Duplicatas" e analise os resultados destacados.

🇺🇸 English Description (Optional, but Recommended)
📊 Spreadsheet Duplicity Auditor (Duplicity Checker)
This is a frontend-only web system developed using HTML, pure JavaScript, and Tailwind CSS designed to quickly identify and highlight duplicate entries in large spreadsheet datasets (CSV, TXT). It is ideal for rapid auditing of orders, registrations, or any list where data uniqueness is crucial.

✨ Key Features
Flexible Data Input: Supports file upload (CSV/TXT) and direct content pasting into the text area.

Intelligent Delimiter Detection: Automatically analyzes the content's first line to identify the correct delimiter (comma, semicolon, or tab).

Dynamic Column Selection: After data loading, the user can select which columns (e.g., Order_ID + Date) should be combined to define the rule for duplicity.

Clear Results Visualization: Rows identified as duplicates are displayed in a table and highlighted in red for easy inspection and manual correction.

Performance: Being a light, JavaScript-based application, all processing is done locally in the browser, ensuring speed and data privacy.

🛠️ Technology Stack
HTML5: Application structure.

JavaScript (ES6+): Core logic for data parsing, delimiter detection, and duplicity checking.

Tailwind CSS: Utility-first framework for a responsive and modern design (single-file setup via CDN).

Estrutura do Repositório Sugerida
Mantenha a estrutura simples, já que é um projeto de arquivo único:

auditor-planilhas/
├── index.html       # O código principal do sistema
└── README.md        # A descrição do projeto (que acabamos de criar)
