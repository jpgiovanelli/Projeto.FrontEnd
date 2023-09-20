# Nimbus - Projeto Front-end
Projeto dedicado em formar uma pagina eficiente e bem apresentável

## 1. Sobre a empresa:
Nimbus é uma empresa focada em soluções tecnolígicas de previsões meteorológicas.
Contando com um sistema dedicado em informar previsões em pontos específicos.
Teve seu início no Rio de janeiro, mas a empresa está em expansão e já atua em outros estados do sudeste e sul.

## 2. Sobre os clientes:
Os principais clientes são empresas de construção civil que buscam monitorar e planejar as fases de suas obras, mitigando o risco de acidentes em geral.

## 3. Sobre as ferramentas:
  - A Ferramenta fornece:  
    - Previsão personalizada por área ou região de interesse. Dashboard com diferentes KPI`s.  
    - Alertas de deslocamento de tempestades em tempo real.  
    - Dados históricos disponíveis para consulta e rápida exportação para relatórios e laudos.  

## 4. Objetivos do projeto:
Utilizar das tecnologias aprendidas em sala (git, react) para realizar em grupo uma página protótipo para a empresa de metereologia Nimbus, simulando um trabalho feito
para um cliente real com as ferramentas ensinadas.

## 5. Sobre o sistema:

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

#### Requisitos Funcionais:
  - O sistema Download de relatórios personalizados em diferentes formatos (.csv, .pdf e .png)  
  - O sistema Visualização de pontos pré-configurados no mapa (marcadores de estacões e áreas)
  - O sistema Visualização de dados de estações simultâneas selecionadas no mapa  
  - O sistema Gráficos dinâmicos e ajustáveis em diferentes dispositivos
  - O sistema Visualização em diferentes tamanhos de telas
  - O sistema Tabelas com dados
  - O sistema Interação entre os componentes
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

  

