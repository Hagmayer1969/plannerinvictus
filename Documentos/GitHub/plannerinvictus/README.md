# 📖 Agenda Inteligência Espiritual

Uma agenda web moderna e intuitiva baseada no livro **"Inteligência Espiritual"** de Kris Vallotton.

![Agenda Preview](https://img.shields.io/badge/Status-Ativo-success)
![License](https://img.shields.io/badge/License-MIT-blue)

## ✨ Funcionalidades

### 📅 Calendário Visual
- Grid interativo com todos os dias do mês
- Indicadores visuais para dias com registros
- Navegação rápida entre dias e meses

### 📚 12 Lições Mensais
Cada mês apresenta uma lição de Inteligência Espiritual:
- Janeiro: Descobrindo Sua Identidade Espiritual
- Fevereiro: O Poder da Renovação da Mente
- Março: Desenvolvendo Discernimento Espiritual
- E mais 9 lições...

### 💭 Frases Diárias
365 frases inspiradoras baseadas nos conceitos do livro, uma para cada dia do ano.

### 📝 Registro Diário
- 🙏 **3 Motivos de Gratidão**
- 🎯 **Alvo do Dia**
- 📈 **3 Áreas de Melhoria**

### 🤖 Resumo Mensal com IA
Integração com Google Gemini para gerar resumos inteligentes que:
- Identificam padrões de gratidão
- Analisam alinhamento de objetivos
- Fornecem insights espirituais
- Sugerem próximos passos

## 🚀 Como Usar

### Instalação Local

1. Clone o repositório:
```bash
git clone https://github.com/SEU_USUARIO/plannerinvictus.git
cd plannerinvictus
```

2. Inicie um servidor local:
```bash
python3 -m http.server 8000
```

3. Acesse no navegador:
```
http://localhost:8000
```

### Configurar Resumo com IA (Opcional)

1. Obtenha uma chave da API do Gemini:
   - Acesse: https://makersuite.google.com/app/apikey
   - Crie uma chave gratuita

2. Configure no arquivo `gemini-config.js`:
```javascript
const GEMINI_API_KEY = 'sua-chave-aqui';
```

## 🎨 Design

- **Tema**: Modo escuro premium
- **Cores**: Gradientes vibrantes (roxo, azul, rosa)
- **Efeitos**: Glassmorphism, animações suaves
- **Responsivo**: Funciona em desktop, tablet e mobile

## 📁 Estrutura do Projeto

```
plannerinvictus/
├── index.html          # Estrutura principal
├── styles.css          # Design e estilos
├── app.js             # Lógica da aplicação
├── gemini-config.js   # Configuração da IA
└── README.md          # Este arquivo
```

## 🛠️ Tecnologias

- **HTML5**: Estrutura semântica
- **CSS3**: Design moderno com variáveis CSS
- **JavaScript**: Vanilla JS (sem frameworks)
- **Google Gemini API**: Resumos com IA
- **LocalStorage**: Persistência de dados

## 💾 Armazenamento de Dados

Todos os dados são armazenados **localmente** no navegador usando LocalStorage:
- ✅ Privacidade total
- ✅ Funciona offline
- ✅ Sem necessidade de backend

## 🌟 Recursos Especiais

- **Auto-save**: Salvamento automático após 2 segundos
- **Atalhos de teclado**: 
  - `Ctrl/Cmd + S`: Salvar
  - `Alt + ←/→`: Navegar entre dias
- **Indicadores visuais**: Pontos verdes em dias com registros
- **Resumos mensais**: Compilação automática de dados

## 📖 Sobre o Livro

"Inteligência Espiritual" de Kris Vallotton explora como desenvolver uma compreensão mais profunda de si mesmo e do divino, integrando sabedoria espiritual na vida prática.

## 🤝 Contribuindo

Contribuições são bem-vindas! Sinta-se livre para:
- Reportar bugs
- Sugerir novas funcionalidades
- Melhorar a documentação
- Adicionar mais frases inspiradoras

## 📄 Licença

Este projeto está sob a licença MIT. Veja o arquivo `LICENSE` para mais detalhes.

## 👤 Autor

Desenvolvido com 💜 para crescimento espiritual

---

**⭐ Se este projeto te ajudou, considere dar uma estrela!**
