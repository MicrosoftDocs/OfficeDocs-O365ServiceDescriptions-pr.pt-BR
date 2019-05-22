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
# <a name="mail-floweop"></a><span data-ttu-id="4d992-107">Fluxo de mensagens [EOP]</span><span class="sxs-lookup"><span data-stu-id="4d992-107">Mail Flow[EOP]</span></span>

<span data-ttu-id="4d992-108">Hospedamos as caixas de correio e cuidamos do fluxo de emails da maioria das organizações que usam o Office 365.</span><span class="sxs-lookup"><span data-stu-id="4d992-108">For most organizations that use Office 365, we host your mailboxes and take care of mail flow.</span></span> <span data-ttu-id="4d992-109">É a configuração mais simples e significa que o Office 365 gerencia todas as caixas de correio e filtros.</span><span class="sxs-lookup"><span data-stu-id="4d992-109">It's the simplest configuration and means that Office 365 manages all mailboxes and filtering.</span></span> <span data-ttu-id="4d992-110">No entanto, algumas organizações têm a necessidade comercial de manter todas as caixas de correio no local.</span><span class="sxs-lookup"><span data-stu-id="4d992-110">However, some organizations have a business need to keep all their mailboxes on premises.</span></span> <span data-ttu-id="4d992-111">A EOP (Proteção do Exchange Online) permite que você faça isso e oferece o processamento de emails antivírus e antispam na nuvem.</span><span class="sxs-lookup"><span data-stu-id="4d992-111">Exchange Online Protection (EOP) enables you to do that and provides antivirus and anti-spam mail processing in the cloud.</span></span> <span data-ttu-id="4d992-112">Para mais informações e adquirir a EOP, acesse [Proteção do Exchange Online](https://products.office.com/en-us/exchange/exchange-email-security-spam-protection).</span><span class="sxs-lookup"><span data-stu-id="4d992-112">For more information and to purchase EOP, go to [Exchange Online Protection](https://products.office.com/en-us/exchange/exchange-email-security-spam-protection).</span></span>
  
<span data-ttu-id="4d992-p103">Procurando informações sobre o gerenciamento de domínio ou o Bloqueio de Borda Baseado em Diretório (DBEB)? Consulte [Gerenciamento de destinatário, domínios e de empresa](recipient-domain-and-company-management.md). Para saber mais sobre todos os recursos do EOP, consulte [Descrição do serviço de proteção do Exchange Online](exchange-online-protection-service-description.md).</span><span class="sxs-lookup"><span data-stu-id="4d992-p103">Looking for information about domain management or Directory Based Edge Blocking (DBEB)? See [Recipient, Domain, and Company Management](recipient-domain-and-company-management.md). To learn more about all EOP features, see the [Exchange Online Protection Service Description](exchange-online-protection-service-description.md).</span></span>
  
## <a name="routing-email-between-office-365-and-your-own-email-servers"></a><span data-ttu-id="4d992-116">Direcionar os emails entre seus próprios servidores de email e o Office 365</span><span class="sxs-lookup"><span data-stu-id="4d992-116">Routing email between Office 365 and your own email servers</span></span>
<span data-ttu-id="4d992-117"><a name="BKMK_outboundmailrouting"> </a></span><span class="sxs-lookup"><span data-stu-id="4d992-117"></span></span>

<span data-ttu-id="4d992-p104">Você pode configurar um conector para permitir o fluxo de emails entre o Office 365 (incluindo o Exchange Online ou a EOP) e um servidor de emails baseado em SMTP, como o Exchange. Confira mais detalhes sobre isso em [Do I need a connector](http://technet.microsoft.com/library/16731ae9-c909-49dd-bffc-a46e6151fc29.aspx)? e [Set up connectors to route mail between Office 365 and your own email servers](http://technet.microsoft.com/library/2e93fd60-a5ef-4e64-8e62-2b862b2d1033.aspx).</span><span class="sxs-lookup"><span data-stu-id="4d992-p104">You can configure a connector to enable mail flow between Office 365 (including Exchange Online or EOP) and an SMTP-based email server such as Exchange. For details about this, see [Do I need a connector](http://technet.microsoft.com/library/16731ae9-c909-49dd-bffc-a46e6151fc29.aspx)? And [Set up connectors to route mail between Office 365 and your own email servers](http://technet.microsoft.com/library/2e93fd60-a5ef-4e64-8e62-2b862b2d1033.aspx).</span></span>
  
## <a name="secure-messaging-with-a-trusted-partner"></a><span data-ttu-id="4d992-121">Secure messaging with a trusted partner</span><span class="sxs-lookup"><span data-stu-id="4d992-121">Secure messaging with a trusted partner</span></span>
<span data-ttu-id="4d992-122"><a name="BKMK_securemessagingwithatrustedpartner"> </a></span><span class="sxs-lookup"><span data-stu-id="4d992-122"></span></span>

<span data-ttu-id="4d992-p105">Como cliente da EOP, você configura um fluxo de emails seguro com um parceiro de confiança usando os conectores do Office 365. O Office 365 dá suporte à comunicação segura por meio de TLS (Transport Layer Security), e você cria um conector para impor criptografia por meio de TLS. O [TLS](https://technet.microsoft.com/en-us/library/mt163898.aspx) é um protocolo criptográfico que oferece segurança para comunicações pela Internet. Usando conectores, você configura o TLS forçado tanto de entrada quanto de saída usando certificados autoassinados ou certificados validados pela AC (autoridade de certificação). Você também aplica outras restrições de segurança, como especificar nomes de domínio ou intervalos de endereços IP, dos quais a organização parceira envia emails.</span><span class="sxs-lookup"><span data-stu-id="4d992-p105">As an EOP customer, you can set up secure mail flow with a trusted partner by using Office 365 connectors. Office 365 supports secure communication through Transport Layer Security (TLS), and you can create a connector to enforce encryption via TLS. [TLS](https://technet.microsoft.com/en-us/library/mt163898.aspx) is a cryptographic protocol that provides security for communications over the Internet. By using connectors, you can configure both forced incoming and outgoing TLS using self-signed or certification authority (CA)-validated certificates. You can also apply other security restrictions, such as specifying domain names or IP address ranges from which your partner organization sends mail.</span></span> 
  
<span data-ttu-id="4d992-128">Saiba mais em [Configurar conectores para fluxo de email seguro com uma organização parceira](https://technet.microsoft.com/en-us/library/dn751021%28v=exchg.150%29.aspx)</span><span class="sxs-lookup"><span data-stu-id="4d992-128">For more information, see [Set up connectors for secure mail flow with a partner organization](https://technet.microsoft.com/en-us/library/dn751021%28v=exchg.150%29.aspx).</span></span>
  
## <a name="safe-listing-a-partners-ip-address"></a><span data-ttu-id="4d992-129">Lista segura de endereço IP de um parceiro</span><span class="sxs-lookup"><span data-stu-id="4d992-129">Safe listing a partner's IP address</span></span>
<span data-ttu-id="4d992-130"><a name="BKMK_safelistingapartnersipaddress"> </a></span><span class="sxs-lookup"><span data-stu-id="4d992-130"></span></span>

<span data-ttu-id="4d992-p106">Você pode adicionar o endereço IP de um parceiro de confiança a uma lista segura para garantir que as mensagens enviadas por ele não fiquem sujeitas ao filtro antispam. Para tanto, você pode usar a Lista de IPs Permitidos do filtro de conexão. Saiba mais em [Configure a política de filtro de conexão](https://go.microsoft.com/fwlink/p/?LinkID=287108).</span><span class="sxs-lookup"><span data-stu-id="4d992-p106">You can add a trusted partner's IP address to a safe list to ensure that messages they send to you are not subject to spam filtering. To do this, you can use the connection filter's IP Allow list. For more information, see [Configure the connection filter policy](https://go.microsoft.com/fwlink/p/?LinkID=287108).</span></span>
  
## <a name="conditional-mail-routing"></a><span data-ttu-id="4d992-134">Roteamento de email condicional</span><span class="sxs-lookup"><span data-stu-id="4d992-134">Conditional mail routing</span></span>
<span data-ttu-id="4d992-135"><a name="BKMK_conditionalmailrouting"> </a></span><span class="sxs-lookup"><span data-stu-id="4d992-135"></span></span>

<span data-ttu-id="4d992-p107">Você pode configurar um conector com uma regra de Transporte que roteia emails para um site específico, com base em condições. Saiba mais em [Scenario: Conditional email routing](http://technet.microsoft.com/library/82d105e2-e955-4e03-99c3-3314a5d21a4c.aspx).</span><span class="sxs-lookup"><span data-stu-id="4d992-p107">You can configure a connector with a Transport rule that routes mail to a specific site, based on conditions. For more information, see [Scenario: Conditional email routing](http://technet.microsoft.com/library/82d105e2-e955-4e03-99c3-3314a5d21a4c.aspx).</span></span>
  
## <a name="hybrid-mail-routing"></a><span data-ttu-id="4d992-138">Hybrid mail routing</span><span class="sxs-lookup"><span data-stu-id="4d992-138">Hybrid mail routing</span></span>
<span data-ttu-id="4d992-139"><a name="BKMK_hybridmailrouting"> </a></span><span class="sxs-lookup"><span data-stu-id="4d992-139"></span></span>

<span data-ttu-id="4d992-p108">Híbrido significa que você hospeda parte das caixas de correio no local e parte na nuvem (Exchange Online). Você pode mudar de uma implantação autônoma (no local) para uma híbrida.</span><span class="sxs-lookup"><span data-stu-id="4d992-p108">Hybrid means that you host a portion of your mailboxes on premises, and a portion in the cloud (Exchange Online). You can move from a standalone (on-premises) deployment to a hybrid deployment.</span></span>
  
<span data-ttu-id="4d992-p109">Se tiver uma implantação híbrida, poderá proteger suas caixas de correio locais e na nuvem com a EOP. São necessárias licenças autônomas para as caixas de correio locais protegidas por EOP. Confira mais informações sobre o roteamento de emails em uma implantação híbrida em [Roteamento de Transporte em implantações híbridas do Exchange](https://go.microsoft.com/fwlink/p/?LinkId=271757).</span><span class="sxs-lookup"><span data-stu-id="4d992-p109">If you have a hybrid deployment, you can protect your cloud and on-premises mailboxes with EOP. Standalone licenses are required for on-premises mailboxes, when they are protected by EOP. For more information about mail routing in a hybrid deployment, see [Transport routing in Exchange hybrid deployments](https://go.microsoft.com/fwlink/p/?LinkId=271757).</span></span>
  
<span data-ttu-id="4d992-145">O [Assistente de Implantação do Microsoft Exchange Server](https://go.microsoft.com/fwlink/p/?LinkId=287036) também oferece um provisionamento de implantação híbrida e um guia de transporte de mensagens híbrido.</span><span class="sxs-lookup"><span data-stu-id="4d992-145">The [Microsoft Exchange Server Deployment Assistant](https://go.microsoft.com/fwlink/p/?LinkId=287036) also provides detailed hybrid deployment provisioning and hybrid message transport guidance.</span></span> 
  
## <a name="feature-availability"></a><span data-ttu-id="4d992-146">Disponibilidade do recurso</span><span class="sxs-lookup"><span data-stu-id="4d992-146">Feature Availability</span></span>
<span data-ttu-id="4d992-147"><a name="BKMK_hybridmailrouting"> </a></span><span class="sxs-lookup"><span data-stu-id="4d992-147"></span></span>

<span data-ttu-id="4d992-148">Para exibir a disponibilidade de recursos nos planos do Office 365 nas opções autônomas e nas soluções locais, consulte [Descrição do serviço de proteção do Exchange Online](exchange-online-protection-service-description.md).</span><span class="sxs-lookup"><span data-stu-id="4d992-148">To view feature availability across Office 365 plans, standalone options, and on-premise solutions, see [Exchange Online Protection Service Description](exchange-online-protection-service-description.md).</span></span>
  

