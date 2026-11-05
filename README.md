# Monitor de Pragas

### Tecnologia conectada à operação de controle de pragas

Aplicativo web instalável (PWA) desenvolvido por **João Pedro Krass Ramalho**, no contexto da **Control Up**, para centralizar o acompanhamento de armadilhas, sensores e atividades de manutenção.

O projeto foi desenvolvido para uma feira em **São Paulo**, da qual participei presencialmente. Essa experiência conectou a construção de uma solução digital a um contexto real de apresentação de produto e necessidades de negócio.

> **Portfólio de projeto:** este repositório apresenta a solução e suas funcionalidades. O código-fonte e os arquivos operacionais não estão disponíveis neste repositório.

## O desafio de negócio

Acompanhar armadilhas distribuídas entre diferentes clientes exige organizar informações de dispositivos, identificar ocorrências e controlar manutenções. A falta de uma visão centralizada dificulta definir quais pontos precisam de atenção e planejar as visitas da equipe.

O Monitor de Pragas reúne essas informações em uma interface acessível pelo navegador e instalável na tela inicial do celular, com o objetivo de apoiar o monitoramento remoto e a organização do trabalho em campo.

## Minha contribuição

Desenvolvimento do web app, reunindo interface, integração com dispositivos IoT e recursos de acompanhamento operacional. O trabalho conecta programação e compreensão de processos de negócio para transformar dados de sensores e registros de manutenção em informações úteis à operação.

## Funcionalidades

As funcionalidades abaixo estão documentadas no briefing técnico do sistema. A disponibilidade dos recursos conectados depende dos dispositivos, das permissões da plataforma IoT e dos serviços em execução.

| Recurso | Aplicação na operação |
| --- | --- |
| Cadastro e organização de empresas | Agrupa os clientes atendidos e seus dispositivos. |
| Organização por famílias de pragas | Separa dispositivos destinados a roedores, aves e insetos. |
| Mapa de dispositivos | Posiciona e permite reorganizar pontos de monitoramento sobre a planta de cada empresa. |
| Monitoramento de eventos | Consulta eventos de movimento de sensores e câmeras integrados à plataforma Tuya. |
| Notificações | Exibe avisos no painel e oferece notificações Web Push em segundo plano, conforme compatibilidade e configuração. |
| Vídeo ao vivo | Permite visualizar a câmera de uma armadilha pelo aplicativo. |
| Controle de manutenção | Registra trocas de refil e lâmpada e sinaliza prazos de manutenção. |
| Pendências e roteiro de visitas | Reúne ocorrências e manutenções pendentes para apoiar a priorização das visitas. |
| Históricos e acompanhamento | Organiza eventos, notificações e informações de visita por empresa e dispositivo. |
| Catálogo de produtos | Apresenta famílias de produtos, especificações e intervalos de manutenção. |
| Instalação como aplicativo | Permite acesso pela tela inicial do celular, como PWA. |

### Registro de manutenção em campo

O projeto também contempla um módulo NFC para facilitar a confirmação de trocas pelo técnico em campo. O briefing documenta sua evolução para vincular os registros à empresa e ao dispositivo corretos, além da necessidade de sincronizar esses registros com o painel principal.

## Tecnologias utilizadas

| Camada | Tecnologias |
| --- | --- |
| Interface | HTML, CSS e JavaScript puro |
| Aplicativo web | PWA, manifesto e Service Worker |
| Back-end | PHP 8 e integração com APIs via cURL |
| Integração IoT | Tuya OpenAPI |
| Notificações | Python, Web Push e VAPID |
| Vídeo | HLS |
| Persistência | localStorage e arquivos JSON |

## Competências demonstradas

- Desenvolvimento de uma aplicação web voltada a um problema operacional concreto.
- Integração entre software, serviços de nuvem e dispositivos físicos.
- Organização de dados por empresa, dispositivo e histórico de ocorrências.
- Construção de recursos de monitoramento, notificação e manutenção.
- Conexão entre funcionalidades técnicas e necessidades de equipes em campo.
- Participação presencial em uma feira em São Paulo vinculada ao projeto.

## Escopo e evolução

A versão documentada combina dispositivos conectados e alguns elementos simulados. O acompanhamento de consumo inclui simulação; por isso, ele não é apresentado aqui como medição física implementada.

Parte dos dados é armazenada no navegador utilizado, enquanto outros registros ficam no servidor. A centralização e a sincronização desses dados são pontos de evolução. O aplicativo depende de conectividade para consultar eventos e vídeo; a instalação como PWA não implica funcionamento offline.

Os benefícios de redução de deslocamentos e melhoria do planejamento são objetivos da solução, sem métricas de impacto apresentadas neste portfólio.

## Sobre este portfólio

Este material apresenta o projeto sem distribuir código-fonte, credenciais, identificadores de dispositivos, dados de clientes ou configurações de infraestrutura. Nomes de produtos e marcas são mencionados apenas para contextualizar a experiência profissional.

**Autor do web app:** João Pedro Krass Ramalho  
**Áreas de interesse:** desenvolvimento de sistemas, integração de tecnologias e soluções para negócios.
