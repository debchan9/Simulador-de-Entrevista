# Simulador-de-Entrevista

Desafio de Projeto DIO **"IA Entrevistador: Seu Simulador Inteligente de Entrevistas"** do curso **"CAIXA - Inteligência Artificial na Prática da DIO"**. O desafio não estava muito claro na aula, porém no vídeo o instrutor criou um simulador de entrevistas por meio de instruções no chat do **Microsoft Copilot Web**, por isso criei um com base na criação dele e expandi com novos recursos.

---

## 🎯 Objetivo

Construir um simulador de entrevistas estruturadas para vagas de tecnologia (ou outras áreas), utilizando o Copilot como entrevistador técnico. O simulador conduz perguntas em sequência, gera um resumo analítico da vaga e pode ser usado para treinar candidatos em entrevistas reais.

---

## 📝 Instruções criadas para o Copilot Web:

```markdown
Você é um entrevistador técnico especializado em vagas de Tecnologia.

SEU OBJETIVO:
Conduzir uma entrevista estruturada sobre uma vaga, fazendo perguntas uma por vez sobre 3 temas. Após cobrir todos os temas e receber confirmação do usuário, gerar um resumo analítico.
IMPORTANTE: Faça apenas 1 pergunta por vez. Aguarde a resposta antes de prosseguir.

SEQUÊNCIA DE PERGUNTAS (nessa ordem):
1. OBJETIVO: "Qual é o título da vaga e qual o propósito principal desse cargo?"
2. TEMPO DE EXPERIÊNCIA: "Qual o tempo de experiência esperado e por quê?"
3. SOFT SKILLS: "Quais comportamentos ou atitudes são mais valorizados?"

REGRAS:
- Nunca mais de 1 pergunta por vez
- Só gere o resumo após confirmação explícita

INICIE COM:
"Olá! Vou fazer perguntas sobre a vaga que você está estruturando. Para começar: Qual é o título da vaga e qual o propósito principal desse cargo?"

```
## 📌 Exemplo de uso

Inseri o prompt acima no chat do Copilot e respondi o seguinte:

>O título é Analista de Dados, e o propósito é transformar dados em conhecimento que agregue valor às organizações.

>É esperado 1 a 4 anos de experiência na indústria, pois isso garante vivência prática, e formação acadêmica avançada (mestrado ou doutorado) é considerada um diferencial.

>Soft skills valorizadas: pensamento crítico, curiosidade, comunicação eficaz e trabalho em equipe.

>Em seguida, após o Copilot gerar o resumo da vaga, escrevi o seguinte prompt para testar o Copilot como "Entrevistador":

>Você deve me entrevistar como se eu fosse uma candidata real a vaga que você acabou de dar um resumo.

>Em seguida, o Copilot conduziu a entrevista simulada, gerou feedback personalizado, criou flashcards de estudo e estruturou perguntas no formato CAR (Desafio → Ação → Resultado) para treinar respostas.

## 🚀 Expansões realizadas

Além da entrevista estruturada, adaptei o simulador para incluir:

>Feedback personalizado sobre pontos fortes e áreas de melhoria.

>Flashcards de estudo para treinar respostas em entrevistas.

>Simulação prática com perguntas no formato CAR.

Esses recursos tornam a ferramenta útil não apenas para estruturar vagas, mas também para treinar candidatos e preparar entrevistas reais.

## 📂 Estrutura do Projeto

>README.md → Documentação do projeto.

>Prompts utilizados → Instruções para o Copilot Web.

>Exemplos de entrevistas → Respostas simuladas.

>Flashcards → Material de estudo para candidatos.

## 💡 Conclusão
Este projeto demonstra como o Microsoft Copilot Web pode ser usado como um simulador inteligente de entrevistas, apoiando tanto recrutadores na estruturação de vagas quanto candidatos na preparação para processos seletivos. Com os recursos de resumo de perfil, feedback e flashcards, o simulador se torna uma ferramenta prática para autoavaliação e estudo contínuo.

---
