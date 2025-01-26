# Proposta de Estrutura Organizacional para Gestão e Governança de TI

## Estrutura Organizacional e Descrições dos Cargos

A seguir, apresenta-se a estrutura organizacional para a gestão e governança de TI em um hospital de referência, incluindo as descrições dos cargos:

```mermaid
graph TD
    %% Estrutura Organizacional
    DiretorGeral[Diretor Geral do Hospital]
    ConselhoGovernanca[Conselho de Governança de TI]
    CIO[Diretor de TI -CIO-]
    GerenteGovernanca[Gerente de Governança de TI]
    Infraestrutura[Gerente de Segurança da Informação e Infraestrutura de TI]
    Sistemas[Gerente de Sistemas de Informação]
    Suporte[Coordenador de Suporte Técnico]
    Dados[Analistas de Dados]
    Projetos[Equipe de Projetos de TI]

    DiretorGeral --> ConselhoGovernanca
    ConselhoGovernanca --> CIO
    CIO --> GerenteGovernanca
    CIO --> Infraestrutura
    CIO --> Sistemas
    Infraestrutura --> Suporte
    Infraestrutura --> Redes
    GerenteGovernanca --> Dados
    GerenteGovernanca --> Projetos

    %% Descrições dos Cargos
    note1[Diretor Geral: Neste contexto é responsável pelo alinhamento estratégico da TI com os objetivos gerais do hospital. Garante que os investimentos e políticas de TI estejam conectados às necessidades institucionais.]
    note2[Conselho de Governança: Define políticas, estratégias e prioridades de TI. Avalia investimentos e assegura conformidade com regulamentações e boas práticas.]
    note3[CIO: Lidera a estratégia de TI no hospital. ' Supervisiona gerentes e promove inovações tecnológicas alinhadas às metas do hospital.]
    note4[Gerente de Governança: Implementa boas práticas como COBIT e ITIL. Gerencia indicadores de desempenho, compliance e alinhamento estratégico da TI.]
    note5[Gerente de Infraestrutura: Gerencia redes, servidores, equipamentos médicos conectados e data centers. Garante a continuidade operacional e monitora a performance dos serviços de TI.]
    note6[Gerente de Sistemas: Supervisiona sistemas hospitalares como prontuários eletrônicos e ERP. Garante a integração e funcionalidade dos sistemas para atender às demandas do hospital.]
    note7[Gerente de Segurança: Define políticas e estratégias de proteção de dados sensíveis - LGPD. Monitora e responde a incidentes de segurança, prevenindo ataques cibernéticos.]
    note8[Coordenador de Suporte: Lidera a equipe de suporte técnico, responsável por resolver problemas operacionais. Garante disponibilidade de serviços e suporte aos usuários finais.]
    note9[Analistas de Dados: Trabalham na análise e integração de dados para apoiar decisões estratégicas e operacionais. Desenvolvem relatórios e dashboards para administração e áreas clínicas.]
    note10[Equipe de Projetos: Executa projetos específicos de TI, como novos sistemas ou upgrades. Utiliza metodologias ágeis ou tradicionais, dependendo da complexidade do projeto.]

    note1 --> note2
    note2 --> note3
    note3 --> note4
    note4 --> note5
    note5 --> note6
    note6 --> note7
    note7 --> note8
    note8 --> note9
    note9 --> note10

