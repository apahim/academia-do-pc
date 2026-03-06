# Mês 5 — Segurança

Semanas 17 a 20. Aqui você aprende a proteger seu computador e seus dados contra ameaças, golpes e invasões de privacidade.

**Pré-requisitos:** Ter completado o Mês 4, saber gerenciar programas e manter o Windows atualizado.

**Ao final deste mês você vai saber:**
- Usar o Windows Defender para proteger contra vírus e malware
- Criar senhas fortes e usar verificação em duas etapas
- Reconhecer golpes, phishing e sites falsos
- Controlar sua privacidade no Windows, navegador e serviços online

### Índice
- [Semana 17 — Windows Defender e Antivírus](#semana-17--windows-defender-e-antivírus)
- [Semana 18 — Senhas Seguras](#semana-18--senhas-seguras)
- [Semana 19 — Phishing, Golpes e Sites Falsos](#semana-19--phishing-golpes-e-sites-falsos)
- [Semana 20 — Privacidade](#semana-20--privacidade)

---

## Semana 17 — Windows Defender e Antivírus

> Objetivo: usar o Windows Defender para proteger o computador contra vírus e malware
> Tempo estimado: 2–3 horas

### Missão 1 — Conhecer o Windows Defender

O Windows Defender (Segurança do Windows) já vem instalado e é suficiente para a maioria dos usuários.

1. Pressione `Win + S` e pesquise "Segurança do Windows"
2. Explore o painel principal. Você verá ícones com status:
   - Marcação verde: tudo certo
   - Triângulo amarelo: atenção necessária
   - X vermelho: ação necessária
3. Clique em **Proteção contra vírus e ameaças**
4. Verifique se a proteção em tempo real está **ativada**

> **Dica:** Não é necessário instalar outro antivírus. O Windows Defender é bom e gratuito. Ter dois antivírus ao mesmo tempo pode causar conflitos.

### Missão 2 — Executar uma Verificação

1. Em Proteção contra vírus e ameaças, clique em **Verificação rápida**
2. Aguarde a verificação terminar (pode levar alguns minutos)
3. Veja o resultado: arquivos verificados e ameaças encontradas
4. Para uma verificação mais completa: clique em **Opções de verificação** > **Verificação completa**
5. A verificação completa demora mais, mas analisa todos os arquivos

### Missão 3 — Configurar a Proteção

1. Em Proteção contra vírus e ameaças > **Configurações de proteção**
2. Verifique se estas opções estão ativadas:
   - Proteção em tempo real
   - Proteção fornecida pela nuvem
   - Envio automático de amostra
3. Explore **Proteção contra ransomware** > ative o "Acesso controlado a pastas"
4. Em **Firewall e proteção de rede**, verifique se o firewall está ativo para todas as redes

### Missão 4 — Verificar o Histórico de Proteção

1. Em Proteção contra vírus e ameaças > **Histórico de proteção**
2. Veja se houve ameaças detectadas recentemente
3. Para cada ameaça, o Windows mostra:
   - Nome da ameaça
   - Gravidade (baixa, alta, grave)
   - Ação tomada (colocado em quarentena, removido, permitido)
4. Se houver algo em quarentena, geralmente é seguro manter lá ou remover

### Desafio da Semana

**Cenário:** Você baixou um programa e o Windows Defender bloqueou dizendo que é uma ameaça.

**Resolver:**
1. Não abra o arquivo
2. Veja o nome da ameaça no alerta do Defender
3. Pesquise no Google: "[nome da ameaça] é perigoso?"
4. Se for falso positivo (programa legítimo que foi bloqueado por engano), pesquise como permitir
5. Se for ameaça real, delete o arquivo e esvazie a Lixeira

### Projeto da Semana

Crie um documento chamado **"Status de Segurança do Meu PC"**.

- Print do painel da Segurança do Windows (mostrando todos os ícones verdes)
- Resultado da verificação rápida
- Configurações de proteção ativadas
- Histórico de proteção (ameaças encontradas ou "nenhuma ameaça")

### Checklist

- [ ] Missão 1 — Conhecer o Windows Defender
- [ ] Missão 2 — Executar verificação
- [ ] Missão 3 — Configurar proteção
- [ ] Missão 4 — Histórico de proteção
- [ ] Desafio da semana
- [ ] Projeto da semana

---

## Semana 18 — Senhas Seguras

> Objetivo: criar senhas fortes e aprender a usar um gerenciador de senhas
> Tempo estimado: 2–3 horas

### Missão 1 — Entender o que É uma Senha Forte

1. Pesquise: "como criar senha segura"
2. Regras de uma boa senha:
   - Mínimo 12 caracteres
   - Mistura de maiúsculas, minúsculas, números e símbolos
   - Não usar dados pessoais (nome, data de nascimento)
   - Não usar a mesma senha em vários sites
   - Não usar palavras comuns ("senha123", "qwerty")
3. Exemplo de senha fraca: `maria2024`
4. Exemplo de senha forte: `Tr0v@o-Azul#47!Gato`

> **Dica:** Uma técnica boa é criar uma frase e transformar em senha. Ex: "Meu gato tem 3 anos!" → `MgT3a!`

### Missão 2 — Verificar se Suas Senhas Já Vazaram

1. Acesse o site [haveibeenpwned.com](https://haveibeenpwned.com)
2. Digite seu email e veja se aparece em algum vazamento
3. Se apareceu, troque a senha dos serviços listados imediatamente
4. No Google Chrome: Configurações > Privacidade e segurança > Gerenciador de senhas > Verificação de senhas

### Missão 3 — Conhecer um Gerenciador de Senhas

Um gerenciador de senhas guarda todas as suas senhas em um cofre protegido por uma senha mestra.

1. O Google Chrome já tem um gerenciador embutido: Configurações > Senhas
2. Para algo mais completo, pesquise sobre o **Bitwarden** (gratuito e seguro)
3. Vantagens:
   - Você só precisa decorar uma senha (a mestra)
   - Ele gera senhas fortes automaticamente
   - Preenche login e senha nos sites automaticamente
4. Se quiser, crie uma conta no Bitwarden e instale a extensão no navegador

### Missão 4 — Ativar Verificação em Duas Etapas

A verificação em duas etapas (2FA) pede uma segunda confirmação além da senha.

1. Na sua conta Google: acesse myaccount.google.com > Segurança
2. Ative a **Verificação em duas etapas**
3. Escolha o método: SMS, app de autenticação ou chave de segurança
4. O método mais seguro é um app de autenticação (Google Authenticator, por exemplo)
5. Faça o mesmo para outros serviços importantes (email, banco, redes sociais)

### Desafio da Semana

**Cenário:** Você recebe um email dizendo que sua senha de um serviço foi comprometida.

**Resolver:**
1. Verifique se o email é legítimo (veja a seção de phishing na Semana 19)
2. Não clique em links do email — vá diretamente ao site do serviço
3. Troque a senha por uma forte e única
4. Ative a verificação em duas etapas
5. Verifique se usou a mesma senha em outros sites e troque neles também

### Projeto da Semana

Crie um documento chamado **"Meu Plano de Senhas"** (guarde em local seguro ou no gerenciador de senhas).

- Liste seus serviços mais importantes (email, banco, redes sociais)
- Para cada um, anote se a senha é forte (sem anotar a senha em si)
- Marque quais têm verificação em duas etapas ativada
- Plano de ação: quais senhas precisam ser trocadas

### Checklist

- [ ] Missão 1 — Senhas fortes
- [ ] Missão 2 — Verificar vazamentos
- [ ] Missão 3 — Gerenciador de senhas
- [ ] Missão 4 — Verificação em duas etapas
- [ ] Desafio da semana
- [ ] Projeto da semana

---

## Semana 19 — Phishing, Golpes e Sites Falsos

> Objetivo: reconhecer tentativas de golpe na internet e se proteger
> Tempo estimado: 2–3 horas

### Missão 1 — Identificar Emails de Phishing

Phishing é quando alguém finge ser uma empresa ou pessoa para roubar seus dados.

1. Pesquise: "exemplos de email phishing" no Google Imagens
2. Sinais de phishing:
   - Remetente com email estranho (ex: banco@gmail.com em vez de @itau.com.br)
   - Erros de português
   - Urgência exagerada ("sua conta será bloqueada em 24h!")
   - Links que não levam ao site real (passe o mouse sobre o link sem clicar para ver o endereço)
   - Pede dados pessoais, senha ou número de cartão
3. Regra de ouro: empresas sérias nunca pedem senha por email

### Missão 2 — Reconhecer Sites Falsos

1. Pesquise: "como identificar site falso"
2. Sinais de site falso:
   - URL diferente da oficial (ex: amaz0n.com em vez de amazon.com.br)
   - Sem HTTPS (sem cadeado na barra de endereço)
   - Design estranho ou imagens de baixa qualidade
   - Preços absurdamente baixos
   - Pede dados desnecessários
3. Antes de comprar, pesquise: "[nome do site] é confiável" ou verifique no Reclame Aqui

### Missão 3 — Golpes Comuns na Internet

1. Pesquise sobre os golpes mais comuns:
   - **Falso suporte técnico**: popup dizendo que seu PC tem vírus, ligue para esse número
   - **Promoção falsa**: "você ganhou um iPhone, clique aqui"
   - **Falso boleto**: boleto com dados bancários de criminosos
   - **WhatsApp clonado**: alguém finge ser você pedindo dinheiro
   - **Falso emprego**: vaga que pede dinheiro ou dados bancários
2. Anote as regras para cada tipo de golpe

### Missão 4 — O que Fazer se Cair em um Golpe

1. Se deu sua senha: troque imediatamente em todos os serviços onde usou a mesma senha
2. Se deu dados do cartão: ligue para o banco e bloqueie o cartão
3. Se instalou um programa suspeito: execute verificação completa do Windows Defender, depois desinstale o programa
4. Se enviou dinheiro: registre um boletim de ocorrência (pode ser feito online em muitos estados)
5. Pesquise: "boletim de ocorrência online [seu estado]"

### Desafio da Semana

**Cenário:** Analise estas situações e diga se são golpe ou não:
1. Email do "banco" pedindo para atualizar seus dados clicando em um link
2. Site de loja com preços 80% abaixo do mercado
3. Mensagem do WhatsApp de um amigo pedindo Pix urgente
4. Popup no navegador dizendo "Seu computador está infectado!"

**Resolver:**
1. Para cada cenário, explique por que é ou não é golpe
2. Descreva o que faria em cada situação
3. Documente tudo no Google Docs

### Projeto da Semana

Crie um guia chamado **"Como Não Cair em Golpes na Internet"**.

- Pelo menos 5 tipos de golpes com explicação
- Como identificar cada um
- O que fazer se cair
- Dicas gerais de segurança
- Compartilhe o guia com alguém da sua família

### Checklist

- [ ] Missão 1 — Emails de phishing
- [ ] Missão 2 — Sites falsos
- [ ] Missão 3 — Golpes comuns
- [ ] Missão 4 — O que fazer se cair em um golpe
- [ ] Desafio da semana
- [ ] Projeto da semana

---

## Semana 20 — Privacidade

> Objetivo: controlar suas informações pessoais e navegar com mais privacidade
> Tempo estimado: 2–3 horas

### Missão 1 — Permissões de Aplicativos

1. Vá em Configurações > Privacidade e segurança
2. Role até "Permissões de aplicativos" e explore:
   - **Câmera**: quais apps podem usar sua câmera
   - **Microfone**: quais apps podem ouvir
   - **Localização**: quais apps sabem onde você está
3. Desative permissões para apps que não precisam (ex: uma calculadora não precisa de câmera)
4. Revise todas as categorias de permissão

> **Dica:** O Windows mostra um ícone na barra de tarefas quando a câmera ou microfone estão em uso.

### Missão 2 — Privacidade no Navegador

1. No navegador, abra Configurações > Privacidade e segurança
2. Configure:
   - **Cookies**: bloqueie cookies de terceiros
   - **Histórico**: saiba que tudo que você acessa fica registrado
   - **Limpar dados**: Configurações > Privacidade > Limpar dados de navegação
3. Para navegar sem salvar histórico: use a **janela anônima** (`Ctrl + Shift + N` no Chrome)
4. A janela anônima não salva histórico nem cookies, mas seu provedor de internet ainda vê o que você acessa

### Missão 3 — Configurações de Privacidade do Google

1. Acesse myaccount.google.com
2. Vá em **Dados e privacidade**
3. Revise:
   - **Atividade na Web e de Apps**: o Google salva suas pesquisas. Você pode desativar ou excluir
   - **Histórico de localização**: desative se não quiser ser rastreado
   - **Histórico do YouTube**: desative se preferir
4. Faça uma **Verificação de privacidade** (link disponível na página)

### Missão 4 — Configurações de Privacidade do Windows

1. Vá em Configurações > Privacidade e segurança > Geral
2. Revise cada opção:
   - ID de publicidade: desative se não quiser anúncios personalizados
   - Conteúdo sugerido: desative se preferir
   - Dados de diagnóstico: Configurações > Privacidade > Diagnóstico e feedback
3. Desative o que não quiser compartilhar com a Microsoft

### Desafio da Semana

**Cenário:** Você quer verificar o quanto da sua vida digital está exposta.

**Resolver:**
1. Pesquise seu nome completo no Google e veja o que aparece
2. Revise as permissões dos apps no celular também
3. Verifique suas configurações de privacidade nas redes sociais
4. Faça a Verificação de privacidade do Google
5. Limpe o histórico de navegação e cookies

### Projeto da Semana

Crie um documento chamado **"Auditoria de Privacidade"**.

- O que você encontrou ao pesquisar seu nome no Google
- Lista de permissões de apps que foram revogadas
- Configurações de privacidade alteradas no Windows e Google
- Checklist de boas práticas de privacidade que você vai seguir

### Checklist

- [ ] Missão 1 — Permissões de aplicativos
- [ ] Missão 2 — Privacidade no navegador
- [ ] Missão 3 — Privacidade do Google
- [ ] Missão 4 — Privacidade do Windows
- [ ] Desafio da semana
- [ ] Projeto da semana

---

[Voltar ao índice](README.md) | [Anterior: Mês 4](mes-4-diagnostico.md) | [Próximo: Mês 6](mes-6-avancado.md)
