# 🎲 Criador de Ficha de RPG
### Laboratório de CSS Externo e UI/UX

Este repositório contém o código-fonte de uma aplicação web conceitual focada em design, arquitetura de software front-end e estruturação de interfaces. O projeto foi desenvolvido com objetivos acadêmicos, servindo como uma **Prova de Conceito (PoC)** e ambiente controlado para o aprendizado prático de organização de estilos via **CSS Externo**, modularização de arquivos e boas práticas de desenvolvimento web.

</div>

---

> ⚠️ **NOTA IMPORTANTE (PROTÓTIPO):** 
> O código disponibilizado aqui é uma **versão preliminar, simplificada e serve como um protótipo experimental** para validação de conceitos de design. Ele foi projetado especificamente para testar o isolamento de folhas de estilo, a reutilização de classes globais e a navegação estruturada entre múltiplas páginas, funcionando como a **fundação visual para um sistema web final** integrado e completo.

---

## 🎯 Objetivos do Projeto

*   **Estudo de CSS Externo:** Validar os benefícios da separação de responsabilidades, isolando toda a camada de apresentação em arquivos `.css` independentes para manter o código HTML limpo, semântico e focado na estrutura.
*   **Modularização e Arquitetura:** Explorar a organização profissional de um projeto front-end, agrupando recursos visuais, subpáginas e folhas de estilo em diretórios específicos e padronizados.
*   **Navegação e Fluxo de Usuário:** Estruturar a transição suave e consistente entre a página inicial e as demais seções do site, garantindo uma identidade visual unificada em todas as telas da aplicação.

---

## 📂 Estrutura de Arquivos e Pastas

A organização do repositório foi planejada para simular o ecossistema de um site real em produção, dividindo-se em componentes lógicos:

```plaintext
├── 📁 Img_folder/          # Diretório de mídia para imagens e assets visuais
├── 📁 pages/               # Subpáginas internas que expandem o conteúdo do site
├── 📁 stylesheets/         # Folhas de estilo (.css) externas e centralizadas
├── 📄 index.html           # Página principal e ponto de entrada da aplicação
└── 📄 README.md            # Documentação do projeto
```

### 🔍 Detalhes dos Componentes:
*   `index.html`: A porta de entrada do site, responsável por carregar os estilos globais e apresentar a introdução da plataforma.
*   `/stylesheets`: Centraliza as regras de layout, tipografia e paleta de cores de forma externa, evitando redundância de código.
*   `/pages`: Páginas secundárias que herdam as mesmas referências de estilo globais para manter a consistência visual.

---

## 🛠️ Tecnologias e Ferramentas

| Tecnologia / Ferramenta | Função no Projeto |
| :--- | :--- |
| **HTML5** | Estruturação semântica de tags para garantir acessibilidade e legibilidade de tela. |
| **CSS3** | Estilização externa com foco em layouts responsivos (Flexbox) e reaproveitamento de código. |
| **Vercel** | Plataforma em nuvem utilizada para a automação de deploy e hospedagem contínua. |

---

## 🔗 Link do Deploy

O projeto está publicado e pode ser visualizado em tempo real pelo link abaixo:

🚀 **Acesse o protótipo online:** [Clique aqui para visualizar o site](https://responsive-flexbox-layout-webdesign.vercel.app/)

---

<div align="center">
  <sub>Desenvolvido para fins de estudo em Web Design e Desenvolvimento Front-End.</sub>
</div>
