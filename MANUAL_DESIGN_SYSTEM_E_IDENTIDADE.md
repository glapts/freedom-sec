# MANUAL DE DESIGN SYSTEM & GUIA DE ESTILO VISUAL
## FREEDOM.SEC CONTROLE DE PRAGAS – WEB DESIGNER & UI/UX SPEC

---

**Projeto:** Ecossistema Digital Freedom.sec  
**Proprietário:** Marcelo Baptista das Graças  
**Localização:** Jd. Comercial, São Paulo – SP  
**Slogan:** *"Proteção que dá liberdade. Resultados que duram."*  
**Paleta Oficial:** Azul Escudo, Verde Proteção e Branco  

---

## 1. CONCEITO DE MARCA E IDENTIDADE VISUAL

A identidade da **FREEDOM.SEC** foi concebida para transmitir **invulnerabilidade, assepsia técnica, modernidade e segurança ambiental**. O logotipo oficial integra:
1. **O Escudo Protetor (Azul Marinho Sólido):** Simboliza barreira impenetrável contra agentes patogênicos e pragas urbanas.
2. **A Casa e Janela:** Representa o ambiente a ser preservado (lares familiares e estabelecimentos comerciais).
3. **O Círculo de Supressão de Pragas (Verde):** A barreira ecológica e química que neutraliza insetos rastejantes, voadores e roedores (baratas, formigas, ratos e besouros).
4. **O Selo/Badge de Garantia:** Emblema inferior com o checkmark verde, simbolizando serviço certificado e duradouro.

---

## 2. PALETA DE CORES OFICIAL (HEX, RGB & HSL)

```
┌─────────────────┐ ┌─────────────────┐ ┌─────────────────┐ ┌─────────────────┐
│   AZUL ESCUDO   │ │  AZUL PROFUNDO  │ │  VERDE ESCUDO   │ │  VERDE SUCESSO  │
│     #0B1B3D     │ │     #060E1E     │ │     #1E6F38     │ │     #22C55E     │
│  (Deep Navy)    │ │   (Dark Night)  │ │ (Forest Green)  │ │ (Emerald Glow)  │
└─────────────────┘ └─────────────────┘ └─────────────────┘ └─────────────────┘
┌─────────────────┐ ┌─────────────────┐ ┌─────────────────┐ ┌─────────────────┐
│   BRANCO PURO   │ │  CINZA ASSEPSIA │ │   VERDE TINT    │ │  AMARELO ALERTA │
│     #FFFFFF     │ │     #F8FAFC     │ │     #DCFCE7     │ │     #F59E0B     │
│   (Pure White)  │ │  (Clean Slate)  │ │  (Soft Mint)    │ │  (Pest Warning) │
└─────────────────┘ └─────────────────┘ └─────────────────┘ └─────────────────┘
```

### 2.1. Códigos Exatos da Paleta
* **Azul Escudo Primário (Primary Brand):**
  * HEX: `#0B1B3D` | RGB: `rgb(11, 27, 61)` | HSL: `221°, 69%, 14%`
  * Uso: Barras de navegação, títulos de alta autoridade, botões primários institucionais, background de destaque.
* **Azul Noite Profundo (Surface Dark Mode):**
  * HEX: `#060E1E` | RGB: `rgb(6, 14, 30)` | HSL: `220°, 67%, 7%`
  * Uso: Fundo do portal no tema escuro e containers de alta tecnologia.
* **Verde Bio-Proteção (Secondary Brand / Accent):**
  * HEX: `#1E6F38` | RGB: `rgb(30, 111, 56)` | HSL: `139°, 57%, 28%`
  * Uso: Acentos de marca, linhas de destaque do logotipo, bordas de segurança sanitária.
* **Verde Destaque / Ação (CTA & Sucesso):**
  * HEX: `#22C55E` / `#16A34A` | RGB: `rgb(34, 197, 94)`
  * Uso: Botões de compra de leads ("Comprar com PIX"), tags de status "Disponível", selos de garantia e ícones de WhatsApp.
* **Branco Puro (Neutral Light):**
  * HEX: `#FFFFFF` | RGB: `rgb(255, 255, 255)`
  * Uso: Planos de fundo limpos, cards em modo claro e tipografia em fundos escuros.
* **Cinza Superfície / Assepsia (Background Soft):**
  * HEX: `#F8FAFC` | RGB: `rgb(248, 250, 252)`
  * Uso: Fundo padrão de landing pages em modo diurno para descanso visual.

---

## 3. TIPOGRAFIA & HIERARQUIA

Utilizaremos a família tipográfica **Plus Jakarta Sans** combinada com **Inter**:

* **Família Principal de Títulos:** `Plus Jakarta Sans`, sans-serif
  * Peso 800 (Extra Bold): Títulos de impacto na Hero Section.
  * Peso 700 (Bold): Títulos de seções, cartões de leads e valores monetários.
  * Peso 600 (Semi Bold): Subtítulos, rótulos de botões e links da navegação.
* **Família de Corpo de Texto e Dados:** `Inter`, sans-serif
  * Peso 500 (Medium): Parágrafos de leitura, inputs de formulário e dados cadastrais.
  * Peso 400 (Regular): Textos descritivos secundários e observações de rodapé.

### Escala de Tamanhos Recomendada:
* `Hero Title`: 48px a 64px (desktop) / 32px a 40px (mobile) – Leading 1.1
* `Section Heading (H2)`: 32px a 36px – Leading 1.2
* `Card Heading (H3)`: 20px a 24px – Leading 1.3
* `Body Normal`: 16px – Leading 1.6
* `Caption / Badges`: 12px a 14px – Tracking wider (+0.05em)

---

## 4. DESIGN DE COMPONENTES CHAVE

### 4.1. Card da Vitrine de Agendamentos (Marketplace Lead Card)
O componente visual mais importante da plataforma:
* **Borda & Sombra:** `border border-slate-200 dark:border-slate-800 rounded-2xl shadow-lg hover:shadow-xl transition-all duration-300`
* **Badge de Praga:** Tag no topo esquerdo com ícone (Barata, Rato, Cupim) e cor de alerta suave:
  * Baratas/Formigas: Fundo Verde Claro `#DCFCE7` com texto `#166534`;
  * Roedores/Ratos: Fundo Âmbar Claro `#FEF3C7` com texto `#92400E`;
  * Cupins de Madeira: Fundo Azul Suave `#E0F2FE` com texto `#075985`.
* **Badge de Exclusividade:** Selo verde com ícone de escudo: `"100% Exclusivo"`.
* **Bloco de Endereço & Horário:** Ícone de pino de mapa (Bairro e Cidade, sem o número até a compra) e calendário com data e turno (Ex: *Amanhã, 14:00*).
* **Grid de Valores Financeiros:**
  * `Valor do Serviço:` **R$ 380,00** (Verde Escuro Bold)
  * `Custo do Lead:` **R$ 85,00** (Azul Petróleo)
  * `Margem Líquida Estimada:` **R$ 295,00** (+77% de lucro)
* **Botão CTA:** Verde Destaque (`#22C55E`) com texto branco em negrito e ícone de raio: `Aceitar Agendamento (PIX)`.

### 4.2. Botões & Interações
* **Botão Primário (Hero & Vendas):**
  * `bg-emerald-600 hover:bg-emerald-500 text-white font-bold py-3.5 px-8 rounded-xl shadow-lg shadow-emerald-900/20 active:scale-95 transition-all`
* **Botão Secundário (Institucional):**
  * `bg-[#0B1B3D] hover:bg-[#162E5C] text-white font-semibold py-3.5 px-6 rounded-xl border border-slate-700`
* **Botão WhatsApp Flutuante:**
  * Verde WhatsApp clássico (`#25D366`) posicionado no canto inferior direito com pulso luminoso sutil, abrindo diretamente o bot inteligente.

### 4.3. Modo de Visualização Sob o Sol ("Modo Legível / Rua")
Inspirado na funcionalidade descoberta no código-fonte do Higio (`localStorage.getItem('higio-display-mode') === 'legivel'`):
* Desenvolvido especialmente para o técnico de controle de pragas que opera sob a luz direta do sol no veículo ou na calçada;
* Aumenta o tamanho base das fontes em 15%;
* Força contraste preto e branco total (fundo `#FFFFFF` puro e textos `#000000` 100% opaco), eliminando sombras translúcidas difusas.

---

## 5. REGRAS DE LAYOUT E RESPONSIVIDADE

* **Mobile-First Obrigatório:** Mais de 85% dos acessos de técnicos e clientes ocorrem em celulares. O cabeçalho possui navegação tipo gaveta (*drawer*) acessível com o polegar.
* **Grid System:** Grid de 12 colunas no desktop (max-width de 1280px centralizado) e 1 coluna fluida com padding lateral de 16px no mobile.
* **Transições e Microinterações:** Framer Motion com aceleração via hardware (`transform: translate3d`) para sensação de aplicativo nativo ultrarrápido.

---
**Guia Visual Homologado para a Equipe de Web Design & Frontend Freedom.sec**
