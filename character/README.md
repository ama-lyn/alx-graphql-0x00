# Exploring and Implementing GraphQL

## Rick and Morty GraphQL Queries - Character Information

This project includes GraphQL queries to fetch information about characters using their IDs from the Rick and Morty API.

### Endpoint

https://rickandmortyapi.com/graphql
---

### Part 1: Querying a Specific Character by ID

Learners will write a GraphQL query to retrieve a specific character’s information using their ID.

#### Instructions:
Use the `character(id: ID!)` field to fetch character details by ID.

#### Fields to Fetch:
- `id`
- `name`
- `status`
- `species`
- `type`
- `gender`

#### Files:
Each character has its own GraphQL query and result file.

- `character-id-1.graphql` + `character-id-1-output.json`
- `character-id-2.graphql` + `character-id-2-output.json`
- `character-id-3.graphql` + `character-id-3-output.json`
- `character-id-4.graphql` + `character-id-4-output.json`

---

### Part 2: Querying a Paginated List of Characters

Learners will create a GraphQL query to retrieve a paginated list of all characters.

#### Instructions:
Use the `characters(page: Int)` field to fetch a paginated list of characters for pages **1, 2, 3, and 4**.

#### Fields to Fetch:
- `id`
- `name`
- `status`
- `image`

#### Files:
Each page has its own GraphQL query and result file.

- `characters-page-1.graphql` + `characters-page-1-output.json`
- `characters-page-2.graphql` + `characters-page-2-output.json`
- `characters-page-3.graphql` + `characters-page-3-output.json`
- `characters-page-4.graphql` + `characters-page-4-output.json`

---