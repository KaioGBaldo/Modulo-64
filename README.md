# 📦 Django REST Framework - API de Produtos Profissional

Este projeto demonstra a criação de uma API robusta e padronizada utilizando **Django** e **Django REST Framework (DRF)**. O foco principal é a automação de rotas e a serialização de modelos para fornecer uma interface de dados eficiente para aplicações front-end ou mobile.

---

# 📝 Resumo (Resume)
Neste projeto, implementei o fluxo completo de uma API de produtos utilizando o padrão **Model-View-Serializer**. Defini o esquema de dados através do `models.Model`, garantindo a persistência em banco de dados relacional. Utilizei o **ModelSerializer** para converter objetos complexos em JSON e o **ModelViewSet** para gerenciar a lógica de negócio de forma simplificada. A navegação foi automatizada com o **DefaultRouter**, que gera automaticamente os endpoints de listagem, criação, edição e exclusão de produtos.



## 🚀 Tecnologias e Ferramentas (Tech Stack)

[![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)](https://www.python.org/)
[![Django](https://img.shields.io/badge/Django-092E20?style=for-the-badge&logo=django&logoColor=white)](https://www.djangoproject.com/)
[![DRF](https://img.shields.io/badge/Django_REST_Framework-A30000?style=for-the-badge&logo=django&logoColor=white)](https://www.django-rest-framework.org/)

## 📋 Funcionalidades em Destaque
* **Modelagem de Dados Relacional:** Uso do ORM do Django para definir produtos com campos tipados como `DecimalField` (para precisão monetária) e `TextField`.
* **Serialização Inteligente (ModelSerializer):** Mapeamento automático dos campos do modelo para o formato JSON, facilitando a comunicação com o Front-End.
* **ViewSets Poderosos:** Implementação do `ModelViewSet` para fornecer todas as operações de um CRUD completo (GET, POST, PUT, PATCH, DELETE) nativamente.
* **Roteamento Automático (DefaultRouter):** Geração dinâmica de URLs padronizadas, eliminando a necessidade de declarar cada endpoint manualmente.
* **Consistência de Dados:** Configuração de `default_auto_field` para gerenciamento eficiente de chaves primárias (PKs) em larga escala.
* **Interface Administrativa:** Integração nativa com o painel do Django para gestão visual dos produtos cadastrados no banco de dados.



---

# 👨‍💻 Sobre mim (About Me)
Olá, meu nome é **Kaio**, tenho 22 anos. Como meu foco principal é o **Back-End com Python**, dominar o Django REST Framework é um diferencial crucial. Minha experiência anterior com **React** e **Redux** me permite entender exatamente como a API deve ser estruturada para facilitar o consumo no Front-End. Ao construir Serializers no Django, percebo a semelhança com a organização de dados que eu fazia no React, mas agora com o poder de persistência e segurança que só um back-end profissional oferece.

### Entre em contato (Contact me)

[![LinkedIn](https://img.shields.io/badge/LinkedIn-000?style=for-the-badge&logo=linkedin&logoColor=092E20)](https://linkedin.com/in/kaio-grativol-baldo-071a74150/)
[![Instagram](https://img.shields.io/badge/Instagram-000?style=for-the-badge&logo=instagram&logoColor=092E20)](https://www.instagram.com/kaiull__/)
[![GitHub](https://img.shields.io/badge/Github-000?style=for-the-badge&logo=github&logoColor=092E20)](https://github.com/SeuUsuarioAqui)

---
*Projeto desenvolvido para consolidar o desenvolvimento de APIs RESTful utilizando as melhores práticas do Django REST Framework.*
