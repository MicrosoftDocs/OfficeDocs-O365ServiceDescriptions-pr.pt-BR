---
title: Fluxo de mensagens
ms.author: office365servicedesc
author: pamelaar
audience: ITPro
ms.topic: reference
f1_keywords:
- exchange-online-mail-flow
ms.service: o365-administration
localization_priority: Normal
ms.custom:
- Adm_ServiceDesc
- Adm_ServiceDesc_top
ms.assetid: 8e5267e6-d224-485b-a081-c71a1fd0c4c3
description: Para a maioria das organizações, hospedamos suas caixas de correio e cuidamos do fluxo de emails. É a configuração mais simples e significa que a Microsoft gerencia todas as caixas de correio e filtragem. Entretanto, algumas organizações precisam de configurações de fluxo de emails mais complexas para garantir que eles atendam às necessidades regulamentares ou de negócios específicas. Saiba mais sobre essas opções aqui.
ms.openlocfilehash: 1ada5a3199e6ae65c6aaa99873f13a4025366a8d
ms.sourcegitcommit: d2cd67e52dd646b68bfbfd8a387e70a6da140a62
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 07/14/2020
ms.locfileid: "45132715"
---
# <a name="mail-flow"></a>Fluxo de emails

Para a maioria das organizações, hospedamos suas caixas de correio e cuidamos do fluxo de emails. É a configuração mais simples e significa que a Microsoft gerencia todas as caixas de correio e filtragem. Entretanto, algumas organizações precisam de configurações de fluxo de emails mais complexas para garantir que eles atendam às necessidades regulamentares ou de negócios específicas. Saiba mais sobre essas opções aqui. 
  
## <a name="custom-routing-of-outbound-email"></a>Roteamento personalizado de email de saída

O Microsoft Exchange Online pode rotear os emails que estão saindo da sua organização por meio de um servidor local ou um serviço hospedado (às vezes chamado de "host inteligente"). Isso permite que sua organização use dispositivos DLP (prevenção contra perda de dados), execute o pós-processamento personalizado de emails de saída e envie emails para parceiros de negócios por meio de redes privadas. O Exchange Online também dá suporte à Regravação de Endereço, que encaminha emails de saída por meio de um gateway local que modifica os endereços. Esse recurso permite ocultar subdomínios, fazer com que os emails de uma organização de vários domínios sejam exibidos como um único domínio ou fazer com que o email retransmitido por parceiro pareça ser enviado de dentro da sua organização. Os administradores configuram o roteamento do email personalizado dentro do EAC (Centro de Administração do Exchange).
  
Para saber mais, confira [set up Connectors to Route mail between the Microsoft e seus próprios servidores de email](https://docs.microsoft.com/exchange/mail-flow-best-practices/use-connectors-to-configure-mail-flow/set-up-connectors-to-route-mail).
  
> [!IMPORTANT]
> O Exchange Online entrega emails fluindo para dentro ou para fora da organização. Se o domínio do destinatário estiver hospedado no Exchange Online com registros MX do DNS apontando para a proteção do Exchange Online, o fluxo de emails do seu locatário para o destinatário não viajará pela Internet.
  
## <a name="secure-messaging-with-a-trusted-partner"></a>Secure messaging with a trusted partner

Como cliente do Exchange Online, você pode configurar o fluxo de email seguro com um parceiro confiável usando conectores da Microsoft. A Microsoft dá suporte à comunicação segura através da Transport Layer Security (TLS) e você pode criar um conector para impor a criptografia via TLS. O [TLS](https://docs.microsoft.com/office365/securitycompliance/exchange-online-uses-tls-to-secure-email-connections) é um protocolo criptográfico que oferece segurança para comunicações pela Internet. Usando conectores, você configura o TLS forçado tanto de entrada quanto de saída usando certificados autoassinados ou certificados validados pela AC (autoridade de certificação). Você também aplica outras restrições de segurança, como especificar nomes de domínio ou intervalos de endereços IP, dos quais a organização parceira envia emails. 
  
Saiba mais em [Set up connectors for secure mail flow with a partner organization](https://docs.microsoft.com/exchange/mail-flow-best-practices/use-connectors-to-configure-mail-flow/set-up-connectors-for-secure-mail-flow-with-a-partner).
  
> [!IMPORTANT]
> Pode ser necessário um certificado validado por CA. 
  
## <a name="conditional-mail-routing"></a>Roteamento de email condicional

You can direct mail to specific sites by using connectors and transport rules. With criteria-based routing, you can choose a connector based on specific conditions.
  
Saiba mais em [Scenario: Conditional mail routing](https://docs.microsoft.com/exchange/mail-flow-best-practices/use-connectors-to-configure-mail-flow/conditional-mail-routing).
  
## <a name="incoming-mail-safe-list"></a>Lista segura de emails de entrada

You can add a trusted partner's IP address to a safe list to ensure that messages the partner sends to you are not subject to anti-spam filtering. To do this, you can use the connection filter's IP Allow list.
  
Saiba mais em [Configure the connection filter policy](https://docs.microsoft.com/office365/SecurityCompliance/configure-the-connection-filter-policy).
  
## <a name="hybrid-email-routing"></a>Roteamento de email híbrido

A hybrid deployment gives organizations the ability to extend the feature-rich experience and administrative control they have with their existing on-premises Microsoft Exchange organization to the cloud. With hybrid transport, messages sent between recipients in either organization are authenticated, encrypted, and transferred using Transport Layer Security (TLS), and appear as "internal" to Exchange components such as transport rules, journaling, and anti-spam policies. You configure hybrid transport by using the Hybrid Configuration Wizard in Exchange Server.
  
Para saber mais sobre o roteamento de emails em uma implantação híbrida, confira [Roteamento de Transporte em Implantações Híbridas do Exchange](https://go.microsoft.com/fwlink/p/?LinkId=271757).
  
O [Assistente de Implantação do Microsoft Exchange Server](https://go.microsoft.com/fwlink/p/?LinkId=287036) também oferece um provisionamento de implantação híbrida e um guia de transporte de mensagens híbrido. 
  
### <a name="shared-address-space-with-on-premises-routing-control-mx-points-to-on-premises"></a>Espaço de endereço compartilhado com controle de roteamento local (MX aponta para local)

Espaço de endereçamento compartilhado com controle de roteamento local (os pontos MX para local) é um cenário de roteamento de email de implantação híbrida no qual as suas caixas de correio são hospedadas parcialmente no Exchange Online e no local, e o fluxo de emails de entrada e saída é roteado através da organização do Exchange local. Esse cenário é também chamado de transporte de email centralizado. Neste cenário, o Exchange Online é provisionado com o EOP e o email de entrada da Internet é roteado para o seu servidor de email local antes de ser roteado para o EOP e finalmente para caixas de correio hospedadas no Exchange Online. Além disso, o email de saída das caixas de correio do Exchange Online é encaminhado por meio da organização do Exchange local para mensagens enviadas a destinatários externos. Com essa configuração, você usa um namespace de domínio SMTP único para todas as caixas de correio na organização do Exchange local e na sua organização do Exchange Online. 
  
Para saber mais sobre as opções de transporte em uma implantação híbrida, confira [Opções de Transporte em Implantações Híbridas do Exchange](https://go.microsoft.com/fwlink/p/?LinkID=271758).
  
### <a name="shared-address-space-without-on-premises-routing-control-mx-points-to-eop"></a>Espaço de endereço compartilhado sem controle de roteamento local (MX aponta para EOP)

Espaço de Endereço Compartilhado sem Controle de Roteamento Local (o MX aponta para o EOP) é um cenário de roteamento de email híbrido no qual suas caixas de correio são hospedadas parcialmente na nuvem usando o Exchange Online e parcialmente o Exchange local, e seu registro MX aponta para o EOP. Este cenário é apropriado quando você usa a Microsoft para hospedar algumas das caixas de correio da sua organização e deseja que o EOP proteja as suas caixas de correio locais e em nuvem. Neste cenário, o email enviado aos destinatários na organização é inicialmente encaminhado por meio do EOP, em que a filtragem de spam e de política ocorre, antes de chegar às caixas de correio locais e na nuvem. 
  
Para saber mais sobre as opções de transporte em uma implantação híbrida, confira [Opções de Transporte em Implantações Híbridas do Exchange](https://go.microsoft.com/fwlink/p/?LinkID=271758).
  
### <a name="troubleshooting-a-deployment-with-the-hybrid-configuration-wizard"></a>Solucionando problemas de uma implantação com o Assistente de Configuração Híbrida

Using the Hybrid Configuration Wizard to configure a hybrid deployment in Microsoft Exchange Server greatly minimizes the potential that the hybrid deployment will experience problems. However, there are some typical areas outside the scope of the Hybrid Configuration Wizard that, if misconfigured, may present problems in a hybrid deployment. These include proper Client Access server configuration and proper certificate installation and configuration.
  
Saiba mais sobre a solução de problemas de uma implantação com o Assistente de Configuração Híbrida em [Solucionar problemas de implantação híbrida](https://go.microsoft.com/fwlink/p/?LinkId=271040).
  
### <a name="managing-a-hybrid-configuration"></a>Gerenciando uma configuração híbrida

You can modify an existing hybrid configuration by changing settings in the Hybrid Configuration Wizard. Scenarios include disabling centralized transport or disabling secure mail transport.
  
Saiba mais sobre o gerenciamento de uma configuração de implantação híbrida em [Gerenciar uma Implantação Híbrida](https://go.microsoft.com/fwlink/p/?LinkId=271044).
  
### <a name="hybrid-deployment-requirements"></a>Requisitos de implantação híbrida

Saiba mais sobre os requisitos de implantação híbrida em [Pré-requisitos da implantação híbrida](https://go.microsoft.com/fwlink/p/?LinkId=271759).
  
> [!IMPORTANT]
> Em algumas configurações híbrida, pode ser preciso adquirir as licenças da Proteção do Exchange Online para as suas caixas de correio local. 
  
## <a name="feature-availability"></a>Disponibilidade de recursos

Para exibir a disponibilidade de recursos nos planos, nas opções autônomas e nas soluções locais, consulte a [Descrição do serviço do Exchange Online](exchange-online-service-description.md).
  