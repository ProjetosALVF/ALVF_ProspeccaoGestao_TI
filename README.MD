# Proposta de Estrutura Organizacional para Gestão e Governança de TI

## Estrutura Organizacional e Descrições dos Cargos

A seguir, apresenta-se a estrutura organizacional para a gestão e governança de TI em um hospital de referência, incluindo as descrições dos cargos:

```mermaid
graph TD
    %% Estrutura Organizacional
    DiretorGeral[Diretor Geral do Hospital]
    CIO[Gerente de TI]
    GerenteGovernanca[Lider de Governança de TI]
    Infraestrutura[Lider de Segurança da Informação e Infraestrutura de TI]
    Sistemas[Lider de Sistemas de Informação]
    Suporte[Equipe de Suporte Técnico]
    Dados[Analistas de Dados]
    Projetos[Equipe de Projetos de TI]

    DiretorGeral --> CIO
    CIO --> GerenteGovernanca
    CIO --> Infraestrutura
    CIO --> Sistemas
    Infraestrutura --> Suporte
    GerenteGovernanca --> Dados
    GerenteGovernanca --> Projetos

    %% Descrições dos Cargos
    note1[Diretor Geral: Neste contexto é responsável pelo alinhamento estratégico da TI com os objetivos gerais do hospital. Garante que os investimentos e políticas de TI estejam conectados às necessidades institucionais.]
    note3[Gerente de TI: Lidera a estratégia de TI no hospital. Supervisiona equipes e promove inovações tecnológicas alinhadas às metas do hospital. Implementa políticas, estratégias e prioridades de TI. Supervisiona investimentos e assegura conformidade com regulamentações e boas práticas.]
    note4[Lider de Governança de TI: Implementa boas práticas como COBIT e ITIL, DevOps. Gerencia indicadores de desempenho, compliance e alinhamento estratégico da TI.]
    note5[Equipe de Suporte Técnico: Gerencia redes, servidores, equipamentos médicos conectados e data centers. Garante a continuidade operacional e monitora a performance dos serviços de TI. Define políticas e estratégias de proteção de dados sensíveis - LGPD. Monitora e responde a incidentes de segurança, prevenindo ataques cibernéticos.]
    note6[Lider de Sistemas de Informação: Supervisiona sistemas hospitalares como prontuários eletrônicos e ERP. Garante a integração e funcionalidade dos sistemas para atender às demandas do hospital.]
    note8[Lider de Segurança da Informação e Infraestrutura de TI: Lidera a equipe de suporte técnico, responsável por resolver problemas operacionais. Garante disponibilidade de serviços e suporte aos usuários finais.]
    note9[Analistas de Dados: Trabalham na análise e integração de dados para apoiar decisões estratégicas e operacionais. Desenvolvem relatórios e dashboards para administração e áreas clínicas.]
    note10[Equipe de Projetos de TI: Executa projetos específicos de TI, como novos sistemas ou upgrades. Utiliza metodologias ágeis ou tradicionais, dependendo da complexidade do projeto.]

    note1 <--> note3
    note4 <--> note8
    note6 <--> note5 <-->  note9
 

