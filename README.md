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

#### 5W2H

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
  - O Design do sistema precisa ser responsivo
  - O sistema deve ter acessibildade para mobile
  - O sistema deve fazer requisições na API disponibilizada
  - O sistema deve tratar o json vindo do End-Point da API
  - Sistema será versionado no GitHub
  - Sistema feito no REACT (Framework JS)

## 3. Casos de uso
  - 1º Caso:
    - Nome: Geração de Relatórios de Dados Meteorológicos
    - Ator Principal: Usuário (Engenheiros, Mestres de obras, Setor financeiro e de planejamento)
    - Pré-Condições:
      - O usuário está logado no sistema.
      - O setor financeiro deve ter acesso aos dados climáticos históricos.
      - A plataforma deve fornecer ferramentas para criar relatórios detalhados.  
        
    - Fluxo Básico:
      
      1 - O usuário acessa a opção de "Gerar Relatórios de Dados Meteorológicos" no sistema.
      
      2 - O sistema apresenta opções para configurar o relatório, como seleção do período de tempo e tipos de dados a serem incluídos.
       
      3 - O usuário configura as opções do relatório.
      
      4 - O sistema gera o relatório de acordo com as configurações.
      
      5 - O usuário pode fazer o download do relatório no formato desejado (por exemplo, CSV ou PDF).
         
    
    - Pós-Condições:
      - O usuário possui um relatório de dados meteorológicos para fins de análise financeira e planejamento orçamentário.


  - 2º Caso :
    - Caso de Uso: Exportar Dados Meteorológicos
    - Ator Principal: Usuário do sistema (Engenheiros, Mestres de obras, Setor financeiro e de planejamento)

    - Objetivo: Permitir que o usuário exporte dados meteorológicos em diferentes formatos (JSON, CSV) para análises ou relatórios externos.

    - Pré-condições:
      - O usuário está autenticado no sistema.
      - O usuário já realizou uma consulta de dados meteorológicos ou configurou os filtros desejados.
     
        
    - Fluxo Principal:

      1 - O usuário realiza uma consulta de dados meteorológicos no sistema, configurando os filtros de acordo com suas necessidades.

      2 - Após visualizar os dados na tela principal, o usuário decide exportar os dados para análise externa.

      3 - O sistema exibe a opção de exportação de dados em diferentes formatos, incluindo JSON e CSV.

      4 - O usuário seleciona o formato desejado para a exportação (por exemplo, CSV).

      5 - O sistema gera um arquivo no formato escolhido, contendo os dados meteorológicos de acordo com os filtros aplicados.

      6 - O sistema disponibiliza o arquivo gerado para download.

      

    - Fluxo Alternativo:

      - No passo 4, se o usuário decidir cancelar a exportação, o caso de uso é encerrado sem gerar um arquivo.
      
    - Pós-condições:

      - O usuário obtém um arquivo exportado contendo os dados meteorológicos conforme solicitado.



  

