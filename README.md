# ATS Flow

## O Desafio Proposto

No atual mercado de tecnologia, o volume de candidaturas para vagas de emprego cresceu exponencialmente. Para lidar com isso, as empresas utilizam sistemas **ATS (Applicant Tracking Systems)** que filtram currículos de forma automatizada com base em palavras-chave e formatação. 

O grande problema enfrentado pelos candidatos é o "buraco negro" dos processos seletivos: currículos altamente qualificados são descartados simplesmente por não estarem otimizados para a leitura do robô ou por faltarem jargões específicos descritos na vaga. Adaptar o currículo manualmente para cada aplicação é um processo lento, tedioso e suscetível a erros.

## A Solução

Esta aplicação web foi desenvolvida do zero para automatizar e democratizar a otimização de currículos. Através de um motor de *Matchmaking* inteligente, a plataforma cruza os dados do currículo do usuário com os requisitos da vaga (extraídos via URL ou texto), gerando um diagnóstico preciso e reformulando o documento para ser 100% *ATS-Friendly*. 

O objetivo é maximizar a taxa de conversão em entrevistas, garantindo que a formatação e a semântica do documento passem pelos filtros automatizados sem perder a essência da trajetória profissional do candidato.

---

## Funcionalidades Principais

*  **Extrator de Vagas Automatizado:** Insira a URL da vaga (LinkedIn, Gupy, etc.) e o sistema fará o *scraping* automático dos requisitos, título e empresa.
*  **Motor de Matchmaking (Fit Score):** Análise de compatibilidade de 0 a 100%, dividida em 4 pilares visuais:
  * *Hard Skills & Ferramentas*
  * *Experiência e Senioridade*
  * *Formação e Certificações*
  * *Soft Skills e Idiomas*
*  **Otimização Orientada por IA:** Reescreve seções do currículo para incluir palavras-chave de forma orgânica (sem *keyword stuffing*).
*  **Diff Checker Visual:** Uma interface de comparação lado a lado que destaca em verde as adições e melhorias feitas pelo motor de IA no texto original.
*  **Gerador de PDF ATS-Friendly:** Exportação do currículo em layouts de coluna única, tipografia limpa e sem elementos gráficos que quebrem os parsers de recrutamento.
*  **Gerador de Cover Letter:** Criação automatizada e contextualizada de cartas de apresentação baseadas na vaga específica e no perfil do candidato.

---

## UI/UX e Design System

A interface foi projetada com foco absoluto em acessibilidade, usabilidade e estética moderna.

* **Design System:** [ShadCN UI](https://ui.shadcn.com/)
* **Identidade Visual:** Paleta futurista e corporativa centrada no **Roxo Imperial**, complementada por tons escuros e efeitos de *glassmorphism*.
* **Interatividade:** Animações fluidas de transição e feedback visual constante (toasts, barras de progresso, gauges circulares).

---

## Como Acessar o Projeto

**Link para a aplicação**: https://resume-glowing.lovable.app/

---

_Aplicação gerada a partir do Lovable e usando engenharia de prompt._
