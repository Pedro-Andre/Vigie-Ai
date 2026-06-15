# 🛡️ Vigie.Ai

> **Plataforma educacional sobre crimes cibernéticos, engenharia social e computação forense.**

---

## 📋 Sobre o Projeto

O **Vigie.Ai** é uma plataforma educacional desenvolvida como projeto acadêmico com o objetivo de capacitar usuários comuns e instituições a identificarem vetores de ataque cibernético e compreenderem os procedimentos corretos de Computação Forense para preservação de evidências digitais.

O projeto nasce da necessidade de democratizar o acesso à educação em segurança digital — tornando conteúdos técnicos acessíveis, visuais e interativos para um público amplo, sem exigir conhecimento prévio na área.

---

## 🎯 Objetivos

| #   | Objetivo            | Descrição                                                                                                 |
| --- | ------------------- | --------------------------------------------------------------------------------------------------------- |
| 1   | **Conscientização** | Educar sobre os perigos de crimes cibernéticos: phishing, deepfakes, engenharia social e fraudes digitais |
| 2   | **Capacitação**     | Ensinar técnicas de perícia digital e análise forense de forma acessível                                  |
| 3   | **Conformidade**    | Democratizar o acesso às normas internacionais de segurança (ISO/IEC) e à LGPD                            |
| 4   | **Defesa**          | Transformar o usuário no primeiro elo da corrente de defesa digital                                       |

---

## 🗂️ Estrutura de Páginas

```
vigie.ai/
│
├── index.html               # Página inicial
├── info/
│   ├── ameacas.html         # Engenharia social, phishing e golpes digitais
│   │                          ↳ Simulação interativa: Golpe do Banco Falso
│   │                          ↳ Simulação interativa: Golpe do Familiar Falso
│   │                          ↳ Infográfico: 6 Princípios da Manipulação
│   ├── deepfakes.html       # O que são deepfakes, como identificar e se proteger
│   ├── guia.html            # Guia de proteção e boas práticas de segurança digital
│   └── ferramentas.html # Ferramentas forenses: Autopsy e FTK Imager
│
└── src/
    ├── css/
    │   └── style.css
    └── images/
```

---

## ✨ Funcionalidades

### 🎭 Simulações Interativas

Demonstrações passo a passo de golpes reais, com alertas educativos em cada etapa:

- **Golpe do Banco Falso** — conta falsa se passando por instituição financeira via mensagem
- **Golpe do Familiar Falso** — criminoso se passa por filho ou parente pedindo Pix urgente
- **6 Princípios da Engenharia Social** — infográfico interativo: urgência, autoridade, reciprocidade, escassez, prova social e afinidade

### 🕵️ Deepfakes

- O que são e como funcionam (GANs)
- Guia visual de identificação: bordas, sincronia labial, textura de pele
- Dicas de proteção e ferramentas de detecção

### 🛡️ Guia de Proteção

- Checklist de sobrevivência digital (senhas, 2FA, permissões)
- Protocolo de resposta a vazamentos de dados
- Configurações recomendadas para navegadores, mobile, mensageria e cloud

### 🔬 Perícia Digital

- Apresentação das ferramentas **Autopsy** e **FTK Imager**
- Simulação de fluxo forense com terminal mockup
- Tabela comparativa das ferramentas
- Explicação do processo forense: coleta → preservação → análise → apresentação

---

## 🛠️ Tecnologias Utilizadas

| Tecnologia                 | Uso                                |
| -------------------------- | ---------------------------------- |
| **HTML5**                  | Estrutura de todas as páginas      |
| **Tailwind CSS** (via CDN) | Estilização e layout responsivo    |
| **JavaScript** (vanilla)   | Simulações interativas e animações |
| **Google Fonts**           | Space Grotesk, Saira, Inter        |
| **Material Symbols**       | Ícones (Google)                    |

> Nenhum framework ou bundler necessário — o projeto roda diretamente no navegador.

---

## 🚀 Como Executar

```bash
# 1. Clone o repositório
git clone https://github.com/seu-usuario/vigie-ai.git

# 2. Acesse a pasta do projeto
cd vigie-ai

# 3. Abra o arquivo inicial no navegador
# Opção A: abra index.html diretamente pelo explorador de arquivos
# Opção B: use um servidor local (recomendado para evitar erros de CORS)
npx serve .
# ou
python -m http.server 8080
```

> ⚠️ **Recomendado:** usar um servidor local (Live Server do VS Code, `npx serve`, ou similar) para garantir que os caminhos relativos de imagens e CSS funcionem corretamente.

---

## 📁 Convenções do Projeto

- **Tema visual:** Dark mode — fundo `#001122`, destaque ciano `#00aaff`
- **Fontes:** `Space Grotesk` para títulos, `Saira` para corpo de texto
- **Componentes:** `floating-card` com borda `rgba(0,170,255,0.12)` como padrão de cards
- **Responsivo:** todas as páginas adaptadas para mobile e desktop

---

## 📚 Conteúdo Educativo Abordado

- Phishing e URLs camufladas
- Engenharia social e manipulação psicológica
- Golpes via WhatsApp/Telegram (banco falso, familiar falso)
- Deepfakes: vídeo, áudio e clonagem de voz por IA
- Computação forense: cadeia de custódia, imagem forense, hash MD5/SHA
- Ferramentas: **Autopsy** (análise) e **FTK Imager** (aquisição)
- LGPD e normas ISO/IEC aplicadas à segurança digital

---

## 👥 Equipe

Projeto desenvolvido como trabalho acadêmico.

| Função              | Responsabilidade                               |
| ------------------- | ---------------------------------------------- |
| Desenvolvimento Web | Estrutura HTML, CSS e interatividade           |
| Pesquisa e Conteúdo | Levantamento bibliográfico e redação educativa |
| Design              | Identidade visual e UX                         |

---

## 📄 Licença

Este projeto foi desenvolvido para fins **exclusivamente educacionais**.  
Nenhum dado real é coletado ou transmitido pela plataforma.

---

<div align="center">
  <sub>Feito com 💙 para tornar a segurança digital acessível a todos.</sub>
</div>
