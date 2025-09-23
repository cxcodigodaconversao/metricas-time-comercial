# 🚀 Instruções de Deploy - GitHub + Netlify

## 📁 Estrutura dos Arquivos

Você precisa de 3 arquivos principais:

```
seu-projeto/
├── index.html          # Calculadora principal
├── README.md          # Documentação
└── .gitignore         # Arquivos ignorados pelo Git
```

## 1️⃣ Preparando os Arquivos

1. **Crie uma pasta no seu computador** (ex: `calculadora-vendas`)

2. **Salve os 3 arquivos na pasta:**
   - `index.html` - Cole o código da calculadora
   - `README.md` - Cole a documentação
   - `.gitignore` - Cole as regras do Git

## 2️⃣ Subindo para o GitHub

### Opção A: Via GitHub Web (Mais Fácil)

1. **Acesse [GitHub.com](https://github.com)** e faça login

2. **Clique em "New repository"**

3. **Configure o repositório:**
   - **Repository name**: `calculadora-vendas` (ou outro nome)
   - **Description**: "Calculadora de Métricas de Vendas"
   - ✅ **Public** (para funcionar no Netlify grátis)
   - ✅ **Add a README file** (desmarque, pois já temos um)

4. **Clique em "Create repository"**

5. **Upload dos arquivos:**
   - Clique em "uploading an existing file"
   - Arraste os 3 arquivos para a página
   - Escreva uma mensagem: "Initial commit - Calculadora de Vendas"
   - Clique em "Commit changes"

### Opção B: Via Git Command Line

```bash
# No terminal/prompt, dentro da pasta do projeto
git init
git add .
git commit -m "Initial commit - Calculadora de Vendas"
git branch -M main
git remote add origin https://github.com/SEU-USUARIO/calculadora-vendas.git
git push -u origin main
```

## 3️⃣ Deploy no Netlify

### Método Automático (Recomendado)

1. **Acesse [Netlify.com](https://netlify.com)** e faça login

2. **Clique em "New site from Git"**

3. **Conecte ao GitHub:**
   - Selecione "GitHub"
   - Autorize o Netlify
   - Escolha seu repositório

4. **Configure o deploy:**
   - **Branch to deploy**: `main`
   - **Build command**: (deixe vazio)
   - **Publish directory**: `./` (ou deixe vazio)

5. **Clique em "Deploy site"**

6. **Aguarde o deploy** (1-2 minutos)

7. **Seu site estará live!** 
   - URL temporária: `https://random-name-123456.netlify.app`
   - Você pode personalizar o nome depois

### Personalizando a URL

1. **No painel do Netlify:**
   - Vá em "Site settings"
   - Clique em "Change site name"
   - Digite: `calculadora-vendas-sua-empresa`
   - Sua URL será: `https://calculadora-vendas-sua-empresa.netlify.app`

## 4️⃣ Atualizações Futuras

**Para fazer mudanças:**

1. **Edite os arquivos localmente**
2. **Suba as mudanças para o GitHub:**
   ```bash
   git add .
   git commit -m "Atualização da calculadora"
   git push
   ```
3. **O Netlify atualiza automaticamente** em 1-2 minutos

## 5️⃣ Verificação Final

**Teste estas funcionalidades no site:**
- ✅ Calculadora funciona corretamente
- ✅ Responsiva no mobile
- ✅ Cursor customizado funciona
- ✅ Tooltips aparecem
- ✅ Formatação brasileira (1.000.000,00)

## 🔧 Troubleshooting

### Problema: Site não carrega
**Solução**: Verifique se o arquivo se chama exatamente `index.html`

### Problema: Deploy falhou
**Solução**: 
- Verifique se o repositório é público
- Confirme que o arquivo `index.html` está na raiz do repositório

### Problema: Calculadora não funciona
**Solução**: 
- Abra o console do navegador (F12)
- Veja se há erros de JavaScript
- Verifique se todos os campos são obrigatórios

## 📞 Suporte

Se tiver problemas:
1. Verifique o console do navegador (F12)
2. Confira os logs do Netlify
3. Compare com o código original

---

🎉 **Parabéns! Sua calculadora está online!**
