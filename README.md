# LJD Advogados Associados — página de contato

Página estática usada como link da bio do Instagram
([@ljdsociedadedeadvogados](https://instagram.com/ljdsociedadedeadvogados)).
Lista os advogados do escritório com suas áreas de atuação e encaminha o
contato para o WhatsApp de cada profissional.

Publicada via GitHub Pages.

## Estrutura

Arquivo único e autocontido: `index.html`. A logo está embutida em base64 e
não há dependência de CDN, fonte externa ou script de terceiros — a página
abre offline e não quebra se algum serviço externo sair do ar.

## Como alterar

**Advogado, OAB ou área de atuação** — edite o bloco `<article class="adv">`
correspondente em `index.html`.

**Número de WhatsApp** — o link segue o formato
`https://wa.me/55DDDNUMERO?text=MENSAGEM`, com a mensagem pré-preenchida
codificada em URL (`%20` para espaço, `%3A` para dois-pontos).

Depois de editar, faça commit na branch `main`: o GitHub Pages republica
automaticamente em cerca de um minuto.

## Conformidade

O rodapé traz a nota exigida pelo Código de Ética e Disciplina da OAB e pelo
Provimento n° 205/2021 do Conselho Federal: conteúdo informativo, sem oferta
de serviços nem captação de clientela. Ao alterar textos da página, preserve
essa nota e evite promessa de resultado, menção a valores de honorários ou
qualquer expressão de mercantilização da advocacia.
