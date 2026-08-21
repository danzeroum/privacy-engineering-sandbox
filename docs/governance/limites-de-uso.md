# Limites de uso do sandbox

## Finalidade

O sandbox serve para testar métodos, modelos de dados, regras verificáveis, templates e automações assistivas de Engenharia de Privacidade.

## Permitido

- Simular processos, sistemas, integrações e achados com conteúdo fictício.
- Testar detecção de lacunas de documentação, evidência, retenção, acesso e dependências.
- Produzir relatórios que indiquem necessidade de validação humana.
- Criar protótipos locais e descartáveis.

## Não permitido

- Processar dados pessoais reais ou informação interna de clientes neste repositório.
- Usar credenciais de cliente, copiar artefatos internos ou integrar ambiente sem autorização formal.
- Tomar decisão automática sobre base legal, retenção, descarte, risco ou alteração produtiva.

## Pré-requisitos para evolução com cliente

Antes de qualquer atividade fora do sandbox, registrar:

1. Caso de uso e finalidade.
2. Dados, sistemas, áreas e fornecedores envolvidos.
3. Responsável pelo processo e aprovadores.
4. Canal e ambiente autorizado.
5. Perfil de acesso mínimo e prazo de revogação.
6. Política aplicável de retenção, segurança, logs e compartilhamento.
7. Critério de aceite, plano de teste e risco residual.

## Modelo de decisão

```text
Hipótese -> evidência disponível -> lacuna -> risco -> recomendação -> validação formal -> decisão -> implementação pela área responsável
```

O sandbox pode apoiar até a recomendação. A decisão formal e a implementação pertencem às áreas e aprovadores competentes.