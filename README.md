# MiauConta

Site responsivo para comparar ofertas de produtos para gatos e planejar estoque. Catálogo com 11 produtos, fotos reais e 31 links de lojas.

## Hospedar na Vercel

1. Importe este repositório em https://vercel.com/new.
2. Mantenha Root Directory na raiz do repositório.
3. Framework Preset: Other.
4. Output Directory: dist.
5. Não é necessário instalar dependências ou executar build. Clique em Deploy.

O arquivo vercel.json já define essa configuração. Não são necessárias variáveis de ambiente.

## Editar o site

- dist/index.html: página e conteúdo.
- dist/reference.css e dist/tools.css: visual e layout mobile.
- dist/catalog.js: produtos, fotos e links das lojas.
- dist/app.js: comparação de custo, favoritos e estoque.
- dist/assets/: imagens e fontes locais.

Os preços são informados pela pessoa na calculadora. O catálogo não consulta preços automaticamente. Favoritos e planejamento ficam salvos no navegador por localStorage. A compra acontece na loja escolhida.

A publicação nesta hospedagem é independente da versão hospedada em chatgpt.site.
