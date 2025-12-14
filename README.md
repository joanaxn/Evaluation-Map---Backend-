# Evaluation Map System — Backend  
Backend desenvolvido em **Java Spring Boot** para gestão dos mapas de avaliação do Departamento de Ciência e Tecnologia da Universidade Portucalense.

Este sistema permite que administradores e coordenadores criem, editem e submetam mapas de avaliação, garantindo o cumprimento das regras académicas e evitando conflitos de datas, horas e salas.

---

## Tecnologias Utilizadas

### **Back-end**
- Java 17+
- Spring Boot
- Spring Web
- Spring Data JPA
- MySQL
- Maven

### **Outras ferramentas**
- Hibernate ORM
- MySQL Workbench
- Git & GitHub

---

## Funcionalidades do Backend

### Gestão de utilizadores
- Login para dois perfis: **Administrador** e **Coordenador**
- Controlo de permissões por tipo de utilizador

### Gestão de Mapas de Avaliação
- Criação de mapas por curso e semestre
- Registo de assiduidade, tipo de avaliação e momentos avaliativos
- Submissão final quando todas as UCs estiverem completas

### Validação e Regras
- Conflitos automáticos:
  - Mesma data de avaliação entre anos diferentes
  - Menos de 24h entre avaliações do mesmo curso (exceto apresentações)
- Campos obrigatórios verificados antes de submissão

### Atribuição Automática de Salas
- Sala definida conforme:
  - Tipo de avaliação  
  - Número de computadores  
  - Disponibilidade  

---
## Perfis de Utilizador

### Administrador (ambiente de teste)

Permissões:
- Criar coordenadores
- Criar e editar mapas de qualquer curso
- Aceder a todas as funcionalidades do sistema

**Credenciais:**
Username: adm
Password: 123

# NOTAS
Este projeto foi desenvolvido em equipa, tendo estado envolvida no desenvolvimento backend deste sistema.



