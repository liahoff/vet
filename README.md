# Lia Hoff — Site premium V5

## O que mudou nesta versão
- Logo real da marca aplicada no cabeçalho, rodapé e favicon (gerada a partir do arquivo enviado, com fundo transparente).
- Todas as fotos com texto "queimado" na imagem (Ansiedade, Emoções, Saúde etc.) foram recortadas para remover o texto duplicado — a legenda já aparece em HTML por cima da foto. Os arquivos originais ficaram guardados em `assets/_originais-com-texto/` só por segurança.
- Imagens convertidas para WebP (com PNG como alternativa automática) — o site ficou ~90% mais leve e carrega bem mais rápido no celular.
- Pequenas animações originais em CSS/SVG no lugar de GIFs prontos da internet: patinha "andando" no divisor do topo, rabinho balançando nos botões principais, ponto pulsante de "disponível agora/online" e o botão do WhatsApp com anel pulsante. Tudo respeita a preferência do sistema "reduzir movimento" (acessibilidade).
- Seção "Conteúdos" deixou de ficar vazia: agora tem 3 blocos (Artigos, Vídeos, Instagram) com CTA para seguir o perfil.
- Seção de Contato reorganizada em cartões com ícones (WhatsApp, Instagram, E-mail, Local) — mais fácil de escanear.
- SEO: meta tags Open Graph/Twitter Card, link canônico, dados estruturados (Schema.org) para negócio de saúde animal e para o FAQ — ajuda o Google a exibir o site com mais destaque.
- Acessibilidade: link "pular para o conteúdo", estados de foco visíveis, alt descritivo em todas as imagens, aria-* no menu mobile, e respeito a "prefers-reduced-motion".
- Performance: imagens com carregamento tardio (loading="lazy") fora da primeira tela, imagem do topo pré-carregada, dimensões fixas para não "pular" o layout.

## Antes de publicar, substitua:
- [Inserir número] -> WhatsApp
- [Inserir @perfil] / SEU_PERFIL_AQUI -> Instagram (aparece em 3 lugares: seção Conteúdos, Contato e rodapé)
- [Inserir e-mail] -> e-mail (e o href="mailto:" correspondente)
- [Inserir número] do CRMV
- https://www.liahoff.com.br/ -> domínio real do site (aparece no link canonical, Open Graph e dados estruturados)

## Sobre os "GIFs"
Em vez de usar GIFs de cães/gatos baixados da internet, optei por pequenas animações originais em CSS/SVG (patinha, rabinho, pulsação). Isso evita:
1. Risco de direitos autorais ao usar imagens de terceiros num site comercial;
2. Arquivos pesados que deixariam o site lento no celular;
3. Um visual genérico que destoa da identidade visual da marca.

Se você tiver fotos ou vídeos curtos dos próprios atendimentos (com autorização dos tutores), me envie que eu transformo em GIFs/clipes leves, otimizados e no estilo do site.

## Outras notas
- Grande Florianópolis. Atendimento presencial e online.
- Layout responsivo, pronto para GitHub Pages.
