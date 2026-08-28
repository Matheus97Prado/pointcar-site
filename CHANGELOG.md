# Changelog — PointCar Site

Este arquivo registra as versões do site. Serve de referência pra saber o que mudou entre uma tag e outra no GitHub (Releases).

## Padrão de versão
- **vX.0** → mudança grande (redesign, nova seção, nova estrutura)
- **vX.Y** → ajuste pequeno (trocar foto, corrigir texto, mudar horário/telefone)

Sempre que publicar uma nova tag no GitHub (Releases → Create a new release), adicione uma entrada aqui embaixo, na mesma mensagem do "Commit changes".

---

## v1.1 — Rastreamento de conversão do Google Ads (tag geral)
- Instalada a tag geral do Google (`gtag.js`, conta `AW-18253915002`) logo após o `<head>`, em todas as páginas
- Ainda pendente: snippet de evento específico da conversão "Clique no WhatsApp" (depende do amigo concluir a criação da ação de conversão no Google Ads)

## v1.0 — Versão inicial publicada
- Site completo: Início, Serviços, Sobre Nós, Localização e Contato
- Logo e foto real da oficina
- Mapa do Google com o endereço real embutido
- Botão flutuante de WhatsApp + botões de contato no cabeçalho e na seção de contato
- Menu mobile (hambúrguer) com rolagem suave até cada seção
- Instagram (@pointcaramericana) linkado na seção de contato
- CSS compilado para produção (sem dependência do CDN de desenvolvimento do Tailwind)
- Cabeçalhos de segurança básicos (`_headers`) configurados para a Netlify
- `robots.txt` e `sitemap.xml` para indexação no Google
