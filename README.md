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
  - 1º Caso:
    - Nome: Configuração de Alertas Meteorológicos
    - Ator Principal: Usuário (QUEM?????????)
    - Pré-Condições:
      - O usuário está logado no sistema.
    - Fluxo Básico:
      - O usuário acessa a opção de "Configurar Alertas Meteorológicos" no sistema.
      - O sistema exibe uma lista de tipos de alerta disponíveis (por exemplo, chuvas fortes, ventos fortes).
      - O usuário seleciona um ou mais tipos de alerta.
      - O sistema permite ao usuário definir as condições para acionar o alerta, como intensidade da chuva ou velocidade do vento.
      - O usuário configura as condições de acionamento.
      - O sistema salva as configurações do alerta.
    - Pós-Condições:
      - O usuário está configurado para receber alertas meteorológicos personalizados com base nas condições especificadas.

  - 2º Caso:
    - Nome: Geração de Relatórios de Dados Meteorológicos
    - Ator Principal: Usuário (Setor Financeiro)
    - Pré-Condições:
      - O usuário está logado no sistema.
    - Fluxo Básico:
      - O usuário acessa a opção de "Gerar Relatórios de Dados Meteorológicos" no sistema.
      - O sistema apresenta opções para configurar o relatório, como seleção do período de tempo e tipos de dados a serem incluídos.
      - O usuário configura as opções do relatório.
      - O sistema gera o relatório de acordo com as configurações.
      - O usuário pode fazer o download do relatório no formato desejado (por exemplo, CSV ou PDF).
    - Pós-Condições:
      - O usuário possui um relatório de dados meteorológicos para fins de análise financeira e planejamento orçamentário.

  - 3º Caso:
    - Nome: Compartilhamento de Previsões Meteorológicas
    - Ator Principal: Usuário (QUEM????????????)
    - Pré-Condições:
      - O usuário está logado no sistema.
    - Fluxo Básico:
      - O usuário acessa a opção de "Compartilhar Previsões Meteorológicas" no sistema.
      - O sistema permite ao usuário selecionar as previsões meteorológicas desejadas.
      - O usuário escolhe o método de compartilhamento, como gerar um link compartilhável ou enviar por e-mail.
      - O sistema gera o link ou envia o e-mail com as previsões.
    - Pós-Condições:
      - As previsões meteorológicas são compartilhadas com outros membros da equipe ou partes interessadas conforme a escolha do usuário.



  

