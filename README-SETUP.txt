ESTRUTURA SUGERIDA NO GITHUB PAGES

/
  index.html
  /admin/index.html
  Produtos.xlsx
  /Catalogo/...
  /data/disponibilidade.json
  /data/pedidos/
  logo-olympikus.png

COMO USAR
1. Publique o index na raiz.
2. Publique a mesma versão em /admin/index.html para ter a URL /admin.
3. No modo admin, preencha owner, repo, branch, token, caminho do JSON de disponibilidade e pasta dos pedidos.
4. Clique em “Salvar config”.
5. Edite a disponibilidade por produto e clique em “Salvar disponibilidade.json”.
6. Os pedidos serão gravados em data/pedidos/*.json.

OBSERVAÇÃO IMPORTANTE
- Como o site roda 100% no front-end, o salvamento direto no GitHub exige token no navegador.
- Para uso público externo, o ideal é intermediar esse salvamento por um backend/worker.
