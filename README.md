# 📊 Calculadora de Métricas de Vendas

Uma calculadora web moderna e interativa para definir métricas e estrutura de equipe necessárias para atingir metas de vendas.

## 🚀 Demo

[Ver Demo no Netlify](https://seu-projeto.netlify.app)

## ✨ Funcionalidades

- **📈 Cálculo de Métricas de Vendas**
  - Leads necessários
  - Vendas necessárias
  - Reuniões marcadas e realizadas
  - Estrutura completa de equipe

- **👥 Estrutura Hierárquica**
  - Closers necessários
  - SDRs necessários
  - Gerentes
  - Coordenadores
  - Head de Vendas
  - Diretores

- **🎨 Interface Moderna**
  - Cursor personalizado
  - Animações suaves
  - Design responsivo
  - Tooltips informativos

- **🇧🇷 Formatação Brasileira**
  - Valores monetários em Real (R$)
  - Números formatados (1.000.000,00)
  - Percentuais brasileiros

## 🛠️ Tecnologias Utilizadas

- **HTML5** - Estrutura da página
- **CSS3** - Estilos e animações
- **JavaScript ES6** - Lógica de cálculos
- **Design Responsivo** - Compatível com mobile

## 📊 Métricas e Produtividades

### Produtividades Base:
- **1 Closer** = 77 reuniões realizadas/mês
- **1 SDR** = 500 leads abordados/mês

### Hierarquia:
- **Gerentes**: Math.ceil(Closers ÷ 3,67)
- **Coordenadores**: 1 para cada 7,5 SDRs (mínimo 15 SDRs)
- **Head de Vendas**: 1 quando tiver 4+ gerentes
- **Diretores**: 1 quando tiver 4+ gerentes

## 🚀 Como Usar

1. **Preencha os campos obrigatórios:**
   - Meta de Faturamento (R$)
   - Ticket Médio (R$)
   - Número de SDRs e Closers atuais
   - Taxa de Conversão (%)
   - Taxa de Não Comparecimento (%)
   - Leads por Agendamento

2. **Clique em "🚀 Calcular!"**

3. **Veja os resultados:**
   - Métricas de vendas necessárias
   - Estrutura de equipe recomendada

## 💻 Instalação Local

```bash
# Clone o repositório
git clone https://github.com/seu-usuario/calculadora-vendas.git

# Entre na pasta
cd calculadora-vendas

# Abra o index.html no navegador
# Ou use um servidor local como Live Server
```

## 🌐 Deploy

### Netlify (Recomendado)
1. Faça o push para o GitHub
2. Conecte seu repositório no Netlify
3. Configure o build:
   - **Build command**: (deixe vazio)
   - **Publish directory**: `./`
4. Deploy automático!

### GitHub Pages
1. Vá em Settings → Pages
2. Selecione a branch `main`
3. Salve e aguarde o deploy

## 📱 Responsividade

A calculadora é totalmente responsiva e funciona em:
- 💻 Desktop
- 📱 Mobile
- 📊 Tablet

## 🎯 Validação de Dados

- Validação em tempo real dos campos
- Mensagens de erro claras
- Prevenção de valores inválidos
- Feedback visual durante cálculos

## 📊 Estrutura do Projeto

```
calculadora-vendas/
├── index.html          # Arquivo principal
├── README.md          # Documentação
└── .gitignore         # Arquivos ignorados pelo Git
```

## 🤝 Contribuição

1. Fork o projeto
2. Crie uma branch para sua feature (`git checkout -b feature/AmazingFeature`)
3. Commit suas mudanças (`git commit -m 'Add some AmazingFeature'`)
4. Push para a branch (`git push origin feature/AmazingFeature`)
5. Abra um Pull Request

## 📝 Licença

Este projeto está sob a licença MIT. Veja o arquivo `LICENSE` para mais detalhes.

## 📧 Contato

Seu Nome - [@seuusuario](https://twitter.com/seuusuario) - email@exemplo.com

Link do Projeto: [https://github.com/seu-usuario/calculadora-vendas](https://github.com/seu-usuario/calculadora-vendas)

---

⭐ Se este projeto te ajudou, considere dar uma estrela!
