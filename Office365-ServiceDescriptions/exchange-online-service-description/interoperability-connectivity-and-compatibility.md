---
title: Interoperabilidade, Conectividade e Compatibilidade
ms.author: sharik
author: skjerland
manager: mnirkhe
audience: ITPro
ms.topic: reference
f1_keywords:
- exchange-online-interoperability-connectivity-compatibility
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: cdfe686d-a059-4f4d-bb8d-9c2c0ebfa423
ms.openlocfilehash: 38ab8f7baf16c5bf837bca9310a0d34a5e25469f
ms.sourcegitcommit: 96dc758c790ddaf05f5c2b836451b417729cf119
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 07/18/2019
ms.locfileid: "35776792"
---
# <a name="interoperability-connectivity-and-compatibility"></a><span data-ttu-id="459ea-102">Interoperabilidade, Conectividade e Compatibilidade</span><span class="sxs-lookup"><span data-stu-id="459ea-102">Interoperability, Connectivity, and Compatibility</span></span>

## <a name="interoperability-with-other-microsoft-products"></a><span data-ttu-id="459ea-103">Interoperabilidade com outros produtos da Microsoft</span><span class="sxs-lookup"><span data-stu-id="459ea-103">Interoperability with other Microsoft products</span></span>

### <a name="skype-for-business-online"></a><span data-ttu-id="459ea-104">Skype for Business Online</span><span class="sxs-lookup"><span data-stu-id="459ea-104">Skype for Business Online</span></span>

<span data-ttu-id="459ea-105">Para clientes que implantaram o Microsoft Lync Server 2010, o Lync Server 2013 ou o Microsoft Office Communications Server 2007 R2 localmente, o Microsoft Office Communicator poderá se conectar ao Microsoft Exchange Online usando os Serviços Web do Exchange para acessar dados de calendário e mensagens de ausência temporária.</span><span class="sxs-lookup"><span data-stu-id="459ea-105">For customers who have deployed Microsoft Lync Server 2010, Lync Server 2013 or Microsoft Office Communications Server 2007 R2 on-premises, Microsoft Office Communicator can connect to Microsoft Exchange Online by using Exchange Web Services to access out-of-office messages and calendar data.</span></span>
  
<span data-ttu-id="459ea-106">O Lync Server 2010 e o Lync Server 2013 locais poderão interoperar com o Exchange Online de duas maneiras adicionais:</span><span class="sxs-lookup"><span data-stu-id="459ea-106">On-premises Lync Server 2010 and Lync Server 2013 can interoperate with Exchange Online in two additional ways:</span></span>
  
- <span data-ttu-id="459ea-107">IM (Mensagens instantâneas) e interoperabilidade de presença no Outlook Web App</span><span class="sxs-lookup"><span data-stu-id="459ea-107">IM and presence interoperability in Outlook Web App</span></span>
    
- <span data-ttu-id="459ea-108">Interoperabilidade de caixa postal</span><span class="sxs-lookup"><span data-stu-id="459ea-108">Voice mail interoperability</span></span>
    
<span data-ttu-id="459ea-p101">Para saber mais sobre como configurar o Skype for Business Server 2015 com o Exchange Online, confira [Configurando a integração local do Skype for Business Server 2015 com o Exchange Online](https://go.microsoft.com/fwlink/p/?LinkId=271804). Para configurações híbridas, confira [Configurações híbridas do Skype for Business Server 2015 compatíveis](https://go.microsoft.com/fwlink/?LinkID=513084).</span><span class="sxs-lookup"><span data-stu-id="459ea-p101">For more information about how to configure Skype for Business Server 2015 with Exchange Online, see [Configuring On-premises Skype for Business Server 2015 Integration with Exchange Online](https://go.microsoft.com/fwlink/p/?LinkId=271804). For hybrid configurations, see [Supported Skype for Business Server 2015 hybrid configurations](https://go.microsoft.com/fwlink/?LinkID=513084).</span></span>
  
### <a name="microsoft-sharepoint"></a><span data-ttu-id="459ea-111">Microsoft SharePoint</span><span class="sxs-lookup"><span data-stu-id="459ea-111">Microsoft SharePoint</span></span>

<span data-ttu-id="459ea-112">Para os clientes que implantaram o Microsoft SharePoint Server ou o SharePoint Online, como parte de um plano de assinatura do Office 365, o SharePoint pode conectar-se ao Exchange Online para serviços integrados.</span><span class="sxs-lookup"><span data-stu-id="459ea-112">For customers who have deployed Microsoft SharePoint Server or SharePoint Online as part of an Office 365 subscription plan, SharePoint can connect to Exchange Online for integrated services.</span></span>
  
<span data-ttu-id="459ea-113">Para saber mais sobre conectar o SharePoint ao Exchange Online, confira [Utilizar o SharePoint Online em um domínio personalizado junto com outros serviços](https://go.microsoft.com/fwlink/?LinkId=271805).</span><span class="sxs-lookup"><span data-stu-id="459ea-113">For more information about connecting SharePoint to Exchange Online, see [Use SharePoint Online on a custom domain together with other services](https://go.microsoft.com/fwlink/?LinkId=271805).</span></span>
  
## <a name="features-for-external-connectivity"></a><span data-ttu-id="459ea-114">Recursos para conectividade externa</span><span class="sxs-lookup"><span data-stu-id="459ea-114">Features for external connectivity</span></span>

<span data-ttu-id="459ea-115">O Exchange Online oferece os seguintes recursos para a conexão com aplicativos e dispositivos externos:</span><span class="sxs-lookup"><span data-stu-id="459ea-115">Exchange Online offers the following features for connecting with external applications and devices:</span></span>
  
- <span data-ttu-id="459ea-p102">**Por meio de protocolos de mensagem, como MAPI sobre HTTP, SMTP, POP3, IMAP4 ou Serviços Web do Exchange** Os aplicativos externos que estão sendo executados no local, no Azure ou em outros serviços hospedados podem acessar os dados armazenados com o Exchange Online usando protocolos de mensagem, como MAPI sobre HTTP, SMTP, POP3 e IMAPv4. Os Serviços Web Exchange, ou API de Serviços Gerenciados do Web Exchange são recomendados para o desenvolvimento do aplicativo.</span><span class="sxs-lookup"><span data-stu-id="459ea-p102">**Through messaging protocols such as MAPI over HTTP, SMTP, POP3, IMAP4, or Exchange Web Services** External applications that are running on-premises, in Azure, or in other hosted services can access data stored with Exchange Online by using messaging protocols such as MAPI over HTTP, SMTP, POP3, and IMAPv4. Exchange Web Services or the Exchange Web Services Managed API is recommended for application development.</span></span> 
    
- <span data-ttu-id="459ea-118">**Como uma retransmissão SMTP** O Exchange Online pode ser configurado como um serviço de entrega SMTP para retransmitir mensagens de email enviadas por gateways de fax, dispositivos de rede e aplicativos personalizados.</span><span class="sxs-lookup"><span data-stu-id="459ea-118">**As an SMTP relay** Exchange Online can be set up as an SMTP delivery service to relay email messages sent from fax gateways, network appliances, and custom applications.</span></span> 
    
### <a name="exchange-web-services"></a><span data-ttu-id="459ea-119">Serviços Web do Exchange</span><span class="sxs-lookup"><span data-stu-id="459ea-119">Exchange Web Services</span></span>

<span data-ttu-id="459ea-p103">Serviços Web Exchange (EWS) são o API de desenvolvimento preferencial para o Exchange Server e o Exchange Online. Usando o EWS ou a API gerenciada do EWS, os administradores podem acessar os dados armazenados com o Exchange Online a partir dos aplicativos executados no local, no Azure ou em outros serviços hospedados. O EWS permite que os administradores realizem ações especializadas, como consultar o conteúdo de uma caixa de correio em fila, publicar um evento de calendário, criar uma tarefa ou disparar uma ação específica baseada no conteúdo de uma mensagem de email. O Exchange Online habilita a funcionalidade EWS, concedendo permissões de aplicativo para as contas de clientes. Essas permissões permitem que o aplicativo de cliente acesse a caixa de correio do aplicativo e adicione conteúdo. A Representação do Exchange é um método usado para conceder permissões de aplicativo. Para obter mais detalhes sobre como usar os Serviços Web do Exchange com o Exchange Online, consulte os artigos técnicos no Centro de Desenvolvimento do Exchange Online.</span><span class="sxs-lookup"><span data-stu-id="459ea-p103">Exchange Web Services (EWS) is the preferred development API for Exchange Server and Exchange Online. Using EWS or the EWS Managed API, administrators can access data stored with Exchange Online from applications that are running on-premises, in Azure, or in other hosted services. EWS enables administrators to perform specialized actions, such as querying the contents of a mailbox, posting a calendar event, creating a task, or triggering a specific action based on the content of an email message. Exchange Online enables EWS functionality by granting application permissions to customer accounts. These permissions allow the customer application to access the application mailbox and add content. Exchange Impersonation is one method used to grant application permissions. For details about how to use Exchange Web Services with Exchange Online, refer to the technical articles at the Exchange Online Developer Center.</span></span>
  
### <a name="smtp-relay"></a><span data-ttu-id="459ea-127">Retransmissão SMTP</span><span class="sxs-lookup"><span data-stu-id="459ea-127">SMTP relay</span></span>

<span data-ttu-id="459ea-p104">O Exchange Online pode ser usado como um serviço de entrega SMTP, para retransmitir as mensagens de email enviadas de gateways de fax, dispositivos de rede e aplicativos personalizados. Por exemplo, se um aplicativo de linha de negócios envia alertas de email para usuários, ele pode ser configurado para usar o Exchange Online como o sistema de entrega de email. O aplicativo ou serviço deve ser autenticado com o nome de usuário e senha de uma caixa de correio válida e licenciada do Exchange Online, e conectar-se usando o protocolo TLS (Transport Layer Security).</span><span class="sxs-lookup"><span data-stu-id="459ea-p104">Exchange Online can be used as an SMTP delivery service to relay email messages sent from fax gateways, network appliances, and custom applications. For example, if a line-of-business application sends email alerts to users, it can be configured to use Exchange Online as the mail delivery system. The application or service must authenticate with the username and password of a valid, licensed Exchange Online mailbox, and connect by using Transport Layer Security (TLS).</span></span>
  
## <a name="feature-availability"></a><span data-ttu-id="459ea-131">Disponibilidade do recurso</span><span class="sxs-lookup"><span data-stu-id="459ea-131">Feature Availability</span></span>

<span data-ttu-id="459ea-132">Para exibir a disponibilidade de recursos nos planos do Office 365 nas opções autônomas e nas soluções locais, consulte [Descrição de Serviço do Exchange Online](exchange-online-service-description.md).</span><span class="sxs-lookup"><span data-stu-id="459ea-132">To view feature availability across Office 365 plans, standalone options, and on-premise solutions, see [Exchange Online Service Description](exchange-online-service-description.md).</span></span>
  

