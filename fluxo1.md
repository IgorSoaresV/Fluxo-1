```mermaid
graph TD
    A[Identificação do Comportamento Problema] --> B[Avaliação Inicial pela Equipe Escolar]
    B --> C[Desenvolvimento de Plano de Intervenção Individualizado]
    
    subgraph Desenvolvimento de PII
        C1[Coleta de Dados do Aluno]
        C2[Avaliação Multidisciplinar]
        C3[Definição de Metas e Objetivos]
        C4[Escolha de Estratégias de Intervenção]
        C5[Revisão e Aprovação pelo Corpo Docente]
        
        C --> C1
        C1 --> C2
        C2 --> C3
        C3 --> C4
        C4 --> C5
    end
    
    C --> D[Implementação das Estratégias de Intervenção na Escola]

    subgraph Implementação de Estratégias
        D1[Formação dos Professores e Funcionários]
        D2[Adaptação do Ambiente Escolar]
        D3[Apoio Pedagógico Individualizado]
        D4[Uso de Tecnologias Assistivas]
        
        D --> D1
        D1 --> D2
        D2 --> D3
        D3 --> D4
    end

    D --> E[Acompanhamento e Monitoramento do Comportamento]

    subgraph Acompanhamento e Monitoramento
        E1[Registro Diário de Comportamentos]
        E2[Reuniões Semanais da Equipe Multidisciplinar]
        E3[Feedback Regular para os Pais ou Responsáveis]
        E4[Revisões Mensais do Plano de Intervenção]
        
        E --> E1
        E1 --> E2
        E2 --> E3
        E3 --> E4
    end
    
    E --> F{Comportamento Melhorou?}
    F --> G[Sim]
    F --> H[Não]
    G --> I[Manutenção do Plano e Reavaliação Periódica]
    H --> J[Revisão do Plano de Intervenção]
    J --> K[Persistência do Comportamento Problema]

    K --> L{Necessidade de Encaminhamento?}
    L --> M[Sim]
    L --> N[Não]
    N --> O[Adaptação e Novas Estratégias]
    M --> P[Encaminhamento à Rede de Proteção e Assistência]

    P --> Q[CAPS]
    P --> R[CRAS]
    P --> S[CREAS]
    P --> T[Conselho Tutelar]
    P --> U[Unidade Básica de Saúde]
    P --> V[Ministério Público]

    subgraph Critérios para Encaminhamento
        Q1[CAPS: Transtornos mentais graves, necessidade de acompanhamento psicológico ou psiquiátrico especializado]
        R1[CRAS: Situações de vulnerabilidade social, assistência social e fortalecimento de vínculos familiares]
        S1[CREAS: Situações de violação de direitos, como abuso ou exploração]
        T1[Conselho Tutelar: Casos de negligência, abuso ou violação dos direitos da criança e do adolescente]
        U1[Unidade Básica de Saúde: Necessidade de atendimento médico básico, acompanhamento de saúde geral]
        V1[Ministério Público: Casos que envolvam infrações graves ou demandas judiciais para a proteção dos direitos do aluno]
        
        Q --> Q1
        R --> R1
        S --> S1
        T --> T1
        U --> U1
        V --> V1
    end
