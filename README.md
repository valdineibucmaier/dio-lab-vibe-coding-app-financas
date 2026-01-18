# 💸 App de Organização de Finanças Pessoais com Vibe Coding

Aprenda a **criar soluções com IA** de forma criativa, guiando ferramentas como o **Copilot** e o **Lovable** com uma comunicação simples e natural. O foco é desenvolver o conceito de um **App de Organização de Finanças Pessoais**, mas, acima de tudo, aprender o **jeito Vibe de programar com IA**.

## ✨ O que é Vibe Coding

**Vibe Coding** é uma forma leve e criativa de desenvolver com IA, baseada em **conversas naturais e bem estruturadas**. Você não precisa escrever código linha por linha. Em vez disso, aprende a **guiar a IA** descrevendo suas ideias de forma clara, com **intenção e contexto**. Em outras palavras:

> Você mostra a vibe da sua ideia e a IA transforma em solução (ou em um caminho para ela).

## 🎯 Desafio

Problema: Muitas pessoas não conseguem manter um controle financeiro porque os aplicativos exigem muita entrada de dados manual, e a criação de orçamentos é vista como algo tedioso. 

Precisamos de uma solução que permita **controlar as finanças por meio de uma conversa simples**, com **agentes de IA** capazes de criar **planos de economia personalizados e automatizados**. Você deve utilizar as ideias de **Vibe Coding** e **MVP (Produto Mínimo Viável)** para desenvolver o **conceito de um aplicativo** que resolva o problema citado.

> [!IMPORTANT]
> Você **não precisa construir o código**! O foco está em **usar a IA como sua parceira criativa**, transformando boas ideias e prompts em conceitos funcionais que simulam um produto real.

## 🪄 Etapas do Desafio

### 1. Saber o que Pedir é a Chave! Otimize seus Prompts!

Antes de pedir para a IA "criar um app", é importante definir com clareza o que você quer construir e por quê. Para isso, você vai criar um **PRD (Product Requirements Document)** simplificado, uma especificação que serve como _briefing_ para a IA entender sua ideia.

Um bom PRD deve descrever o problema, quem será beneficiado, as principais funcionalidades e o que você espera que a IA entregue. Use o modelo abaixo como ponto de partida e adapte conforme o seu estilo:

```txt
Gostaria que me ajudasse a revisar esse meu PRD(Product Requirements Document), pois pretendo usá-lo no Lovable para exercitar minhas skills de Vibe Coding.
Poderia me ajudar?
Como resposta me mande o PRD revisado e sisnteti-ze de forma didática os conceitos de Vibe Coding e PRD, pois ainda estou aprendendo sobre eles.

# Contexto
Quero criar um aplicativo de Organização de Finanças Pessoais que funcione por meio de conversas com o usuário.  
A ideia é facilitar o controle financeiro de forma simples e natural, sem formulários manuais ou planilhas complexas.

# Problema
Muitas pessoas desistem de controlar seus gastos porque os apps atuais exigem muita entrada manual e pouca personalização.  
Quero resolver isso com uma experiência de conversa e recomendações automáticas de economia.

# Público-Alvo
Pessoas que querem começar a organizar suas finanças de forma prática e sem complicação, principalmente iniciantes.

# Funcionalidades-Chave
1. Registrar gastos via chat em linguagem natural.  
2. Classificar automaticamente as transações.  
3. Definir e acompanhar metas financeiras.  
4. Receber dicas de economia do “Agente Financeiro”.  
5. Visualizar relatórios simples e personalizados.

# Entregável da IA
Gerar um plano de MVP com as principais telas, recursos necessários e um esboço de validação inicial.  
Usar tom educativo e linguagem acessível, em português.
```

Depois de preencher o modelo, use o Copilot Web para revisar e melhorar o seu prompt antes de ir ao Lovable. A ideia é lapidar o texto até que ele fique claro, direto e reflita exatamente a sua intenção.

> [!TIP]
> Pense no PRD/Prompt como “o briefing que a IA precisa para entender sua vibe”. Portanto, quanto mais claro e intencional for o texto, mais próximas do ideal serão as respostas da IA.
>
>

Entendendo o conceito de desig universal e aplicado ao PRD:
O que é Design Universal?
O Design Universal é o conceito de projetar produtos e ambientes para que sejam utilizáveis por todas as pessoas, na maior medida possível, sem a necessidade de adaptação ou design especializado.
Imagine uma rampa na calçada: ela foi feita para cadeirantes, mas ajuda a pessoa com carrinho de bebê, o idoso com mobilidade reduzida e o entregador com uma carga pesada. No mundo digital, o Design Universal segue lógica semelhante através de 7 princípios, focando em:

Flexibilidade: O app deve ser útil para quem prefere digitar ou quem prefere comandos de voz.

Simplicidade e Intuição: O uso deve ser fácil de entender, independentemente da experiência, conhecimento ou nível de concentração do usuário (perfeito para o seu público iniciante).

Informação Perceptível: O app deve comunicar informações de forma eficaz, usando contrastes de cores adequados e textos legíveis.

Tolerância ao Erro: Se o usuário digitar algo errado no chat, o app deve minimizar o impacto e ajudar a corrigir facilmente.

Adicionei uma nova seção específica para garantir que a IA (Lovable) siga essas diretrizes.

#### PRD Atualizado (Versão 2.0)
#### Título do Projeto: Finanças Flow

Visão: Gestão financeira natural, inclusiva e acessível para todos.

1. Objetivo e Valor
Criar um MVP de um assistente financeiro baseado em chat que remove barreiras técnicas e cognitivas, permitindo que qualquer pessoa organize suas finanças.

2. Premissa de Design: Design Universal
Acessibilidade Visual: Contrastes elevados (padrão WCAG), fontes de tamanho legível e ícones que complementam o texto (não dependa apenas de cores para passar informação).

Simplicidade Cognitiva: Linguagem clara, sem termos técnicos bancários complexos. O "Agente" deve falar como um amigo prestativo.

Navegação Consistente: Botões grandes e fáceis de clicar (target touch adequado para diferentes habilidades motoras).

3. Funcionalidades Detalhadas
Input Natural e Flexível: Aceitar diferentes formas de entrada (texto, números isolados, ou frases completas).

Dashboard de Leitura Rápida: Gráficos com legendas claras e suporte a leitores de tela.

Feedback Instantâneo: Sempre que o usuário registrar algo, o app deve confirmar visualmente e por texto o que foi entendido (ex: "Ok! Notei R$ 50 em Alimentação").

4. Requisitos Técnicos (Vibe Coding)
Stack: React, Tailwind CSS, Lucide Icons.

Componentes: Usar a biblioteca Radix UI (através do Shadcn) por já possuir componentes com acessibilidade nativa (Aria-labels).

Responsividade: O layout deve ser perfeito tanto em celulares antigos com telas pequenas quanto em desktops.

Como aplicar isso no Lovable (Exemplo de Prompt)
Para garantir que a "vibe" seja universal, você pode usar este prompt:

"Estou construindo o Finanças Flow. Quero que a interface siga os princípios do Design Universal. Isso significa que as cores devem ter alto contraste, os botões devem ser fáceis de clicar e o layout deve ser extremamente intuitivo para pessoas que não têm intimidade com tecnologia. Use componentes acessíveis do Shadcn/UI."

### 2. Explorando o Lovable na Prática

Com seu PRD pronto e revisado, é hora de colocar a IA em ação. Abra o Lovable, cole seu prompt completo e peça o plano inicial do MVP do seu aplicativo. Como o plano gratuito limita você a 5 interações por dia, seja estratégico:
- Faça perguntas diretas e construtivas, como “crie o fluxo de telas com base nas funcionalidades listadas” ou “gere uma versão resumida do plano de MVP”;
- Priorize clareza nas instruções para aproveitar ao máximo cada resposta;

Durante essa etapa, você pode orientar a IA para três entregas principais:
1. Agente Financeiro: defina o comportamento e o tom de voz de um consultor financeiro pessoal, alinhado ao público e objetivo do app.
2. Fluxo de Telas: peça à IA para gerar o fluxo conceitual de telas com base nas funcionalidades descritas no PRD, simulando a interação por conversa.
3. Plano de MVP: solicite um resumo das 5 funcionalidades principais, dos recursos necessários e um plano de validação inicial (como medir se o app cumpre seu propósito).

> [!TIP]
> Se preferir, você pode fazer tudo com o **Copilot**. O importante é exercitar a habilidade de transformar intenções em instruções claras e testar os limites da IA como parceira criativa.

#### Prompts utilizados no Lovable:

Etapa 1: O "Esqueleto" e a Vibe Visual
Nesta etapa, você define a identidade e a estrutura básica.

Prompt: "Quero criar um MVP de um app de finanças chamado 'Finanças Flow'. Use React, Tailwind CSS e Shadcn/UI. A interface deve ser baseada em Design Universal: cores de alto contraste (Slate-900 para texto, Blue-700 para destaques, Slate-50 para fundo), fontes com tamanho mínimo de 16px e botões com pelo menos 44px de altura. A tela principal deve ser um chat centralizado com um cabeçalho simples que mostre o 'Saldo Atual'."

Etapa 2: A Experiência de Conversa (Frontend)
Agora você dá vida à interação de chat, antes mesmo de ligar o banco de dados.

Prompt: "Agora, implemente a interface do chat. As mensagens do usuário devem aparecer à direita e as do 'Agente Financeiro' à esquerda. Adicione ícones da Lucide React para cada mensagem. Quando o usuário digitar um gasto, como 'Gastei 50 reais em pizza', simule uma resposta do agente confirmando: 'Entendido! Registrei R$ 50,00 em Alimentação'."

Etapa 3: Estrutura de Dados (Supabase)
Aqui você prepara o "cérebro" que vai guardar as informações.

Prompt: "Configure o banco de dados Supabase para este projeto. Preciso de uma tabela chamada transactions com as colunas: id, created_at, description (texto), amount (numérico), category (texto) e type (gasto ou ganho). Além disso, crie uma tabela goals para metas financeiras com title, target_amount e current_amount."

Etapa 4: Lógica de Extração com IA
Esta é a parte crucial do Vibe Coding: transformar linguagem natural em dados estruturados.

Prompt: "Implemente a lógica onde o chat processa a entrada do usuário. Use uma função para identificar o valor e a categoria no texto digitado. Se o usuário disser 'Recebi 3000 de salário', o app deve salvar na tabela transactions como um 'ganho'. Se disser 'Gasolina 200', deve salvar como 'gasto' na categoria 'Transporte'. Garanta que o Saldo Atual no topo da tela seja atualizado automaticamente."

Etapa 5: Dashboard e Relatórios Acessíveis
Adicionando a parte visual para o usuário acompanhar o progresso.

Prompt: "Crie uma aba ou seção de 'Relatórios'. Use gráficos simples (barras ou pizza) que sejam acessíveis para leitores de tela. O gráfico deve mostrar os gastos por categoria do mês atual. Adicione também uma seção de 'Metas' que mostre barras de progresso para as metas salvas no banco de dados."

Etapa 6: O Agente de Insights (Educação Financeira)
Finalizando com a funcionalidade de "Dicas".

Prompt: "Adicione um botão chamado 'Dica de Economia'. Quando clicado, o Agente Financeiro deve analisar as transações recentes e dar uma dica educativa personalizada em tom amigável, focada em ajudar iniciantes a economizar. Exemplo: 'Notei que você gastou bastante com delivery esta semana. Que tal tentar cozinhar em casa amanhã?'"

Imagem do resultado obtido durante os prompts de vibe coding:
<img width="1366" height="604" alt="app_financas_flow" src="https://github.com/user-attachments/assets/7328607e-34ee-444d-94ed-04091a731c3a" />

### 3. Entregando o Desafio na DIO

Resumo da aplicação desenvolvida:

📱 Finanças Flow - Funcionalidades do MVP
O Finanças Flow é um assistente financeiro inteligente projetado para ser simples, acessível e educativo. Abaixo estão as principais funcionalidades implementadas no MVP:

1. 💬 Registro por Linguagem Natural (Chat-First)
O que é: Em vez de formulários, o usuário registra gastos e ganhos conversando.

Como funciona: A IA interpreta frases como "Gastei 40 reais com Uber" ou "Caiu o salário de 3000" e extrai automaticamente o valor, a categoria e o tipo de transação.

Vantagem: Elimina a barreira da entrada manual complexa.

2. 🤖 Agente Financeiro Educativo
O que é: Um assistente proativo que analisa o comportamento de gastos.

Como funciona: Através de um botão de "Insights", o agente sugere dicas de economia personalizadas.

Vantagem: Transforma o app de um simples "extrato" em uma ferramenta de educação financeira.

3. 📊 Dashboard de Visão Geral (Acessível)
O que é: Um resumo visual do saldo e das despesas do mês.

Como funciona: Gráficos de alta legibilidade que mostram a distribuição dos gastos por categoria.

Vantagem: Permite entender a saúde financeira em segundos, seguindo diretrizes de Design Universal (alto contraste e leitura clara).

4. 🎯 Gestão de Metas Simplicada
O que é: Acompanhamento de objetivos financeiros (ex: Reserva de Emergência).

Como funciona: Barras de progresso visuais que mostram o quanto falta para atingir cada objetivo definido.

Vantagem: Motiva o usuário iniciante a manter o foco no longo prazo.

5. ♿ Design Universal e Acessibilidade
O que é: Interface pensada para todos os tipos de usuários.

Como funciona: * Botões grandes e áreas de toque otimizadas (mínimo 44px).

Uso de ícones + texto para facilitar a compreensão.

Paleta de cores com alto contraste para garantir legibilidade.

🛠️ Tecnologias Utilizadas
Frontend: React + Tailwind CSS (Vibe Coding via Lovable).

Componentes: Shadcn/UI & Radix UI (Acessibilidade nativa).

Banco de Dados: Supabase.

Ícones: Lucide React.

> [!TIP]
> Publique seu repositório e compartilhe o link na plataforma da DIO! Sua entrega é a prova de que você domina o raciocínio de Vibe Coding, mesmo sem escrever uma única linha de código.

## 💬 Conclusão

Vibe Coding é sobre clareza, curiosidade e criatividade, não sobre perfeição técnica. O verdadeiro objetivo aqui é aprender a pensar junto com a IA, transformando ideias em conceitos reais e enxergando a tecnologia como uma extensão do seu raciocínio criativo. Cada interação é um experimento, quanto mais clara for sua intenção, mais surpreendente será o resultado.
