# Wireframe
# Entregaveis incluidos

- wireframes das tipologias de pagina;
- esquema global de navegacao;
- separacao entre area publica e areas privadas;
- master CSS unico para todas as paginas;
- documento explicativo das opcoes de desenho e desenvolvimento.

## Base funcional identificada nos trabalhos anteriores

Entidades:

- Companhia
- Aeroporto
- Voo
- Reserva
- Passageiro
- Utilizador
- LogSistema

Perfis:

- Publico
- Passageiro
- Responsavel da companhia
- Gestor / administrador


### Area publica

- Pagina inicial / pesquisa de voos
- Resultados de pesquisa
- Detalhe do voo
- Login / registo

### Area privada do passageiro

- Dashboard do passageiro
- Comparacao de voos
- Efetuar reserva
- Minhas reservas
- Historico de viagens
- Cancelamento de reserva
- Perfil

### Area privada da companhia

- Dashboard da companhia
- Inserir novo voo
- Anular voo
- Consultar reservas
- Relatorios operacionais

### Area privada da administracao

- Dashboard administrativo
- Inserir companhia
- Ativar / desativar companhia
- Inserir aeroporto
- Inserir passageiro
- Relatorio geral
- Log do sistema

## Fluxos principais

`Inicio/Pesquisa` -> `Resultados` -> `Detalhe do voo` -> `Login/Registo` -> `Reserva`

`Login Passageiro` -> `Dashboard Passageiro` -> `Comparar voos / Minhas reservas / Historico`

`Login Companhia` -> `Dashboard Companhia` -> `Inserir voo / Anular voo / Reservas`

`Login Administrador` -> `Dashboard Admin` -> `Companhias / Aeroportos / Passageiros / Relatorios / Log`

## Restricoes por perfil

- Publico: pesquisa e consulta apenas
- Passageiro: reservas e historico pessoal
- Companhia: gestao exclusiva da propria operacao
- Administrador: acesso global a entidades e auditoria
