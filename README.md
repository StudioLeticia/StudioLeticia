# Studio Letícia Duarte - Landing Page

Uma landing page moderna e responsiva para o Studio Letícia Duarte, especializado em serviços de manicure profissional.

## 🚀 Características

- **Design Responsivo**: Funciona perfeitamente em desktop, tablet e mobile
- **Performance Otimizada**: Carregamento rápido e otimizado para SEO
- **Interatividade**: Animações suaves e efeitos de hover
- **Acessibilidade**: Seguindo as melhores práticas de acessibilidade web
- **Integração WhatsApp**: Botão direto para agendamento via WhatsApp

## 📋 Serviços Apresentados

- Alongamento de Unhas (R$ 170 aplicação / R$ 110 manutenção)
- Banho de Gel (R$ 120 aplicação / R$ 95 manutenção)
- Blindagem (R$ 70)
- Esmaltação em Gel (R$ 60)
- Spa dos Pés (R$ 70)
- Serviços Adicionais (decorações, sobrancelha, depilações)

## 🛠️ Tecnologias Utilizadas

- HTML5 semântico
- CSS3 com variáveis customizadas e Grid/Flexbox
- JavaScript vanilla para interatividade
- Font Awesome para ícones
- Google Fonts (Playfair Display + Inter)
- Imagens otimizadas do Unsplash

## 📱 Como Hospedar no GitHub Pages

### 1. Criar Repositório no GitHub

1. Acesse [GitHub.com](https://github.com) e faça login
2. Clique em "New repository" (botão verde)
3. Nome do repositório: `studio-leticia-landing` (ou outro nome de sua escolha)
4. Marque como "Public"
5. Marque "Add a README file"
6. Clique em "Create repository"

### 2. Upload dos Arquivos

**Opção A - Via Interface Web:**
1. No seu repositório, clique em "uploading an existing file"
2. Arraste todos os arquivos da pasta do projeto:
   - `index.html`
   - `styles.css`
   - `script.js`
   - `README.md`
3. Adicione uma mensagem de commit: "Adicionar landing page do Studio Letícia Duarte"
4. Clique em "Commit changes"

**Opção B - Via Git (se você tem Git instalado):**
```bash
git clone https://github.com/SEU_USUARIO/studio-leticia-landing.git
cd studio-leticia-landing
# Copie os arquivos para esta pasta
git add .
git commit -m "Adicionar landing page do Studio Letícia Duarte"
git push origin main
```

### 3. Ativar GitHub Pages

1. No seu repositório, vá em "Settings" (aba no topo)
2. Role para baixo até encontrar "Pages" no menu lateral
3. Em "Source", selecione "Deploy from a branch"
4. Em "Branch", selecione "main" e "/ (root)"
5. Clique em "Save"
6. Aguarde alguns minutos e sua página estará disponível em:
   `https://SEU_USUARIO.github.io/studio-leticia-landing/`

## 🎨 Personalização

### Cores
As cores principais estão definidas no arquivo `styles.css` nas variáveis CSS:
```css
:root {
    --primary-color: #d4a574;
    --primary-dark: #b8956a;
    --secondary-color: #f5f1eb;
    --accent-color: #8b6f47;
}
```

### Conteúdo
- **Textos**: Edite diretamente no arquivo `index.html`
- **Preços**: Atualize os valores na seção de serviços
- **Contatos**: Modifique telefone, Instagram e endereço
- **Imagens**: Substitua as URLs das imagens do Unsplash por suas próprias fotos

### WhatsApp
O link do WhatsApp está configurado para o número (15) 99142-7933. Para alterar:
1. Abra o arquivo `index.html`
2. Procure por `https://wa.me/5515991427933`
3. Substitua pelo seu número no formato: `5515SEUNUMERO`

## 📊 SEO e Performance

- Meta tags otimizadas para SEO
- Estrutura semântica HTML5
- Imagens otimizadas e com lazy loading
- CSS e JavaScript minificados para produção
- Schema markup para melhor indexação

## 🔧 Manutenção

### Atualizando Preços
1. Edite o arquivo `index.html`
2. Procure pela seção `<!-- Services Section -->`
3. Atualize os valores nas classes `.price-value`
4. Faça commit das mudanças no GitHub

### Adicionando Novos Serviços
1. Copie um `.service-card` existente
2. Modifique o conteúdo (ícone, título, descrição, preços)
3. Adicione à grid de serviços

## 📞 Contato

- **WhatsApp**: (15) 99142-7933
- **Instagram**: @studioleticiaduarte_
- **Endereço**: Rua Goiacoz 260 - Vila Progresso

## 📄 Licença

Este projeto foi desenvolvido especificamente para o Studio Letícia Duarte. Todos os direitos reservados.

---

**Desenvolvido com ❤️ para o Studio Letícia Duarte**

