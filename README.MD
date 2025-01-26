# Proposta de Estrutura Organizacional para Gestão e Governança de TI

### Estrutura Organizacional para hospital de referência:

A seguir, apresenta-se a estrutura organizacional para a gestão e governança de TI 

```mermaid
graph TD
    DiretorGeral[Diretor Geral do Hospital]
    ConselhoGovernanca[Conselho de Governança de TI]
    CIO[Diretor de TI - CIO -]
    GerenteGovernanca[Gerente de Governança de TI]
    Infraestrutura[Gerente de Infraestrutura de TI]
    Sistemas[Gerente de Sistemas de Informação]
    Seguranca[Gerente de Segurança da Informação]
    Suporte[Coordenador de Suporte Técnico]
    Dados[Analistas de Dados]
    Projetos[Equipe de Projetos de TI]

    %% Relações hierárquicas
    DiretorGeral --> ConselhoGovernanca
    ConselhoGovernanca --> CIO
    CIO --> GerenteGovernanca
    CIO --> Infraestrutura
    CIO --> Sistemas
    CIO --> Seguranca
    Infraestrutura --> Suporte
    GerenteGovernanca --> Dados
    GerenteGovernanca --> Projetos

    end


```mermaid
 %% Descrições
        note1[Diretor Geral: Alinha a TI aos objetivos estratégicos do hospital e assegura investimentos alinhados às necessidades institucionais.]
        note2[Conselho de Governança: Define políticas, avalia investimentos e assegura conformidade com regulamentações.]
        note3[CIO: Lidera a estratégia de TI e supervisiona as áreas de infraestrutura, sistemas e segurança.]
        note4[Gerente de Governança: Implementa boas práticas como COBIT e ITIL e gerencia compliance e KPIs.]
        note5[Gerente de Infraestrutura: Garante redes, servidores e continuidade operacional dos sistemas hospitalares.]
        note6[Gerente de Sistemas: Supervisiona prontuários eletrônicos e integra sistemas de gestão hospitalar.]
        note7[Gerente de Segurança: Define políticas de proteção de dados e responde a incidentes de segurança cibernética.]
        note8[Coordenador de Suporte: Lidera o suporte técnico, resolvendo problemas operacionais dos usuários.]
        note9[Analistas de Dados: Integram e analisam dados para decisões estratégicas e relatórios gerenciais.]
        note10[Equipe de Projetos: Gerencia a execução de projetos de TI com metodologias ágeis ou tradicionais.]
    end
