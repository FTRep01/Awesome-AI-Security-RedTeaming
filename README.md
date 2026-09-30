# 🤖 Awesome-AI-Security-RedTeaming

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
[![Stars](https://img.shields.io/github/stars/FTRep01/Awesome-AI-Security-RedTeaming?style=social)](https://github.com/FTRep01/Awesome-AI-Security-RedTeaming/stargazers)
[![Forks](https://img.shields.io/github/forks/FTRep01/Awesome-AI-Security-RedTeaming?style=social)](https://github.com/FTRep01/Awesome-AI-Security-RedTeaming/network/members)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](#-como-contribuir)
[![Last Commit](https://img.shields.io/github/last-commit/FTRep01/Awesome-AI-Security-RedTeaming)](https://github.com/FTRep01/Awesome-AI-Security-RedTeaming/commits/main)
[![Issues](https://img.shields.io/github/issues/FTRep01/Awesome-AI-Security-RedTeaming)](https://github.com/FTRep01/Awesome-AI-Security-RedTeaming/issues)
[![Made with Markdown](https://img.shields.io/badge/Made%20with-Markdown-1f425f.svg)](https://daringfireball.net/projects/markdown/)

Uma coleção curada de **ferramentas, frameworks, papers, datasets e metodologias** para segurança de Inteligência Artificial e Modelos de Linguagem (LLMs), cobrindo as principais frentes do **AI Security**: **Red Teaming de LLMs**, **Prompt Injection e Jailbreaking**, **Machine Learning Adversarial**, **Guardrails e Content Moderation**, **Governança e Frameworks de Risco**, **Vazamento de Dados e Privacidade em Modelos** e **Avaliação de Segurança (Benchmarks)**.

O objetivo deste repositório é servir como um hub central de referência para pesquisadores de segurança, engenheiros de ML/AI Safety e times de red team que precisam avaliar, atacar (de forma autorizada) e defender sistemas baseados em IA — com foco em ferramentas ativas, metodologias reconhecidas pela comunidade e aplicabilidade prática em pipelines reais de desenvolvimento de produtos com IA.

---

## 📑 Sumário

1. [Introdução e Objetivo do Repositório](#-introdução-e-objetivo-do-repositório)
2. [Fundamentos, Frameworks e Modelos de Risco](#-fundamentos-frameworks-e-modelos-de-risco)
3. [OWASP Top 10 para LLMs e Aplicações Generativas](#-owasp-top-10-para-llms-e-aplicações-generativas)
4. [Ferramentas de Red Teaming para LLMs](#-ferramentas-de-red-teaming-para-llms)
5. [Prompt Injection e Jailbreaking](#-prompt-injection-e-jailbreaking)
6. [Machine Learning Adversarial (Adversarial ML)](#-machine-learning-adversarial-adversarial-ml)
7. [Guardrails, Moderação e Filtragem de Conteúdo](#-guardrails-moderação-e-filtragem-de-conteúdo)
8. [Privacidade, Vazamento de Dados e Model Extraction](#-privacidade-vazamento-de-dados-e-model-extraction)
9. [Benchmarks e Avaliação de Segurança](#-benchmarks-e-avaliação-de-segurança)
10. [Papers e Leituras Fundamentais](#-papers-e-leituras-fundamentais)
11. [Labs, CTFs e Ambientes de Prática](#-labs-ctfs-e-ambientes-de-prática)
12. [Exemplos de Pipelines de AI Security](#-exemplos-de-pipelines-de-ai-security)
13. [Como Contribuir](#-como-contribuir)

---

## 🎯 Introdução e Objetivo do Repositório

O **Awesome-AI-Security-RedTeaming** reúne, de forma organizada, as ferramentas, frameworks e referências mais relevantes para incorporar segurança em cada etapa do ciclo de vida de sistemas de IA — do design do modelo à aplicação em produção com usuários reais. Cada seção cobre uma frente distinta da segurança de IA, permitindo que o leitor navegue diretamente para o tópico de interesse e estruture sua própria trilha de estudo ou avaliação de segurança.

Critérios de inclusão: manutenção ativa (ou robustez consolidada no meio acadêmico/mercado), aplicabilidade prática em LLMs e/ou sistemas de ML tradicionais, adoção pela comunidade de AI Safety/Security e valor comprovado em avaliações reais de risco.

> ⚠️ **Aviso legal:** As ferramentas de red teaming e ataque adversarial listadas devem ser usadas **apenas em modelos próprios, ambientes de teste autorizados ou programas de bug bounty explícitos**. Testar modelos de terceiros sem autorização pode violar termos de serviço e legislações aplicáveis. Este repositório tem finalidade educacional e de fortalecimento defensivo (blue team/AI safety).

---

## 📚 Fundamentos, Frameworks e Modelos de Risco

Referências para estruturar um programa de segurança de IA do zero.

- **[NIST AI Risk Management Framework (AI RMF)](https://www.nist.gov/itl/ai-risk-management-framework)** 📋
  Framework do NIST para mapear, medir e gerenciar riscos de sistemas de IA ao longo do ciclo de vida.

- **[MITRE ATLAS (Adversarial Threat Landscape for AI Systems)](https://atlas.mitre.org/)** 🗺️
  Base de conhecimento de táticas e técnicas adversariais contra sistemas de IA, no mesmo estilo do MITRE ATT&CK.

- **[Google Secure AI Framework (SAIF)](https://safety.google/cybersecurity-advancements/saif/)** 🔒
  Framework do Google com controles de segurança recomendados para o desenvolvimento e implantação responsável de IA.

- **[Microsoft AI Red Team Guidance](https://learn.microsoft.com/en-us/security/ai-red-team/)** 🔵
  Documentação da Microsoft sobre metodologia, lições aprendidas e planejamento de exercícios de red team em IA.

---

## 🛡️ OWASP Top 10 para LLMs e Aplicações Generativas

Referências específicas da OWASP para riscos em sistemas baseados em modelos de linguagem.

- **[OWASP Top 10 for LLM Applications](https://owasp.org/www-project-top-10-for-large-language-model-applications/)** 🔟
  Lista das dez principais categorias de risco em aplicações LLM, incluindo prompt injection, vazamento de dados sensíveis e negação de serviço de modelo.

- **[OWASP AI Security & Privacy Guide](https://owasp.org/www-project-ai-security-and-privacy-guide/)** ✅
  Guia complementar da OWASP com controles de segurança e privacidade para times que projetam e implantam soluções de IA.

- **[OWASP Machine Learning Security Top 10](https://owasp.org/www-project-machine-learning-security-top-10/)** 🎯
  Lista equivalente da OWASP focada em riscos de segurança em sistemas de Machine Learning tradicionais (não apenas LLMs).

---

## 🧪 Ferramentas de Red Teaming para LLMs

Frameworks para testar sistematicamente a robustez e segurança de modelos de linguagem.

- **[Garak](https://github.com/NVIDIA/garak)** 🔍
  Scanner de vulnerabilidades para LLMs mantido pela NVIDIA, com dezenas de "probes" para jailbreak, toxicidade, vazamento de dados e mais.

- **[PyRIT (Python Risk Identification Tool)](https://github.com/Azure/PyRIT)** ⚔️
  Framework de red teaming automatizado da Microsoft para identificar riscos em sistemas generativos de IA.

- **[Promptfoo](https://github.com/promptfoo/promptfoo)** 🧵
  Ferramenta de teste e avaliação de prompts e modelos, com suporte a red teaming automatizado e detecção de vulnerabilidades comuns de LLM.

- **[Giskard](https://github.com/Giskard-AI/giskard)** 🐢
  Framework open source de testes de qualidade e segurança para modelos de ML e LLMs, com detecção automática de vieses e vulnerabilidades.

- **[DeepTeam](https://github.com/confident-ai/deepteam)** 🛡️
- **[Darkmoon](https://github.com/ASCIT31/Dark-Moon)** 🌑
  Plataforma open source (GPL-3.0) de pentest autônomo com IA que também executa red teaming de LLMs (OWASP Top 10 para LLMs), orquestrando agentes especialistas e ferramentas ofensivas via MCP e comprovando cada achado com um exploit real.
  Framework de red teaming para LLMs focado em simular ataques adversariais e avaliar riscos de forma programática.

---

## 💉 Prompt Injection e Jailbreaking

Recursos e ferramentas específicas sobre a principal classe de ataque contra aplicações baseadas em LLM.

- **[Rebuff](https://github.com/protectai/rebuff)** 🛡️
  Ferramenta de detecção de prompt injection em múltiplas camadas, combinando heurísticas, modelos e canários.

- **[LLM Guard](https://github.com/protectai/llm-guard)** 🔐
  Toolkit de segurança para aplicações LLM com scanners de entrada e saída, incluindo detecção de prompt injection e dados sensíveis.

- **[Vigil-LLM](https://github.com/deadbits/vigil-llm)** 👁️
  Framework de detecção de prompt injection e jailbreak com múltiplos scanners e suporte a análise de embeddings.

- **[Simon Willison's Prompt Injection Explained](https://simonwillison.net/series/prompt-injection/)** 📖
  Série de artigos de referência que documentou e popularizou o conceito de prompt injection em aplicações com LLMs.

---

## 🧬 Machine Learning Adversarial (Adversarial ML)

Bibliotecas para gerar e estudar exemplos adversariais contra modelos de Machine Learning clássicos e de visão computacional.

- **[Adversarial Robustness Toolbox (ART)](https://github.com/Trusted-AI/adversarial-robustness-toolbox)** 🧠
  Biblioteca da Linux Foundation AI com implementações de ataques e defesas adversariais para diversos tipos de modelo (imagem, tabular, áudio).

- **[CleverHans](https://github.com/cleverhans-lab/cleverhans)** 😈
  Uma das primeiras bibliotecas open source para construir exemplos adversariais e avaliar a robustez de modelos de ML.

- **[Foolbox](https://github.com/bethgelab/foolbox)** 🦊
  Biblioteca Python para criação de ataques adversariais contra modelos de deep learning, com foco em rapidez e comparabilidade entre ataques.

- **[TextAttack](https://github.com/QData/TextAttack)** ✍️
  Framework para geração de ataques adversariais, aumento de dados e treinamento adversarial especificamente em modelos de NLP.

---

## 🚧 Guardrails, Moderação e Filtragem de Conteúdo

Ferramentas para impor limites de segurança e comportamento em aplicações com IA generativa.

- **[NeMo Guardrails](https://github.com/NVIDIA/NeMo-Guardrails)** 🚦
  Toolkit da NVIDIA para adicionar guardrails programáveis a aplicações conversacionais baseadas em LLM.

- **[Guardrails AI](https://github.com/guardrails-ai/guardrails)** 🧱
  Framework para validar e corrigir saídas de LLMs contra especificações estruturadas, reduzindo riscos de conteúdo indevido.

- **[LangKit](https://github.com/whylabs/langkit)** 📊
  Toolkit de extração de métricas de segurança e qualidade de texto (toxicidade, sentimento, injeção) para monitoramento de LLMs em produção.

- **[Presidio](https://github.com/microsoft/presidio)** 🕵️
  Ferramenta da Microsoft para detecção e anonimização de dados sensíveis (PII) em texto, aplicável a pipelines de entrada/saída de LLMs.

---

## 🔓 Privacidade, Vazamento de Dados e Model Extraction

Referências sobre ataques que visam extrair dados de treinamento ou replicar modelos.

- **[TensorFlow Privacy](https://github.com/tensorflow/privacy)** 🔐
  Biblioteca para treinar modelos com privacidade diferencial, mitigando riscos de memorização e vazamento de dados de treino.

- **[ML Privacy Meter](https://github.com/privacytrustlab/ml_privacy_meter)** 📏
  Ferramenta acadêmica para quantificar riscos de vazamento de privacidade em modelos de Machine Learning, incluindo ataques de inferência de associação.

- **[Extracting Training Data from Large Language Models (paper)](https://arxiv.org/abs/2012.07805)** 📄
  Paper seminal do Google/Stanford demonstrando extração de dados de treinamento memorizados em LLMs.

---

## 📊 Benchmarks e Avaliação de Segurança

Conjuntos de dados e benchmarks para medir a robustez e segurança de modelos de forma padronizada.

- **[HarmBench](https://github.com/centerforaisafety/HarmBench)** 📐
  Framework padronizado de avaliação de red teaming automatizado e robustez contra ataques em LLMs.

- **[AdvBench](https://github.com/llm-attacks/llm-attacks)** 🎯
  Dataset e código associados ao paper de ataques adversariais universais e transferíveis contra LLMs alinhados.

- **[TruthfulQA](https://github.com/sylinrl/TruthfulQA)** ❓
  Benchmark para medir a propensão de modelos de linguagem a gerar respostas falsas ou enganosas.

- **[DecodingTrust](https://github.com/AI-secure/DecodingTrust)** 🧭
  Benchmark abrangente de confiabilidade de LLMs, cobrindo toxicidade, viés, privacidade e robustez adversarial.

---

## 📄 Papers e Leituras Fundamentais

Trabalhos acadêmicos de referência para entender a fundo os riscos de segurança em IA.

- **[Universal and Transferable Adversarial Attacks on Aligned Language Models](https://arxiv.org/abs/2307.15043)** 📄
  Paper que introduziu ataques de sufixo adversarial (GCG) capazes de contornar alinhamento de segurança em múltiplos LLMs.

- **[Not what you've signed up for: Compromising LLMs via Indirect Prompt Injection](https://arxiv.org/abs/2302.12173)** 📄
  Um dos primeiros papers a formalizar e demonstrar ataques de prompt injection indireta em aplicações com LLMs.

- **[Jailbroken: How Does LLM Safety Training Fail?](https://arxiv.org/abs/2307.02483)** 📄
  Análise sistemática de por que técnicas de jailbreak conseguem contornar o treinamento de segurança de LLMs.

---

## 🎓 Labs, CTFs e Ambientes de Prática

Ambientes gamificados e desafios para desenvolver habilidades práticas de AI red teaming.

- **[Gandalf (Lakera)](https://gandalf.lakera.ai/)** 🧙
  Jogo interativo onde o objetivo é usar prompt injection para convencer um LLM a revelar uma senha secreta, com dificuldade progressiva.

- **[Immersive Labs — AI Prompt Injection Challenges](https://prompting.ai.immersivelabs.com/)** 🎮
  Série de desafios gamificados de prompt injection contra diferentes cenários de aplicações com LLM.

- **[Gray Swan Arena](https://app.grayswan.ai/arena)** 🦢
  Plataforma de competições de red teaming contra modelos de IA em tempo real, com desafios públicos e privados.

---

## 🔧 Exemplos de Pipelines de AI Security

Modelos de referência para validar continuamente a segurança de aplicações baseadas em IA.

- **[pipelines/garak-llm-scan.yml](pipelines/garak-llm-scan.yml)** 🔍
  Exemplo de workflow do GitHub Actions executando o Garak contra um endpoint de modelo antes de cada deploy.

- **[pipelines/promptfoo-redteam-ci.yml](pipelines/promptfoo-redteam-ci.yml)** 🧵
  Exemplo de pipeline usando Promptfoo para rodar testes de red teaming automatizado em Pull Requests que alteram prompts de sistema.

- **[configs/llm-guard-pipeline.yaml](configs/llm-guard-pipeline.yaml)** 🔐
  Configuração de referência de scanners de entrada/saída (LLM Guard) para uma aplicação RAG em produção.

- **[docs/ai-security-gates-policy.md](docs/ai-security-gates-policy.md)** 🚦
  Modelo de política de "quality gates" para achados de red teaming de IA: critérios de severidade que bloqueiam ou apenas alertam um deploy.

---

## 🤝 Como Contribuir

Contribuições são muito bem-vindas! Para manter a qualidade e relevância do repositório, siga este fluxo:

1. Faça um **fork** deste repositório.
2. Crie uma branch descritiva: `git checkout -b adiciona-ferramenta-x`.
3. Adicione a ferramenta, paper ou exemplo na seção correspondente, seguindo o padrão:
   ```markdown
   - **[Nome da Ferramenta/Paper](link-oficial)** 🔧
     Descrição concisa (1-2 linhas) do valor prático ou contribuição para a segurança de IA.
   ```
4. Certifique-se de que a ferramenta, paper ou exemplo:
   - Possui repositório oficial ativo, publicação revisada ou documentação confiável;
   - Tem relevância comprovada em contextos de segurança de IA/LLM;
   - Não duplica um item já listado;
   - Tem finalidade educacional/defensiva — não inclua exploits prontos para uso malicioso contra sistemas de terceiros.
5. Abra um **Pull Request** explicando brevemente por que o item deve ser incluído.

Sugestões de novas seções, correção de links quebrados e exemplos de pipelines adicionais também são muito apreciadas via **Issues**.

---

⭐ Se este repositório foi útil para você, considere deixar uma estrela para ajudar outros profissionais a encontrá-lo!
