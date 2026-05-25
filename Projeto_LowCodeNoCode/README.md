# Projeto Módulo 3 – Low Code / No Code / Vibecode 🚀

## 📌 Desafio Escolhido
O desafio selecionado pelo grupo foi o desenvolvimento de um **Chatbot de Atendimento Simples**. O objetivo é criar uma aplicação funcional contendo um bot configurado para responder a perguntas frequentes de uma loja fictícia (como horários de funcionamento, canais de atendimento e principais contatos de suporte), garantindo uma resposta visual imediata e intuitiva para o utilizador.

---

## 🖥️ Protótipo
* **Link de Desenvolvimento (Bubble):** [Acessar Editor do Bubble](https://bubble.io/page?id=roneyprofissional11&version=test&tab=Design&name=index&ai_generated=true)
* **Funcionamento:** O utilizador acede à página principal da aplicação desenvolvida no Bubble, onde interage com uma interface de chat simulada. Ao clicar nos botões de opções de perguntas frequentes (FAQs), o sistema exibe de forma instantânea as respostas correspondentes cadastradas no fluxo.
> **Nota:** As capturas de tela (prints) demonstrando o design gerado pela IA e o funcionamento do fluxo de atendimento encontram-se organizadas na pasta `/docs` deste repositório.

---

## ⚙️ Plataforma Utilizada
* **Nome da plataforma:** Bubble (com assistente de IA integrado).
* **Justificativa da escolha:** O grupo optou por integrar a abordagem de **Vibecode** (desenvolvimento auxiliado por Inteligência Artificial). A escolha justifica-se pelo facto de o Bubble permitir a criação rápida de interfaces responsivas e robustas através do seu assistente de IA. Isso combinou a facilidade do arrasta-e-solta (*No Code*) com a flexibilidade de gerar o esqueleto visual através de prompts, possibilitando a entrega de um MVP (Produto Mínimo Viável) visualmente impressionante dentro do prazo restrito da aula prática.

---

## ✅ Vantagens Identificadas
Durante a atividade e análise da abordagem adotada, identificámos as seguintes vantagens:
1. **Prototipagem Ágil com IA (Vibecode):** O uso da ferramenta de IA integrada do Bubble permitiu gerar o esqueleto visual e o layout da página de atendimento em poucos segundos a partir de um comando de texto.
2. **Interface Rica e Responsiva:** A plataforma entrega componentes visuais modernos prontos para uso, reduzindo drasticamente o tempo que seria gasto com estilização manual (CSS).
3. **Padrão CRUD e Expansibilidade:** Diferente de ferramentas restritas a chats, o Bubble oferece um banco de dados integrado que permite, no futuro, registar o histórico de conversas e leads de forma simples.

---

## ⚠️ Limitações Encontradas
Com base na análise crítica da ferramenta no laboratório, mapeámos as seguintes restrições técnicas:
1. **Dificuldades em Customizações Muito Específicas:** Embora o assistente de IA gere a estrutura inicial rapidamente, ajustar detalhes finos de layout e comportamentos lógicos complexos exige um entendimento profundo das propriedades nativas da plataforma.
2. **Curva de Aprendizagem Inicial:** O Bubble possui uma interface rica em recursos, o que torna a configuração de workflows de backend mais demorada e complexa para iniciantes se comparada a ferramentas focadas exclusivamente em bots (como o Typebot).
3. **Dependência de Plataforma (Lock-in Tecnológico) e Menor Controle:** O ecossistema construído fica totalmente hospedado nos servidores do Bubble, limitando o controlo direto sobre a performance, segurança e tornando uma eventual migração para código puro um processo de reconstrução do zero.

---

## 📚 Reflexão Crítica
Para contornar a complexidade inicial dos workflows e as limitações de customização, o grupo adotou a estratégia de focar numa abordagem de "função sobre forma", priorizando uma experiência de utilizador (UX) limpa e direta. Utilizámos as lógicas nativas mais simples do Bubble para a troca de estados das mensagens na tela. 

Além disso, para mitigar o risco de *lock-in* tecnológico e garantir a portabilidade dos dados no futuro, planeámos a estruturação do banco de dados de modo a permitir a exportação simples dos logs de atendimento para formatos universais (como CSV/JSON).

---

## 👥 Colaboração
A divisão de responsabilidades garantiu a participação ativa, o trabalho coletivo e o profissionalismo de ambos os integrantes:
* **Roney Costa:** Responsável pela engenharia de prompt no assistente de IA do Bubble, refinamento do design de interface e configuração da lógica dos botões de FAQ.
* **Álefe de Jesus:** Responsável pela estruturação do repositório no GitHub, captura das evidências visuais (prints para a pasta `/docs`), testes de funcionamento do protótipo e elaboração da documentação final.

---

## 📝 Registro da Aula
* **Data:** 11/05/2026  
* **Atividade:** Discussão crítica + mini-projeto de aplicação  
* **Local:** Laboratório de informática / Quadro branco  
* **Professor(a):** Kadidja Valéria  
* **Instituição:** UDF Centro Universitário  

---

## 🚀 Próximos Passos
Para a evolução deste protótipo visando o **Projeto Final da Unidade 3**, o grupo planeia implementar as seguintes melhorias técnicas:

* **Integração Real com IA (OpenAI API):** Substituir as respostas estáticas de FAQ por uma integração direta com a API do ChatGPT através do ecossistema do Bubble, permitindo que o chatbot responda a dúvidas complexas e interprete a linguagem natural dos utilizadores.
* **Criação de Painel Administrativo (Dashboard):** Desenvolver uma área restrita para os gestores visualizarem as métricas de atendimento (número de conversas, perguntas mais frequentes) e gerirem o histórico de interações guardado no banco de dados.
* **Mecanismos de Segurança e Validação:** Implementar validações nos campos de entrada do chat (como reCAPTCHA e sanitização de dados) para evitar ataques de injeção de scripts e envios em massa (spam).
