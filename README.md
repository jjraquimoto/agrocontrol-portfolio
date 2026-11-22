<div align="center">

# 🐄 AgroControl

### Gestão pecuária, da fazenda ao celular

**Projeto acadêmico de desenvolvimento de software • Aplicação Web e Android**

[**🌐 Acessar demonstração online**](https://jjraquimoto.github.io/agrocontrol/) · [**💻 Perfil no GitHub**](https://github.com/jjraquimoto)

**JavaScript** · **HTML5** · **CSS3** · **Supabase** · **PostgreSQL** · **Capacitor** · **Android**

</div>

---

## 📌 Sobre o projeto

O **AgroControl** é um sistema de gestão pecuária desenvolvido como projeto acadêmico de Ciência da Computação. Seu objetivo é centralizar informações do rebanho e facilitar o acompanhamento das atividades da propriedade rural em uma interface adaptada ao computador e ao celular.

A ideia é evitar anotações espalhadas e o recadastramento dos mesmos animais em diferentes controles. Cada animal possui um cadastro central, que pode ser utilizado nos módulos relacionados.

## ✨ Funcionalidades

| Módulo | O que permite fazer |
| --- | --- |
| **Rebanho** | Cadastrar, consultar e acompanhar animais e seus históricos. |
| **Lotes** | Organizar animais em grupos e acompanhar sua distribuição. |
| **Sanidade** | Registrar procedimentos sanitários, vacinas e próximas aplicações. |
| **Produção** | Registrar pesagens e produção de leite. |
| **Movimentações** | Acompanhar compras, vendas, transferências e óbitos. |
| **Dashboard** | Visualizar os principais indicadores da propriedade. |
| **Relatórios** | Consultar informações consolidadas e gerar exportações. |
| **Web e Android** | Acessar o sistema em diferentes dispositivos, com layout responsivo. |

## 🛠️ Tecnologias e soluções

- **HTML, CSS e JavaScript:** construção da aplicação e das interfaces responsivas.
- **Supabase (PostgreSQL e autenticação):** serviços de nuvem, contas e persistência dos registros.
- **Row Level Security (RLS):** regras de acesso aos dados no banco, conforme as permissões configuradas.
- **Capacitor:** empacotamento da aplicação web como aplicativo Android.
- **Armazenamento local e sincronização:** suporte ao uso com conectividade instável e ao envio posterior de alterações.
- **Web Crypto API:** proteção criptográfica do cofre local, quando configurado pelo usuário.
- **GitHub Pages:** publicação da versão web.

## 🧩 Decisões de desenvolvimento

**Cadastro único por animal.** Os registros de sanidade, produção e movimentações se relacionam ao mesmo cadastro, diminuindo a duplicação de informações.

**Experiência mobile.** A interface foi adaptada para telas de diferentes tamanhos, com navegação e formulários apropriados ao uso em celular.

**Conectividade rural.** O projeto contempla armazenamento local e mecanismos de sincronização para situações de conexão intermitente. A validação de conflitos e a segurança de dados dependem de testes contínuos.

**Organização por propriedade.** O projeto utiliza autenticação e políticas de acesso para separar os registros conforme as permissões definidas no banco.

## 🚀 Demonstração

**Versão web:** [Abrir o AgroControl](https://jjraquimoto.github.io/agrocontrol/)

> A demonstração utiliza o aplicativo publicado e pode solicitar autenticação. Não utilize dados pessoais, financeiros ou registros reais de terceiros em contas de demonstração.

## 📱 Capturas de tela

As capturas do dashboard, do cadastro de animais e da versão Android serão adicionadas a esta apresentação. Elas devem ser imagens do sistema real, sem dados pessoais de produtores ou animais identificáveis.

## 📚 Contexto e evolução

O AgroControl nasceu como trabalho de faculdade e evoluiu com melhorias incrementais de interface, cadastro, persistência em nuvem, aplicativo Android e experiência offline.

**Versão de referência desta apresentação:** 6.3.2. A continuidade do projeto inclui testes em novos dispositivos e aperfeiçoamentos de estabilidade e segurança.

## 🔒 Código-fonte e uso

Este repositório é destinado à **apresentação do projeto no portfólio**, sem disponibilização do código-fonte completo. O link da demonstração dá acesso à aplicação web publicada, cujos arquivos enviados ao navegador são naturalmente acessíveis ao visitante.

*Projeto acadêmico apresentado como experiência prática de desenvolvimento de software.*
