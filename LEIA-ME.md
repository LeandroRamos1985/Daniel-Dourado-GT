# Daniel Dourado — site completo

Revisão visual de 16/09/2026: capa editorial clara com título centralizado, vídeo horizontal, destinos antes do perfil, serviços e imprensa em linhas, processo em grade e contato empilhado. A estrutura foi comparada com projetos anteriores e com Downtown Boston Realty; consulte MATRIZ-DIFERENCIACAO-VISUAL.md.

Website estático nos idiomas português brasileiro, inglês e espanhol. A raiz contém index.html, pastas pt-br/en/es, assets, favicon, robots, sitemap e 404. Não requer npm ou servidor de aplicação. Preserve a estrutura de pastas; não envie apenas arquivos HTML isolados.

## Demonstração e operação

A demonstração utiliza WhatsApp +1 (954) 305-3843, telefone, e-mail daniel@ddourado.com e endereço público do profissional. O formulário informa que o atendimento online ainda não está conectado e oferece WhatsApp. Não há recebimento confirmado em CRM/LeadPilot nem Analytics ativo. Os testes de envio usam exclusivamente um servidor sintético local.

Antes de operação definitiva, confirmar licença, contato preferencial, serviços e autorização de marca/retrato; revisar textos legais, retenção e fornecedores. A filmagem é ilustração arquitetônica, sem afirmar localização em Orlando ou imóvel anunciado. Não há catálogo MLS/IDX conectado. As páginas da demonstração estão intencionalmente com noindex e robots bloqueando rastreamento.

## GitHub Pages

O repositório utiliza Daniel-Dourado-Site.zip e .github/workflows/pages.yml. O workflow extrai o ZIP preservando diretórios e publica automaticamente a raiz do website. Para atualizar, substituir o pacote com o mesmo nome, mantendo todos os arquivos e pastas. Usar o workflow fornecido e Settings > Pages > GitHub Actions. O domínio oficial existente não é alterado.

O ZIP completo do usuário pode conter _entrega com documentação, auditoria, licenças e evidências; o workflow exclui essa pasta do website público. Consulte PUBLICACAO.md para o link efetivamente verificado depois da publicação; não considerar URLs planejadas como já publicadas.

## Edição e reconstrução autônoma

Para edição direta, alterar os HTML/CSS/JS prontos e testar os três idiomas. Para reconstruir HTML e metadados com Python padrão, editar _entrega/tools/content.json e executar `python _entrega/tools/regenerate.py` na cópia descompactada. A ferramenta localiza a raiz pela própria localização, não depende dos projetos Allan/Emmanuel, não baixa mídia e preserva assets. Foi testada duas vezes em pasta isolada. Alterações manuais nos HTML serão sobrescritas; preservar a versão anterior antes de regenerar.

prepare.py e demais scripts históricos do workspace não fazem parte dessa reconstrução. Configuração de integração em assets/config.js: leadEndpoint e analyticsId vazios significam serviços desativados. Endpoint real precisa HTTPS, proteção server-side e resposta explícita de sucesso. Antes de GA4, desativar/revisar enhanced measurement e validar ausência de dados pessoais na conta real. Não inserir segredos no JavaScript.

Referência de mídia e autoria: MEDIA-VERIFICADA.md; investigação profissional: PESQUISA-E-BRIEFING.md; testes e limitações: AUDITORIA-72.md e evidence. Viewports mobile são emulados em Microsoft Edge, não aparelhos físicos. Lighthouse é medição de laboratório.
