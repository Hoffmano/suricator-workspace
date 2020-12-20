# suricator-workspace

## Instruções para executar o projeto

1. Clone todos os repositórios que você tem interesse em trabalhar dentro da mesma pasta
    - Vue: https://github.com/Hoffmano/suricator-vue.git
    - Backend: https://github.com/Hoffmano/suricator-backend.git
    - NLP: https://github.com/Hoffmano/suricator-nlp.git
2. Abra um terminal na raiz do repositório `suricator-workspace`
3. Execute `docker-compose up`

## Opcionais

Caso não queira é possivel editar o que será executado pelo docker-compose, não tendo necessidade de inicializar todos os serviços.

Para isso comente o serviço que não tenha interesse dentro do docker-compose.yml

## Estrutura de pastas

- Suricator
  - suricator-workspace
  - suricator-backend
  - suricator-vue
  - suricator-nlp
