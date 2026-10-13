# Cedo, da Gestão Sem Caos — site

Site do Cedo, produto da Gestão Sem Caos: a leitura diária da clínica.
Todas as telas e números do site são fictícios (Clínica Orvalho; nomes de pessoas e pacientes inventados).

- `index.html`: o site inteiro (um arquivo só). `diagnostico.html`: o diagnóstico de 6 perguntas. `vagas.json`: contador de vagas de fundadora (editar a cada contrato assinado).
- Nome do produto: constante `PRODUTO` no script de cada página + `<title>`/og no `<head>`; o HTML marca cada ocorrência com `data-pn`.
- Depoimentos: a seção `#depoimentos` tem a chave `data-depoimentos="exemplo"`; só pode ir ao ar como `real` (com nomes trocados) ou `oculto`.
- Publicação: GitHub Pages (ramo main, raiz) com o domínio `appcedo.gestaosemcaos.com.br` (arquivo CNAME). O `Dockerfile` (nginx) serve para publicar em outro servidor, se precisar.
