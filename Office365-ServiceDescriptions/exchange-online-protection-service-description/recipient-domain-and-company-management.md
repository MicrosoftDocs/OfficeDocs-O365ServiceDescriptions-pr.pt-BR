---
title: Gerenciamento de destinatários, domínios e empresas
ms.author: office365servicedesc
author: pamelaar
audience: ITPro
ms.topic: reference
f1_keywords:
- recipient-domain-and-company-management-features-in-eop
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: 10812b48-7df5-47e9-b643-dbc3c85d7de0
description: O Microsoft proteção do Exchange Online (EOP) oferece vários meios de gerenciamento das informações de destinatário, domínio e da empresa. Como administrador, você pode executar determinadas tarefas de gerenciamento no centro de administração do Exchange (Eat) e verificar outras tarefas de gerenciamento executadas no centro de administração do Microsoft 365.
ms.openlocfilehash: 4a2d2d091a6170e0606702a4a8047a21ad57ac11
ms.sourcegitcommit: d2cd67e52dd646b68bfbfd8a387e70a6da140a62
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 07/14/2020
ms.locfileid: "45132765"
---
# <a name="recipient-domain-and-company-management"></a>Gerenciamento de destinatários, domínios e empresas

O Microsoft proteção do Exchange Online (EOP) oferece vários meios de gerenciamento das informações de destinatário, domínio e da empresa. Como administrador, você pode executar determinadas tarefas de gerenciamento no centro de administração do Exchange (Eat) e verificar outras tarefas de gerenciamento executadas no centro de administração do Microsoft 365.
  
Você está procurando informações sobre todas as características EOP? Consulte a [Descrição do serviço de proteção do Exchange Online](exchange-online-protection-service-description.md).
  
## <a name="mail-recipients"></a>Mail recipients

Os destinatários de email são categorizados como grupos ou usuários de email e podem ser gerenciados por meio da sincronização do diretório, diretamente no EAC ou via Windows PowerShell remoto. Se estiver gerenciando destinatários locais, você deverá executar a sincronização de diretório para que seus destinatários de email sejam refletidos no EAC. Os usuários gerenciados exclusivamente no centro de administração do Microsoft 365 não são visíveis no Eat, mas podem ser adicionados ou removidos da associação em um grupo de funções de administrador no Eat. Confira mais informações sobre destinatários no EOP em [Destinatários no EOP](https://go.microsoft.com/fwlink/p/?LinkId=280011).
  
## <a name="admin-role-group-permissions"></a>Admin role group permissions

In EOP, you can configure administrative roles only. Users can be added and removed from default admin role groups directly in the EAC. No RBAC customization is available. For more information, see [Manage Admin Role Group Permissions in EOP](https://go.microsoft.com/fwlink/p/?LinkId=282238).
  
## <a name="domain-management"></a>Gerenciamento de domínio

Domínios gerenciados são domínios protegidos pelo EOP. Os domínios gerenciados podem ser visualizados e os tipos de domínio podem ser editados no EAC. O provisionamento e o gerenciamento de domínios ocorrem no centro de administração do Microsoft 365 e as alterações são refletidas no Eat. Confira mais informações em [Exibir ou editar domínios gerenciados no EOP](https://go.microsoft.com/fwlink/p/?LinkId=282239).
  
## <a name="match-subdomains"></a>Corresponder subdomínios

In EOP, you can enable mail flow to subdomains of a managed domain. For more information, see [Enable Email Flow for Subdomains in EOP](https://go.microsoft.com/fwlink/p/?LinkId=397213). 
  
## <a name="directory-based-edge-blocking-dbeb"></a>Bloqueio de borda baseado em diretório (DBEB)

O recurso Bloqueio de borda baseado em diretório permite rejeitar mensagens para destinatários inválidos no perímetro da rede de serviços. O DBEB permite que os administradores adicionem destinatários habilitados para email à Microsoft e Bloqueiem todas as mensagens enviadas para endereços de email que não estão presentes na Microsoft. Se uma mensagem for enviada para um endereço de email válido presente no Microsoft, a mensagem continua com o restante das camadas de filtragem de serviço (anti-malware, antispam, regras de transporte). Se o endereço não estiver presente, o serviço bloqueia a mensagem antes mesmo da filtragem ocorrer e uma notificação de falha na entrega (NDR) é enviada para o remetente informando que a mensagem não foi entregue. 
  
Enabling DBEB requires some user and domain configuration. For more information, see [Use Directory Based Edge Blocking to Reject Messages Sent to Invalid Recipients](https://go.microsoft.com/fwlink/p/?LinkId=390676).
  
## <a name="feature-availability"></a>Disponibilidade de recursos

Para exibir a disponibilidade de recursos nos planos, nas opções autônomas e nas soluções locais, consulte [Descrição do serviço do Exchange Online Protection](exchange-online-protection-service-description.md).
