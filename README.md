# Tech Product Backlog & Requisitos Ágeis 📋🎯

Repositório estruturado com documentação de gestão de produto, levantamento de requisitos, mapeamento de regras de negócio e priorização de funcionalidades (framework Scrum/Kanban).

## 🚀 Conteúdo
- **User Stories (Histórias de Utilizador)** no padrão *Como / Quero / Para que*.
- **Critérios de Aceitação** detalhados (Dado que / Quando / Então).
- **Matriz de Priorização (RICE / MoSCoW)** para gestão de sprint.

---

### 📝 Exemplo de História de Utilizador (US-01)

**Título:** Autenticação de Usuário via API REST  
**Como** cliente da plataforma móvel,  
**Quero** realizar login com e-mail e palavra-passe,  
**Para que** eu possa aceder de forma segura aos meus documentos processados por IA.

#### ✅ Critérios de Aceitação:
1. **Sucesso:** Se as credenciais estiverem corretas, a API deve retornar o código `200 OK` e um token JWT válido.
2. **Erro de Validação:** Se a palavra-passe estiver errada, deve retornar `401 Unauthorized` com mensagem explicativa.
3. **Segurança:** A palavra-passe não deve trafegar em texto simples (deve utilizar HTTPS).
