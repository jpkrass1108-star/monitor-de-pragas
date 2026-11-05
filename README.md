# Monitor de Pragas

### Tecnologia conectada à operação de controle de pragas

Aplicativo web instalável (PWA) desenvolvido por **João Pedro Krass Ramalho**, no contexto da **Control Up**, para centralizar o acompanhamento de armadilhas, sensores e atividades de manutenção.

O projeto foi desenvolvido para uma feira em **São Paulo**, da qual participei presencialmente. Essa experiência conectou a construção de uma solução digital a um contexto real de apresentação de produto e necessidades de negócio.

> **Portfólio de projeto:** este repositório apresenta a solução e suas funcionalidades. O código-fonte e os arquivos operacionais não estão disponíveis neste repositório.

## Veja o projeto na prática

**[Ver apresentação visual em PDF](docs/Apresentacao_Monitor_de_Pragas.pdf)**

### Vídeos

- [Demonstração do web app](https://drive.google.com/file/d/1SbvfcFFyd3gb2XRorIdPTERMd2DMwiBT/view)
- [Apresentação da Control Up](https://drive.google.com/file/d/13j6qQrygihnLEpt-E9QiHT5ykUilknQY/view)
- [Montagem e teste da câmera 3D](https://drive.google.com/file/d/1I_R9FeT1KzzvclkLLA2p2lrmKhmb9RnL/view)

[Explorar os registros completos no Google Drive](https://drive.google.com/drive/folders/1ThrB_2z_qpJm7YZ0dIsPDxG72kcLKO5Q)

### Da montagem à exposição

As fotos mostram o desenvolvimento físico e a apresentação dos equipamentos. As telas ilustradas nos totens pertencem ao material de divulgação; para conhecer a interface em uso, acesse o vídeo do web app acima.

| Montagem em bancada | Câmera instalada na armadilha |
| --- | --- |
| ![Montagem dos componentes na armadilha luminosa](imagens/montagem.jpg) | ![Câmera instalada na armadilha luminosa exposta](imagens/camera-instalada.jpg) |
| Preparação e montagem dos componentes físicos. | Equipamento integrado à armadilha luminosa. |

![Registro do teste da câmera ligada por oito horas](imagens/teste-8-horas.jpg)

*Registro identificado como teste da câmera ligada por oito horas. A foto documenta o ensaio, sem representar uma certificação de autonomia ou desempenho.*

### Apresentação na feira em São Paulo

| Smart Station | Control Cam |
| --- | --- |
| ![Totem Smart Station na feira](imagens/smart-station.jpg) | ![Totem Control Cam na feira](imagens/control-cam.jpg) |
| Apresentação do monitoramento de porta-iscas. | Apresentação da câmera para armadilhas luminosas. |

## O desafio de negócio

Acompanhar armadilhas distribuídas entre diferentes clientes exige organizar informações de dispositivos, identificar ocorrências e controlar manutenções. A falta de uma visão centralizada dificulta definir quais pontos precisam de atenção e planejar as visitas da equipe.

O Monitor de Pragas reúne essas informações em uma interface acessível pelo navegador e instalável na tela inicial do celular, com o objetivo de apoiar o monitoramento remoto e a organização do trabalho em campo.

## Minha contribuição

Desenvolvimento do web app, reunindo interface, integração com dispositivos IoT e recursos de acompanhamento operacional. O trabalho conecta programação e compreensão de processos de negócio para transformar dados de sensores e registros de manutenção em informações úteis à operação.

## Projeto 3D e integração dos dispositivos

Além do desenvolvimento do aplicativo, nossa equipe criou o **projeto 3D da câmera e do sensor** e adaptou esses dispositivos à **tecnologia Tuya** para atender à proposta de monitoramento de pragas. Esse trabalho reuniu o projeto físico dos equipamentos e sua integração ao ecossistema IoT utilizado pelo sistema.

O projeto 3D e a adaptação dos dispositivos foram uma construção da equipe, complementando minha atuação no desenvolvimento do web app. A solução conecta, assim, os equipamentos físicos, a plataforma Tuya e a interface de acompanhamento operacional.

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
| Registro de presença via NFC | Tag na armadilha com sensor permite ao técnico registrar sua presença no ponto de monitoramento. |
| Controle de manutenção | Registra trocas de refil e lâmpada e sinaliza prazos de manutenção. |
| Pendências e roteiro de visitas | Reúne ocorrências e manutenções pendentes para apoiar a priorização das visitas. |
| Históricos e acompanhamento | Organiza eventos, notificações e informações de visita por empresa e dispositivo. |
| Catálogo de produtos | Apresenta famílias de produtos, especificações e intervalos de manutenção. |
| Instalação como aplicativo | Permite acesso pela tela inicial do celular, como PWA. |

### Registro de presença e manutenção com NFC

Utilizamos uma **tag NFC na armadilha equipada com sensor** para que o técnico de monitoramento de pragas pudesse **registrar sua presença no local**. Ao aproximar o celular da tag, o técnico acessa o fluxo de registro associado ao ponto de monitoramento, vinculando a visita à armadilha atendida.

O módulo também contempla o registro de trocas e manutenções em campo. Dessa forma, o projeto conecta o acompanhamento remoto dos dispositivos ao registro das visitas presenciais e das intervenções realizadas. O briefing documenta a evolução da vinculação entre empresa, dispositivo e registros, além da necessidade de sincronização com o painel principal.

## Tecnologias utilizadas

| Camada | Tecnologias |
| --- | --- |
| Interface | HTML, CSS e JavaScript puro |
| Aplicativo web | PWA, manifesto e Service Worker |
| Back-end | PHP 8 e integração com APIs via cURL |
| Integração IoT | Tuya OpenAPI |
| Registro em campo | Tags NFC nas armadilhas |
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
