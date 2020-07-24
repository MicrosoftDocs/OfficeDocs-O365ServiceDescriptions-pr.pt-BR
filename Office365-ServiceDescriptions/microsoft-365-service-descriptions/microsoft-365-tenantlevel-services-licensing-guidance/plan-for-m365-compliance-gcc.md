---
title: Planejar a conformidade com o Microsoft 365 – GCC
ms.author: office365servicedesc
author: pamelaar
audience: ITPro
ms.topic: reference
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
description: Esta orientação é para profissionais de ti que estão conduzindo implantações do Office 365 em entidades governamentais, estaduais, locais, tribal ou de governos da região, ou outras entidades que lidam com os dados sujeitos a normas e requisitos governamentais, onde o uso do Microsoft 365 governamental-GCC é adequado para atender a esses requisitos.
ms.openlocfilehash: 1e172588c21c15bd0422edb12d5024764f56ead7
ms.sourcegitcommit: d4025c73f14b663ffcaa1ef8db4174b51debdae7
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 07/23/2020
ms.locfileid: "45388097"
---
# <a name="plan-for-microsoft-365-compliance--gcc"></a>Planejar a conformidade com a Microsoft 365 – GCC

Esta orientação é para profissionais de ti que estão conduzindo implantações do Office 365 em entidades governamentais, estaduais, locais, tribal ou de governos da região, ou outras entidades que lidam com os dados sujeitos a normas e requisitos governamentais, onde o uso do Microsoft 365 governamental-GCC é adequado para atender a esses requisitos.

> [!NOTE]
> Se sua organização já atendeu aos requisitos de qualificação do governo Microsoft 365 e foram aplicados e foram aceitos no programa, você pode ignorar as etapas 1 e 2 e ir diretamente para a etapa 3.

## <a name="step-1-determine-whether-your-organization-needs-microsoft-365-government---gcc-and-meets-eligibility-requirements"></a>Etapa 1. Determinar se sua organização precisa do Microsoft 365 governamentais-GCC e atende aos requisitos de qualificação

O ambiente Microsoft 365 governamental-GCC está em conformidade com os requisitos do governo dos EUA para serviços de nuvem, incluindo FedRAMP moderado e requisitos para justiça criminal e sistemas de informações de tributação Federal (tipos de dados CJI e FTI).

Além de aproveitar os recursos e as funcionalidades do Office 365, as organizações se beneficiam dos seguintes recursos, que são exclusivos do Microsoft 365 governamental-GCC:

- O conteúdo do cliente da sua organização é logicamente separado do conteúdo do cliente nos serviços comerciais do Office 365 da Microsoft.

- O conteúdo do cliente da sua organização é armazenado dentro dos Estados Unidos.

- O acesso ao conteúdo do cliente da sua organização é restrito à equipes selecionadas da Microsoft.

- O Microsoft 365 governamental-GCC está em conformidade com certificações e confirações necessárias para os clientes do setor público nos EUA.

Você pode encontrar mais informações sobre a oferta Microsoft 365 governamentais-GCC para clientes do governo dos EUA nos [planos do governo do Office 365](https://products.office.com/government/compare-office-365-government-plans), incluindo requisitos de qualificação.

A [Descrição do serviço governo dos EUA do Office 365](https://docs.microsoft.com/office365/servicedescriptions/office-365-platform-service-description/office-365-us-government/office-365-us-government) descreve os benefícios da plataforma, que são centralizados em atender aos requisitos de conformidade nos Estados Unidos.

> [!TIP]
> Você pode querer transferir as tabelas de informações na descrição do serviço para uma pasta de trabalho do Excel e adicionar duas colunas: **relevantes para minha organização**   e **atender às necessidades da minha organização y/n**. Em seguida, você pode revisar essa lista com seus colegas para confirmar que esse serviço atende às necessidades da sua organização.

> [!NOTE]
> O Microsoft 365 governamental-GCC só está disponível nos Estados Unidos. Clientes governamentais não americanos podem escolher entre vários [planos governamentais do Office 365](https://products.office.com/government/compare-office-365-government-plans).

**Pontos de decisão**: <br/>
- *Decida se o Microsoft 365 governamentais-GCC é apropriado para sua organização.*
- *Confirme se a sua organização atende aos requisitos de qualificação.*

## <a name="step-2-apply-for-microsoft-365-government---gcc"></a>Etapa 2. Aplicar para o Microsoft 365 governamental-GCC

Para ter decidido que esse serviço é adequado para sua organização, inicie o processo de [aplicação desse serviço](https://products.office.com/government/eligibility-validation).

## <a name="step-3-understand-microsoft-365-government---gcc-default-security-settings"></a>Etapa 3. Entender as configurações de segurança padrão do Microsoft 365 governo-GCC

Recomendamos que você reserve um tempo para revisar cuidadosamente suas configurações de administrador e segurança antes de modificá-las e considere o impacto sobre a conformidade antes de fazer qualquer alteração nas configurações de segurança padrão.

**Ponto de decisão**: *decida se você modificará qualquer uma das configurações de segurança do Microsoft 365 governo-gcc padrão, resolvendo para entender primeiro o impacto de qualquer alteração que você possa fazer.*

## <a name="step-4-understand-which-capabilities-are-currently-unavailable-or-disabled-by-default-in-microsoft-365-government--gccsup1sup"></a>Etapa 4. Entender quais recursos estão atualmente indisponíveis ou estão desabilitados por padrão no Microsoft 365 governamentais – GCC<sup>1</sup>

Para acomodar os requisitos de nossos clientes de nuvem governamental, há algumas diferenças entre os planos Microsoft 365 governamentais-GCC e Enterprise. Consulte a tabela a seguir para ver quais recursos estão disponíveis.

|                                         | **Recurso**                                     | **Status de GCC**         |
| --------------------------------------- | ----------------------------------------------- | ---------------------- |
| **Governança de proteção de informações &** | Arquivamento                                       | Disponível              |
|                                         | Rótulos e políticas manuais<sup>2</sup>          | Disponível              |
|                                         | Aplicação automática de rótulos                      | Disponível              |
|                                         | Rótulos baseados em tipos de dados confidenciais            | Na Backlog de engenharia |
|                                         | Rótulos e políticas associadas com base em consultas | Disponível              |
|                                         | Plano de arquivos                                       | Disponível              |
|                                         | Políticas recomendadas                            | Na Backlog de engenharia |
|                                         | Filtros de importação inteligente                            | Na Backlog de engenharia |
|                                         | Retenção baseada em eventos                           | Disponível              |
|                                         | Revisão de disposição                              | Disponível              |
|                                         | Barreiras de informações                            | Disponível              |
|                                         | Prevenção de perda de dados (DLP) para arquivos e email  | Disponível              |
|                                         | DLP para chat de equipes e conversas de canal    | Na Backlog de engenharia |
|                                         | Correspondência exata dos dados de DLP                            | Na Backlog de engenharia |
|                                         | Explorador de Atividade de Rótulo                         | Na Backlog de engenharia |
|                                         | Classificadores estagiários                           | Na Backlog de engenharia |
|                                         | Rótulo unificado e rótulos de confidencialidade         | Na Backlog de engenharia |
| **Gerenciamento de risco interno**             | Criptografia de mensagem avançada                     | Disponível              |
|                                         | Gerenciamento de riscos internos                         | Na Backlog de engenharia |
|                                         | Conformidade em comunicações                        | Na Backlog de engenharia |
|                                         | Sistema de Proteção de Dados do cliente                                | Disponível              |
|                                         | Chave de Cliente                                    | Disponível              |
|                                         | Gerenciamento de acesso privilegiado                    | Na Backlog de engenharia |
| **Descobrir & responder**                  | Descoberta eletrônica principal: preservação no local                            | Disponível              |
|                                         | Descoberta eletrônica principal: gerenciamento de casos                                 | Disponível              |
|                                         | Descoberta eletrônica principal: pesquisa                                          | Disponível              |
|                                         | Descoberta eletrônica principal: exportar                                          | Disponível              |
|                                         | Descoberta eletrônica principal: descriptografia do RMS                                  | Disponível              |
|                                         | Descoberta eletrônica principal: exportação nativa                                   | Disponível              |
|                                         | Descoberta eletrônica principal: auditoria                                        | Disponível              |
|                                         | Descoberta eletrônica avançada: processamento avançado                             | Disponível |
|                                         | Descoberta eletrônica avançada: encadeamento de email                                 | Disponível |
|                                         | Descoberta eletrônica avançada: identificação próxima duplicada                   | Disponível |
|                                         | Descoberta eletrônica avançada: temas                                          | Disponível |
|                                         | Descoberta eletrônica avançada: codificação de previsão                               | Disponível |
|                                         | Descoberta eletrônica avançada: exportação processada com o arquivo de carregamento                 | Disponível |
|                                         | Descoberta eletrônica avançada: marcação                                         | Disponível |
|                                         | Descoberta eletrônica avançada: visualizadores                                         | Disponível |
|                                         | Descoberta eletrônica avançada: redaçãos                                      | Disponível |
|                                         | Descoberta eletrônica avançada: filtragem                                       | Disponível |
|                                         | Descoberta eletrônica avançada: mapeamento de carga de trabalho                   | Disponível |
|                                         | Descoberta eletrônica avançada: comunicações de responsáveis                        | Disponível |
|                                         | Descoberta eletrônica avançada: conjuntos de revisão                                     | Disponível |
|                                         | Descoberta eletrônica avançada: revisar e anotar                             | Disponível |
|                                         | Descoberta eletrônica avançada: inclusão de não-Office 365                        | Disponível |
|                                         | Descoberta eletrônica avançada: relatório de termos de pesquisa                              | Disponível |

<sup>1</sup> o status identificado está sujeito a alterações à medida que os planos e as prioridades do projeto são reavaliados.<br/>
<sup>2</sup> o aplicativo manual de rótulos requer o [cliente de proteção de informações do Azure (AIP) versão 1](https://docs.microsoft.com/azure/information-protection/rms-client/client-version-release-history).


**Ponto de decisão**: *decida se os recursos de conformidade atendem às necessidades da sua organização.*
