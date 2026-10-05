# Metodologia efetivamente utilizada

## Escopo

Esta metodologia descreve o processo realmente aplicado no case. Ela não descreve um método ideal, nem um sistema automatizado de avaliação de editais.

O trabalho foi uma análise documental qualitativa assistida por LLM, orientada por critérios públicos e revisada por pessoas envolvidas no contexto.

## 1. Leitura do edital

O chamamento foi lido para identificar:

- objetivos do evento;
- critérios de avaliação;
- requisitos de inscrição;
- materiais técnicos solicitados;
- exigências documentais;
- condições posteriores de produção e contratação.

Os critérios públicos se tornaram o eixo da comparação. Isso evitou a criação de critérios arbitrários ou a substituição das regras do edital por preferências do analista.

## 2. Leitura das inscrições e anexos

Foram analisados formulários e materiais associados às três inscrições. O conjunto incluía conteúdos textuais, apresentações, portfólios, riders, mapas de palco e anexos.

A leitura buscou identificar informações comparáveis, como:

- proposta e linguagem artística;
- público e classificação indicativa;
- diversidade declarada;
- duração e possibilidade de adaptação;
- equipe e capacidade de execução;
- necessidades técnicas;
- clareza e organização dos materiais;
- documentação e links exigidos.

## 3. Organização das informações

As informações foram organizadas de maneira qualitativa, em uma matriz de comparação. Não foi criada uma base de dados formal, planilha persistida ou modelo de pontuação.

Cada observação foi relacionada a um destes grupos:

- requisito explícito do edital;
- evidência presente nos materiais;
- inferência analítica baseada na relação entre os dois;
- hipótese que não poderia ser confirmada sem parecer oficial.

## 4. Papel da LLM

A LLM foi usada para:

- sintetizar documentos extensos;
- estruturar campos qualitativos comparáveis;
- localizar relações entre edital e proposta;
- ajudar a redigir uma análise acessível;
- explicitar incertezas e limites.

A LLM não foi usada para decidir, classificar, dar notas ou prever aprovação.

Não houve:

- RAG;
- embeddings;
- banco vetorial;
- fine-tuning;
- classificador;
- algoritmo preditivo;
- automação de triagem;
- pipeline de extração em lote reproduzível.

## 5. Comparação com critérios públicos

A análise comparou as evidências disponíveis com critérios como qualidade, impacto, diversidade, viabilidade e clareza.

Exemplo de raciocínio aplicado:

1. O edital prevê viabilidade técnica e operacional.
2. Um caso apresenta estrutura mais simples e transição curta; outro demanda mais recursos e transição extensa.
3. É razoável inferir diferença de compatibilidade operacional.
4. Não é correto concluir que essa diferença causou o resultado, pois não há parecer ou nota individual.

## 6. Revisão humana e correções factuais

Durante o trabalho, a LIMEBH forneceu esclarecimentos que corrigiram ou qualificaram a leitura inicial. Entre eles, a separação entre materiais efetivamente enviados e arquivos apenas disponíveis localmente, bem como a diferença entre pré-seleção e contratação posterior.

Essas correções foram incorporadas à versão final. Esse processo demonstra que a LLM não foi tratada como fonte autossuficiente e que o contexto humano era essencial.

## 7. Validação qualitativa

A validação consistiu em:

- checagem cruzada entre edital, formulários e materiais técnicos;
- revisão de pontos factuais com a LIMEBH;
- inspeção visual de riders e mapas;
- revisão da linguagem para evitar afirmações causais indevidas;
- verificação do relatório final antes de sua entrega.

Não houve validação pela comissão organizadora, auditoria jurídica, acesso ao sistema de avaliação ou reprodução histórica dos links públicos.

## 8. Limitações de rastreabilidade

O processo teve rastreabilidade documental e narrativa, mas não rastreabilidade técnica plena. Não foram preservados, como ativos reutilizáveis:

- uma planilha final de extração;
- um script de transformação;
- um notebook;
- uma base de dados estruturada;
- um log de versões de todos os documentos;
- um registro completo de prompts e respostas.

Essa limitação é assumida explicitamente no case. Uma evolução futura poderia criar esses artefatos, mas eles não fazem parte do trabalho original.
