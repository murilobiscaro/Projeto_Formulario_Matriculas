
# Formulário de Matrícula - Estrelas do Amanhã

Um projeto focado em **desenvolvimento e estilização de formulários** em HTML e CSS, demonstrando boas práticas de acessibilidade, organização e design responsivo.

## 📋 Sobre o Projeto

Este projeto implementa um formulário de matrícula para uma escola de educação infantil, utilizando:
- **HTML5 semântico** com fieldsets estruturados
- **CSS modularizado** com arquivos separados por componente
- **Design responsivo** adaptável a diferentes telas
- **Acessibilidade** com labels associadas e semântica adequada
- **Tipografia** elegante com Google Fonts (Poppins)

## 📁 Estrutura do Projeto
.
├── index.html # Estrutura HTML do formulário
├── assets/
│ ├── icons/ # Ícones SVG
│ ├── logo.svg
│ └── Illustration.svg
└── styles/
├── index.css # Estilos gerais
├── global.css # Variáveis e resets
├── forms.css # Estilos do formulário
├── layout.css # Layout principal
└── fields/ # Estilos de componentes específicos
├── index.css
├── buttons.css
├── checkbox.css
├── droparea.css
├── input.css
└── radio.css

## 🎯 Recursos Principais
### Elementos de Formulário Implementados
- ✅ Inputs de texto, data, email e telefone
- ✅ Selects (dropdowns)
- ✅ Textareas
- ✅ Radio buttons com ícones
- ✅ Checkboxes
- ✅ Upload de arquivos com drag-and-drop
- ✅ Validação de email com mensagem de erro

### Seções do Formulário
1. **Informações da Criança** - Dados pessoais e médicos
2. **Endereço Residencial** - Integração com CEP
3. **Informações do Responsável** - Contato e email
4. **Opções de Matrícula** - Turno e esporte

## 🎨 Estilização

O projeto utiliza uma arquitetura CSS modularizada:

- **global.css**: Cores, fontes e propriedades CSS globais
- **layout.css**: Layout principal com grid/flexbox
- **forms.css**: Estilos gerais do formulário
- **fields/**: Estilos específicos de cada tipo de campo

## 🚀 Como Usar

1. Clone ou baixe o projeto
2. Abra `index.html` em um navegador
3. Preencha o formulário com as informações solicitadas

## 💡 Conceitos Demonstrados

- Semântica HTML5 com `<fieldset>` e `<legend>`
- Organização de CSS em arquivos modulares
- Labels associadas com `for` e `id`
- Validação de formulário
- Responsividade com flexbox
- Acessibilidade básica

## 📝 Notas de Desenvolvimento

Este projeto é ideal para:
- Aprender estrutura e estilização de formulários
- Estudar organização de arquivos CSS
- Entender boas práticas de acessibilidade
- Praticar design responsivo

## 🔄 Próximos Passos Sugeridos

- Adicionar validação JavaScript
- Implementar máscara de entrada (CPF, CEP, telefone)
- Integrar com API para busca de CEP
- Adicionar temas de cores
- Implementar confirmação de envio

---

**Desenvolvido com foco em HTML e CSS** | Projeto educacional