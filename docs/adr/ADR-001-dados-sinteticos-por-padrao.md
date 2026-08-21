# ADR-001 — Dados sintéticos por padrão

- **Status:** Aceito
- **Data:** 2026-08-20

## Contexto

O repositório é público e tem finalidade de estudo, prototipação e consolidação de métodos de Engenharia de Privacidade. O uso de informações reais de clientes em ambiente público criaria riscos de confidencialidade, privacidade, segurança e governança.

## Decisão

Todos os exemplos, cenários, fixtures, testes e demonstrações usarão dados sintéticos, fictícios, públicos ou previamente redigidos. O repositório não armazenará dados pessoais reais, documentos internos, credenciais, logs produtivos, ROPAs/RIPDs reais ou exportações de clientes.

## Consequências

- Cenários devem indicar explicitamente que são fictícios.
- Dados devem ser criados para teste e não derivados de bases reais sem processo formal.
- Integrações com clientes não fazem parte deste repositório; se forem consideradas no futuro, devem ocorrer em ambiente aprovado e separado.
- A utilidade do sandbox será avaliada pela qualidade dos modelos, regras, testes e artefatos, e não pela disponibilidade de dados reais.

## Alternativas rejeitadas

- Copiar amostras reais anonimizadas para acelerar testes: rejeitado até que exista autorização, método validado de desidentificação e ambiente apropriado.
- Conectar o repositório diretamente a ferramentas de cliente: rejeitado por não atender ao princípio de isolamento e acesso mínimo.