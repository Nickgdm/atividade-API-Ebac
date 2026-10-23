# Testes de API REST com Postman

Coleção de requisições para praticar a validação da API do Catálogo de Livros durante a formação em Quality Assurance na EBAC.

## Objetivos
- Organizar e executar requisições HTTP.
- Configurar URL e dados de ambiente.
- Conferir códigos de status e conteúdo das respostas.

## Tecnologias
- Postman
- API REST
- JSON

## Pré-requisitos
- Postman instalado.
- API de Catálogo de Livros iniciada localmente.

## Como executar
1. Importe o arquivo `Catálogo de Livros.postman_collection.json` no Postman.
2. Importe `Variáveis.postman_environment.json`.
3. Configure a variável `URL` para `http://localhost:3000/api/`.
4. Configure localmente o valor de autenticação exigido pela API, se aplicável.
5. Execute as requisições e valide as respostas.

## Estrutura do projeto
```text
atividade-API-Ebac/
├── Catálogo de Livros.postman_collection.json
├── Variáveis.postman_environment.json
└── README.md
```

## Desafios práticos
Preparar coleção e ambiente, configurar valores variáveis e validar respostas dos endpoints.

## Boas práticas adotadas
- Separação de coleção e ambiente.
- Reutilização de variáveis para evitar repetir configurações.
- Validação de status HTTP e conteúdo retornado.

## 📚 Aprendizados
A atividade permite praticar testes de API REST com Postman, organizar requisições em coleções e usar variáveis de ambiente para adaptar a execução ao serviço testado.

## Considerações finais
A API precisa estar em execução e acessível no endereço configurado. Não inclua credenciais privadas ou valores de autenticação reais em arquivos versionados.

---

## 🎓 Formação
Atividade desenvolvida durante a formação profissionalizante em **Quality Assurance (QA) pela EBAC — Escola Britânica de Artes Criativas e Tecnologia**.