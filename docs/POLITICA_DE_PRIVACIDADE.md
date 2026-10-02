# Política de Privacidade — Rede Pet Care

**Última atualização:** 30/09/2026

> ⚠️ **Nota de elaboração:** este documento é a cópia em Markdown do texto
> publicado na página pública `/privacidade` (`client/src/pages/privacidade.tsx`),
> mantida para referência fora do app. **A página ao vivo é a fonte de
> verdade** — em caso de divergência entre os dois, prevalece o que está
> publicado no sistema. Ajuste `ATUALIZADO_EM` na página e a data acima juntos
> a cada revisão. Texto redigido com apoio de IA a partir da arquitetura real
> de dados da plataforma (ver `DOCUMENTACAO_UNIFICADA.md`), em conformidade
> com os princípios da Lei Geral de Proteção de Dados (LGPD, Lei nº
> 13.709/2018). Recomendável revisão por advogado especializado em proteção
> de dados no Brasil.

---

## 1. Introdução e escopo

Esta Política de Privacidade descreve como a **Rede Pet Care** ("nós", "Plataforma"), operada por **AR PLATAFORMAS DIGITAIS E SERVIÇOS LTDA**, CNPJ **41.568.167/0001-30**, coleta, usa, compartilha, armazena e protege dados pessoais de **tutores**, **Negócios Pet** (administradores, sub-administradores, atendentes, entregadores, médicos veterinários vinculados), **afiliados** e demais usuários da Plataforma, em conformidade com a **Lei Geral de Proteção de Dados (LGPD — Lei nº 13.709/2018)**.

## 2. Quem é o controlador dos dados

**AR PLATAFORMAS DIGITAIS E SERVIÇOS LTDA**, CNPJ **41.568.167/0001-30**, com sede na Rua Goiás, 408-A, Alto Santuário, Araçuaí/MG, CEP 39602-008, é a **controladora** dos dados pessoais tratados através da Plataforma, nos termos do art. 5º, VI, da LGPD. Encarregado(a) pelo tratamento de dados (DPO): contato contato@redepetcare.com.

Cada **Negócio Pet** também decide como usa os dados dos próprios clientes dentro das ferramentas que contrata (por exemplo, o prontuário do seu consultório ou a automação de WhatsApp do seu número), e responde por esse uso perante o tutor.

## 3. Quais dados coletamos

### 3.1. Dados de cadastro

Nome, e-mail, telefone/WhatsApp, CPF/CNPJ, endereço, foto de perfil e credenciais de acesso (senha armazenada de forma criptografada). De **afiliados**, também a chave PIX para o repasse de comissões.

### 3.2. Dados de pets (tutores)

Cadastrados pelo próprio tutor: nome, espécie, raça, idade, peso, porte, sexo, microchip e foto. Quando o Negócio Pet oferece atendimento médico, o veterinário vinculado registra ainda alergias, doenças crônicas e o **prontuário clínico** (histórico de consultas, diagnósticos, receitas, exames e observações). Em reservas de hospedagem, o tutor pode informar restrições alimentares e medicações contínuas específicas daquela estadia.

### 3.3. Dados de uso e transação

Agendamentos, pedidos, cotações, reservas de hospedagem, mensagens de chat com Negócios Pet e com o suporte, avaliações, pontos de fidelidade, solicitações de estorno/ouvidoria/melhorias. Quando o Negócio Pet usa a **Automação de WhatsApp**, as mensagens trocadas entre o tutor e o número do Negócio Pet (texto, nome e telefone do contato) passam pela Plataforma e ficam registradas no painel do Negócio Pet. Chamadas de **teleatendimento** ocorrem por serviço de videochamada de terceiro (Jitsi), sem gravação pela Plataforma.

### 3.4. Dados de dispositivo, acesso e localização aproximada

A cada acesso do tutor, registramos de forma automatizada: tipo de dispositivo (celular, tablet ou computador), sistema operacional, navegador, se o acesso veio do aplicativo instalado ou do navegador, o **endereço IP** e a **localização aproximada** derivada dele (cidade, estado e país). Esses registros alimentam estatísticas agregadas de acesso (seção 4) e segurança; não usamos o IP para descobrir o endereço exato de ninguém. O IP de qualquer visitante também é usado, de forma transitória, para limitar tentativas de login e proteger a Plataforma contra abusos.

### 3.5. Tag de identificação do pet

Quem escaneia o QR Code da tag de um pet vê a foto e o nome do animal e, com o modo "pet perdido" ativado pelo tutor, o contato do tutor. Se **quem encontrou o pet autorizar** no próprio navegador, a localização aproximada do dispositivo dele é enviada ao tutor, para ajudar a recuperar o animal. Nenhuma localização é coletada sem essa autorização.

### 3.6. Cookies e mensuração

Usamos cookies essenciais para manter você conectado (sessão) e para a segurança da Plataforma. Para medir campanhas de anúncios, usamos o pixel e a API de conversões da **Meta** (Facebook e Instagram), que recebem um identificador do evento e e-mail/telefone **criptografados em hash** — nunca em texto legível, e nunca dados de saúde do animal ou conteúdo de conversas. A base legal é o legítimo interesse (art. 7º, IX, da LGPD); você pode se opor a essa finalidade pelos canais da seção 11, sem perder o acesso à Plataforma.

### 3.7. Dados financeiros

A Rede Pet Care **não coleta nem armazena dados de cartão de crédito**. Pagamentos de assinatura, Automação e taxa de intermediação (Negócio Pet) e de assinatura opcional (tutor) são processados por processadores de pagamento terceirizados (Asaas e Stripe), que possuem suas próprias políticas de privacidade e segurança; guardamos apenas os identificadores e o status das cobranças. **Pagamentos entre tutor e Negócio Pet pelo produto/serviço adquirido são feitos diretamente entre as partes, fora da Plataforma, e não passam pelos nossos sistemas** — ver Termos de Uso, seção 8.

## 4. Para que usamos os dados (finalidades)

Utilizamos os dados pessoais coletados para:

1. viabilizar o cadastro, a autenticação e o funcionamento das contas;
2. conectar tutores a Negócios Pet e operacionalizar agendamentos, pedidos, cotações e reservas de hospedagem;
3. processar cobranças de assinatura, Automação e taxa de intermediação (Negócio Pet), de assinatura opcional (tutor) e comissões de afiliados, via processadores terceirizados;
4. enviar notificações operacionais (confirmações, lembretes, status de entrega, cobranças, respostas de ouvidoria/melhorias) por aviso dentro da Plataforma, e-mail, SMS, WhatsApp e Telegram;
5. responder automaticamente, com inteligência artificial, às mensagens que o tutor envia ao WhatsApp de um Negócio Pet que contratou a Automação (seção 5);
6. viabilizar canais de suporte, ouvidoria, melhorias e mediação de disputas de estorno;
7. gerar estatísticas agregadas de uso e acesso à Plataforma (ex.: painel de "Movimentação" e "Acesso ao App" do proprietário de rede);
8. prevenir fraudes, validar cadastros (inclusive a situação do CNPJ na Receita Federal) e proteger a segurança da Plataforma e de seus usuários;
9. medir campanhas de anúncios (seção 3.6);
10. cumprir obrigações legais e regulatórias aplicáveis.

Também usamos dados de uso — de forma agregada e/ou anonimizada sempre que possível — para **analisar e melhorar nossos produtos**: padrões de uso, funcionalidades mais acessadas, gargalos e oportunidades de novas ferramentas.

## 5. Inteligência artificial

5.1. **Automação de WhatsApp.** Quando um Negócio Pet contrata a Automação, as mensagens que o tutor envia ao WhatsApp daquele Negócio Pet, junto com o histórico recente da conversa e as informações cadastradas pelo próprio Negócio Pet (serviços, produtos, horários e documentos da base de conhecimento), são enviadas ao provedor de inteligência artificial **OpenAI** para gerar a resposta. O acesso usa a chave de API do próprio Negócio Pet. Um atendente humano pode assumir a conversa a qualquer momento, o que pausa a automação.

5.2. **Portal do médico veterinário.** O veterinário pode pedir uma análise de apoio de imagens (por exemplo, de exames) por inteligência artificial; a imagem é enviada à OpenAI com a chave da unidade. A análise é apenas apoio — a decisão clínica é sempre do profissional.

5.3. A inteligência artificial **não toma decisões automatizadas que afetem seus direitos** (cobrança, bloqueio de conta, aprovação de cadastro); ela apenas redige respostas e análises de apoio. Você pode pedir atendimento humano ao Negócio Pet e solicitar a revisão de qualquer tratamento automatizado (art. 20 da LGPD) pelos canais da seção 11.

## 6. Com quem compartilhamos

Compartilhamos dados pessoais apenas com quem precisa deles para a Plataforma funcionar, sempre com base legal da LGPD (execução de contrato, obrigação legal, legítimo interesse ou consentimento) e exigindo o mesmo padrão de proteção:

- **Negócios Pet** com quem o tutor se relaciona: os dados necessários ao agendamento, pedido, cotação ou hospedagem;
- **Pagamentos**: Asaas (Negócios Pet) e Stripe (tutor);
- **Infraestrutura e armazenamento**: Hostinger (servidores), Cloudflare (rede, proteção e armazenamento de arquivos e backups);
- **Inteligência artificial**: OpenAI (seção 5);
- **Comunicação**: provedores de WhatsApp contratados pela Plataforma ou pelo Negócio Pet, Integrax/AresFun (SMS), Resend (e-mail), Telegram e Chatwoot (atendimento do suporte — as mensagens enviadas ao suporte são lidas pela nossa equipe nessas ferramentas), Jitsi (videochamada);
- **Consultas públicas**: Receita Federal (via serviço público de CNPJ), ViaCEP e IBGE, para validar CNPJ e endereços;
- **Anúncios**: Meta, com dados criptografados em hash (seção 3.6);
- **Autoridades**, quando exigido por lei ou ordem judicial.

Não vendemos dados pessoais. O titular pode se opor a usos baseados em legítimo interesse ou revogar consentimento a qualquer momento, pelos canais da seção 11.

## 7. Onde os dados ficam e transferência internacional

7.1. O banco de dados e os servidores da Plataforma ficam no **Brasil (São Paulo)**. Arquivos enviados (fotos, receitas, documentos) e cópias de segurança do banco são guardados no serviço de armazenamento da Cloudflare.

7.2. Alguns fornecedores da seção 6 — como Cloudflare, OpenAI, Stripe, Meta, Telegram e Resend — processam dados em servidores fora do Brasil. Essas **transferências internacionais** ocorrem nas hipóteses do art. 33 da LGPD, em especial para a execução do contrato com o titular e com fornecedores que oferecem garantias de proteção compatíveis com a lei brasileira.

## 8. Segurança da informação

Adotamos medidas técnicas e organizacionais para proteger os dados pessoais contra acesso não autorizado, perda, alteração ou vazamento, incluindo criptografia de senhas e de chaves de integração, conexões criptografadas, controle de acesso por papel de usuário (tutor, atendente, administrador etc.) e por unidade, banco de dados sem acesso público e cópias de segurança diárias. Nenhum sistema é totalmente livre de risco; em caso de incidente de segurança que possa gerar risco relevante aos titulares, comunicaremos conforme exigido pela LGPD.

## 9. Por quanto tempo guardamos os dados

Guardamos os dados enquanto a conta estiver ativa e pelo tempo necessário às finalidades desta Política. Alguns dados têm prazo próprio, apagados automaticamente:

- **mensagens de chat** (pedidos, agendamentos, orçamentos, anunciantes e suporte): 40 dias;
- **alertas e notificações já lidos**: 30 dias;
- **registros de acesso do tutor** (dispositivo, IP e localização aproximada): 45 dias — depois disso restam apenas estatísticas mensais agregadas, sem identificação;
- **contas suspensas**: excluídas definitivamente após 90 dias de suspensão.

Dados necessários ao cumprimento de obrigações legais, fiscais ou regulatórias (por exemplo, registros de cobranças e prontuários mantidos pelo Negócio Pet) e ao exercício de direitos em processos são guardados pelos prazos que a lei exigir. As cópias de segurança seguem um ciclo próprio de substituição e não são usadas para outra finalidade.

## 10. Menores de idade

A Plataforma não é destinada a menores de 18 anos desacompanhados. O cadastro como tutor pressupõe capacidade civil plena; eventual tratamento de dados de menores ocorrerá apenas no melhor interesse da criança/adolescente e mediante consentimento específico de um dos pais ou responsável legal, conforme art. 14 da LGPD.

## 11. Canais de contato

Para dúvidas, solicitações relacionadas a dados pessoais ou exercício dos direitos da seção 12, utilize:

- Canal de **suporte** ou **ouvidoria** dentro da própria Plataforma;
- E-mail do encarregado de dados (DPO): contato@redepetcare.com.

## 12. Seus direitos como titular (LGPD)

Você pode, a qualquer momento, solicitar: confirmação e acesso aos seus dados; correção de dados incompletos ou desatualizados; anonimização, bloqueio ou eliminação de dados desnecessários; portabilidade; informação sobre com quem seus dados foram compartilhados; revisão de decisões tomadas com base em tratamento automatizado; oposição a tratamentos baseados em legítimo interesse; e revogação do consentimento. Para exercer esses direitos, use os canais da seção 11. Muitos desses dados também podem ser editados diretamente no seu perfil dentro do app. Se entender que seus direitos não foram atendidos, você também pode recorrer à Autoridade Nacional de Proteção de Dados (ANPD).

## 13. Alterações desta Política

Esta Política pode ser atualizada periodicamente para refletir mudanças na Plataforma ou na legislação aplicável. Alterações relevantes serão comunicadas pelos canais de notificação da Plataforma, com indicação da data da última atualização no topo deste documento.
