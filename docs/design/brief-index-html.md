# Briefing de Design — index.html

## Missão

Desenhar a página inicial de um sandbox público de Engenharia de Privacidade. A página deve ajudar Engenharia de Privacidade e Advocacia/Privacidade a transformar cenários sintéticos em fatos, evidências, lacunas, riscos, recomendações e próximos passos verificáveis.

**Mensagem central:**

> Do processo à decisão responsável: organizar evidências, reduzir incertezas e preparar validações humanas.

## Limites

- Usar somente dados sintéticos, fictícios, públicos ou redigidos.
- Não processar dados pessoais reais, documentos internos, credenciais, logs ou informações de clientes.
- Não indicar aprovação automática, conformidade garantida, decisão jurídica, retenção, descarte, aceite de risco ou alteração produtiva.
- Usar verbos como: avaliar, levantar, sinalizar, propor e encaminhar para validação.
- Deixar visível que decisões formais dependem do papel competente.

## Pessoas e colaboração

| Engenharia de Privacidade | Espaço compartilhado | Advocacia/Privacidade |
|---|---|---|
| Processo, sistemas, APIs, integrações, logs, dependências e viabilidade técnica | Fatos, evidências, lacunas, riscos, backlog, recomendações e decisões pendentes | Finalidade, retenção, transparência, obrigações, direitos, aprovações e validação formal |

Frase obrigatória na interface:

> A engenharia não decide o jurídico; o jurídico não precisa operar a tecnologia. Ambos usam evidências para construir uma recomendação verificável.

Jornada compartilhada:

```text
Processo -> dados -> sistemas -> evidência -> lacuna -> risco -> recomendação -> validação -> decisão humana
```

## Arquitetura da página

### 1. Hero

- Título: `Privacy Engineering Sandbox`
- Subtítulo: `Modele cenários sintéticos, conecte processo, dados e evidências, e prepare decisões humanas mais seguras.`
- Aviso: `Laboratório público: use apenas dados sintéticos.`
- CTAs:
  - Explorar cenários
  - Começar uma análise
  - Ver limites de uso
- Ilustração abstrata da jornada:
  - Processo
  - Dados
  - Evidência
  - Lacuna
  - Validação
  - Decisão

### 2. Como a dupla trabalha

Mostrar dois cartões, Engenharia de Privacidade e Advocacia/Privacidade, conectados por uma área central chamada:

```text
Visão compartilhada
```

A área central deve destacar:

- Fatos
- Evidências
- Lacunas
- Riscos
- Backlog
- Recomendações
- Aprovações pendentes

### 3. Mapa de possibilidades

Criar cartões clicáveis. Cada cartão deve apresentar:

- Objetivo
- Entrada necessária
- Saída esperada
- Áreas envolvidas
- Limites e validações obrigatórias

Possibilidades:

1. Triagem de legado e achados de auditoria
2. Completude de ROPA/RIPD sintético
3. Mapa de processo, dados e sistemas
4. Avaliação de retenção e ciclo de vida
5. Matriz de evidências de controles
6. Avaliação de acesso e segregação de funções
7. Análise de integrações e fornecedores
8. Oportunidades de automação assistiva
9. Fluxos BPMN e decisões DMN
10. Simulação de backlog e priorização
11. Relatório executivo de lacunas e bloqueios
12. Catálogo de controles e critérios de aceite

### 4. Jornada de um caso

Exibir timeline de seis etapas:

1. Definir cenário sintético e objetivo
2. Mapear processo, dados, sistemas e responsáveis
3. Registrar fatos, premissas e lacunas
4. Avaliar risco e evidências necessárias
5. Formular recomendação ou hipótese de automação
6. Encaminhar para validação humana e registrar próximo passo

Cada etapa deve responder:

- Por que importa?
- O que a Engenharia faz?
- O que a Advocacia/Privacidade faz?
- Que evidência deve ser buscada?
- Quem deve validar?
- Qual é o sinal de pronto?

### 5. Catálogo de cenários

Criar cenários fictícios filtráveis por tags:

- Portaria e retenção de registros
- Processo legado sem dono identificado
- Integração fictícia com fornecedor
- Sistema fictício em transição
- Revisão de acesso a dados
- Solicitação simulada de direito do titular
- Coleta excessiva em formulário
- Evidência incompleta de controle

Tags:

```text
legado | retenção | acesso | integração | fornecedor | automação | BPMN | evidência
```

### 6. Painel de análise compartilhada

Criar mockup de área de trabalho com abas ou colunas:

```text
Contexto | Processo | Dados | Sistemas | Evidências | Lacunas | Riscos | Recomendações | Aprovações
```

Exibir dados declaradamente fictícios:

| Tipo | Item | Responsável a consultar | Próximo passo |
|---|---|---|---|
| Lacuna | Prazo de retenção não documentado | Privacidade + Jurídico | Validar regra aplicável |
| Dependência | Backup não mapeado | Segurança + TI | Levantar fluxo de recuperação |
| Hipótese | Regra detectiva para campos ausentes | Engenharia + Privacidade | Criar cenário de teste |

### 7. Radar de decisão

Exibir cinco estados, com cor, ícone e texto:

- Fato informado
- Premissa a validar
- Lacuna de evidência
- Risco a investigar
- Decisão dependente de validação

Mensagem obrigatória:

> O sandbox ajuda a converter incerteza em uma pergunta verificável; não substitui o decisor competente.

### 8. Laboratório de automação

Apresentar automações como hipóteses, não como automações implantadas.

| Tipo | Exemplo seguro | Não deve fazer |
|---|---|---|
| Assistiva | Gerar checklist de campos ausentes | Preencher ou aprovar informação sem revisão |
| Detectiva | Sinalizar retenção sem evidência | Concluir que a retenção é inválida |
| Preventiva | Bloquear avanço de template incompleto | Bloquear processo produtivo sem aprovação |
| Corretiva | Criar pendência de revisão | Excluir dados ou alterar produção automaticamente |

### 9. Biblioteca de artefatos

Criar cards para:

- Template de backlog de privacidade
- Matriz de evidências
- Questionário processo–dados–sistemas
- Fluxos BPMN sintéticos
- Regras de triagem
- ADRs
- Limites de uso
- Glossário
- Checklist de preparação de reunião

### 10. Rodapé

Texto obrigatório:

> Protótipo educacional e experimental. Não processe dados pessoais reais ou informações internas de clientes. Recomendações, retenção, descarte, risco e alterações produtivas exigem validação pelas áreas e aprovadores competentes.

Links:

- Segurança
- Limites de uso
- ADR de dados sintéticos
- Repositório
- Como contribuir

## Possibilidades por fase

### MVP

- Navegação pelos cenários sintéticos
- Jornada de análise compartilhada
- Templates e checklists
- Fluxos BPMN importáveis
- Matriz de fatos, lacunas e riscos
- Catálogo de hipóteses de automação
- Exportação visual de relatório fictício em Markdown

### Validação de método

- Formulário local para montar caso sintético
- Motor de regras explicáveis para campos ausentes
- Comparação entre processo atual e proposto
- Integração visual com BPMNPlay
- Simulação de priorização por criticidade, prazo, impacto e dependência
- Relatório de cobertura de evidências

### Futuro, após governança

- Autenticação e papéis
- Persistência de cenários autorizados
- Integrações aprovadas com ferramentas externas
- Workflows formais de aprovação
- Auditoria de alterações
- Versionamento de evidências
- Integração com catálogo de sistemas, dados ou backlog

## Direção visual

A interface deve ser clara, técnica, acolhedora e não punitiva.

```text
Fundo: #F7FAFC
Superfície: #FFFFFF
Texto principal: #17324D
Texto secundário: #49657D
Ação: #176BBD
Evidência/sucesso: #1F7A5B
Pendência/atenção: #9A6700
Alerta: #B42318
Bordas: #D7E2EC
```

Usar:

- Cartões claros
- Ícones SVG simples
- Timeline
- Tags
- Tabelas responsivas
- Tabs
- Accordions
- Espaçamento generoso
- Foco visível
- Estados explícitos

Evitar:

- Visual hospitalar
- Visual policialesco
- Compliance punitivo
- Dark patterns
- Urgência artificial
- Conteúdo importante dependente de hover

## Acessibilidade

- HTML semântico
- Hierarquia correta de títulos
- Contraste suficiente
- Navegação completa por teclado
- Foco visível
- `aria-expanded` para accordions
- `aria-live` para feedbacks
- Status não indicados apenas por cor
- Texto-base mínimo de 16 px
- Alvos clicáveis mínimos de 44 px
- Respeitar `prefers-reduced-motion`

## Critérios de aceite

1. Em menos de um minuto, a pessoa entende que o sandbox usa dados sintéticos e não toma decisões jurídicas automáticas.
2. A colaboração entre engenharia e advocacia fica clara e equilibrada.
3. As possibilidades de teste, limites, evidências e envolvidos são encontráveis.
4. A interface diferencia fato, premissa, lacuna, risco e decisão pendente.
5. A pessoa encontra um próximo passo seguro para iniciar um cenário.
6. O layout funciona em mobile e desktop.
7. A página é utilizável por teclado.
8. A página não exibe clientes, dados reais, sistemas internos ou decisões automatizadas como se fossem permitidas.
