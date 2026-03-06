# Mês 6 — Técnico + IA + Projeto Final

Semanas 21 a 24. O mês final: você aprende a usar o Prompt de Comando, entender redes, usar IA como ferramenta e compila tudo em um projeto final.

**Pré-requisitos:** Ter completado o Mês 5, saber proteger o computador e gerenciar privacidade.

**Ao final deste mês você vai saber:**
- Usar o Prompt de Comando e conhecer o PowerShell para tarefas avançadas
- Entender como redes e internet funcionam e diagnosticar problemas
- Usar ferramentas de IA (incluindo Copilot) para estudo e produtividade
- Compilar todo o aprendizado em um projeto final completo

### Índice
- [Semana 21 — Prompt de Comando](#semana-21--prompt-de-comando)
- [Semana 22 — Redes](#semana-22--redes)
- [Semana 23 — Inteligência Artificial](#semana-23--inteligência-artificial)
- [Semana 24 — Projeto Final](#semana-24--projeto-final)

---

## Semana 21 — Prompt de Comando

> Objetivo: usar comandos básicos no terminal do Windows para realizar tarefas e diagnósticos
> Tempo estimado: 2–3 horas

### Missão 1 — Abrir o Prompt de Comando

1. Pressione `Win + S` e pesquise "Prompt de Comando" (ou "cmd")
2. Clique com botão direito > **Executar como administrador** (para comandos que precisam de permissão)
3. A tela preta com texto é o terminal. Aqui você digita comandos em vez de clicar
4. Digite `echo Olá Mundo` e pressione Enter — você verá a mensagem na tela
5. Para limpar a tela, digite `cls`

> **Dica:** Você também pode abrir o **Terminal do Windows** (mais moderno) pesquisando "Terminal" no menu Iniciar.

### Missão 2 — Navegar por Pastas

1. Digite `dir` e pressione Enter — mostra os arquivos e pastas do diretório atual
2. Digite `cd Documentos` para entrar na pasta Documentos
3. Digite `cd ..` para voltar uma pasta
4. Digite `cd \` para ir direto à raiz do disco
5. Para ir a uma pasta específica: `cd C:\Users\SeuNome\Documentos\Academia do PC`

> **Dica:** Comece a digitar o nome da pasta e pressione `Tab` para autocompletar.

### Missão 3 — Comandos de Arquivo

1. `mkdir NovaPasta` — cria uma pasta chamada "NovaPasta"
2. `type nul > teste.txt` — cria um arquivo vazio
3. `echo Conteúdo do arquivo > teste.txt` — cria arquivo com texto
4. `type teste.txt` — mostra o conteúdo do arquivo
5. `del teste.txt` — deleta o arquivo
6. `rmdir NovaPasta` — remove a pasta (precisa estar vazia)

Pratique criando e removendo pastas e arquivos dentro de `Academia do PC`.

### Missão 4 — Comandos de Informação

1. `hostname` — mostra o nome do computador
2. `whoami` — mostra o usuário logado
3. `systeminfo` — mostra informações detalhadas do sistema (espere carregar)
4. `tasklist` — lista todos os processos em execução (versão texto do Gerenciador de Tarefas)
5. `ipconfig` — mostra informações de rede (você vai usar mais na próxima semana)

### Missão 5 — CMD vs PowerShell

O Windows tem dois terminais: o CMD (clássico) e o PowerShell (moderno). O PowerShell é o padrão no Windows 11.

1. Pesquise "PowerShell" no menu Iniciar e abra
2. Note que o PowerShell aceita os mesmos comandos do CMD (`dir`, `cd`, `mkdir`) e mais
3. Compare comandos equivalentes:

| CMD | PowerShell | O que faz |
|---|---|---|
| `dir` | `Get-ChildItem` | Lista arquivos e pastas |
| `type arquivo.txt` | `Get-Content arquivo.txt` | Mostra conteúdo de arquivo |
| `del arquivo.txt` | `Remove-Item arquivo.txt` | Deleta arquivo |
| `systeminfo` | `Get-ComputerInfo` | Informações do sistema |

4. Teste: abra o **Terminal do Windows** (pesquise "Terminal") — ele permite usar CMD, PowerShell e mais em abas diferentes
5. Na prática, o CMD é suficiente para a maioria das tarefas. O PowerShell é mais poderoso para automação

> **Dica:** No Terminal do Windows, clique na seta ao lado da aba "+" para escolher entre PowerShell, CMD ou outras opções. Você pode ter os dois abertos ao mesmo tempo.

### Desafio da Semana

**Cenário:** Sem usar o mouse, apenas o Prompt de Comando, faça o seguinte:

**Resolver:**
1. Navegue até a pasta Documentos
2. Crie uma pasta chamada `Desafio-CMD`
3. Dentro dela, crie 3 subpastas: `Textos`, `Dados`, `Backup`
4. Crie um arquivo `readme.txt` com a frase "Criado pelo Prompt de Comando"
5. Liste o conteúdo da pasta para confirmar
6. Tire um print do terminal mostrando os comandos e resultados

### Projeto da Semana

Crie um documento chamado **"Guia de Comandos do CMD"**.

- Tabela com todos os comandos que aprendeu: comando, o que faz, exemplo
- Print do terminal com cada comando sendo executado
- Crie um arquivo `.bat` (script):
  1. Abra o Bloco de Notas
  2. Digite os comandos que organizam pastas (mkdir, etc.), um por linha
  3. Salve como `organizar.bat` (mude o tipo para "Todos os arquivos")
  4. Execute o arquivo .bat com dois cliques e veja os comandos rodarem automaticamente

Crie a pasta `Mes-6` dentro de `Academia do PC/`. Exporte o guia como PDF e salve o PDF e o arquivo `organizar.bat` em `Academia do PC/Mes-6/`.

### Checklist

- [ ] Missão 1 — Abrir o Prompt de Comando
- [ ] Missão 2 — Navegar por pastas
- [ ] Missão 3 — Comandos de arquivo
- [ ] Missão 4 — Comandos de informação
- [ ] Missão 5 — CMD vs PowerShell
- [ ] Desafio da semana
- [ ] Projeto da semana

---

## Semana 22 — Redes

> Objetivo: entender como a internet funciona, diagnosticar problemas de conexão
> Tempo estimado: 2–3 horas

### Missão 1 — Entender IP e DNS

1. Abra o Prompt de Comando e digite `ipconfig`
2. Encontre seu **Endereço IPv4** — esse é o "CEP" do seu computador na rede
3. Encontre o **Gateway Padrão** — esse é o endereço do seu roteador
4. Pesquise: "o que é DNS e como funciona"
5. Anote:
   - IP: endereço do computador na rede
   - DNS: traduz nomes de sites para endereços IP (google.com → 142.250.xxx.xxx)
   - Gateway: o endereço do roteador, porta de saída para a internet

> **Dica:** IP interno (192.168.x.x) é o endereço dentro da sua casa. IP externo é como o mundo te vê. Pesquise "meu IP" no Google para ver seu IP externo.

### Missão 2 — Testar Conexão com Ping

O comando `ping` testa se o seu computador consegue se comunicar com outro.

1. No Prompt de Comando, digite `ping google.com`
2. Observe:
   - **Tempo** (ms): quanto menor, melhor a conexão
   - **TTL**: tempo de vida do pacote
   - **Pacotes perdidos**: se perder pacotes, a conexão está instável
3. Teste: `ping 8.8.8.8` (servidor DNS do Google)
4. Teste: `ping [gateway padrão]` (o número que você encontrou no ipconfig)
5. Compare os tempos de resposta

### Missão 3 — Diagnosticar Problemas de Rede

1. Se `ping [gateway]` falha: problema entre o PC e o roteador (Wi-Fi, cabo)
2. Se `ping [gateway]` funciona mas `ping google.com` falha: problema de internet ou DNS
3. Para testar DNS: `nslookup google.com` — se falhar, o problema é DNS
4. Para mudar o DNS: Configurações > Rede e Internet > Wi-Fi > Propriedades > Atribuição de servidor DNS > Manual
5. DNS recomendados: Google (8.8.8.8) ou Cloudflare (1.1.1.1)

### Missão 4 — Conhecer as Configurações de Rede do Windows

1. Vá em Configurações > Rede e Internet
2. Veja o status da sua conexão (Wi-Fi ou Ethernet)
3. Clique em **Propriedades** da sua rede para ver detalhes
4. Em **Configurações avançadas de rede**, explore:
   - Adaptadores de rede: os dispositivos que conectam seu PC à rede
   - Uso de dados: quanto de internet você usou
5. Pesquise: "Wi-Fi 2.4 GHz vs 5 GHz" — diferença entre as bandas do Wi-Fi

### Desafio da Semana

**Cenário:** A internet parou de funcionar no seu computador, mas outros dispositivos estão conectados normalmente.

**Resolver:**
1. Verifique se o Wi-Fi está ligado no PC
2. Desconecte e reconecte ao Wi-Fi
3. Abra o CMD e teste: `ping [gateway]` — funciona?
4. Teste: `ping google.com` — funciona?
5. Se nenhum funcionar: desative e reative o adaptador de rede em Configurações > Rede
6. Último recurso: no CMD, execute `ipconfig /release` depois `ipconfig /renew`
7. Documente cada passo e o resultado

### Projeto da Semana

Crie um documento chamado **"Mapa da Minha Rede"**.

- Diagrama simples: Internet → Roteador → Seus dispositivos
- Informações do `ipconfig`: IP, Gateway, DNS
- Resultado do `ping` para diferentes destinos
- Velocidade da internet (pesquise "teste de velocidade" no Google)
- Qual banda Wi-Fi você está usando (2.4 GHz ou 5 GHz)

Exporte como PDF e salve em `Academia do PC/Mes-6/`.

### Checklist

- [ ] Missão 1 — IP e DNS
- [ ] Missão 2 — Testar conexão com ping
- [ ] Missão 3 — Diagnosticar problemas de rede
- [ ] Missão 4 — Configurações de rede do Windows
- [ ] Desafio da semana
- [ ] Projeto da semana

---

## Semana 23 — Inteligência Artificial

> Objetivo: usar IA como ferramenta de estudo, pesquisa e produtividade
> Tempo estimado: 2–3 horas

### Missão 1 — Conhecer as Ferramentas de IA

1. Acesse e crie conta (gratuita) em pelo menos dois:
   - [ChatGPT](https://chat.openai.com) (OpenAI)
   - [Claude](https://claude.ai) (Anthropic)
   - [Gemini](https://gemini.google.com) (Google)
   - **Copilot** (Microsoft) — já vem no Windows 11. Clique no ícone do Copilot na barra de tarefas ou pressione `Win + C`
2. Faça a mesma pergunta nos dois: "Explique como funciona a memória RAM de um computador"
3. Compare as respostas: qual foi mais clara? Mais completa?
4. Anote as diferenças entre cada ferramenta

### Missão 2 — Aprender a Fazer Boas Perguntas (Prompts)

A qualidade da resposta da IA depende da qualidade da sua pergunta.

1. Pergunta ruim: "me ajuda com computador"
2. Pergunta boa: "Meu computador com Windows 11 está demorando 3 minutos para ligar. O que posso fazer para acelerar a inicialização?"
3. Dicas para bons prompts:
   - Seja específico sobre o que quer
   - Dê contexto (Windows 11, qual programa, o que aconteceu)
   - Peça formato específico: "me dê uma lista de passos" ou "explique de forma simples"
   - Se a resposta for confusa, peça: "explique isso como se eu fosse iniciante"
4. Pratique: faça 5 perguntas diferentes usando essas técnicas

### Missão 3 — Usar IA para Estudar

1. Peça à IA para explicar um conceito que você achou difícil no curso (ex: "o que é DNS?")
2. Peça para criar um quiz: "Crie 10 perguntas de múltipla escolha sobre segurança digital"
3. Responda o quiz e peça para a IA corrigir
4. Peça para resumir um texto longo: copie um artigo e diga "Resuma este texto em 5 pontos principais"
5. Peça para criar um plano de estudo: "Crie um plano de 1 semana para aprender sobre redes de computadores"

### Missão 4 — Usar IA para Resolver Problemas

1. Descreva um problema real do seu computador para a IA e siga as instruções
2. Peça ajuda com uma fórmula do Google Planilhas: "Como faço uma fórmula que soma apenas os valores maiores que 100?"
3. Peça para a IA escrever um script .bat: "Crie um script que organize arquivos por extensão em pastas separadas"
4. Peça para revisar um texto que você escreveu: "Revise este texto e sugira melhorias"

> **Dica:** A IA pode errar. Sempre verifique informações importantes em outras fontes. Use a IA como assistente, não como verdade absoluta.

> **Dica de Privacidade:** Nunca cole dados pessoais sensíveis em ferramentas de IA — senhas, CPF, dados bancários, documentos confidenciais. Tudo que você digita pode ser usado para treinar o modelo ou ficar armazenado nos servidores da empresa.

### Desafio da Semana

**Cenário:** Você precisa preparar uma apresentação sobre um tema que não conhece bem.

**Resolver:**
1. Escolha um tema (ex: "Como a internet funciona")
2. Peça à IA para criar um roteiro com os principais tópicos
3. Para cada tópico, peça uma explicação simples
4. Peça para criar exemplos e analogias
5. Monte um documento no Google Docs com todo o conteúdo
6. Peça à IA para revisar o documento final

### Projeto da Semana

Crie um documento chamado **"Guia Prático de IA"**.

- Comparação entre ChatGPT, Claude, Gemini e Copilot (pontos fortes de cada um)
- 10 exemplos de prompts úteis para o dia a dia
- Dicas de como conseguir respostas melhores
- Limitações da IA (quando não confiar)
- Um exemplo prático de problema que você resolveu com ajuda da IA

Exporte como PDF e salve em `Academia do PC/Mes-6/`.

### Checklist

- [ ] Missão 1 — Conhecer ferramentas de IA
- [ ] Missão 2 — Boas perguntas (prompts)
- [ ] Missão 3 — IA para estudar
- [ ] Missão 4 — IA para resolver problemas
- [ ] Desafio da semana
- [ ] Projeto da semana

---

## Semana 24 — Projeto Final

> Objetivo: compilar tudo que aprendeu em um projeto final organizado
> Tempo estimado: 4–6 horas

### Missão 1 — Revisar Todo o Curso

1. Releia o checklist de cada semana
2. Identifique semanas ou missões que ficaram incompletas
3. Complete o que faltar (não precisa ser perfeito, mas tente completar tudo)
4. Revise sua planilha de progresso com tudo que completou

### Missão 2 — Verificar a Pasta do Curso

Sua pasta `Academia do PC/` já contém todo o trabalho organizado por mês. Verifique se está completa:

```
Academia do PC/
  Mes-1/    → fundamentos, projetos e PDFs do mês 1
  Mes-2/    → produtividade, planilha de progresso
  Mes-3/    → hardware, ficha técnica, periféricos
  Mes-4/    → diagnóstico, limpeza, atualizações
  Mes-5/    → segurança, senhas, privacidade
  Mes-6/    → CMD, redes, IA
  Prints/   → prints de tela do curso todo
```

1. Navegue por cada pasta e confirme que os PDFs e arquivos estão lá
2. Se faltar algo, exporte e salve agora
3. Crie a pasta `Relatorio-Final/` dentro de `Academia do PC/` para o relatório da próxima missão

### Missão 3 — Escrever o Relatório Final

Crie um documento no Google Docs chamado **"Relatório Final — Academia do PC"**.

Estrutura:
1. **Introdução**: quem é você e por que fez o curso
2. **O que aprendi**: um parágrafo para cada mês do curso
3. **Habilidades adquiridas**: lista das coisas que você sabe fazer agora
4. **Desafios**: o que foi mais difícil e como superou
5. **Próximos passos**: o que quer aprender depois
6. **Progresso**: quantas semanas e missões completou

Exporte como PDF e salve em `Academia do PC/Relatorio-Final/`.

### Missão 4 — Compactar e Entregar

1. Verifique se todos os arquivos estão nas pastas corretas
2. Abra o Explorador de Arquivos e vá até a pasta `Academia do PC`
3. Selecione a pasta, clique com botão direito > "Compactar para arquivo ZIP"
4. Renomeie para `Academia-do-PC_[SeuNome].zip`
5. Faça upload do ZIP para o Google Drive
6. Compartilhe o link com quem estiver acompanhando seu progresso

### Desafio Final

**Cenário:** Simule que você é o "técnico de informática" da família. Alguém te procura com um destes problemas:
- "Meu PC está lento"
- "Não consigo achar um arquivo"
- "Acho que peguei um vírus"
- "A internet caiu"

**Resolver:**
1. Escolha pelo menos 2 cenários
2. Escreva o passo a passo completo que você seguiria para resolver
3. Use tudo que aprendeu no curso: Gerenciador de Tarefas, CMD, Defender, configurações de rede
4. Inclua no Relatório Final

### Projeto Final

O projeto final é a soma de tudo:

- [ ] Pasta `Academia do PC` completa e organizada com todos os trabalhos do curso
- [ ] Relatório Final completo no Google Docs e exportado como PDF
- [ ] Planilha de progresso atualizada
- [ ] Tudo compactado em um arquivo ZIP
- [ ] Upload feito no Google Drive
- [ ] Link compartilhado

### Checklist

- [ ] Missão 1 — Revisar o curso
- [ ] Missão 2 — Criar pasta do Projeto Final
- [ ] Missão 3 — Escrever Relatório Final
- [ ] Missão 4 — Compactar e entregar
- [ ] Desafio final
- [ ] Projeto final completo

---

## Parabéns!

Você completou a **Academia do PC**. Agora você sabe:

- Organizar arquivos e pastas de forma eficiente
- Criar documentos e planilhas profissionais
- Entender o hardware do seu computador
- Diagnosticar e resolver problemas comuns
- Proteger seu computador e seus dados
- Usar o terminal para tarefas avançadas
- Entender como redes e internet funcionam
- Usar IA como ferramenta de produtividade

O mais importante: você aprendeu a **se virar**. Qualquer problema novo que aparecer, você tem as ferramentas para pesquisar, entender e resolver.

---

[Voltar ao índice](README.md) | [Anterior: Mês 5](mes-5-seguranca.md)
