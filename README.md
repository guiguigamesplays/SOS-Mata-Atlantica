SOS-Mata-Atlantica
Plataforma web acadêmica para divulgação de projetos e ações da Fundação SOS Mata Atlântica.
Fundação SOS Mata Atlântica

Projeto acadêmico de desenvolvimento de uma plataforma web para a **Fundação SOS Mata Atlântica**, desenvolvido como atividade da disciplina de desenvolvimento web.

O projeto tem como objetivo criar uma presença digital organizada, acessível e informativa, apresentando a organização, seus projetos ambientais, formas de participação e informações para voluntários e apoiadores.

---

Sobre o projeto
A plataforma foi desenvolvida com foco na divulgação das ações relacionadas à conservação da Mata Atlântica.

O sistema apresenta:
* Informações institucionais;
* Missão e áreas de atuação;
* Projetos ambientais;
* Informações sobre voluntariado;
* Formas de contribuição;
* Indicadores de impacto;
* Informações de contato;
* Formulário de cadastro;
* Estrutura preparada para futuras funcionalidades com CSS3 e JavaScript.

---

Objetivos

Objetivo geral

Desenvolver uma plataforma web para apresentar informações sobre a Fundação SOS Mata Atlântica e facilitar o acesso da sociedade às suas iniciativas.

Objetivos específicos
* Aplicar os fundamentos do HTML5;
* Utilizar estruturas semânticas;
* Criar formulários utilizando recursos nativos do HTML5;
* Aplicar conceitos de acessibilidade;
* Organizar arquivos e recursos de forma profissional;
* Preparar a estrutura para implementação de CSS3;
* Preparar a estrutura para implementação de JavaScript;
* Utilizar controle de versão através do Git e GitHub.

---

Páginas do projeto

Página Inicial — `index.html`

Apresenta:
* Sobre a Fundação;
* Missão;
* História;
* Principais causas;
* Áreas de atuação;
* Informações institucionais;
* Transparência;
* Formas de ajudar;
* Contato.

Projetos — `projetos.html`

Apresenta:
* Projetos de restauração;
* Conservação da Mata Atlântica;
* Monitoramento de rios;
* Parques e reservas;
* Proteção ambiental;
* Voluntariado;
* Formas de contribuição;
* Indicadores de impacto.

Cadastro — `cadastro.html`
Possui formulário para cadastro do usuário contendo:
* Nome completo;
* E-mail;
* CPF;
* Telefone;
* Data de nascimento;
* Endereço;
* CEP;
* Cidade;
* Estado;
* Perfil de participação;
* Área de interesse;
* Mensagem;
* Aceite dos termos.

---

Tecnologias utilizadas
Nesta primeira etapa do projeto:
* HTML5
* Git
* GitHub

Tecnologias previstas para as próximas etapas
* CSS3
* JavaScript

---

Acessibilidade
O projeto utiliza recursos básicos de acessibilidade, incluindo:
* Estrutura semântica do HTML5;
* Hierarquia lógica de títulos;
* Texto alternativo nas imagens;
* Elementos `label` associados aos campos;
* Navegação através de links;
* Agrupamento de campos com `fieldset` e `legend`;
* Uso de elementos semânticos como `header`, `nav`, `main`, `section`, `article` e `footer.

---

Responsividade
A estrutura HTML foi desenvolvida considerando a futura implementação de um layout **mobile-first** com CSS3.

A versão atual utiliza:

html
<meta name="viewport" content="width=device-width, initial-scale=1.0">


A responsividade visual será implementada na etapa de CSS3.

---

Validação do formulário

O formulário utiliza recursos nativos do HTML5, como:
* `required`
* `type="email"`
* `type="tel"`
* `type="date"`
* `pattern`
* `minlength`
* `maxlength`

Também foram utilizados padrões para:
* CPF: `000.000.000-00`
* Telefone: `(00) 00000-0000`
* CEP: `00000-000`

As máscaras automáticas serão implementadas posteriormente utilizando JavaScript.

---

Estrutura do projeto
sos-mata-atlantica/
│
├── index.html
├── projetos.html
├── cadastro.html
│
├── imagens/
│   ├── logo-sos.jpg
│   ├── mata-atlantica.jpg
│   ├── restauracao.jpg
│   ├── rios.jpg
│   ├── parques.jpg
│   └── voluntariado.jpg
│
└── README.md

---

Próximas etapas
Etapa 1 — HTML5

* [x] Estrutura das páginas
* [x] Navegação
* [x] Conteúdo institucional
* [x] Projetos
* [x] Formulário
* [x] Validação nativa
* [x] Estrutura semântica

Etapa 2 — CSS3
* [ ] Identidade visual
* [ ] Layout responsivo
* [ ] Mobile-first
* [ ] Flexbox
* [ ] Grid
* [ ] Media queries
* [ ] Tipografia
* [ ] Cores
* [ ] Cards de projetos
* [ ] Menu responsivo

Etapa 3 — JavaScript
* [ ] Máscara de CPF
* [ ] Máscara de telefone
* [ ] Máscara de CEP
* [ ] Validação personalizada
* [ ] Interações
* [ ] Menu mobile
* [ ] Elementos dinâmicos
* [ ] Sistema de progresso das campanhas

---

Tema - Conservação da Mata Atlântica

O projeto foi desenvolvido com finalidade acadêmica e utiliza a Fundação SOS Mata Atlântica como organização de referência para a construção da plataforma.

---

Integrantes
* Guilherme Santos Santarelli
* Bernardo Lima
* Nome do integrante 3

---

Projeto acadêmico
Projeto desenvolvido para a disciplina de Desenvolvimento Web.
Tecnologia principal: HTML5
