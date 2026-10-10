title: Política de Privacidade
description: Como o {{APP_NAME}} trata as suas fotos e os seus dados: o que é enviado ao serviço de IA, bases legais, o que é armazenado e por quanto tempo, e os seus direitos em todo o mundo.

# Política de Privacidade

> Data de vigência: {{EFFECTIVE_DATE}}

O {{APP_NAME}} (o "App") transforma as suas fotos em retratos de monstros de Halloween usando um serviço de imagens com IA de terceiros. Esta política explica quais informações o App trata, por quê e com qual base legal, quem as recebe, por quanto tempo elas são mantidas e quais direitos e escolhas você tem, onde quer que more. O App é operado por {{DEVELOPER_NAME}} ("nós"), o controlador dos seus dados pessoais (a parte que decide como e por que eles são tratados). Nossos dados de contato estão na seção 14.

## 1. Resumo

- As fotos que você escolhe são enviadas a um serviço de IA externo (OpenAI) somente para criar o retrato que você pediu. Pedimos a sua permissão clara antes da primeira vez que isso acontece, e você pode revogá-la a qualquer momento.
- Não guardamos as fotos que você envia. Nós as repassamos, na memória, ao serviço de IA e devolvemos o resultado ao seu celular. O App guarda uma cópia reduzida do original somente no seu celular, para uma comparação antes/depois (seção 2c).
- Seus retratos prontos ficam salvos no seu celular. Para que um retrato não se perca se a sua conexão cair ou o App for fechado durante a criação, mantemos uma cópia criptografada de cada retrato recém-gerado no nosso servidor por no máximo 24 horas. Ela é usada somente para entregar o retrato ao seu celular e é excluída assim que o seu celular confirma que o salvou, ou após 24 horas, no máximo.
- Não usamos as suas fotos nem o seu rosto para treinar modelos de IA, para publicidade nem para análise de uso. Não identificamos nem reconhecemos pessoas pelo rosto.
- Não há conta, nem SDK de publicidade ou de análise de uso no App, nem rastreamento em apps e sites de outras empresas. Nosso servidor compartilha o seu identificador anônimo e os seus registros de compra (nunca fotos) com um provedor de análise de assinaturas (RevenueCat, seção 4).
- Você pode excluir os seus dados dentro do App a qualquer momento (Perfil > Excluir todos os meus dados) e revogar o seu consentimento de IA (Perfil > Revogar consentimento de IA).

## 2. Informações que tratamos

**a. Fotos que você escolhe ou tira.** Quando você escolhe uma foto da sua biblioteca ou tira uma com a câmera e toca para criar um retrato, a foto (um JPEG redimensionado) e o visual selecionado são enviados ao nosso backend e, em seguida, ao serviço de IA. Se você escolher um visual de grupo ou de casal com selfies separadas, cada selfie é enviada. As fotos podem mostrar o rosto de você e de outras pessoas. Acessamos somente as fotos que você escolhe explicitamente; o App não varre a sua biblioteca de fotos.

**b. Verificação de rostos no seu aparelho.** Antes de uma foto ser enviada, o App usa o framework Vision da Apple, no seu aparelho, para verificar se há um número adequado de rostos (por exemplo, exatamente dois para um visual de casal). Essa verificação roda inteiramente no seu celular. Ela encontra onde estão os rostos e quantos são. Ela não cria um modelo facial nem qualquer identificador biométrico, não identifica nem reconhece quem é cada pessoa, e os resultados não são enviados a lugar nenhum, a não ser como a contagem de rostos usada para escrever as instruções ao serviço de IA. Em uma criação feita a partir de uma única foto, a posição do rosto (um retângulo simples, normalizado em relação à foto) também fica guardada nos dados da criação, somente no seu celular, para alinhar a comparação antes/depois (seção 2c).

**c. Retratos gerados.** O resultado do serviço de IA volta para o App e é salvo no seu celular. Uma cópia temporária de cada retrato gerado fica criptografada no nosso armazenamento em nuvem por no máximo 24 horas, apenas para entregá-lo ao seu celular se a conexão falhar; as suas selfies e as demais fotos enviadas nunca são armazenadas nos nossos servidores. Somente no seu celular, uma criação feita a partir de uma única foto (individual ou uma foto de grupo) guarda também, ao lado do retrato, uma cópia reduzida da foto original (lado maior de 1280 pixels), para mostrar uma comparação antes/depois. Essa cópia nunca é enviada, fica fora dos backups do aparelho e é excluída junto com a criação ou por Excluir todos os meus dados. Criações feitas com selfies separadas e retratos recuperados da nossa cópia de entrega de 24 horas não têm cópia da foto original.

**d. Identificador anônimo e créditos.** O App cria um identificador anônimo do Firebase para a sua instalação. Nós o usamos para manter o seu saldo de créditos e registrar compras e movimentações de créditos (ID da transação, produto, data). Não pedimos que você crie uma conta e não coletamos no App o seu nome, e-mail nem número de telefone. Ao chamar o serviço de IA, incluímos um identificador pseudônimo derivado do seu ID anônimo por meio de um hash unidirecional com chave; ele não é o seu identificador real e o serviço de IA não consegue associá-lo a você. Ele ajuda o serviço de IA a detectar abusos.

**e. Compras.** As compras e assinaturas são processadas pela Apple. Nunca recebemos os dados do seu cartão de pagamento nem da sua Conta Apple. Recebemos a confirmação de uma transação (ID da transação, produto, datas, status de renovação ou reembolso) para poder conceder ou remover créditos. Se você tocar em Restaurar compras, o App envia ao nosso servidor os registros de compra assinados pela Apple, para que possamos verificá-los e vincular de novo as suas compras e os créditos restantes ao App neste aparelho. Esses registros contêm o produto, as datas e o identificador de compra aleatório por instalação que geramos; eles não contêm o seu nome, e-mail nem dados de pagamento. Se os registros corresponderem a outra instalação do App, os créditos restantes dessa instalação são movidos (não copiados) para esta. A restauração não exige login e não cria nenhum novo tipo de dado pessoal. Também repassamos esses registros de compra, junto com o seu identificador anônimo, do nosso servidor para a RevenueCat (seção 4), para que possamos ver estatísticas de assinaturas e receita; o App em si não contém software da RevenueCat e não envia nada à RevenueCat.

**f. Integridade do aparelho.** Para proteger o serviço contra abusos, usamos o App Attest da Apple (por meio do Firebase App Check) para confirmar que as solicitações vêm de uma cópia genuína do App e o DeviceCheck da Apple para lembrar, com uma única configuração liga/desliga armazenada pela Apple, que um aparelho já usou o seu primeiro retrato grátis. O DeviceCheck não nos diz quem você é.

**g. Registros técnicos.** Nossos serviços em nuvem e o serviço de IA podem registrar informações técnicas, como endereço IP, horário da solicitação e códigos de erro, por segurança e para operar o serviço. O nosso próprio código não grava fotos, dados faciais nem dados pessoais nos registros. Não usamos esses registros para criar perfis sobre você.

**h. Mensagens ao suporte.** Se você nos escrever por e-mail, recebemos o seu endereço de e-mail e o que você escrever, e os usamos somente para responder.

**i. Configurações no aparelho.** O App guarda preferências simples no seu celular (por exemplo, que você concluiu a introdução e que concordou com o aviso de IA).

Não coletamos a sua localização precisa, os seus contatos, dados de saúde nem o seu histórico de navegação.

## 3. Por que usamos essas informações e bases legais

| Finalidade | Informações | Base legal (GDPR e UK GDPR; bases equivalentes em outras leis) |
| --- | --- | --- |
| Criar o retrato que você pede: enviar as suas fotos e o visual escolhido ao serviço de IA | Fotos, visual selecionado, contagem de rostos, identificador pseudônimo | O seu consentimento (art. 6(1)(a)), dado no App antes da primeira criação. Você pode revogá-lo a qualquer momento; a revogação não afeta o tratamento anterior. |
| Créditos, compras, assinaturas, Restaurar compras, devolução de créditos | Identificador anônimo, saldo de créditos, registros de compra | Execução do nosso contrato com você (art. 6(1)(b)); guarda de registros que a lei nos obriga a manter (art. 6(1)(c)) |
| Entender assinaturas e receita (análise de assinaturas) | Identificador anônimo, registros de compra e renovação assinados pela Apple | Nossos legítimos interesses em operar e melhorar um serviço pago (art. 6(1)(f)). Você pode se opor (seção 7). |
| Prevenir fraudes e abusos, fazer valer o limite de um retrato grátis por aparelho, manter o serviço seguro (App Check, DeviceCheck, limites de uso, filtros de segurança, registros) | Identificador anônimo, sinais de integridade do aparelho, registros técnicos | Nossos legítimos interesses em proteger o serviço, os outros usuários e a nós mesmos (art. 6(1)(f)). Você pode se opor (seção 7). |
| Responder a solicitações de suporte | E-mail, mensagem, ID de suporte | Nosso contrato com você e o nosso legítimo interesse em ajudar você |
| Cumprir a lei e tratar de reivindicações legais | Registros descritos na seção 6 | Obrigação legal e legítimos interesses |

**Rostos e fotos.** Os rostos e as fotos nas suas imagens são usados somente para gerar o retrato que você pediu. Eles não são usados para treinar nem aprimorar nenhum modelo de IA, para publicidade ou marketing, para análise de uso ou criação de perfis, nem vendidos ou compartilhados para essas finalidades. Não montamos um banco de dados de rostos e não analisamos fotos para inferir características sensíveis de ninguém.

Se você não concordar em enviar fotos ao serviço de IA, ainda poderá abrir o App, mas ele não poderá criar retratos.

## 4. Quem recebe as informações

Compartilhamos informações somente com os prestadores de serviço necessários para operar o App:

- **OpenAI** (geração de imagens). As suas fotos e o visual selecionado são enviados à API da OpenAI para produzir o seu retrato. A OpenAI atua como nossa operadora. De acordo com a política de dados de API publicada pela OpenAI, os dados enviados à API não são usados para treinar nem aprimorar os modelos da OpenAI, a menos que o cliente opte por isso (nós não optamos), e o conteúdo da API pode ficar em registros de monitoramento de abuso por até 30 dias, ou por mais tempo se a lei exigir ou se for necessário para proteger os serviços. Política da OpenAI: https://developers.openai.com/api/docs/guides/your-data . A OpenAI também pode examinar as imagens enviadas em busca de material de abuso sexual infantil e guardar uma imagem sinalizada para revisão, conforme descrito nessa política.
- **Google (Firebase e Google Cloud)** (hospedagem do backend, identificador anônimo, registros de créditos e de compras, verificações de integridade do app, armazenamento temporário criptografado dos retratos gerados). O Google atua como nosso operador, conforme os seus termos de tratamento de dados. Nosso backend roda nos Estados Unidos (Iowa).
- **RevenueCat, Inc.** (Estados Unidos) (análise de assinaturas e compras). Nosso servidor envia à RevenueCat o seu identificador anônimo e os registros de compra assinados pela Apple das suas compras (produto, datas, ambiente, o identificador aleatório da compra e eventos de renovação, reembolso e cancelamento). A RevenueCat atua como nosso operador. Nenhuma foto, rosto, nome, e-mail ou identificador de aparelho é enviado, e o App não contém software da RevenueCat. Quando você usa Excluir todos os meus dados, também pedimos à RevenueCat que exclua o registro do seu identificador anônimo.
- **Apple** (compras na App Store, App Attest, DeviceCheck e compartilhamento opcional dos seus retratos pela folha de compartilhamento do iOS, que é você quem inicia). A Apple atua como controladora independente para os próprios serviços.
- **Autoridades ou sucessores**, quando exigido por lei ou para proteger direitos e segurança, ou como parte de uma transferência de negócio, com aviso quando exigido.

Não vendemos as suas informações pessoais e não as compartilhamos para publicidade comportamental entre contextos.

Quando você compartilha um retrato com outro app (por exemplo, pela folha de compartilhamento), a política de privacidade desse app se aplica ao que você compartilha.

## 5. Transferências internacionais

Estamos sediados na Turquia, e os nossos prestadores tratam dados nos Estados Unidos e possivelmente em outros países onde operam. Se você usa o App no Espaço Econômico Europeu, no Reino Unido, na Suíça, na Turquia, no Brasil, na Coreia do Sul, no Japão ou em outro lugar, as suas informações são, portanto, transferidas para outros países, inclusive países cuja lei de proteção de dados pode ser diferente da sua.

Adotamos as salvaguardas que a sua lei exige para essas transferências, quando aplicáveis: uma decisão de adequação (por exemplo, o EU-US Data Privacy Framework, quando o destinatário participa), cláusulas contratuais padrão (da UE e o adendo do Reino Unido) nos termos de tratamento de dados dos nossos prestadores, outros mecanismos lícitos reconhecidos pela legislação local (veja a seção 8) e o seu consentimento, quando a lei o permitir. Também limitamos o que é enviado ao necessário, usamos conexões criptografadas e não enviamos ao serviço de IA o seu nome, e-mail nem identificador real de conta. Você pode nos pedir informações sobre as salvaguardas (seção 14).

## 6. Por quanto tempo guardamos as informações

| Informações | Retenção |
| --- | --- |
| Fotos enviadas para uma criação | Não são armazenadas por nós. Ficam apenas na memória enquanto a solicitação é processada. O serviço de IA pode guardá-las por até 30 dias em registros de monitoramento de abuso (veja a seção 4). |
| Retratos gerados e, nas criações feitas a partir de uma única foto, a cópia da foto original | No seu celular, até você excluí-los ou usar Excluir todos os meus dados. A cópia reduzida da foto original e o retângulo do rosto nunca saem do seu celular e ficam fora dos backups do aparelho. Uma cópia de entrega temporária do retrato fica criptografada no nosso servidor por no máximo 24 horas (excluída quando o seu celular confirma o salvamento e por Excluir todos os meus dados). |
| Identificador anônimo, saldo de créditos, movimentações de créditos, registros de compra (inclusive os usados por Restaurar compras) | Até você excluir os seus dados no App. Registros com saldo zero, sem assinatura ativa e sem uso do App por 24 meses são excluídos automaticamente (verificação diária), junto com o registro de login anônimo. |
| Registro na RevenueCat (identificador anônimo, registros de compra e renovação) | Até você excluir os seus dados no App ou o registro ser excluído automaticamente após 24 meses de inatividade (veja acima); nesse caso, pedimos à RevenueCat que o exclua. Os termos próprios da RevenueCat regem eventuais cópias de backup. |
| Registros de transações de compra depois que você exclui os seus dados no App ou após a exclusão automática | O ID da transação, o produto e as datas são mantidos sem nenhum vínculo com o seu identificador anônimo, para processar reembolsos e evitar conceder créditos duas vezes, e quando a lei exigir (por exemplo, para fins contábeis). Se você tinha uma assinatura ativa, o registro de assinatura anonimizado também guarda os créditos semanais restantes do período atual, igualmente sem nenhum vínculo com o seu identificador anônimo, para que a assinatura possa ser restaurada em uma nova instalação (Restaurar compras); eles são usados somente para isso e ficam guardados enquanto esses registros de transações forem mantidos. |
| Marcador de exclusão | Depois que você exclui os seus dados, mantemos o seu antigo identificador anônimo aleatório e o horário da exclusão, para que o registro excluído não possa ser recriado. Ele não contém nenhuma outra informação. |
| Registros técnicos | Um período limitado, necessário para segurança e operação (por exemplo, o Firebase Authentication registra endereços IP por algumas semanas). |
| E-mails ao suporte | Pelo tempo necessário para ajudar você; depois, são excluídos. |

## 7. Seus direitos e escolhas

Dependendo de onde você mora, você tem alguns destes direitos ou todos eles: saber se tratamos os seus dados e obter uma cópia (acesso); corrigi-los; excluí-los; restringir o tratamento; receber os seus dados em formato portável; opor-se ao tratamento baseado em legítimos interesses; revogar o consentimento a qualquer momento; não ficar sujeito a decisões baseadas unicamente em tratamento automatizado com efeitos jurídicos ou igualmente significativos (não tomamos nenhuma); e apresentar reclamação a uma autoridade de proteção de dados.

Como exercê-los:

- **Excluir todos os meus dados (no App).** Perfil > Excluir todos os meus dados remove os retratos, as fotos originais, as miniaturas das selfies e o consentimento de IA armazenados no seu celular e nos pede para excluir o registro do lado do servidor vinculado ao seu identificador anônimo (saldo de créditos e registros de compra) e pede à RevenueCat que exclua o registro desse identificador. Os pacotes de créditos não usados são perdidos quando você faz isso. Os créditos semanais restantes de uma assinatura ativa não são perdidos: ficam guardados junto com o registro de assinatura anonimizado (seção 6) para que você possa restaurar a assinatura em uma nova instalação. Excluir apenas o App não exclui o registro do lado do servidor.
- **Revogar consentimento de IA.** Perfil > Revogar consentimento de IA. As fotos não serão enviadas de novo até você concordar outra vez.
- **Acesso, portabilidade, correção, restrição, oposição.** Envie um e-mail para {{SUPPORT_EMAIL}} e informe o ID de suporte exibido na aba Perfil, para que possamos encontrar o seu registro. Não conseguimos localizar os seus dados sem ele, porque o App é anônimo. Enviaremos a você o registro vinculado ao seu ID de suporte (saldo de créditos, movimentações de créditos e registros de compra) em um formato comum, legível por máquina. Seus retratos já estão no seu celular.
- **Acesso às fotos.** Você pode alterar as permissões de câmera e de fotos nos Ajustes do iOS. O App usa o seletor de fotos do sistema, que lhe dá acesso somente às fotos que você seleciona, e só salva na sua biblioteca quando você toca em Salvar.
- **As assinaturas** são gerenciadas ou canceladas nos ajustes da sua Conta Apple (veja os nossos Termos de Uso).

Respondemos em até um mês (GDPR e UK GDPR; podemos prorrogar por até mais dois meses em solicitações complexas e avisaremos você) ou dentro do prazo fixado pela lei que se aplica a você. Podemos pedir que você confirme que a solicitação vem do titular do ID de suporte. Você também pode apresentar reclamação à autoridade local de proteção de dados (no EEE, a autoridade do país onde você mora ou trabalha; no Reino Unido, o Information Commissioner's Office; na Turquia, a Autoridade de Proteção de Dados Pessoais; no Brasil, a ANPD; na Coreia do Sul, a PIPC; no Japão, a PPC). Agradeceríamos a oportunidade de resolver primeiro a sua questão.

## 8. Informações para regiões específicas

### 8.1 Espaço Econômico Europeu, Reino Unido e Suíça

{{DEVELOPER_NAME}} é o controlador. As bases legais estão na seção 3, as transferências na seção 5, a retenção na seção 6 e os seus direitos na seção 7, inclusive os direitos de oposição e de revogação do consentimento. Não designamos um encarregado de proteção de dados (DPO); as dúvidas sobre privacidade vão para o endereço da seção 14. Quando a lei do seu país fixar, para consentir com o tratamento de dados pessoais, uma idade maior que 13 anos (por exemplo, de 14 a 16 anos em vários países europeus), veja a seção 9.

### 8.2 Turquia (Lei nº 6.698, KVKK)

{{DEVELOPER_NAME}} é o controlador de dados. Tratamos dados pessoais para as finalidades da seção 3, com fundamento no seu consentimento explícito (envio de fotos ao serviço de IA), na celebração e execução de um contrato, nos nossos legítimos interesses (prevenção de fraudes e segurança) e em obrigações legais. Nos termos do art. 11 da Lei nº 6.698 de Proteção de Dados Pessoais (Kişisel Verilerin Korunması Kanunu, KVKK), você pode perguntar se os seus dados são tratados, solicitar informações, saber a finalidade e se são usados de forma adequada, conhecer os terceiros para os quais são transferidos na Turquia ou no exterior, pedir correção ou exclusão, pedir que essas ações sejam comunicadas a terceiros, opor-se a resultados desfavoráveis a você e pleitear indenização por danos. Dirija-se a nós no endereço da seção 14, com o seu ID de suporte; respondemos em até trinta dias, no máximo. Se não ficar satisfeito, você pode apresentar reclamação ao Conselho de Proteção de Dados Pessoais (Kişisel Verileri Koruma Kurulu, KVKK). Os dados são transferidos para o exterior (seção 5) nas condições do art. 9 da Lei nº 6.698.

### 8.3 Brasil (LGPD)

{{DEVELOPER_NAME}} é o controlador, e o contato para os titulares dos dados é o endereço da seção 14. Nossas bases legais, conforme o art. 7º da Lei nº 13.709/2018 (Lei Geral de Proteção de Dados Pessoais, LGPD), são o consentimento, a execução de contrato, o exercício regular de direitos e o legítimo interesse. Você tem os direitos do art. 18 (confirmação da existência de tratamento, acesso, correção, anonimização, bloqueio ou eliminação, portabilidade, informação sobre o compartilhamento, informação sobre as consequências de negar o consentimento e revogação do consentimento) e pode peticionar à ANPD (Autoridade Nacional de Proteção de Dados). As transferências internacionais são feitas conforme descrito na seção 5 e no art. 33 da LGPD.

### 8.4 Coreia do Sul (PIPA)

Tratamos as informações pessoais da seção 2 somente para as finalidades da seção 3 e as mantemos pelos prazos da seção 6. Não fornecemos informações pessoais a terceiros, exceto conforme descrito na seção 4. Delegamos à OpenAI, ao Google e à RevenueCat o tratamento descrito na seção 4 e os supervisionamos por meio de termos contratuais. As suas fotos e as informações relacionadas são transferidas para o exterior da seguinte forma, com o seu consentimento dado no App:

| Destinatário e país | Itens | Finalidade | Quando e como | Retenção |
| --- | --- | --- | --- | --- |
| OpenAI, Estados Unidos | Fotos, visual selecionado, identificador pseudônimo | Gerar o retrato | A cada vez que você cria um retrato, por rede criptografada | Até 30 dias em registros de monitoramento de abuso |
| Google (Firebase e Google Cloud), Estados Unidos | Identificador anônimo, registros de créditos e de compras, cópia temporária do retrato gerado | Hospedagem, livro de créditos, entrega do retrato | A cada vez que você usa o App, por rede criptografada | Conforme a seção 6 |
| RevenueCat, Estados Unidos | Identificador anônimo, registros de compra e assinatura | Análise de assinaturas | A cada compra, renovação ou reembolso processado, por rede criptografada | Conforme a seção 6 |

Você pode exercer os seus direitos de acesso, correção, exclusão, suspensão do tratamento e revogação do consentimento nos termos da Lei de Proteção de Informações Pessoais (PIPA) entrando em contato conosco no endereço da seção 14; você pode recusar o consentimento, mas então o App não poderá criar retratos. O responsável pela privacidade é {{DEVELOPER_NAME}} ({{SUPPORT_EMAIL}}). Você também pode pedir ajuda à Comissão de Proteção de Informações Pessoais (PIPC) ou ao Centro de Privacidade da KISA (118).

### 8.5 Japão (APPI)

{{DEVELOPER_NAME}} é o operador de negócios que trata informações pessoais. Usamos informações pessoais somente para as finalidades da seção 3. Quando você consente no App, as suas fotos e as informações relacionadas são fornecidas a empresas em um país estrangeiro: a OpenAI e o Google, nos Estados Unidos e em outros países onde operam. O seu identificador anônimo e os seus registros de compra também são fornecidos à RevenueCat, nos Estados Unidos. Os Estados Unidos não têm uma lei única e abrangente de proteção de informações pessoais como a Lei de Proteção de Informações Pessoais (APPI); os nossos prestadores tratam os dados conforme os próprios compromissos e termos contratuais descritos na seção 4 (sem treinamento com dados de API, retenção limitada, criptografia). Você pode solicitar a divulgação, a correção, a exclusão e a cessação do uso dos dados pessoais retidos, bem como um registro dos fornecimentos a terceiros, entrando em contato conosco no endereço da seção 14.

### 8.6 Estados Unidos

Dependendo de onde você mora (por exemplo, Califórnia, Colorado, Connecticut, Virgínia, Texas, Oregon e outros estados com leis de privacidade do consumidor), você pode ter o direito de saber quais informações pessoais mantemos, acessá-las, corrigi-las, excluí-las, receber uma cópia portátil e recorrer da nossa decisão. Não vendemos informações pessoais, não as compartilhamos para publicidade direcionada e não as usamos para criação de perfis com efeitos jurídicos ou igualmente significativos. Não tratamos fotos para identificar uma pessoa de forma única. Para exercer esses direitos, use Excluir todos os meus dados no App ou envie um e-mail para {{SUPPORT_EMAIL}}; responderemos em até 45 dias (podemos prorrogar uma vez, quando a lei permitir) e não discriminaremos você por exercer os seus direitos. Você pode usar um representante autorizado; podemos pedir o ID de suporte para verificar a solicitação. Se negarmos uma solicitação, você pode recorrer respondendo ao nosso e-mail, e pode entrar em contato com a procuradoria-geral do seu estado.

As solicitações do "Shine the Light" da Califórnia e de Nevada podem ser enviadas ao mesmo endereço. Não respondemos a sinais "Do Not Track" porque não rastreamos você.

### 8.7 Outros países

Se a lei do seu país lhe der direitos adicionais sobre os seus dados pessoais, nós os respeitaremos na medida em que se apliquem a nós. Escreva para o endereço da seção 14.

## 9. Crianças

O App não é direcionado a crianças, e não coletamos conscientemente informações pessoais de crianças menores de 13 anos. Não use o App nem envie fotos de crianças menores de 13 anos. Quando a lei do seu país fixar uma idade mínima maior para consentir com o tratamento de dados pessoais (por exemplo, 14 anos na Coreia do Sul e de 14 a 16 anos em vários países europeus), você deve ter pelo menos essa idade, ou ter o consentimento de um dos pais ou de um responsável, para usar o App. Se você acredita que informações de uma criança foram enviadas a nós, entre em contato com {{SUPPORT_EMAIL}} e as excluiremos.

## 10. Tratamento automatizado e biometria

Os retratos são criados por um modelo de IA a partir da sua foto e de um visual escolhido por nós. Não tomamos nenhuma decisão sobre você com efeitos jurídicos ou igualmente significativos e não criamos perfis seus. As únicas verificações automatizadas são controles contra fraude e abuso (por exemplo, limites por aparelho e filtros de segurança de conteúdo); se uma criação for recusada, você pode tentar de novo com outra foto ou entrar em contato conosco.

Não usamos identificação biométrica. A detecção de rostos roda somente no seu aparelho, para verificar se há um rosto e contar os rostos. Não criamos nem armazenamos modelos faciais, não comparamos rostos e não usamos rostos para identificar ninguém. O retângulo do rosto (somente posição e tamanho) que fica no seu celular para a comparação antes/depois não é um modelo facial, não é usado para mais nada e nunca é enviado a nós.

## 11. Fotos de outras pessoas

Adicione apenas fotos de pessoas que concordaram com isso. As fotos de outras pessoas são enviadas ao serviço de IA da mesma forma que as suas. Você é responsável por ter a permissão delas.

## 12. Segurança

Os dados circulam entre o App, o nosso backend e o serviço de IA por conexões criptografadas (HTTPS/TLS). Nossos provedores de nuvem criptografam os dados armazenados. A chave da API da OpenAI fica no nosso servidor e nunca está dentro do App. Nenhum sistema é perfeitamente seguro, portanto não podemos garantir segurança absoluta. Se uma violação afetar os seus dados pessoais, notificaremos você e as autoridades conforme a lei exigir.

## 13. Alterações e este site

Se alterarmos esta política de forma relevante, atualizaremos a data acima e, se a alteração afetar o que é enviado ao serviço de IA, pediremos a sua permissão de novo no App. Se esta política for exibida no seu idioma, a tradução é fornecida para a sua conveniência; a versão em inglês prevalece se as versões divergirem.

Este site é estático. Ele não define cookies e não usa análise de uso nem recursos externos. Ele é hospedado no GitHub Pages, e o GitHub pode tratar dados técnicos, como o seu endereço IP, quando o seu navegador carrega uma página.

## 14. Contato

{{DEVELOPER_NAME}}
{{SUPPORT_EMAIL}}
{{SITE_URL}}/privacy.html
