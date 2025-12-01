# 🚀 Landing Page de Personal Trainer: High-Impact (Design P/B/V)

## 🎯 Objetivo do Projeto
Desenvolvimento de uma Landing Page *One-Page* com foco em alta conversão para Personal Trainers/Consultorias Esportivas. O projeto utiliza a estratégia de design **Preto, Branco e Vermelho (P/B/V)** para criar uma hierarquia visual de alto contraste e direcionar o usuário para o Call-to-Action (CTA).

A estrutura segue um fluxo de vendas otimizado: **Atenção → Credibilidade → Conversão → Fechamento**.

## ✨ Destaques de UX/UI e Desenvolvimento

Este projeto foi construído com uma abordagem **Mobile First** e implementa práticas modernas de desenvolvimento e usabilidade:

| Funcionalidade | Conceito de UX Aplicado | Detalhes Técnicos |
| :--- | :--- | :--- |
| **Paleta P/B/V** | Hierarquia Visual e Foco | Uso de `var(--cor-primaria-acao)` (Vermelho) exclusivamente para CTAs, Preços e Títulos de Destaque. |
| **Efeito Neon** | Microinteração e Modernidade | Transições `hover` nos cards de Metodologia, usando `box-shadow` vermelho para simular luz neon. |
| **Cards de Depoimento** | Prova Social e Alinhamento | Uso de **Flexbox** (`display: flex; flex-direction: column; justify-content: space-between;`) para garantir que todos os cards fiquem na mesma altura, independentemente do tamanho do texto. |
| **Menu Fixo** | Navegabilidade (UX) | `position: fixed` no cabeçalho e código JavaScript para **Smooth Scrolling**. |
| **Responsividade** | Acessibilidade e Mobile First | **Ajustes específicos para telas menores que 425px**, ocultando a navegação (priorizando o CTA) e centralizando a marca. |
| **Formulário Moderno** | Clareza e Minimalismo | Inputs com fundo transparente e foco (linha inferior vermelha) para uma experiência de usuário limpa. |

## 📐 Estrutura do Site (Seções)

1.  **Capa Inicial (`#capa-inicial`):** Apresentação da marca sobre imagem de fundo com overlay escuro para contraste.
2.  **Metodologia (`#metodologia`):** Detalhamento do processo (Credibilidade).
3.  **Depoimentos/Resultados (`#resultados`):** Prova social com design moderno e estrelas na cor da paleta (Vermelho).
4.  **Planos e Preços (`#planos`):** Destaque visual (fundo vermelho/botão preto) para o Plano Elite (Dilema de Escolha).
5.  **Contato (`#contato`):** Formulário de captação e CTA direto para WhatsApp.
6.  **Cabeçalho e Rodapé:** Navegação fixa e informações legais.

## 🛠️ Tecnologias Utilizadas

* `HTML5` (Semântica)
* `CSS3` (Variáveis CSS, Flexbox, Media Queries Mobile First)
* `JavaScript` (Smooth Scrolling)
* `Font Awesome` (Ícones para estrelas e redes sociais)

## ⚙️ Como Executar o Projeto Localmente

1.  **Clone o repositório:**
    ```bash
    git clone https://github.com/guilhermesolagarcia/personal-trainer-landing-page.git
    cd personal-trainer-landing-page
    ```
2.  **Abra o arquivo:**
    Abra o arquivo `index.html` diretamente no seu navegador.

---
