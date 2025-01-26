# Proposta de Estrutura Organizacional para Gestão e Governança de TI

## Estrutura Organizacional para hospital de referência

A seguir, apresenta-se a estrutura organizacional para a gestão e governança de TI em um hospital de referência:

```mermaid
graph TD
    DiretorGeral[Diretor Geral do Hospital]
    ConselhoGovernanca[Conselho de Governança de TI]
    CIO[Diretor de TI -CIO-]
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

## Estrutura Organizacional para hospital de referência
