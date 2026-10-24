# Testes de API REST com Postman

Coleção de requisições para praticar a validação da API do Catálogo de Livros durante a formação em Quality Assurance na EBAC.

## Objetivos
- Organizar e executar requisições HTTP.
- Configurar URL e dados de ambiente.
- Validar códigos de status, estrutura JSON e dados retornados.

## Tecnologias
- Postman
- API REST
- JSON

## Pré-requisitos
- Postman instalado.
- API de Catálogo de Livros iniciada localmente e acessível.

## Como executar
1. Importe `Catálogo de Livros.postman_collection.json` no Postman.
2. Importe `Variáveis.postman_environment.json`.
3. Selecione o ambiente importado e configure `URL` para `http://localhost:3000/api/`, caso esse seja o endereço local da API.
4. Configure localmente os valores de autenticação exigidos pela API, sem salvar tokens reais em arquivos versionados.
5. Execute as requisições individualmente ou pela coleção e confira o status HTTP e o corpo da resposta.

## Estrutura do projeto
```text
atividade-API-Ebac/
├── Catálogo de Livros.postman_collection.json
├── Variáveis.postman_environment.json
└── README.md
```

## Cenários de teste
A coleção contempla operações de consulta e manipulação de dados por meio de requisições HTTP. Para cada cenário, confira se o status retornado e os dados do JSON correspondem ao resultado esperado. Em testes de criação, atualização e exclusão, verifique também o estado final do recurso quando a API oferecer uma consulta apropriada.

## Boas práticas
- Separar coleção e ambiente.
- Reutilizar variáveis para reduzir configurações repetidas.
- Não versionar credenciais, tokens ou segredos.
- Preferir asserções sobre propriedades e valores JSON esperados, além de verificações genéricas de texto.
- Restaurar os dados de teste quando os cenários alterarem recursos persistentes.

## 📚 Aprendizados
A atividade permite praticar testes de API REST com Postman, organização de coleções, variáveis de ambiente, autenticação e validação de respostas.

## Considerações finais
A API precisa estar em execução e acessível no endereço configurado. Os cenários podem depender de dados existentes; ajuste a URL e os valores de ambiente conforme a instalação utilizada.

---

## 🎓 Formação
Atividade desenvolvida durante a formação profissionalizante em **Quality Assurance (QA) pela EBAC — Escola Britânica de Artes Criativas e Tecnologia**.
