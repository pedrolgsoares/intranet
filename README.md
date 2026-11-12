# 💬 Intranet Social & Comunicação Interna

> Plataforma web full-stack de comunicação interna, engajamento e gestão do conhecimento corporativo, desenvolvida com **Java 25 (Spring Boot)** e **React 20 (TypeScript)**.

`Java 25` • `Spring Boot 3` • `React 20` • `TypeScript 5` • `PostgreSQL 16` • `Docker` • `License: MIT`

> 🚧 **Status do Projeto:** Em desenvolvimento inicial.

---

## 📋 Sobre o Projeto

É uma intranet social projetada para aproximar equipes, centralizar a comunicação da empresa e facilitar o acesso a documentos importantes em um ambiente dinâmico e interativo.

O projeto combina a experiência de uma **rede social corporativa** (feed, comunicados, interações) com a segurança de um **portal interno** (controle de cargos e repositório por departamentos).

### ✨ Funcionalidades Planejadas
- **Feed Corporativo & Comunicados:** Linha do tempo para publicação de novidades, avisos oficiais, conquistas de equipe e anexos.
- **Interações Sociais:** Sistema de curtidas (reações), comentários em publicações e fixação de avisos importantes no topo.
- **Comunidades / Departamentos:** Espaços dedicados para cada setor (RH, TI, Marketing, Operações) com publicações e arquivos específicos.
- **Diretório de Colaboradores:** Perfis internos com foto, cargo, departamento, habilidades e status.
- **Repositório Rápido:** Área organizada para manuais, políticas e documentos institucionais com download seguro.
- **Controle de Acesso (RBAC):** Perfis distintos (`ADMIN`, `GESTOR`, `COLABORADOR`) definindo quem pode publicar avisos oficiais ou moderar conteúdos.

---

## 🛠️ Stack Tecnológica

* **Back-end:** Java 25, Spring Boot, Spring Security (JWT), Spring Data JPA.
* **Front-end:** React 20, TypeScript, Vite, Tailwind CSS.
* **Banco de Dados & Storage:** PostgreSQL, MinIO (armazenamento de fotos de perfil, imagens de posts e anexos).
* **Infraestrutura:** Docker e Docker Compose.

---

## 🏗️ Arquitetura Resumida

```text
[ React 20 ] ──(REST / JWT)──► [ API Java 25 ] ──► [ PostgreSQL ] (Posts, Comentários, Usuários)
                                      │
                                      └──────────► [ MinIO / S3 ] (Mídias e Anexos)
```

---

## 🚀 Como Rodar (Em Breve)

As instruções detalhadas de execução com Docker serão adicionadas assim que a estrutura base do back-end e front-end estiver concluída.

---

## 📄 Licença

Este projeto está sob a licença **MIT**. Veja o arquivo [LICENSE](LICENSE) para mais detalhes.

---

## 👨‍💻 Autor

Desenvolvido por **[Pedro Lucas]**  
🔗 [LinkedIn](https://linkedin.com) • 💻 [GitHub](https://github.com)
