# Conceitos Básicos, Terminologias e Papéis em Qualidade de Software

## O que é Qualidade de Software?
Hoje em dia os consumidores de software buscam mais produtos cada vez melhores e mais rápidos, por isso a qualidade de software é importante. Pois busca garantir um produto final que satisfaça os seus usuários, por isso é uma construção continua que depende principalmente de um processo de desenvolvimento.

## As Três Siglas Principais: QA vs. QC vs. Testing
| Conceitos | Foco Principal | Abordagem | Exemplo no dia a dia |
| :--- | :--- | :--- | :--- |
| **QA (Quality Assurance)** | Processo | Preventiva | Criar diretrizes de escrita de código, alinhar regras de negócio com time antes de programar ou melhorar o fluxo no Jira. |
| **QC (Quality Control)** | Produto | Detectiva | Inspeções de código, revisões técnicas e validações de entregáveis. |
| **Testing (Teste)** | Execução | Operacional | Executar cenários manuais ou automatizados para encontrar falhas no sistema |

QA previne erros melhorando processos, o QC valida se o produto atende aos requisitos, e os testes são a execução prática para encontrar esses erros.

## O que é bug? (Erro vs. Defeito vs. Falha)

1. **Erro (Error / Mistake):** uma ação humana incorreta cometida pelo ser humano (ex: interpretação errada do requisito ou lógica de código incorreto)
2. **Defeito/Bug (Defect / Bug):** imperfeição no código ou documento causado pelo erro humano. O bug "mora" no código ou na documentação
3. **Falha (Failure):** A manifestação visível do defeito durante a execução do software (ex: a tela congela ou um erro 500 aparece para o usuário)

## Validação vs. Verificação
- **Verificação (Estamos construindo o produto CORRETAMENTE):** Avalia os artefatos de software (requisitos, código, diagramas) sem executar o código.
    - Exemplo: Revisão de Histórias do Usuário, Code Review.
- **Validação (Estamos construindo o produto Certo):** Avalia se o software funciona atende às reais necessidades do cliente/usuário.
    - Exemplo: Execução de testes de aceitação do usuário (UAT).

## Por que Testar É Impossível de Forma Exaustiva?
Com base no ITSQB *"Testes exaustivos são impossíveis"* devido à infinidade de combinações de dados, navegadores, cenários e caminhos, o objetivo do QA não é provar que o software está 100% livre de erros, mas sim reduzir o risco do negócio a uma nível aceitável.