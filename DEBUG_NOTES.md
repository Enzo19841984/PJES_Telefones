# Debug / auditoria

## Correções aplicadas
- Removido conteúdo residual `// Repository indexing update` de templates.
- Consulta preparada para não misturar contatos de registros diferentes na mesma linha.
- WhatsApp normalizado para `(27) 93134-4700` e link `wa.me`.
- Campos da consulta normalizados de forma tolerante a variações de cabeçalho.
- Tratamento explícito de registros sem microrregião.
- Mapa configurado por URL pública do Google Drive, evitando referência a arquivo local inexistente no HTML Service.
- Busca e filtro de comarcas limitados à microrregião selecionada.

## Validação necessária
O acesso ao mapa depende de o arquivo do Google Drive estar compartilhado como acessível ao público/qualquer pessoa com o link. O Web App precisa conseguir carregar a imagem sem autenticação.
