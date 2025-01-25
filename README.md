# :checkered_flag: NOME DO PROJETO

O Sistema de Gestão de Feiras Locais é uma plataforma projetada para auxiliar na organização de feiras locais. 
Ele permite o cadastro de expositores, exibição de calendários de feiras e divulgação de eventos, visando melhorar a eficiência e a gestão desses eventos.

## :technologist: Membros da equipe

5105220 - Jopão Ferreira Lima Neto - Redes de Computadores

## :bulb: Objetivo Geral
Desenvolver um sistema para organizar feiras locais, permitindo o cadastro de expositores e a divulgação de eventos.

## :eyes: Público-Alvo
Organizadores de feiras e expositores.


## :star2: Impacto Esperado
O impacto desse sistema na sociedade é significativo. Ao facilitar a organização de feiras, ele promove o empreendedorismo local e fortalece a economia regional. 
Pequenos produtores e artesãos ganham uma vitrine para seus produtos, aumentando suas oportunidades de negócio. 
Além disso, a comunidade se beneficia com eventos mais organizados e acessíveis, gerando um ambiente favorável para a troca de conhecimentos e experiências, 
e fomentando o desenvolvimento econômico sustentável da região.
## :people_holding_hands: Papéis ou tipos de usuário da aplicação

Expositores de Startups, Organizadores de feiras e eventos e Pessoas interessadas em assistir as exposições 
> Tenha em mente que obrigatoriamente a aplicação deve possuir funcionalidades acessíveis a todos os tipos de usuário e outra funcionalidades restritas a certos tipos de usuários.

## :triangular_flag_on_post:	 Principais funcionalidades da aplicação
Cadastro de Eventos:
Registro de informações Espaço, Horarios e Vagas.
(Apenas com Cadastro e apenas para a entidade Administrador)

Cadastro de Expositores:
Registro de informações como produtos e espaço reservado.
(Apenas com Cadastro e apenas para a entidade expositor)

Cadastro de Interessado:
Registro de informações como Nome, CPF e Instituição.
(Cadastro Livre)

Calendário de Feiras:
Exibição das próximas datas e locais.
(Visivel sem cadastro).

Página de Divulgação:
Detalhes sobre os eventos.
(Visivel sem cadastro).

## :spiral_calendar: Entidades ou tabelas do sistema

Entidade Administrador:
A entidade que pode registrar Eventos.
Apenas uma entidade deste tipo.

Entidade Evento: 
Contém: número de participantes, data, Horario e Nome;

Entidade Expositor:
Contém: Nome, Instituição, CPF, Projeto e permissão para se cadastrar em eventos

Entidade Interessado:
Contém: Nome, CPF e Instituição

----

:warning::warning::warning: As informações a seguir devem ser enviadas juntamente com a versão final do projeto. :warning::warning::warning:


----

## :desktop_computer: Tecnologias e frameworks utilizados

**Frontend:**

Lista as tecnologias, frameworks e bibliotecas utilizados.

**Backend:**

Lista as tecnologias, frameworks e bibliotecas utilizados.


## :shipit: Operações implementadas para cada entidade da aplicação


| Entidade| Criação | Leitura | Atualização | Remoção |
| --- | --- | --- | --- | --- |
| Entidade 1 | X |  X  |  | X |
| Entidade 2 | X |    |  X | X |
| Entidade 3 | X |    |  |  |

> Lembre-se que é necessário implementar o CRUD de pelo menos duas entidades.

## :neckbeard: Rotas da API REST utilizadas

| Método HTTP | URL |
| --- | --- |
| GET | api/entidade1/|
| POST | api/entidade2 |
