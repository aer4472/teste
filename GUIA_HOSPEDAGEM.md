# 🌐 Guia Completo - Como Usar o Sistema Online

## 📋 Índice
1. [Opções de Hospedagem Gratuita](#opções-de-hospedagem-gratuita)
2. [Método Recomendado: GitHub Pages](#método-recomendado-github-pages)
3. [Alternativa: Netlify](#alternativa-netlify)
4. [Alternativa: Vercel](#alternativa-vercel)
5. [Hospedagem Paga](#hospedagem-paga)
6. [Configuração Após Hospedagem](#configuração-após-hospedagem)

---

## 🆓 Opções de Hospedagem Gratuita

### 1. GitHub Pages (100% Grátis - RECOMENDADO)
- ✅ Totalmente gratuito
- ✅ SSL/HTTPS automático
- ✅ Domínio personalizado disponível
- ✅ Fácil de usar
- ✅ Ilimitado

### 2. Netlify (Grátis)
- ✅ Muito fácil de usar
- ✅ Deploy por drag & drop
- ✅ SSL automático
- ✅ 100GB de banda mensal

### 3. Vercel (Grátis)
- ✅ Deploy rápido
- ✅ SSL automático
- ✅ Ótima performance

---

## 🚀 Método Recomendado: GitHub Pages

### Passo 1: Criar Conta no GitHub
1. Acesse: https://github.com
2. Clique em "Sign up" (Cadastrar)
3. Preencha: email, senha e nome de usuário
4. Confirme seu email

### Passo 2: Criar um Repositório
1. Faça login no GitHub
2. Clique no botão verde "New" ou no ícone "+"
3. Nome do repositório: `meu-cardapio` (ou qualquer nome)
4. Marque: ✅ Public
5. Marque: ✅ Add a README file
6. Clique em "Create repository"

### Passo 3: Upload dos Arquivos
1. No seu repositório, clique em "Add file" → "Upload files"
2. Arraste os 3 arquivos:
   - `login.html`
   - `admin-v4.html`
   - `cardapio-v4.html`
3. Clique em "Commit changes"

### Passo 4: Ativar GitHub Pages
1. No repositório, clique em "Settings" (Configurações)
2. No menu lateral, clique em "Pages"
3. Em "Source", selecione: **main** (branch)
4. Clique em "Save"
5. Aguarde 1-2 minutos

### Passo 5: Acessar Seu Site
Seu site estará disponível em:
```
https://seu-usuario.github.io/meu-cardapio/login.html
```

**Exemplo:**
- Usuário: joaosilva
- Repositório: cardapio-pizza
- URL: `https://joaosilva.github.io/cardapio-pizza/login.html`

---

## 🎨 Alternativa: Netlify (Super Fácil!)

### Método 1: Drag & Drop (Mais Fácil)

1. **Criar Conta**
   - Acesse: https://netlify.com
   - Clique em "Sign up" (usar email ou GitHub)

2. **Deploy do Site**
   - Após login, clique em "Add new site" → "Deploy manually"
   - Arraste os 3 arquivos HTML para a área indicada
   - Pronto! Seu site já está no ar!

3. **URL do Site**
   - Netlify gera uma URL automática: `https://nome-aleatorio.netlify.app`
   - Para acessar: `https://nome-aleatorio.netlify.app/login.html`

4. **Personalizar URL (Opcional)**
   - No painel do site, clique em "Site settings"
   - Clique em "Change site name"
   - Digite um nome único: `meu-cardapio-pizza`
   - Nova URL: `https://meu-cardapio-pizza.netlify.app`

### Método 2: Conectar com GitHub
1. No Netlify, clique em "Add new site" → "Import existing project"
2. Escolha "GitHub"
3. Autorize o Netlify
4. Selecione seu repositório
5. Clique em "Deploy site"

---

## ⚡ Alternativa: Vercel

### Passo a Passo:

1. **Criar Conta**
   - Acesse: https://vercel.com
   - Clique em "Sign up"
   - Use conta do GitHub (recomendado)

2. **Importar Projeto**
   - Clique em "Add New..." → "Project"
   - Selecione "Import Git Repository"
   - Escolha seu repositório do GitHub
   - Clique em "Import"

3. **Deploy**
   - Clique em "Deploy"
   - Aguarde alguns segundos
   - Pronto! Seu site está online

4. **URL do Site**
   - URL automática: `https://nome-projeto.vercel.app`
   - Acesse: `https://nome-projeto.vercel.app/login.html`

---

## 💰 Hospedagem Paga (Profissional)

### Para Empresas / Uso Comercial:

#### 1. Hostinger (Recomendado)
- 💵 A partir de R$ 9,99/mês
- ✅ Domínio grátis (.com.br)
- ✅ SSL grátis
- ✅ Suporte 24/7 em português
- 🌐 Site: https://hostinger.com.br

#### 2. Hostgator Brasil
- 💵 A partir de R$ 12,99/mês
- ✅ Domínio grátis
- ✅ SSL grátis
- 🌐 Site: https://hostgator.com.br

#### 3. UmbleHost
- 💵 A partir de R$ 6,99/mês
- ✅ Servidores no Brasil
- ✅ SSL grátis
- 🌐 Site: https://umbler.com

### Como Usar Hospedagem Paga:

1. **Contratar Plano**
   - Escolha um plano básico
   - Registre um domínio (ex: meupizzaria.com.br)

2. **Upload via FTP**
   - Use FileZilla (grátis): https://filezilla-project.org
   - Conecte com as credenciais do painel
   - Faça upload dos 3 arquivos HTML
   - Coloque na pasta `public_html/`

3. **Acessar**
   - URL: `https://seudominio.com.br/login.html`

---

## ⚙️ Configuração Após Hospedagem

### 1. Renomear Arquivo Inicial (Opcional)

Para que o site abra direto na página de login:

**Opção A: GitHub Pages**
- Renomeie `login.html` para `index.html`
- Agora acesse: `https://seu-usuario.github.io/meu-cardapio/`

**Opção B: Criar index.html**
Crie um arquivo `index.html` com este conteúdo:
```html
<!DOCTYPE html>
<html>
<head>
    <meta http-equiv="refresh" content="0; url=login.html">
    <title>Redirecionando...</title>
</head>
<body>
    <p>Redirecionando para o sistema...</p>
</body>
</html>
```

### 2. Configurar o Sistema

Após hospedar, acesse pela primeira vez:

1. **Faça Login**
   - Email: `admin@sistema.com`
   - Senha: `admin123`

2. **Configure o Restaurante**
   - Vá em "Configurações"
   - Adicione nome, logo e informações
   - Configure número do WhatsApp
   - Salve as configurações

3. **Crie Usuários Adicionais**
   - Vá em "Usuários"
   - Crie contas para funcionários
   - **IMPORTANTE:** Altere a senha do admin!

4. **Adicione Produtos**
   - Vá em "Produtos"
   - Adicione seus produtos e preços
   - Configure estoque

5. **Compartilhe com Clientes**
   - URL do cardápio: `sua-url/cardapio-v4.html`
   - Compartilhe no WhatsApp, Instagram, Facebook

---

## 📱 Como Compartilhar com Clientes

### Link Direto:
```
https://seu-site.com/cardapio-v4.html
```

### QR Code:
1. Acesse: https://qr-code-generator.com
2. Cole a URL do cardápio
3. Baixe o QR Code
4. Use em: cardápios físicos, redes sociais, WhatsApp

### Redes Sociais:
- **Instagram Bio:** Cole o link na bio
- **Facebook:** Fixe o link nos posts
- **WhatsApp Status:** Compartilhe o link

---

## 🔧 Solução de Problemas

### Problema: Página não carrega
**Solução:**
- Verifique se os arquivos foram enviados corretamente
- Aguarde 5-10 minutos (propagação DNS)
- Limpe cache do navegador (Ctrl + F5)

### Problema: Login não funciona
**Solução:**
- Verifique se está usando as credenciais corretas
- Limpe dados do navegador (localStorage)
- Teste em aba anônima

### Problema: WhatsApp não abre
**Solução:**
- Configure o número no formato: `5511999999999`
- Inclua código do país (55) + DDD + número

---

## 📞 Suporte

**Desenvolvido por:**
Eduardo Soluções Tecnológicas

**Contato:**
- 📧 Email: contato@eduardosolucoes.com.br
- 📱 WhatsApp: (11) 99999-9999
- 🌐 Site: www.eduardosolucoes.com.br

---

## ✅ Checklist de Lançamento

Antes de compartilhar com clientes:

- [ ] Site hospedado e funcionando
- [ ] Login testado e funcionando
- [ ] Configurações do restaurante preenchidas
- [ ] Logo adicionada
- [ ] Produtos cadastrados com preços
- [ ] WhatsApp configurado e testado
- [ ] Teste de pedido completo realizado
- [ ] QR Code gerado
- [ ] Link compartilhado nas redes sociais

---

## 🎯 Dicas Profissionais

1. **Domínio Próprio**
   - Registre: `meupizzaria.com.br`
   - Mais profissional e fácil de lembrar

2. **Certificado SSL**
   - Todas as opções gratuitas já incluem
   - Aparece o cadeado 🔒 no navegador
   - Clientes confiam mais

3. **Backup Regular**
   - Use o botão "Backup" semanalmente
   - Guarde os arquivos JSON em segurança

4. **Atualizações**
   - Para atualizar: substitua os arquivos HTML
   - Os dados (produtos, pedidos) ficam salvos no navegador

5. **Performance**
   - Otimize imagens (use TinyPNG.com)
   - Tamanho máximo: 500KB por imagem
   - Formato: JPG ou PNG

---

## 🚀 Próximos Passos

Após configurar:

1. ✅ Teste fazer um pedido completo
2. ✅ Teste impressão térmica
3. ✅ Configure notificações WhatsApp
4. ✅ Treine funcionários no sistema
5. ✅ Lance para clientes!

**Boa sorte com seu sistema de pedidos online!** 🎉
