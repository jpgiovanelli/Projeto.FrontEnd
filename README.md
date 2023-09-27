# Nimbus - Projeto Front-end
Projeto dedicado em formar uma pagina eficiente e bem apresentável

## 1. Objetivos do projeto:
Utilizar das tecnologias aprendidas em sala (git, react) para realizar em grupo uma página protótipo para a empresa de metereologia Nimbus, simulando um trabalho feito
para um cliente real com as ferramentas ensinadas.

## 2. Sobre o sistema:

#### O sistema será utilizado por:
  - Engenheiros  
  - Mestres de obras  
  - Setor financeiro e de planejamento

#### Como serão consumidos os dados:
  - End-point das APIs 
    - JSON  
    - CSV   
    
  -> JSON: Estrutura de dados em par chave:valor  
  -> CSV: Arquivo de dados separado por vírgula

#### Propósito do sistema:
O sistema fornece recursos essenciais para a análise de dados meteorológicos. Permite o download de relatórios personalizados em diferentes formatos, facilitando a análise. Os usuários podem visualizar pontos no mapa, incluindo estações e áreas, e comparar dados de várias estações simultaneamente. Gráficos dinâmicos que se ajustam a diferentes dispositivos e tabelas detalhadas. A interação entre componentes é intuitiva. Em resumo, é uma ferramenta completa para análise de dados meteorológicos, com flexibilidade e interatividade.

#### 5W2H:

##### O Quê

- Adquire informações meteorológicas por meio de fontes como radares que acompanham em tempo real as condições das nuvens.

##### Por quê

- Utilizar equações físicas e matemáticas para oferecer previsões que auxiliem no planejamento da obra.

##### Quem

- As empresas que adquirem o serviço (departamentos de planejamento, engenharia e meteorologia).

##### Quando

- A entrada de dados ocorre continuamente, enquanto a consulta do cliente varia de acordo com o horário de sua escolha, seja 24 horas por dia ou conforme um agendamento previamente definido.

##### Como

- Haverá uma solicitação de dados por meio de um formulário preenchido pelo usuário. Posteriormente, os dados serão obtidos por meio de uma API e exportados no formato de uma tabela de arquivo.

##### Onde

- Será acessado por dispositivos móveis e página web com responsividade.

#### 5W2H Do Sistema

#### O quê?
O sistema processa informações meteorológicas, incluindo dados de radares que monitoram as condições das nuvens em tempo real.

#### Por quê?
O sistema é feito com o propósito de oferecer previsões baseadas em equações físicas e matemáticas, facilitando o planejamento de projetos.

#### Quem?
O sistema será utilizado principalmente por empresas e profissionais envolvidos em planejamento, engenharia e meteorologia que contratam o serviço.

#### Quando?
O sistema será utilizado pelo cliente dependendo do horário desejado, podendo ser em tempo real ou previamente planejado.

#### Como?
O sistema permite que o usuário solicite os dados por meio de um formulário, os quais são obtidos através de uma API e posteriormente exportados em um formato de tabela.

#### Onde?
O sistema é aplicado em situações que envolvem o planejamento de obras e em pesquisas relacionadas à meteorologia.

#### Quanto?
O tempo investido no desenvolvimento do programa, pelos programadores, constitui um aspecto relevante em termos de recursos.


#### Requisitos Funcionais:
  - O sistema deve disponibilizar o download de relatórios personalizados em diferentes formatos (.csv, .pdf e .png)  
  - O sistema deve ter a visualização de pontos pré-configurados no mapa (marcadores de estacões e áreas)
  - O sistema deve ter a visualização de dados de estações simultâneas selecionadas no mapa  
  - O sistema deve ter gráficos dinâmicos e ajustáveis em diferentes dispositivos
  - O sistema daverá ser oferecido em diferentes tamanhos de telas
  - O sistema deve ter tabelas com dados
  - O sistema deve ter interação entre os componentes
  - O sistema deve incorporar e exibir os dados meteorológicos, bem como as equações matemáticas e físicas pertinentes, na tela principal.
  - O Sistema irá possuir um formulário que considera uma série de critério de filtro, tais como: Data inicial, data final, tipo de variável metereológica, ponto de monitoramento.

#### Requisitos não-funcionais:
  - A página deve ter um tempo de carregamento rápido
  - O Design precisa ser responsivo
  - Acessibildade para mobile
  - Requisições na API disponibilizada
  - Tratamento do json vindo do End-Point da API
  - Sistema será versionado no GitHub
  - Sistema feito no REACT (Framework JS)

## 3. Casos de uso
 -1º Caso:
    -Ator Principal: Usuário do sistema (Engenheiros, Mestres de obras, Setor financeiro e de planejamento)
    -Objetivo: Permitir que o usuário exporte dados meteorológicos em diferentes formatos (JSON, CSV) para análises ou relatórios externos.

-Pré-condições:
  -O usuário está autenticado no sistema.
  -O usuário já realizou uma consulta de dados meteorológicos ou configurou os filtros desejados.
  
-Fluxo Principal:
  -O usuário realiza uma consulta de dados meteorológicos no sistema, configurando os filtros de acordo com suas necessidades.
  -Após visualizar os dados na tela principal, o usuário decide exportar os dados para análise externa.
  -O sistema exibe a opção de exportação de dados em diferentes formatos, incluindo JSON e CSV.
  -O usuário seleciona o formato desejado para a exportação (por exemplo, CSV).
  -O sistema gera um arquivo no formato escolhido, contendo os dados meteorológicos de acordo com os filtros aplicados.
  -O sistema disponibiliza o arquivo gerado para download.

-Fluxo Alternativo:
  -No passo 4, se o usuário decidir cancelar a exportação, o caso de uso é encerrado sem gerar um arquivo.
  
-Pós-condições:

  -O usuário obtém um arquivo exportado contendo os dados meteorológicos conforme solicitado.
  
-Requisitos Relacionados:

   -Requisitos Funcionais:
   -O sistema deve disponibilizar o download de relatórios personalizados em diferentes formatos (.csv, .pdf e .png).
   -O sistema deve incorporar e exibir os dados meteorológicos na tela principal.

  - 2º Caso:



  

