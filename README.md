# 🇵🇹 Marcas PT - Data

Uma base de dados colaborativa, de código aberto (Open Data), que reúne marcas 100% portuguesas. 

O objetivo deste projeto é centralizar a informação sobre marcas nacionais.

## 🤝 Como Contribuir

Toda a ajuda é bem-vinda! Se conheces uma marca portuguesa que não está na lista, podes adicioná-la:

1. Faz um **Fork** deste repositório.
2. Vai à pasta `/dados` e abre o ficheiro `.json` da categoria correspondente (ex: `alimentacao.json`).
3. Adiciona um novo bloco com os dados da marca dentro da lista `[ ]`, seguindo a estrutura abaixo.
4. Submete um **Pull Request**.

### Estrutura do Ficheiro JSON

Ao adicionar uma marca, certifica-te de que usas exatamente estas chaves e tipos de dados:

```json
  {
    "nome": "Nome da Marca",
    "descricao": "Uma breve descrição sobre o que a marca faz.",
    "categoria_principal": "Alimentação",
    "ano_fundacao": 2015,
    "disponivel_em": ["Loja Própria", "Supermercados", "Online"],
    "website": "[https://www.site-da-marca.pt](https://www.site-da-marca.pt)",
    "ativo": true
  }
