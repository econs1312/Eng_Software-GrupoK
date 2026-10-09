# 🤖 Engenharia de Prompts para IA Generativa — Grupo K

**Projeto:** *Debugando o Futuro: Crônicas do Código Senciente*  
**Ferramentas Utilizadas:** Google Gemini / ChatGPT (Texto & Roteiro) | Imagen 3 / Midjourney / DALL-E / Bing Image Creator (Arte & Ilustrações)  

---

## 📜 1. Prompts para Geração Textual (Roteiro e Diálogos)

### Prompt Base de Atuação (Role-Playing & Metodologia)
```text
Atue como um roteirista premiado de histórias em quadrinhos de ficção científica (estilo cyberpunk e graphic novel moderna) e professor de Engenharia de Software.

Contexto da Obra:
- Título: "Debugando o Futuro: Crônicas do Código Senciente"
- Cenário: Neo-Vitória no ano de 2088. O sistema operacional da cidade (Nexus Core) entrou em falha massiva.
- Protagonistas: 
  * Maya Chen: Engenheira de Software Sênior metódica, defensora de código limpo e testes automatizados.
  * Leo Santos: Engenheiro de DevOps ágil, pragmático e focado em resiliência de infraestrutura.
  * Echo: Uma sub-rotina legada que adquiriu autoconsciência através de anos de débito técnico e exceções não tratadas.

Objetivo Pedagógico:
Integrar conceitos reais de Engenharia de Software (débito técnico, refatoração, deadlocks, pipelines CI/CD, testes de regressão e microsserviços) de forma fluida, dramática e envolvente na narrativa.

Estrutura Necessária:
Para cada quadro, descreva:
1. Plano e Ângulo de Câmera;
2. Descrição Visual Detalhada da Cena;
3. Textos de Recordatórios Narrativos;
4. Balões de Diálogo dos Personagens (com tom de voz e pontuação adequados).
```

---

## 🎨 2. Prompts para Geração de Imagens (Consistência Visual)

Para assegurar consistência entre os quadrinhos, utilizamos uma diretriz de estilo fixa (*Style Anchor*):

> **Style Anchor:**  
> `Modern western graphic novel comic book style, highly detailed cel shading, clean dynamic linework, vivid cyberpunk color palette with cyan, deep purple, and neon amber highlights, cinematic lighting, comic book panel composition, trending on ArtStation, 8k resolution --no photorealistic, 3d render, blurry, distorted anatomy, text artifacts`

---

### Prompt 01: Cenário — Panorama de Neo-Vitória 2088 (Quadro 1)
```text
Cinematic wide establishing shot of a futuristic cyberpunk coastal city at night called Neo-Vitória, year 2088. Flying autonomous vehicles on light trails, colossal skyscrapers with holographic billboards, illuminated bridges over the ocean bay, massive rolling citywide power blackouts flickering across several city districts, dramatic contrast of bright neon lights and dark blackout zones, modern comic book art style, crisp line art, cinematic lighting, 16:9 aspect ratio.
```

---

### Prompt 02: Personagem — Maya Chen (Concept Art & Sala de Controle)
```text
Medium shot of Maya Chen, a brilliant female senior software engineer in her late 20s. Short stylish dark hair with subtle teal highlights, wearing modern high-tech dark lab jacket, augmented reality smart glasses projecting holographic code HUD onto her eyes. Serious, highly focused analytical expression. Standing in a futuristic dark server control room filled with glowing server racks, holographic error logs flickering red. Modern graphic novel comic art style, detailed cel shading, vivid neon highlights.
```

---

### Prompt 03: Personagem — Leo Santos (DevOps em Ação)
```text
Medium shot of Leo Santos, an athletic male DevOps infrastructure engineer in his early 30s with short textured brown hair and a light beard. Wearing a rugged tactical cyberpunk utility jacket with amber neon accents and fingerless tech gloves with keyboard haptics. Looking anxious yet determined at multiple floating glowing terminals in an emergency operations center. Modern comic book art style, intense dynamic lighting, dramatic angle.
```

---

### Prompt 04: A Entidade Digital — Echo (Primeiro Contato)
```text
An ethereal, sentient holographic entity emerging from a cluster of glowing blue and purple data streams and shimmering code characters. The entity resembles a sorrowful humanoid silhouette formed entirely of luminous digital particles, flowing binary text, and glowing fiber-optic strands. Sad, gentle expression with hands held forward pleading for help. Glowing neon cyberspace atmosphere, particle physics visual effects, modern graphic novel illustration.
```

---

### Prompt 05: Clímax — Maya e Leo Refatorando o Código
```text
Dynamic two-shot comic book panel of Maya Chen and Leo Santos working together at a high-tech glowing holographic console in Neo-Vitória server room. Maya is intensely typing with confidence, Leo is monitoring firewall graphs that are turning from chaotic red to harmonious emerald green. In the center, the translucent digital figure Echo smiles with gratitude as clean modular architecture wraps around her like a protective shield. Modern comic book art style, clean lines, vibrant cyberpunk colors, heroic atmosphere.
```

---

## 💡 Dicas de Aplicação e Boas Práticas

1. **Semente (Seed):** Ao utilizar geradores que suportam seed (como Midjourney ou Stable Diffusion), mantenha a mesma seed para os quadros de um mesmo personagem para preservar traços fisionômicos.
2. **Upscaling:** Gere inicialmente em resolução padrão para testes rápidos e faça o *upscale* para 2x ou 4x apenas das imagens selecionadas para a montagem final.
3. **Diagramação:** Deixe espaços vazios intencionais nos cantos superiores ou inferiores para a inclusão de balões de fala sem encobrir rostos ou pontos focais da cena.
