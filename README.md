Beeterprise - Dashboard de Gestão Integrada
📖 Sobre o Projeto
O Beeterprise é um painel de controle (dashboard) completo para gestão empresarial, desenvolvido como uma aplicação de página única (SPA - Single Page Application). A interface, construída inteiramente com HTML, Tailwind CSS e JavaScript puro, oferece uma visão 360º da empresa, consolidando dados de diferentes departamentos em um ambiente interativo e visualmente agradável.

Este projeto foi criado para demonstrar a construção de uma aplicação web moderna e funcional sem a necessidade de frameworks complexos, utilizando bibliotecas leves e CDNs para uma prototipagem rápida e eficiente.

✨ Funcionalidades Principais
O dashboard é dividido em múltiplos painéis, cada um com funcionalidades específicas:

1. 👥 Gestão de Usuários
CRUD Completo: Adicione, edite e exclua usuários através de modais interativos.
Busca em Tempo Real: Filtre a lista de usuários instantaneamente por nome, email ou cargo.
Ordenação Dinâmica: Classifique a tabela clicando nos cabeçalhos das colunas (Nome, Cargo, Último Acesso).
Paginação: Navegue facilmente por grandes volumes de dados.
Visualização de Produtividade: Gráficos de linha (sparklines) individuais para cada usuário.

2. 💰 Dashboard Financeiro
KPIs em Destaque: Cards com resumo de Faturamento, Custos, Lucro Líquido e Crescimento.

Gráficos Detalhados:

Receita vs. Despesa: Gráfico de linha para análise de performance ao longo do tempo.

Distribuição de Custos: Gráfico de pizza (doughnut) para entender a alocação de recursos.

3. 📋 Projetos em Andamento
Quadro Kanban: Organize projetos nas colunas "Planejado", "Em Progresso" e "Concluído".

Filtro por Departamento: Visualize projetos específicos de cada área da empresa.

4. 📊 Relatórios e Indicadores
Métricas de RH: Acompanhe o NPS interno e a taxa de Turnover.

Análise de Performance: Gráfico de barras comparando a produtividade entre os departamentos.

5. 🎓 Plataforma de Cursos
Recomendação Inteligente: Selecione um colaborador e veja os cursos mais adequados para o seu cargo.

Catálogo Completo: Explore todos os treinamentos disponíveis na empresa.

6. 📞 Helpdesk e Suporte
Métricas de Atendimento: Cards com o status dos tickets (Abertos, Resolvidos) e o Tempo Médio de Resposta.

Lista de Tickets: Tabela com os chamados recentes para acompanhamento.

🛠️ Tecnologias Utilizadas

HTML5: Estrutura semântica do conteúdo.
Tailwind CSS: Framework CSS utilitário para um design rápido e responsivo.
JavaScript (ES6+): Toda a lógica de interatividade, manipulação do DOM e gerenciamento de estado.
Chart.js: Biblioteca para a criação dos gráficos dinâmicos e interativos.

🚀 Como Executar

Este projeto foi construído para ser o mais simples possível de executar. Por ser um único arquivo HTML que utiliza CDNs para carregar suas dependências, não há necessidade de um processo de build ou instalação de pacotes.
Faça o download do arquivo tabela_interativa.html.
Abra o arquivo em qualquer navegador de internet moderno (Google Chrome, Firefox, Microsoft Edge, etc.).
Pronto! A aplicação estará funcionando completamente.

📄 Estrutura do Código JavaScript
O código JavaScript está contido em uma única tag <script> no final do arquivo HTML e é organizado em blocos lógicos para facilitar a manutenção:

Configurações Personalizáveis: 

Constantes para configurações globais, como linhas por página.
Dados Fictícios (Mock): Arrays e objetos que simulam uma base de dados.
Estado Global: Variáveis que controlam o estado atual da aplicação (página, filtros, etc.).
Seleção de Elementos do DOM: Centralização da captura de todos os elementos HTML necessários.
Funções de Navegação: Lógica para alternar entre as diferentes telas do dashboard.
Funções Utilitárias: Funções de formatação (data, moeda) e outras tarefas repetitivas.
Blocos de Renderização: Funções dedicadas a desenhar cada tela (usuários, financeiro, etc.).
Bloco de Modais e Notificações: Funções que controlam a exibição de modais e toasts.
Bloco de Event Listeners: Centralização de todos os "ouvintes" de eventos (cliques, digitação, etc.).
Execução Inicial: Chamada das funções principais quando a página é carregada.

Criado e desenvolvido de forma colaborativa.
