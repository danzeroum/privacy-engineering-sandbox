# Dados do sandbox

Todo conteúdo em `data/` é sintético e existe exclusivamente para demonstrar fluxos, regras e testes.

## Regras

- Use nomes, identificadores, endereços, e-mails, documentos e sistemas inteiramente fictícios.
- Não derive cenários diretamente de registros de cliente.
- Não inclua dados pessoais reais, mesmo que pareçam inofensivos.
- Declare a finalidade de cada cenário e a regra que ele pretende testar.
- Mantenha os arquivos pequenos, legíveis e versionáveis.

## Estrutura sugerida

```text
/synthetic       Cenários fictícios
/fixtures        Entradas específicas para testes
/schemas         Contratos de dados, quando existirem
```

O arquivo `synthetic/portaria-ficticia.json` é um cenário de teste: ele representa uma lacuna de retenção e deve gerar uma pendência para validação humana.