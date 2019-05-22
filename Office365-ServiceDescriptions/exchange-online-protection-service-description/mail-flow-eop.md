---
title: Fluxo de mensagens [EOP]
ms.author: sharik
author: skjerland
manager: mnirkhe
ms.date: 6/13/2018
audience: ITPro
ms.topic: reference
f1_keywords:
- mail-flow-in-eop
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: 214e5779-35c6-4912-af0c-8b0552239f13
description: Hospedamos as caixas de correio e cuidamos do fluxo de emails da maioria das organizações que usam o Office 365. É a configuração mais simples e significa que o Office 365 gerencia todas as caixas de correio e filtros. No entanto, algumas organizações têm a necessidade comercial de manter todas as caixas de correio no local. A EOP (Proteção do Exchange Online) permite que você faça isso e oferece o processamento de emails antivírus e antispam na nuvem. Para mais informações e adquirir a EOP, acesse Proteção do Exchange Online.
ms.openlocfilehash: c55d1d376d617b863a75ff609cbc3f064418746b
ms.sourcegitcommit: 15e92292209454f6778bfef26ecab96bfc71ef5f
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 05/22/2019
ms.locfileid: "34341820"
---
# <a name="mail-floweop"></a>Fluxo de mensagens [EOP]

Hospedamos as caixas de correio e cuidamos do fluxo de emails da maioria das organizações que usam o Office 365. É a configuração mais simples e significa que o Office 365 gerencia todas as caixas de correio e filtros. No entanto, algumas organizações têm a necessidade comercial de manter todas as caixas de correio no local. A EOP (Proteção do Exchange Online) permite que você faça isso e oferece o processamento de emails antivírus e antispam na nuvem. Para mais informações e adquirir a EOP, acesse [Proteção do Exchange Online](https://products.office.com/en-us/exchange/exchange-email-security-spam-protection).
  
Procurando informações sobre o gerenciamento de domínio ou o Bloqueio de Borda Baseado em Diretório (DBEB)? Consulte [Gerenciamento de destinatário, domínios e de empresa](recipient-domain-and-company-management.md). Para saber mais sobre todos os recursos do EOP, consulte [Descrição do serviço de proteção do Exchange Online](exchange-online-protection-service-description.md).
  
## <a name="routing-email-between-office-365-and-your-own-email-servers"></a>Direcionar os emails entre seus próprios servidores de email e o Office 365
<a name="BKMK_outboundmailrouting"> </a>

Você pode configurar um conector para permitir o fluxo de emails entre o Office 365 (incluindo o Exchange Online ou a EOP) e um servidor de emails baseado em SMTP, como o Exchange. Confira mais detalhes sobre isso em [Do I need a connector](http://technet.microsoft.com/library/16731ae9-c909-49dd-bffc-a46e6151fc29.aspx)? e [Set up connectors to route mail between Office 365 and your own email servers](http://technet.microsoft.com/library/2e93fd60-a5ef-4e64-8e62-2b862b2d1033.aspx).
  
## <a name="secure-messaging-with-a-trusted-partner"></a>Secure messaging with a trusted partner
<a name="BKMK_securemessagingwithatrustedpartner"> </a>

Como cliente da EOP, você configura um fluxo de emails seguro com um parceiro de confiança usando os conectores do Office 365. O Office 365 dá suporte à comunicação segura por meio de TLS (Transport Layer Security), e você cria um conector para impor criptografia por meio de TLS. O [TLS](https://technet.microsoft.com/en-us/library/mt163898.aspx) é um protocolo criptográfico que oferece segurança para comunicações pela Internet. Usando conectores, você configura o TLS forçado tanto de entrada quanto de saída usando certificados autoassinados ou certificados validados pela AC (autoridade de certificação). Você também aplica outras restrições de segurança, como especificar nomes de domínio ou intervalos de endereços IP, dos quais a organização parceira envia emails. 
  
Saiba mais em [Configurar conectores para fluxo de email seguro com uma organização parceira](https://technet.microsoft.com/en-us/library/dn751021%28v=exchg.150%29.aspx)
  
## <a name="safe-listing-a-partners-ip-address"></a>Lista segura de endereço IP de um parceiro
<a name="BKMK_safelistingapartnersipaddress"> </a>

Você pode adicionar o endereço IP de um parceiro de confiança a uma lista segura para garantir que as mensagens enviadas por ele não fiquem sujeitas ao filtro antispam. Para tanto, você pode usar a Lista de IPs Permitidos do filtro de conexão. Saiba mais em [Configure a política de filtro de conexão](https://go.microsoft.com/fwlink/p/?LinkID=287108).
  
## <a name="conditional-mail-routing"></a>Roteamento de email condicional
<a name="BKMK_conditionalmailrouting"> </a>

Você pode configurar um conector com uma regra de Transporte que roteia emails para um site específico, com base em condições. Saiba mais em [Scenario: Conditional email routing](http://technet.microsoft.com/library/82d105e2-e955-4e03-99c3-3314a5d21a4c.aspx).
  
## <a name="hybrid-mail-routing"></a>Hybrid mail routing
<a name="BKMK_hybridmailrouting"> </a>

Híbrido significa que você hospeda parte das caixas de correio no local e parte na nuvem (Exchange Online). Você pode mudar de uma implantação autônoma (no local) para uma híbrida.
  
Se tiver uma implantação híbrida, poderá proteger suas caixas de correio locais e na nuvem com a EOP. São necessárias licenças autônomas para as caixas de correio locais protegidas por EOP. Confira mais informações sobre o roteamento de emails em uma implantação híbrida em [Roteamento de Transporte em implantações híbridas do Exchange](https://go.microsoft.com/fwlink/p/?LinkId=271757).
  
O [Assistente de Implantação do Microsoft Exchange Server](https://go.microsoft.com/fwlink/p/?LinkId=287036) também oferece um provisionamento de implantação híbrida e um guia de transporte de mensagens híbrido. 
  
## <a name="feature-availability"></a>Disponibilidade do recurso
<a name="BKMK_hybridmailrouting"> </a>

Para exibir a disponibilidade de recursos nos planos do Office 365 nas opções autônomas e nas soluções locais, consulte [Descrição do serviço de proteção do Exchange Online](exchange-online-protection-service-description.md).
  

