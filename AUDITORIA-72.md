# Auditoria real dos 72 itens — Daniel Dourado

Data: 15/09/2026. Demonstração publicada e testada no GitHub Pages.

Resultado: **47 aprovados, 23 com atenção, 0 falhas e 2 não aplicáveis**. Pontuação estrita: 67.1% dos 70 itens aplicáveis. Itens com atenção não contam como aprovados.

As pendências incluem integrações reais de CRM e Analytics, validação profissional/legal e configurações da operação definitiva. A demonstração pode ser apresentada; esses serviços não são anunciados como conectados.

| Item | Critério | Status | Evidência ou limite |
|---|---|---|---|
| 1 | CTA principal na primeira dobra | Aprovado | CTA de WhatsApp na primeira dobra nos 21 cenários; responsive-final.json. |
| 2 | CTAs claros e consistentes | Aprovado | Três jornadas com seleção correta de objetivo; inquiry-classification.json. |
| 3 | CTA fixo no mobile, quando adequado | Aprovado | CTA fixo no mobile com safe-area; navegação e teclado testados. |
| 4 | Promessa/expectativa de tempo de resposta, quando aplicável | Não aplicável | Nenhum prazo de resposta foi fornecido ou inventado. |
| 5 | Página de obrigado após conversão | Atenção | Página de agradecimento somente após confirmação explícita; CRM real pendente. |
| 6 | Formulários com validação e estados de erro/sucesso | Atenção | Validação, consentimento, honeypot e recuperação após HTTP 500 testados localmente; gateway real pendente. |
| 7 | Links e URLs amigáveis/personalizados | Aprovado | 35 arquivos HTML; 34 rotas renderizadas e uma entrada com redirecionamento. |
| 8 | Seção de cases/resultados quando houver material autorizado | Não aplicável | Sem casos individuais autorizados. Resultados agregados publicados com fonte e ano. |
| 9 | Avaliações reais e verificáveis | Atenção | Sem estrelas ou citações de avaliações; relatos individuais não certificados. |
| 10 | Mapas, endereço e rotas | Aprovado | Endereço público conferido e link do Maps com HTTP 200; sem iframe automático. |
| 11 | Responsividade completa para celular, tablet e desktop | Aprovado | 21 cenários: sete larguras, de 320 a 1440 px, nos três idiomas; nenhum overflow. |
| 12 | Meta title único por página | Aprovado | 33 títulos únicos verificados em seo-audit.json. |
| 13 | Meta description única por página | Aprovado | 33 descrições únicas verificadas em seo-audit.json. |
| 14 | H1 único e hierarquia correta de H2/H3 | Aprovado | Um H1 por página; hierarquia semântica revisada e AXE sem violações. |
| 15 | Títulos e conteúdo sem duplicações desnecessárias | Aprovado | Conteúdo próprio nos três idiomas e seis regiões; sem textos do cliente anterior. |
| 16 | Alt text contextual nas imagens | Aprovado | Marca e retrato reais identificados; descrição da filmagem traduzida. |
| 17 | Breadcrumbs quando fizerem sentido | Aprovado | 18 páginas regionais com navegação e retorno corretos. |
| 18 | FAQ + dados estruturados de FAQ somente quando aplicáveis | Aprovado | Quatro perguntas frequentes nos três idiomas; sem marcação artificial de FAQ. |
| 19 | URLs amigáveis | Aprovado | Slugs claros e diretórios portáteis. |
| 20 | Canonical tags | Aprovado | Canonical único por rota; reconstrução idempotente dos 35 HTML. |
| 21 | robots.txt | Aprovado | robots.txt bloqueia o rastreamento da demonstração intencionalmente. |
| 22 | sitemap.xml | Aprovado | Sitemap com 27 rotas editoriais; exclui agradecimentos e páginas 404. |
| 23 | Página 404 personalizada | Aprovado | Página 404 personalizada; endereço de retorno compatível com GitHub Pages. |
| 24 | Favicon | Aprovado | Favicon DD em SVG e arquivo ICO na raiz. |
| 25 | Open Graph | Aprovado | Open Graph com título, descrição, URL e imagem; metadados verificados. |
| 26 | Imagem adequada para compartilhamento social | Aprovado | Imagem social própria, coerente com a identidade azul, marfim e champanhe. |
| 27 | Dados estruturados LocalBusiness ou tipo mais específico aplicável | Aprovado | 33 blocos JSON-LD válidos, com contatos e filiação corretos; revisão independente. |
| 28 | Google Search Console configurável após domínio/verificação | Atenção | Search Console depende da verificação do titular; não conectado. |
| 29 | Verificação automática de links quebrados | Atenção | Nenhum link interno quebrado. Proteções de serviços externos documentadas. |
| 30 | Indexabilidade das páginas verificada | Atenção | noindex verificado; indexação definitiva depende da aprovação e do domínio de produção. |
| 31 | Compressão e otimização automática de imagens | Aprovado | Retrato WebP de aproximadamente 69 KB; vídeos de 1,83 MB e 0,55 MB. |
| 32 | Formatos modernos de imagem quando adequados | Aprovado | WebP nos ativos fotográficos; favicon vetorial em SVG. |
| 33 | Lazy loading | Aprovado | Retrato com lazy loading; vídeo com metadados e poster; fonte com swap. |
| 34 | Teste de PageSpeed/Lighthouse | Aprovado | Lighthouse: desempenho 100 no desktop e 97 no mobile; relatórios HTML e JSON incluídos. |
| 35 | Core Web Vitals | Atenção | LCP de laboratório: 0,52 s e 2,48 s; CLS inferior a 0,001. INP de campo indisponível. |
| 36 | Otimização de carregamento de fontes, CSS e JavaScript | Aprovado | CSS e JavaScript leves, fonte local; sem framework em execução. |
| 37 | HTTPS/SSL | Aprovado | HTTPS público confirmado após publicação; github-pages-live.json. |
| 38 | Headers e configurações básicas de segurança | Atenção | GitHub Pages não permite personalizar todos os cabeçalhos de segurança. |
| 39 | Proteção anti-spam/bot nos formulários | Atenção | Honeypot do cliente testado; proteção no servidor depende do gateway real. |
| 40 | Tratamento seguro dos dados enviados | Atenção | Sem segredos no código; retenção e fornecedores dependem da integração real. |
| 41 | Política de Privacidade | Atenção | Política nos três idiomas; revisão jurídica e do titular pendente para operação definitiva. |
| 42 | Cookies/consentimento quando juridicamente necessário | Aprovado | Analytics opcional inativo; recusa e preferências testadas sem coleta externa. |
| 43 | Dados empresariais/profissionais no rodapé | Aprovado | Nome, corretora, endereço e contatos no rodapé; licença ainda não certificada. |
| 44 | Google Analytics ou solução equivalente | Atenção | GA4 desativado por identificador vazio; conta real não configurada. |
| 45 | Eventos de conversão configurados | Atenção | Eventos observáveis localmente; recebimento na conta GA real pendente. |
| 46 | Cliques em WhatsApp monitoráveis | Atenção | Cliques de WhatsApp observáveis localmente; conta GA real pendente. |
| 47 | Envios de formulário monitoráveis | Atenção | Confirmação de envio testada apenas com servidor sintético; endpoint real pendente. |
| 48 | Origem/campanha do lead preservada quando possível | Aprovado | UTM permitidas preservadas; parâmetros pessoais excluídos dos eventos. |
| 49 | Integração com CRM do LeadPilot | Atenção | LeadPilot não conectado; nenhum recebimento real de lead alegado. |
| 50 | Teste real dos eventos antes da publicação | Atenção | Teste local de privacidade de Analytics passou; enhanced measurement da conta real exige revisão. |
| 51 | Logo e identidade visual | Aprovado | Identidade própria; marca real de Daniel preservada em monocromia legível. |
| 52 | Informações reais do negócio | Aprovado | Pesquisa com fontes; resultados anuais de 2025 atribuídos à RealTrends, sem alegar clientes famosos. |
| 53 | Telefone/WhatsApp conferidos | Aprovado | Telefone +1 954 305-3843 e WhatsApp corretos; schema e navegação revisados nos três idiomas. |
| 54 | Endereço e horários conferidos | Atenção | Endereço público conferido; horários, licença e contato preferencial exigem confirmação do titular. |
| 55 | Serviços/especialidades conferidos | Aprovado | Jornadas coerentes com as fontes; sem garantias financeiras ou serviço de gestão inventado. |
| 56 | Fotos reais autorizadas | Aprovado | Retrato real do site fornecido, utilizado na demonstração solicitada; autorização definitiva pelo titular pendente. |
| 57 | Informações da equipe/profissionais conferidas | Aprovado | Identidade e filiação cruzadas com RealTrends e Instagram; homônimos excluídos. |
| 58 | Avaliações reais sem fabricação por IA | Aprovado | Sem avaliações, estrelas ou depoimentos fabricados. |
| 59 | Conteúdo adaptado ao segmento e localização | Aprovado | Conteúdo adequado à Flórida Central; Miami não anunciado sem confirmação. |
| 60 | Revisão de informações sensíveis ou regulamentadas | Atenção | Sem garantias de retorno; consulta de licença DBPR e revisão profissional final pendentes. |
| 61 | Teste desktop | Aprovado | Verificado no Microsoft Edge: desktop a 1440 px e cenários de acessibilidade. |
| 62 | Teste mobile | Aprovado | Mobile e tablet emulados nos 21 cenários; não foram usados aparelhos físicos. |
| 63 | Teste de todos os formulários | Atenção | Formulários nos três idiomas testados com endpoint local; entrega externa pendente. |
| 64 | Teste de todos os CTAs | Aprovado | CTAs, idiomas, menu, Escape, FAQ, regiões e controles de vídeo testados. |
| 65 | Teste dos links externos | Atenção | Links externos pesquisados e testados. CARAS retorna 403 ao cliente HTTP; conteúdo verificado na pesquisa. |
| 66 | Teste de WhatsApp, telefone e e-mail | Atenção | WhatsApp retorna HTTP 200; número e e-mail coerentes. Não foram enviados contatos de QA a terceiros. |
| 67 | Auditoria SEO | Aprovado | 33 páginas com SEO individual; Lighthouse SEO 69 devido ao noindex intencional da demonstração. |
| 68 | Auditoria de acessibilidade básica | Aprovado | AXE sem violações em nove cenários; WCAG 2.2 mobile sem violações após ajuste dos alvos do rodapé. |
| 69 | Auditoria de performance | Aprovado | Lighthouse 100/97; vídeos e imagens otimizados. Não há medição de INP de campo. |
| 70 | Auditoria de segurança | Atenção | Revisão de código sem falhas críticas; auditoria da infraestrutura e do endpoint real limitada. |
| 71 | Verificação de domínio/SSL | Aprovado | Demonstração pública, HTTPS e rotas confirmados; domínio oficial permanece inalterado. |
| 72 | Site Quality Score final | Aprovado | 72 itens com status, evidências e limitações; demonstração diferenciada da operação definitiva. |

Correções verificadas: telefone no JSON-LD, classificação de jornadas, overflow em 390 px, alvos do rodapé para WCAG 2.2, metadados e imprensa idempotentes, tradução espanhola, favicon na raiz e gerador autônomo.

Os erros HTTP 500 e 404 nos testes locais são cenários intencionais. O relatório distingue esses retornos de falhas de JavaScript ou de arquivos do site. Não foram enviadas mensagens ou leads de QA a terceiros. Viewports mobile foram emulados; Lighthouse é medição de laboratório.
