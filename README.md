# 📝 Formulário de Briefing - HTML & CSS

<img width="1916" height="950" alt="Captura de tela 2025-10-10 114020" src="https://github.com/user-attachments/assets/55831244-4f4e-42bb-8442-ae5379b4c706" />

> Formulário web completo e estilizado para captação de informações de clientes, desenvolvido como parte do curso de HTML e CSS da Alura.

## 📋 Sobre o Projeto

Este projeto consiste em um **formulário de briefing de serviços** profissional, criado para coletar informações detalhadas de clientes interessados em serviços digitais como Landing Pages, SEO, Tráfego Pago e Criação de Sites.

O formulário demonstra boas práticas de desenvolvimento web, incluindo validação de dados, acessibilidade e design responsivo.

> 🎓 **Projeto desenvolvido como parte do curso de HTML e CSS da Alura**, aplicando conhecimentos sobre formulários, validações e estilização avançada.

## 🎯 Objetivo

Criar um formulário funcional e esteticamente agradável que demonstre o domínio de:
- Estruturação semântica em HTML
- Estilização avançada com CSS
- Validação de formulários
- Experiência do usuário (UX)

## 🚀 Tecnologias Utilizadas

- **HTML5** - Estrutura semântica e validação nativa
- **CSS3** - Estilização, efeitos e layout
- Fontes **Sans-serif** do sistema

## ✨ Funcionalidades

### 📥 Campos do Formulário

- ✅ **Dados Pessoais**
  - Nome e Sobrenome (campos obrigatórios)
  - Email (validação de formato)
  - Telefone (validação de 10-11 dígitos com DDD)

- ✅ **Serviços Disponíveis** (Radio buttons)
  - Landing Page
  - SEO
  - Tráfego Pago
  - Criação de Sites

- ✅ **Tipo de Acompanhamento** (Select)
  - Mensal
  - Bimestral
  - Trimestral

- ✅ **Canais de Conhecimento** (Checkboxes)
  - Instagram
  - LinkedIn
  - WhatsApp
  - Twitter
  - Site

- ✅ **Área de Texto**
  - Descrição do diferencial (mínimo 30 caracteres)

### 🎨 Recursos de Design

- ✅ Paleta de cores roxo/lilás profissional
- ✅ Efeitos de hover e focus nos campos
- ✅ Sombras e bordas arredondadas
- ✅ Botão de submit estilizado com animações
- ✅ Layout organizado com fieldsets
- ✅ Validação visual de campos

## 🎨 Paleta de Cores

```css
--cor-titulo: #380B61;        /* Roxo escuro (títulos) */
--cor-principal: #59429d;     /* Roxo médio (campos e textos) */
--cor-hover: #CCBBFF;         /* Lilás claro (hover) */
--cor-focus: #E0E0F8;         /* Lilás muito claro (focus) */
--cor-fundo: #F0F8FF;         /* Azul alice (background) */
```

## 📁 Estrutura do Projeto

```
formularios_html-css/
│
├── index.html          # Estrutura do formulário
└── formulario.css      # Estilos e layout
```

## 💻 Como Usar

### Opção 1: Visualização Direta

1. Clone o repositório:
```bash
git clone https://github.com/victorarielima/Formularios_HTML-CSS.git
```

2. Navegue até a pasta:
```bash
cd Formularios_HTML-CSS
```

3. Abra o arquivo `index.html` no navegador

### Opção 2: Servidor Local

```bash
# Usando Python
python -m http.server 8000

# Usando Node.js
npx serve
```

Acesse `http://localhost:8000` no navegador

## 🔍 Validações Implementadas

| Campo | Validação |
|-------|-----------|
| Nome/Sobrenome | `required` - Campo obrigatório |
| Email | `type="email"` - Formato de email válido |
| Telefone | `pattern="\d{10,11}"` - 10 ou 11 dígitos (fixo/celular) |
| Select | `required` - Seleção obrigatória |
| Textarea | `minlength="30"` - Mínimo 30 caracteres |

## 📚 Conceitos Aplicados

Durante o desenvolvimento deste formulário, foram aplicados:

### HTML
- ✅ Elementos semânticos (`<fieldset>`, `<label>`, `<form>`)
- ✅ Tipos de input diversos (text, email, tel, radio, checkbox)
- ✅ Atributos de validação (required, pattern, minlength)
- ✅ Select com opções
- ✅ Textarea configurável
- ✅ Agrupamento lógico com fieldsets

### CSS
- ✅ Seletores avançados
- ✅ Pseudo-classes (`:hover`, `:focus`, `:before`, `:after`)
- ✅ Box model completo
- ✅ Posicionamento (absolute, relative)
- ✅ Transform e animações
- ✅ Box-shadow e text-shadow
- ✅ Clearfix com pseudo-elementos

## 🎓 Aprendizados do Curso

Este projeto foi desenvolvido no curso de **HTML e CSS** da [Alura](https://www.alura.com.br/), onde foram explorados:

- 📌 Criação de formulários completos
- 📌 Validação de dados no front-end
- 📌 Estilização de elementos de formulário
- 📌 Melhoria da experiência do usuário
- 📌 Boas práticas de acessibilidade
- 📌 Organização e estruturação de código

## 🎯 Casos de Uso

Este formulário pode ser adaptado para:

- 📊 Captação de leads
- 🤝 Briefing de projetos
- 📋 Cadastro de clientes
- 📝 Coleta de informações comerciais
- 💼 Propostas comerciais
- 🎨 Orçamentos de serviços

## 🔧 Possíveis Melhorias Futuras

- [ ] Adicionar responsividade para mobile
- [ ] Integração com back-end (PHP, Node.js)
- [ ] Máscaras de input com JavaScript
- [ ] Confirmação visual após envio
- [ ] Validação em tempo real
- [ ] Acessibilidade ARIA
- [ ] Modo escuro (dark mode)

## 👨‍💻 Autor

**Victor Ariel**

- GitHub: [@victorarielima](https://github.com/victorarielima)

## 📄 Licença

Este projeto foi desenvolvido para fins educacionais como parte de um curso da Alura.

## 🤝 Contribuições

Contribuições são bem-vindas! Sinta-se à vontade para:

1. Fazer um fork do projeto
2. Criar uma branch para sua feature (`git checkout -b feature/MinhaFeature`)
3. Commit suas mudanças (`git commit -m 'Adiciona MinhaFeature'`)
4. Push para a branch (`git push origin feature/MinhaFeature`)
5. Abrir um Pull Request

## 📖 Recursos Adicionais

### Documentação Útil
- [MDN - Formulários HTML](https://developer.mozilla.org/pt-BR/docs/Learn/Forms)
- [MDN - Validação de Formulários](https://developer.mozilla.org/pt-BR/docs/Learn/Forms/Form_validation)
- [W3C - Input Types](https://www.w3.org/TR/html52/sec-forms.html)

### Dicas de Boas Práticas
- 💡 Sempre use labels para acessibilidade
- 💡 Valide dados no front-end E back-end
- 💡 Forneça feedback visual claro ao usuário
- 💡 Agrupe campos relacionados com fieldsets
- 💡 Use placeholder com moderação

---

<div align="center">
  Desenvolvido com 💜 durante o curso da Alura
</div>
