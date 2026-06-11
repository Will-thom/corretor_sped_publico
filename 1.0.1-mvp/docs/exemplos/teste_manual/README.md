# Kit De Teste Manual

Este diretorio contem arquivos ficticios para testar instalacao e uso do Corretor SPED sem dados reais.

## Conteudo

- `entrada/sped/efd_icms_ipi_exemplo.txt`: SPED ficticio com participante ausente, produto ausente e totalizadores inconsistentes.
- `entrada/pva/relatorio_pva_exemplo.txt`: relatorio PVA textual ficticio.
- `entrada/planilhas/participantes.csv`: evidencia CSV para o participante ausente.
- `entrada/planilhas/produtos.csv`: CSV auxiliar adicional para teste de leitura.
- `entrada/xml/nfe/nfe_produto_exemplo.xml`: evidencia XML para o produto ausente.

No fluxo oficial do MVP, a licenca ficticia de teste e embutida no MSI e expira 7 dias apos a geracao do pacote. O arquivo `licenca_teste.json` permanece apenas como referencia local de fixture historica e nao deve ser usado como caminho principal de onboarding.

## Observacao

Todos os CNPJs, chaves, nomes, valores e codigos sao ficticios.
