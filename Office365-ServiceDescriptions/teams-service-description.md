---
title: Descrição do serviço do Microsoft Teams
ms.author: sharik
author: skjerland
manager: mnirkhe
audience: ITPro
ms.topic: reference
ms.service: o365-administration
localization_priority: Normal
description: O Microsoft Teams fornece mensagens instantâneas, colaboração de arquivos e dados, chamadas de áudio e vídeo, reuniões online avançadas, experiências móveis e recursos de Webconferência abrangentes.
ms.openlocfilehash: cd16f511c5bd0af7c8e64cf4efd383ca48f74b30
ms.sourcegitcommit: 83c602d9c498df5a2fe0095c6fb0a267c8a708b7
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 03/12/2020
ms.locfileid: "42609982"
---
# <a name="microsoft-teams-service-description"></a>Descrição do serviço do Microsoft Teams

O Microsoft Teams é o Hub para trabalho em equipe no Microsoft 365. O serviço Teams permite mensagens instantâneas, chamadas de áudio e vídeo, reuniões online avançadas, experiências móveis e recursos de Webconferência abrangentes. Além disso, o Microsoft Teams oferece colaboração de dados e recursos e recursos de extensibilidade e integra-se com o Microsoft 365 e outros aplicativos de parceiros e da Microsoft.

O Skype for Business online será desativado no dia 31 de julho de 2021, que foi [lançado](https://techcommunity.microsoft.com/t5/Microsoft-Teams-Blog/Skype-for-Business-Online-to-Be-Retired-in-2021/ba-p/777833) em 30 de julho de 2019. O Microsoft Teams é um serviço totalmente novo, desenvolvido para a nuvem desde o início, aproveitando o Azure e outras inovações de serviço da Microsoft. O Microsoft Teams é desenvolvido em grupos do Office 365, Microsoft Graph e com a mesma segurança de nível empresarial, conformidade e capacidade de gerenciamento como o restante do Office 365. O Microsoft Teams aproveita as identidades armazenadas no Azure Active Directory (Azure AD). Esses serviços são fornecidos pelos data centers da Microsoft e são acessíveis aos usuários em uma ampla variedade de dispositivos de dentro de uma rede corporativa ou pela Internet. Para obter mais informações, consulte os [diagramas de soluções de telefonia e de arquitetura do Microsoft Teams](https://docs.microsoft.com/microsoftteams/teams-architecture-solutions-posters).

A Microsoft continua comprometida com a segurança de seus dados e com a [acessibilidade](https://www.microsoft.com/trust-center/compliance/accessibility) de nossos serviços. Para obter mais informações, consulte a [central de confiabilidade da Microsoft](https://www.microsoft.com/trust-center) e o centro de acessibilidade do [Office](https://support.office.com/article/Office-Accessibility-Center-Resources-for-people-with-disabilities-ecab0fcf-d143-4fe8-a2ff-6cd596bddc6d).

Para sua referência, incluímos esta tabela mestra das assinaturas do Office 365 que permitem aos usuários do Microsoft Teams. Para obter detalhes completos, consulte [Office 365 Licensing for Microsoft Teams](https://docs.microsoft.com/microsoftteams/office-365-licensing). Para saber mais sobre o Office 365 em planos governamentais, confira [planejamentos governamentais do office 365](https://www.microsoft.com/microsoft-365/government/compare-office-365-government-plans). O Office 365 G1 a G5 inclui acesso a recursos do teams.

|||||
|:-----|:-----|:-----|:-----|
|**Planos para pequenas empresas** <br/> |**Planos empresariais** <br/> |**Planos de educação** <br/> |**Planos de desenvolvedor** <br/> |
|Office 365 Business Essentials  <br/> |Office 365 Enterprise E1  <br/> |Office 365 Education  <br/> |Desenvolvedor do Office 365  <br/> |
|Office 365 Business Premium  <br/> |Office 365 Enterprise E3  <br/> |Office 365 Education Plus  <br/> |   <br/> |
|Microsoft 365 para empresas  <br/> |Office 365 Enterprise E4 (desativado)  <br/> |Office 365 Education E3 (desativado)  <br/> |  <br/> |
|  <br/> |Office 365 Enterprise E5  <br/> |Office 365 Education E5  <br/> |  <br/> |
|  <br/> |Office 365 Enterprise F1  <br/> |  <br/> |  <br/> |

Para obter diretrizes detalhadas de implementação de recursos do produto, consulte a [documentação de administração do Microsoft Teams](https://docs.microsoft.com/MicrosoftTeams). Esta descrição de serviço detalha as principais diferenças entre os serviços fornecidos nas várias instalações de nuvem. As funcionalidades do Microsoft Teams Core não diferem entre as assinaturas do Office 365. A disponibilidade dos recursos de conformidade depende do nível de assinatura. Para saber mais, confira [segurança e conformidade no Microsoft Teams](https://docs.microsoft.com/microsoftteams/security-compliance-overview). Para obter uma lista detalhada dos recursos disponíveis em cada assinatura, consulte a [Descrição do serviço da plataforma do Office 365](https://docs.microsoft.com/office365/servicedescriptions/office-365-platform-service-description/office-365-platform-service-description).

**Recursos de voz em nuvem**: para audioconferência, sua organização deve comprar e atribuir uma licença de audioconferência a cada usuário que configurará as reuniões de discagem. Para os recursos do teams que exigem planos de chamadas, cada usuário precisa de um sistema de telefonia e um plano de chamadas domésticas ou domésticas e internacionais. Para saber mais, confira [Licenciamento de Complementos do Microsoft Teams](https://docs.microsoft.com/microsoftteams/teams-add-on-licensing/microsoft-teams-add-on-licensing).

**Eventos ao vivo**: essa oferta no Office 365 substitui a transmissão de reunião do Skype desativada. Recursos de eventos ao vivo estão disponíveis para planos de licenciamento, conforme detalhado no serviço de fluxo. Revise os [detalhes de licenciamento aqui](https://docs.microsoft.com/stream/license-overview). O serviço Live Events pode ser acessado por meio do Stream, do Yammer ou do Microsoft Teams. Para saber mais sobre recursos de eventos ao vivo, confira [eventos em tempo real em microsoft 365 no Yammer, Microsoft Teams e Microsoft Stream](https://docs.microsoft.com/stream/live-event-m365).

Todos os planos de assinatura suportados estão qualificados para acessar o cliente Web do Microsoft Teams, clientes de desktop e aplicativos móveis.

O Microsoft Teams não está disponível como um serviço autônomo.

## <a name="feature-category-reference"></a>Referência de categoria de recurso 

Esta tabela lista a disponibilidade de recursos do Microsoft Teams em planos de licenciamento ou instâncias de nuvem. Determinadas limitações se aplicam. Confira as notas de rodapé para obter mais informações. Esta tabela pode ser alterada sem aviso prévio. Consulte Microsoft 365 Message Center Notifications for Core Service Change Messaging e a [documentação de referência de termos de licenciamento da Microsoft](https://www.microsoft.com/licensing/product-licensing/products).

|||||||
|:-----|:-----|:-----|:-----|:-----|:-----|:-----|
| <br/>|**Pequena empresa** <br/> |**Planos empresariais** <br/> |**GCC** <br/> |**GCC-alto** <br/> |**DOD** <br/> |**Educação** <br/> |
|Chat  <br/> |Sim  <br/> |Sim  <br/> |Sim  <br/> |Sim  <br/> |Sim  <br/> |Sim  <br/> |
|Teams  <br/> |Sim <br/> |Sim <br/> |Sim <br/> |Sim<sup>1</sup>  <br/> |Sim<sup>1</sup>  <br/> |Sim  <br/> |
|Canais-padrão  <br/> |Sim  <br/> |Sim  <br/> |Sim  <br/> |Sim  <br/> |Sim  <br/> |Sim  <br/> |
|Canais-privado  <br/> |Sim  <br/> |Sim<sup>2</sup>  <br/> |Não<sup>3</sup>  <br/> |Não<sup>3</sup>  <br/> |Não<sup>3</sup>  <br/> |Sim  <br/> |
|Reuniões  <br/> |Sim  <br/> |Sim  <br/> |Sim  <br/> |Sim  <br/> |Sim  <br/> |Sim  <br/> |
|Área de trabalho de áudio/vídeo do PowerPoint para compartilhamento de tela <br/> |Sim  <br/> |Sim  <br/> |Sim  <br/> |Sim  <br/> |Sim  <br/> |Sim  <br/> |
|Voz  <br/> |Sim  <br/> |Sim  <br/> |Sim  <br/> |Sim  <br/> |Sim  <br/> |Sim  <br/> |
|Audioconferência  <br/> |Sim  <br/> |Sim  <br/> |Sim  <br/> |Sim  <br/> |Sim  <br/> |Sim  <br/> |
|Aplicativos, bots, & conectores  <br/> |Sim  <br/> |Sim  <br/> |Sim<sup>4</sup>  <br/> |Sim<sup>4</sup>  <br/> |Sim<sup>4</sup>  <br/> |Sim  <br/> |
|Eventos ao vivo  <br/> |Sim  <br/> |Sim  <br/> |Sim  <br/> |Nenhum<sup>5</sup>  <br/> |Nenhum<sup>5</sup>  <br/> |Sim  <br/> |

<sup>1</sup> o Microsoft Teams em GCC-alto e DOD dão suporte a 2500 Membros em uma equipe individual.<br/>
<sup>2</sup> o Microsoft Planner não está disponível no momento para o acesso em canais privados.<br/>
<sup>3</sup> os canais privados não estão disponíveis em nuvens gcc no momento. Outras atualizações sobre a disponibilidade serão publicadas no centro de mensagens.<br/>
<sup>4</sup> o Microsoft OneNote não está disponível em nuvens DOD. Os aplicativos e a publicação de aplicativos não estão disponíveis nessas nuvens no momento.<br/>
<sup>5</sup> eventos ao vivo não estão disponíveis em GCC-High ou DOD no momento.<br/>

## <a name="next-steps"></a>Próximas etapas

Comece a planejar sua implantação do Microsoft Teams visitando a [documentação técnica do Microsoft Teams](https://aka.ms/SuccessWithTeams). Mantenha-se atualizado sobre os recursos e recursos do teams [participando da nossa comunidade e visitando o blog do Microsoft Teams](https://aka.ms/TeamsBlog).