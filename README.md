# App de Finanças Pessoais com Vibe Coding


1-PRD Refinado do Copilot Web

````
# PRD – Aplicativo de Organização de Finanças Pessoais Conversacional (Design Universal)

## Contexto
O aplicativo será um organizador de finanças pessoais baseado em conversas, permitindo que o usuário registre e acompanhe seus gastos por meio de linguagem natural.  
O diferencial está em oferecer uma experiência simples, inclusiva e acessível, sem formulários complexos ou planilhas, para que qualquer pessoa — independentemente de idade, nível de instrução, familiaridade com tecnologia ou condição física — consiga usar de forma independente.  
O projeto seguirá os princípios de Design Universal, garantindo que acessibilidade e inclusão não sejam apenas funcionalidades extras, mas parte da filosofia do produto.

## Problema
Muitos usuários desistem de controlar suas finanças porque:  
- Precisam digitar manualmente cada gasto.  
- Os relatórios são complexos e pouco intuitivos.  
- Falta personalização e recomendações práticas.  
- Poucos apps oferecem recursos inclusivos para pessoas com necessidades especiais.  

O objetivo é resolver essas dores com uma experiência conversacional, relatórios claros e recomendações automáticas de economia adaptadas à realidade de cada usuário, usando linguagem simples e acessível para todos os públicos.

## Público-Alvo
O app é pensado para ser utilizado por diversos perfis de usuários, incluindo:  
- Jovens iniciando o controle financeiro.  
- Pessoas com baixa instrução digital, que precisam de simplicidade.  
- Usuários experientes que buscam praticidade sem burocracia.  
- Famílias e trabalhadores autônomos que desejam organizar gastos do dia a dia.  
- Pessoas com deficiência visual ou motora, que necessitam de comandos de voz e interface acessível.  

Em resumo: o app é para todos que querem organizar suas finanças de forma prática, acessível e sem complicação.

## Princípios de Design Universal
- Acessibilidade nativa: suporte a leitores de tela, comandos de voz, botões grandes e navegação intuitiva.  
- Flexibilidade de uso: interação por texto, voz ou toques simples.  
- Interface inclusiva: linguagem clara, ícones intuitivos e opções de personalização (temas, tamanho da fonte).  
- Compatibilidade ampla: otimizado para rodar em diferentes modelos de celulares, tanto Android quanto iOS.  
- Aprendizado facilitado: tutorial interativo para ensinar como usar o app, com exemplos práticos e suporte em áudio.  
- Integração automática: sincronização de gastos e conexão com bancos/cartões para reduzir esforço manual.  
- Feedback contínuo: espaço para que usuários de diferentes perfis possam sugerir melhorias, ajudando a evoluir o app.  

## Funcionalidades-Chave
1. Registrar gastos via chat em linguagem natural  
   - Exemplo: “Gastei 50 reais no mercado ontem.”  
   - Possibilidade de registrar via comando de voz.  
2. Classificação automática das transações  
   - IA identifica categorias como alimentação, transporte, lazer.  
3. Definir e acompanhar metas financeiras  
   - Página dedicada para criar e alterar metas com ajuda do Agente Financeiro.  
4. Agente Financeiro com dicas personalizadas  
   - Exemplo: “Você gastou 20% a mais em delivery este mês.”  
5. Relatórios simples e personalizados  
   - Gráficos básicos e linguagem acessível: “Você gastou mais em transporte do que em lazer.”  
   - Compatibilidade com leitores de tela e descrições em áudio.  
6. Feedback dos usuários  
   - Área dedicada para enviar opiniões, sugestões e avaliações.  
7. Compatibilidade e otimização  
   - App leve e otimizado para rodar na maioria dos modelos de celulares (Android e iOS).  
8. Sincronização automática  
   - Gastos registrados offline são sincronizados assim que o dispositivo estiver online.  
9. Interface simples e intuitiva  
   - Botões grandes, textos claros e navegação acessível.  
10. Tutorial interativo  
    - Área dedicada para ensinar como usar o app, com exemplos práticos e suporte em áudio.  
11. Personalização  
    - Opções de temas (claro/escuro).  
    - Ajuste de tamanho da fonte para melhor leitura.  
12. Integração com bancos e cartões  
    - Importação automática de gastos sempre que houver transações vinculadas ao cartão ou conta bancária.  

## Entregável da IA
Gerar um plano de MVP contendo:  
- Principais telas:  
  - Tela inicial (chat com suporte a voz).  
  - Tela de metas (criação e alteração com ajuda do agente).  
  - Tela de relatórios com suporte a leitores de tela.  
  - Tela de feedback dos usuários.  
  - Tela de tutorial interativo.  
- Recursos necessários:  
  - Processamento de linguagem natural (NLP).  
  - Reconhecimento de voz e síntese de fala (speech-to-text e text-to-speech).  
  - Banco de dados para transações.  
  - Motor de classificação automática.  
  - Integração com APIs bancárias e de cartões.  
- Validação inicial:  
  - Teste com grupo pequeno de usuários de diferentes perfis, incluindo pessoas com deficiência visual e motora.  
  - Métricas de sucesso:  
    - Usuário consegue registrar gasto em menos de 10 segundos (voz ou texto).  
    - Relatórios são compreendidos sem necessidade de explicação adicional.  
    - Pelo menos 70% dos usuários relatam facilidade de uso.  
    - Usuários com deficiência conseguem realizar as principais tarefas sem barreiras.  
    - Feedback positivo sobre simplicidade e acessibilidade.
  ````




2-interações com o Lovable:

> Crie um app de finanças pessoais seguindo esse PRD:

> Ao falar sobre uma meta no chat, o aplicativo não a criou na aba de metas. Configure para que sempre que mencionarmos uma nova meta, o app a registre automaticamente na aba de metas.



3-Resumo das Funcionalidades do App

```
# Resumo das Funcionalidades do App

## Registro de Gastos
- Inserção de gastos via chat em linguagem natural.
- Possibilidade de registrar gastos por comando de voz.

## Classificação Automática
- Identificação automática das categorias de transações (alimentação, transporte, lazer, etc.).

## Metas Financeiras
- Página dedicada para criar e alterar metas.
- Apoio do Agente Financeiro para definir e acompanhar objetivos.

## Agente Financeiro
- Recomendações personalizadas de economia.
- Alertas sobre padrões de gastos (ex.: aumento em delivery).

## Relatórios
- Relatórios simples e personalizados.
- Gráficos básicos e linguagem acessível.
- Compatibilidade com leitores de tela e descrições em áudio.

## Feedback
- Área para que usuários enviem opiniões, sugestões e avaliações.

## Compatibilidade e Otimização
- App leve e otimizado para rodar na maioria dos modelos de celulares (Android e iOS).

## Sincronização
- Registro offline com sincronização automática quando o dispositivo estiver online.

## Interface
- Navegação simples e intuitiva.
- Botões grandes e textos claros.

## Tutorial
- Área dedicada para ensinar como usar o app.
- Exemplos práticos e suporte em áudio.

## Personalização
- Opções de temas (claro/escuro).
- Ajuste de tamanho da fonte.

## Integração Bancária
- Conexão com bancos e cartões.
- Importação automática de gastos vinculados a transações financeiras.
```



4-Uma breve reflexão sobre o processo :

-O que funcionou bem?
As interações com o Copilot funcionaram muito bem, conforme o esperado.

-O que não funcionou como o esperado?
As interações com o Lovable não saíram como planejado, devido à limitação de ações no site, o que dificultou um pouco as coisas. Mesmo assim, a experiência valeu pelo aprendizado.

-O que aprendeu sobre conversar com IAs?
As conversas com as IAs foram muito positivas, pois ajudaram a gerar ideias e a encontrar soluções para diferentes problemas. Percebi que, para obter bons resultados, é essencial elaborar prompts bem explicados, diretos e com comandos claros. Quando a interação é feita dessa forma, a experiência se torna mais produtiva e eficiente, permitindo explorar diferentes perspectivas e chegar a respostas mais completas.


