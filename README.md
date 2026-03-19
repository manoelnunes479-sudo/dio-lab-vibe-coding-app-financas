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


```txt
# PRD - Aplicativo Conversacional de Finanças Pessoais

## 📌 Contexto
O aplicativo de Organização de Finanças Pessoais será baseado em interações por meio de **conversas naturais**.  
A proposta é substituir formulários e planilhas complexas por um diálogo simples e acessível, onde o usuário conversa com um **Agente Financeiro** para registrar gastos, definir metas e receber recomendações.

---

## 🎯 Problema
Muitos usuários abandonam aplicativos de finanças porque exigem entradas manuais extensas e pouca personalização.  
O objetivo é oferecer uma experiência fluida e personalizada, com registro automático e dicas práticas de economia.

---

## 👥 Público-Alvo
- Pessoas iniciantes no controle financeiro.  
- Usuários que desejam praticidade sem lidar com planilhas.  
- Jovens adultos e profissionais que buscam orientação simples para organizar gastos.  

---

## 🔑 Funcionalidades-Chave
1. **Registro de gastos via chat**  
   - Usuário informa em linguagem natural: “Gastei R$50 no mercado”.  
   - O sistema interpreta e registra automaticamente.  

2. **Classificação automática de transações**  
   - Identificação de categoria (alimentação, transporte, lazer, etc.).  
   - Sugestão de ajustes caso a classificação esteja incorreta.  

3. **Metas financeiras**  
   - Definição de objetivos como “economizar R$200 este mês”.  
   - Acompanhamento automático do progresso.  

4. **Agente Financeiro**  
   - Recomendações personalizadas de economia.  
   - Alertas quando gastos ultrapassarem limites.  

5. **Relatórios simples e personalizados**  
   - Visualização em gráficos claros e acessíveis.  
   - Resumo semanal/mensal enviado pelo chat.  

---

## ⚙️ Requisitos Técnicos
- **Plataforma**: Android e iOS (via Flutter ou React Native).  
- **Banco de dados**: SQLite local com sincronização opcional em nuvem (Firebase).  
- **Processamento de linguagem natural (NLP)**: para interpretar mensagens de texto.  
- **Segurança**: criptografia de dados e autenticação segura.  

---

## 📊 Métricas de Sucesso
- Taxa de retenção após 3 meses.  
- Frequência de uso semanal.  
- Percentual de usuários que definem metas.  
- Feedback positivo em avaliações (nota média > 4,2).  

---

## 🚀 MVP (Produto Mínimo Viável)

### Telas principais
- **Tela de Conversa**: interface central para interação com o Agente Financeiro.  
- **Dashboard simplificado**: resumo de saldo, gastos e metas.  
- **Tela de Relatórios básicos**: gráficos simples por categoria.  

### Recursos necessários
- Motor de NLP para interpretar mensagens.  
- Cadastro de transações com categorização automática.  
- Definição e acompanhamento de metas.  
- Relatórios básicos integrados ao chat.  

### Validação inicial
- Testes com grupo piloto de usuários iniciantes.  
- Coleta de feedback sobre clareza da conversa e utilidade das recomendações.  
- Ajustes rápidos com base em interações reais.  

---

## 📝 Conclusão
Este PRD define um aplicativo inovador de finanças pessoais, centrado em **conversas naturais**.  
O MVP foca em registro via chat, categorização automática, metas e relatórios simples, garantindo uma experiência acessível e educativa para quem deseja começar a organizar suas finanças sem complicação.
```



### 2. Explorando o Lovable na Prática

1.Personalidade do Agente Financeiro
Recomendo um meio-termo: um amigo que entende do assunto — tom leve e acessível, mas com credibilidade.

Durante essa etapa, você pode orientar a IA para três entregas principais:
1. Agente Financeiro: defina o comportamento e o tom de voz de um consultor financeiro pessoal, alinhado ao público e objetivo do app.
2. Fluxo de Telas: peça à IA para gerar o fluxo conceitual de telas com base nas funcionalidades descritas no PRD, simulando a interação por conversa.
3. Plano de MVP: solicite um resumo das 5 funcionalidades principais, dos recursos necessários e um plano de validação inicial (como medir se o app cumpre seu propósito).

   Aspecto	Abordagem
Tom	Informal mas informado — usa "você", emojis moderados, sem jargão
Celebração	Elogia conquistas ("Parabéns, você economizou 20%! 🎉")
Alerta	Avisa sem culpa ("Seus gastos com delivery subiram — quer ver alternativas?")
Dicas	Sempre com contexto real ("Você gasta R$350/mês em alimentação fora. Cozinhar 2x/semana economiza R$180")
Linguagem	Curta, com negrito nos números importantes

   2.Jornada do Usuário e Fluxo de Telas
Filosofia: Chat como hub central
O chat não é "mais uma tela" — é a tela principal. As outras telas são visualizações complementares dos dados que o usuário registra conversando.

Fluxo típico do dia a dia:
Usuário abre o app → Chat aparece
Digita "gastei 35 no almoço" → Agente confirma com categoria
No fim do dia, desliza para Dashboard → vê o resumo
Agente proativamente sugere: "Você já gastou 80% da meta de alimentação"

mkd
3.# Plano de MVP - Aplicativo Conversacional de Finanças Pessoais

## 🔑 Funcionalidades Essenciais
1. **Registro de gastos via chat em linguagem natural**  
   - Usuário informa: “Gastei R$50 no mercado” e o sistema interpreta automaticamente.  

2. **Classificação automática de transações**  
   - O app identifica a categoria (alimentação, transporte, lazer) sem esforço manual.  

3. **Definição e acompanhamento de metas financeiras**  
   - Exemplo: “Quero economizar R$200 este mês” → acompanhamento automático.  

4. **Agente Financeiro com dicas personalizadas**  
   - Recomendações simples e educativas para reduzir gastos e melhorar hábitos.  

5. **Relatórios básicos e personalizados**  
   - Gráficos claros e resumos semanais/mensais enviados pelo chat.  

---

## ⚙️ Recursos Técnicos Indispensáveis
- **Motor de NLP (Processamento de Linguagem Natural)** para interpretar mensagens.  
- **Banco de dados local (SQLite)** com opção de sincronização em nuvem (Firebase).  
- **Framework multiplataforma (Flutter ou React Native)** para Android/iOS.  
- **Autenticação segura** (login por e-mail ou redes sociais).  
- **Camada de segurança** com criptografia de dados e backup automático.  

---

## 📊 Validação Inicial
- **Testes com grupo piloto** de usuários iniciantes em finanças pessoais.  
- **Métricas de uso**: frequência de registros de gastos, número de metas criadas, taxa de engajamento semanal.  
- **Feedback qualitativo**: entrevistas rápidas sobre clareza da conversa e utilidade das recomendações.  
- **Indicadores de sucesso**: retenção após 30 dias, satisfação média > 4 em escala de 1 a 5.  

---

## 📝 Conclusão
O MVP deve entregar uma experiência simples e prática, centrada em conversas naturais.  
Com registro automático, categorização inteligente, metas e relatórios básicos, será possível validar se o app realmente ajuda os usuários a organizar suas finanças sem complicação.

### 3. Entregando o Desafio na DIO

# 📌 Resumo do App
O aplicativo é um **organizador de finanças pessoais baseado em conversas**.  
Em vez de formulários ou planilhas, o usuário interage com um **Agente Financeiro virtual** que entende linguagem natural, registra gastos automaticamente, sugere categorias, ajuda a definir metas e oferece dicas de economia.  
O app também gera relatórios simples e personalizados, tornando o controle financeiro mais acessível e prático para iniciantes.

---

# 🔎 Reflexão sobre o Processo

## ✅ O que funcionou bem
- Clareza da proposta: a ideia de usar conversas como interface central se destacou e trouxe simplicidade.  
- Definição das funcionalidades essenciais: conseguimos priorizar cinco pontos-chave para o MVP sem dispersar esforços.  
- Tom educativo e acessível: o PRD e o plano de MVP foram estruturados em linguagem clara, alinhada ao público-alvo.  
- Visão de evolução: já surgiram ideias de expansão futura (integração com bancos, gamificação, relatórios avançados).

## ⚠️ O que não funcionou como esperado
- Detalhamento do fluxo de interação: ainda falta um esboço visual ou narrativo mais completo da jornada do usuário.  
- Validação prática: o plano de testes piloto está definido, mas ainda não há métricas específicas de engajamento conversacional (ex.: tempo médio de interação, satisfação com respostas do agente).  
- Personalização profunda: o Agente Financeiro foi descrito, mas o tom de voz e estilo de comunicação ainda precisam ser ajustados para diferentes perfis de usuários.

---

# 📝 Conclusão
Esse balanço mostra que já existe uma base sólida para o MVP, mas o próximo passo é **refinar a experiência conversacional** e pensar em como medir a satisfação do usuário além das métricas tradicionais.

> [!TIP]
> Publique seu repositório e compartilhe o link na plataforma da DIO! Sua entrega é a prova de que você domina o raciocínio de Vibe Coding, mesmo sem escrever uma única linha de código.

## 💬 Conclusão

Vibe Coding é sobre clareza, curiosidade e criatividade, não sobre perfeição técnica. O verdadeiro objetivo aqui é aprender a pensar junto com a IA, transformando ideias em conceitos reais e enxergando a tecnologia como uma extensão do seu raciocínio criativo. Cada interação é um experimento, quanto mais clara for sua intenção, mais surpreendente será o resultado.
