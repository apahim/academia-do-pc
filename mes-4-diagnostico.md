# Mês 4 — Diagnóstico e Manutenção

Semanas 13 a 16. Aqui você aprende a identificar problemas, limpar o computador, manter o Windows atualizado e controlar o que roda no seu PC.

**Pré-requisitos:** Ter completado o Mês 3, saber identificar componentes do computador e verificar especificações do sistema.

**Ao final deste mês você vai saber:**
- Usar o Gerenciador de Tarefas para monitorar e controlar processos
- Liberar espaço em disco removendo arquivos desnecessários
- Manter o Windows atualizado e seguro
- Instalar, desinstalar e gerenciar programas de inicialização

### Índice
- [Semana 13 — Gerenciador de Tarefas](#semana-13--gerenciador-de-tarefas)
- [Semana 14 — Limpeza de Disco](#semana-14--limpeza-de-disco)
- [Semana 15 — Atualizações do Windows](#semana-15--atualizações-do-windows)
- [Semana 16 — Programas e Inicialização](#semana-16--programas-e-inicialização)

---

## Semana 13 — Gerenciador de Tarefas

> Objetivo: usar o Gerenciador de Tarefas para monitorar e controlar o que está rodando no PC
> Tempo estimado: 2–3 horas

### Missão 1 — Abrir e Conhecer o Gerenciador de Tarefas

1. Pressione `Ctrl + Shift + Esc` para abrir o Gerenciador de Tarefas
2. Se abrir no modo simplificado, clique em "Mais detalhes"
3. Explore as abas principais:
   - **Processos**: tudo que está rodando agora
   - **Desempenho**: uso de CPU, RAM, disco e rede em tempo real
   - **Aplicativos de inicialização**: o que abre junto com o Windows
   - **Detalhes**: informações avançadas dos processos
4. Observe quais programas estão consumindo mais recursos

> **Dica:** Você também pode abrir o Gerenciador de Tarefas clicando com botão direito na barra de tarefas.

### Missão 2 — Identificar Processos que Consomem Recursos

1. Na aba **Processos**, clique no cabeçalho **CPU** para ordenar pelo uso de CPU
2. Identifique os 3 processos que mais usam CPU
3. Faça o mesmo para **Memória** e **Disco**
4. Pesquise no Google o nome de processos que você não reconhece (ex: "svchost.exe o que é")
5. Anote quais processos são do sistema e quais são programas que você instalou

### Missão 3 — Finalizar Tarefas

1. Abra vários programas ao mesmo tempo (navegador, Bloco de Notas, Explorador de Arquivos)
2. No Gerenciador de Tarefas, observe como o uso de memória aumenta
3. Selecione um programa e clique em **Finalizar Tarefa**
4. Observe que o programa fecha imediatamente

> **Dica:** Só finalize tarefas de programas que você reconhece. Finalizar processos do sistema pode causar problemas.

### Missão 4 — Monitorar em Tempo Real

1. Abra a aba **Desempenho**
2. Deixe o Gerenciador aberto enquanto usa o computador normalmente
3. Abra um programa pesado (navegador com muitas abas) e observe os gráficos
4. Feche o programa e observe os recursos voltando ao normal
5. Teste: abra 20 abas no navegador e veja o impacto na RAM

### Desafio da Semana

**Cenário:** O computador está lento e você não sabe por quê.

**Resolver:**
1. Abra o Gerenciador de Tarefas
2. Identifique qual recurso está no limite (CPU, Memória ou Disco)
3. Encontre o programa responsável
4. Decida: finalizar a tarefa, fechar o programa normalmente, ou esperar terminar
5. Documente: tire prints mostrando antes e depois

### Projeto da Semana

Crie um documento chamado **"Relatório de Desempenho do Meu PC"**.

- Print da aba Processos mostrando os programas em execução
- Print da aba Desempenho mostrando CPU, RAM e Disco
- Lista dos 5 programas que mais consomem recursos
- Comparação: PC em repouso vs PC com vários programas abertos

### Checklist

- [ ] Missão 1 — Conhecer o Gerenciador de Tarefas
- [ ] Missão 2 — Identificar processos
- [ ] Missão 3 — Finalizar tarefas
- [ ] Missão 4 — Monitorar em tempo real
- [ ] Desafio da semana
- [ ] Projeto da semana

---

## Semana 14 — Limpeza de Disco

> Objetivo: liberar espaço no computador removendo arquivos desnecessários
> Tempo estimado: 2–3 horas

### Missão 1 — Verificar o Espaço em Disco

1. Abra Configurações > Sistema > Armazenamento
2. Veja a barra mostrando quanto espaço está sendo usado
3. Clique em **Mostrar mais categorias** para ver o que ocupa mais espaço
4. Identifique as maiores categorias: Aplicativos, Arquivos temporários, Sistema, Outros
5. Anote quanto espaço livre você tem

### Missão 2 — Usar a Limpeza de Disco do Windows

1. Pressione `Win + S` e pesquise "Limpeza de Disco"
2. Selecione o disco C: e clique OK
3. Marque as opções seguras:
   - Arquivos temporários da Internet
   - Arquivos de programas baixados
   - Lixeira
   - Arquivos temporários
4. Clique em **Limpar arquivos do sistema** para opções adicionais
5. Veja quanto espaço será liberado e clique OK

> **Dica:** Essa limpeza é segura. O Windows só remove arquivos que não são mais necessários.

### Missão 3 — Limpar a Pasta Downloads

A pasta Downloads acumula arquivos que você já usou ou nem precisa mais.

1. Abra o Explorador de Arquivos > Downloads
2. Ordene por data (mais antigos primeiro)
3. Identifique arquivos que você não precisa mais (instaladores, PDFs já lidos)
4. Delete o que não precisa (selecione e pressione `Delete`)
5. Esvazie a Lixeira: clique com botão direito na Lixeira > Esvaziar Lixeira

### Missão 4 — Configurar Sensor de Armazenamento

O Windows pode limpar arquivos temporários automaticamente.

1. Vá em Configurações > Sistema > Armazenamento
2. Ative o **Sensor de Armazenamento**
3. Clique em "Sensor de Armazenamento" para configurar:
   - Quando executar (todos os meses é uma boa opção)
   - Excluir arquivos da Lixeira após 30 dias
   - Excluir arquivos da pasta Downloads após 30 dias (cuidado com essa opção)
4. Clique em "Executar Sensor de Armazenamento agora" para uma limpeza imediata

### Desafio da Semana

**Cenário:** O disco está quase cheio e o computador começa a ficar lento.

**Resolver:**
1. Verifique o espaço disponível em Configurações > Armazenamento
2. Execute a Limpeza de Disco
3. Limpe a pasta Downloads
4. Verifique se há arquivos grandes desnecessários
5. Compare o espaço antes e depois da limpeza

### Projeto da Semana

Crie um documento chamado **"Antes e Depois da Limpeza"**.

- Print do armazenamento antes da limpeza
- Lista de tudo que foi removido e quanto espaço liberou
- Print do armazenamento depois da limpeza
- Configure o Sensor de Armazenamento e tire um print das configurações

### Checklist

- [ ] Missão 1 — Verificar espaço em disco
- [ ] Missão 2 — Limpeza de disco
- [ ] Missão 3 — Limpar a pasta Downloads
- [ ] Missão 4 — Sensor de armazenamento
- [ ] Desafio da semana
- [ ] Projeto da semana

---

## Semana 15 — Atualizações do Windows

> Objetivo: entender e gerenciar as atualizações do sistema operacional
> Tempo estimado: 2–3 horas

### Missão 1 — Verificar Atualizações

1. Vá em Configurações > Windows Update
2. Clique em **Verificar se há atualizações**
3. Se houver atualizações disponíveis, observe:
   - Atualizações de qualidade (correções e segurança)
   - Atualizações de recursos (novas funcionalidades)
   - Atualizações de driver (para hardware)
4. Instale as atualizações pendentes

> **Dica:** Atualizações de segurança são as mais importantes. Mantê-las em dia protege seu PC contra ameaças.

### Missão 2 — Entender os Tipos de Atualização

1. Pesquise: "tipos de atualização Windows 11"
2. Anote:
   - **Atualizações de segurança**: corrigem vulnerabilidades. Instale sempre
   - **Atualizações cumulativas**: pacotes mensais com várias correções
   - **Atualizações de recursos**: grandes mudanças (1-2x por ano)
   - **Atualizações de driver**: para hardware funcionar melhor
3. Entenda que reiniciar é necessário para completar muitas atualizações

### Missão 3 — Configurar Horário Ativo

Evite que o Windows reinicie durante seu uso.

1. Vá em Configurações > Windows Update > Opções avançadas
2. Encontre **Horário ativo**
3. Configure o horário em que você costuma usar o computador
4. O Windows não vai reiniciar automaticamente nesse período

### Missão 4 — Ver Histórico de Atualizações

1. Vá em Configurações > Windows Update > Histórico de atualizações
2. Veja quais atualizações foram instaladas recentemente
3. Se uma atualização causou problemas, clique em "Desinstalar atualizações" (use com cuidado)
4. Anote a versão atual do Windows: Configurações > Sistema > Sobre > Especificações do Windows

### Desafio da Semana

**Cenário:** Após uma atualização, um programa parou de funcionar.

**Resolver:**
1. Verifique no histórico qual atualização foi instalada recentemente
2. Pesquise no Google: "[nome do programa] não funciona após atualização Windows"
3. Verifique se há atualização do programa disponível
4. Como último recurso, pesquise como desinstalar a atualização problemática

### Projeto da Semana

Crie um documento chamado **"Status do Meu Windows"**.

- Versão e build do Windows (de Sistema > Sobre)
- Lista de atualizações recentes
- Configuração do Horário Ativo
- Print da tela do Windows Update mostrando que está atualizado

### Checklist

- [ ] Missão 1 — Verificar atualizações
- [ ] Missão 2 — Tipos de atualização
- [ ] Missão 3 — Horário ativo
- [ ] Missão 4 — Histórico de atualizações
- [ ] Desafio da semana
- [ ] Projeto da semana

---

## Semana 16 — Programas e Inicialização

> Objetivo: instalar, desinstalar programas e controlar o que abre com o Windows
> Tempo estimado: 2–3 horas

### Missão 1 — Ver Programas Instalados

1. Vá em Configurações > Aplicativos > Aplicativos instalados
2. Ordene por tamanho para ver quais ocupam mais espaço
3. Ordene por data para ver os mais recentes
4. Identifique programas que você não usa mais
5. Anote os 5 maiores programas e se você realmente usa cada um

### Missão 2 — Desinstalar Programas

1. Na lista de aplicativos instalados, encontre um programa que não usa mais
2. Clique nos três pontos ao lado do nome > **Desinstalar**
3. Siga as instruções do desinstalador
4. Após desinstalar, verifique quanto espaço foi liberado
5. Repita para outros programas desnecessários

> **Dica:** Nunca desinstale programas que você não reconhece sem pesquisar antes. Pode ser algo do sistema.

### Missão 3 — Controlar a Inicialização

Programas que abrem com o Windows deixam a inicialização mais lenta.

1. Abra o Gerenciador de Tarefas (`Ctrl + Shift + Esc`)
2. Vá na aba **Aplicativos de inicialização**
3. Veja a lista de programas e o impacto na inicialização (Baixo, Médio, Alto)
4. Para programas que não precisam abrir com o Windows, clique com botão direito > **Desabilitar**
5. Exemplos seguros para desabilitar: Spotify, Discord, Steam, Teams (se não usar sempre)

> **Dica:** Não desabilite programas de segurança (antivírus) ou drivers de hardware.

### Missão 4 — Instalar Programas com Segurança

1. Sempre baixe programas do **site oficial** do desenvolvedor
2. Na Microsoft Store (pesquise no menu Iniciar), procure e instale um aplicativo gratuito
3. Ao instalar programas de sites, preste atenção:
   - Desmarque opções de instalar programas extras (barras de busca, "otimizadores")
   - Escolha instalação "Personalizada" para controlar o que é instalado
   - Verifique se o site é HTTPS (cadeado na barra de endereço)

### Desafio da Semana

**Cenário:** O computador demora muito para ligar e fica lento nos primeiros minutos.

**Resolver:**
1. Abra o Gerenciador de Tarefas > Inicialização
2. Identifique programas com impacto "Alto" que não são essenciais
3. Desabilite os desnecessários
4. Reinicie o computador e compare o tempo de inicialização
5. Tire prints do antes e depois

### Projeto da Semana

Crie um documento chamado **"Auditoria de Programas"**.

- Lista de todos os programas instalados (organizados por categoria)
- Quais foram desinstalados e por quê
- Quais estavam na inicialização e foram desabilitados
- Espaço liberado com as desinstalações
- Tempo de inicialização antes e depois

### Checklist

- [ ] Missão 1 — Ver programas instalados
- [ ] Missão 2 — Desinstalar programas
- [ ] Missão 3 — Controlar a inicialização
- [ ] Missão 4 — Instalar programas com segurança
- [ ] Desafio da semana
- [ ] Projeto da semana

---

[Voltar ao índice](README.md) | [Anterior: Mês 3](mes-3-hardware.md) | [Próximo: Mês 5](mes-5-seguranca.md)
