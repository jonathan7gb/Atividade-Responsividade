<h1 align="center">📎 Link do Resultado</h1>
<h3 align="center">Clique no link abaixo 👇</h3>
<p align="center">https://atividade-responsividade-two.vercel.app/</p>

---

## 📎 Alguns Recursos que usei
https://colorhunt.co/ -> Cores do Site
<br>
https://michalsnik.github.io/aos/ -> Biblioteca de animação de scroll
<br>
https://fonts.google.com/ -> Fontes
<br>
https://pixabay.com/ -> Galeria de Imagens

---

## 🎨 Algumas fotos que usei do Pixabay
https://pixabay.com/pt/photos/p%C3%B4r-do-sol-areia-praia-ilhas-folha-7133867/
https://pixabay.com/pt/photos/cabine-interior-abrigo-casa-6940711/

---

## 📂 Como Executar

1. Clone o repositório:
    ```bash
   cd documents
   ```
    
   ```bash
   git clone https://github.com/jonathan7gb/Atividade-Responsividade.git
   ```
   
   ```bash
   cd Atividade-Responsividade
   ```
2. Acesse a pasta do projeto e abra o arquivo `index.html` no seu navegador.

---
<br>

# 🧪 Prática Guiada e Desafios

Aprender responsividade exige mais do que teoria — é preciso **experimentar, testar e errar** para compreender como os elementos se comportam em diferentes telas. Esta seção oferece **exercícios práticos guiados** e **desafios crescentes**, ideais para consolidar o conteúdo.


## 🎯 Objetivos da prática

- Aplicar media queries para alterar layouts em diferentes tamanhos
- Usar unidades responsivas como `rem`, `%`, `clamp()` e `vw`
- Criar componentes que se reorganizam (cards, menus, formulários)
- Testar visualmente o layout em diferentes dispositivos

## 🧪 Prática Guiada – Página Responsiva Simples

### ✅ Etapas:

1. **Crie uma estrutura HTML com:**
    - Cabeçalho com logotipo e menu
    - Seção de destaque com imagem e texto
    - Seis cards de serviços
    - Rodapé simples
2. **Estilize com CSS:**
    - Fonte base com `rem`
    - Containers com `max-width`, `margin: auto`, `padding` em `%`
3. **Torne responsivo:**
    - Abaixo de `768px`:
        - O menu fica com logo à esquerda e menu hambuguer à direita
        - Seção de destaque com imagem embaixo e texto em cima.
        - Cards empilham verticalmente
        - Texto centralizado
    - Entre `769px e 1024px`:
        - Menu: Logo à esquerda e itens à direita;
        - Seção de destaque com imagem e texto lado à lado;
        - Cards em 2 colunas
        - Fonte aumenta com `clamp()`
    - `Acima de 1024px`:
        - Seção de destaque com imagem e texto lado à lado;
        - Cards em 3 colunas
        - Fonte aumenta com `clamp()`
4. **Extras (avançado):**
    - Faça o botão do menu desaparecer no desktop
    - Use `clamp()` para o `h1`
    - Torne a imagem responsiva com `max-width: 100%`
