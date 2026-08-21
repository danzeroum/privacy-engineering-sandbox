# Privacy Engineering Sandbox

Laboratório público para modelar, testar e documentar práticas de Engenharia de Privacidade com **dados sintéticos por padrão**.

## Objetivo

Transformar necessidades de privacidade, auditoria e governança em artefatos verificáveis:

- triagem de processos, atividades de tratamento e achados;
- backlog priorizado com evidências e responsáveis;
- regras explicáveis para detectar lacunas;
- hipóteses de automação assistiva e detectiva;
- cenários fictícios para testes reproduzíveis.

## Escopo inicial

Este repositório é um modelo de trabalho. Ele não representa, replica ou se integra a ambientes de clientes.

O primeiro MVP deve apoiar a jornada:

```text
processo -> dados -> sistemas -> lacunas -> regra -> evidência -> decisão humana
```

## Princípios inegociáveis

1. Dados sintéticos, fictícios, públicos ou previamente redigidos por padrão.
2. Nenhuma credencial, segredo, exportação, log, screenshot ou dado pessoal real de cliente.
3. Nenhuma integração com ambiente de cliente sem autorização formal, finalidade definida e acesso mínimo.
4. Automações iniciais são assistivas/detectivas: geram pendências e evidências; não aprovam risco, definem retenção, excluem dados ou alteram produção.
5. Toda recomendação deve registrar hipótese, evidência, limitação, responsável e critério de aceite.

## Estrutura

```text
/docs          ADRs, governança e templates
/data          regras e cenários exclusivamente sintéticos
/rules         regras verificáveis de triagem (futuro)
/scripts       validações e geração de relatórios (futuro)
/tests         casos de teste e fixtures (futuro)
/app           interface ou serviço local (futuro)
```

## Primeiro cenário

`data/synthetic/portaria-ficticia.json` simula um processo fictício de controle de entrada. O cenário serve para testar como uma regra detecta ausência de prazo de retenção documentado. A saída esperada é uma pendência de validação humana — nunca uma decisão ou execução automática de descarte.

## Como contribuir

1. Leia [SECURITY.md](SECURITY.md) e [limites de uso](docs/governance/limites-de-uso.md).
2. Não suba conteúdo de clientes, dados pessoais, segredos ou evidências internas.
3. Prefira criar cenários sintéticos versionados e testes reproduzíveis.
4. Registre decisões arquiteturais em `docs/adr/`.

## Status

Fundação de governança e cenários sintéticos em construção.

> Este projeto é educacional e experimental. Não substitui validação de Privacidade, DPO, Jurídico, Segurança, Compliance, Arquitetura, Infraestrutura ou áreas donas de processo.