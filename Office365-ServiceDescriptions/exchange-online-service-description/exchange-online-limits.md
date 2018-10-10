---
title: Limites do Exchange Online
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.date: 7/13/2018
ms.audience: ITPro
ms.topic: reference
f1_keywords:
- exchange-online-limits
ms.service: o365-administration
localization_priority: Normal
ms.custom:
- Adm_ServiceDesc
- Adm_ServiceDesc_top
ms.assetid: 70b38a05-6cfa-4ced-a137-116019262fed
description: Encontre os limites do Exchange Online para diversas áreas de serviço, incluindo limites de catálogo de endereços, limites de armazenamento de caixa de correio e limites de rastreamento de mensagem e relatórios, para mencionar apenas alguns exemplos.
ms.openlocfilehash: f6b47ddbbba3eeb40c564bbcfa5ace25671ade9e
ms.sourcegitcommit: 451688016111b1ccae37b9b84d7cf53d844acdbc
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 10/08/2018
ms.locfileid: "25450573"
---
# <a name="exchange-online-limits"></a>Limites do Exchange Online

Encontre os limites do Exchange Online para diversas áreas de serviço, incluindo limites de catálogo de endereços, limites de armazenamento de caixa de correio e limites de rastreamento de mensagem e relatórios, para mencionar apenas alguns exemplos.
  
> [!NOTE]
>  Se você precisar de ajuda com uma tarefa, ou se estiver solucionando um problema, talvez considere estes artigos úteis:  <br/> • [Email](https://support.office.com/en-us/article/Email-94275804-7147-4332-9ccd-5d421760a9ed?ui=en-US&amp;rs=en-US&amp;ad=US) (para ajuda criando e enviando email)  <br/> • [Email no Office 365 para empresas - ajuda de Admin](https://go.microsoft.com/fwlink/?linkid=529722) <br/>   • [Corrigir Outlook e problemas do Office 365 com o suporte da Microsoft e o Assistente de recuperação para o Office 365](https://diagnostics.office.com/) <br/>  • [Relatórios de entrega de email no Office 365](https://go.microsoft.com/fwlink/?linkid=526653) <br/> • A [Ajuda Online do exchange](https://go.microsoft.com/fwlink/?linkid=825607) <br/>
  
Os limites no Microsoft Exchange Online se encaixam em uma das seguintes categorias:
  
- [Limites de catálogo de endereços](#address-book-limits)
    
- [Limites de armazenamento de caixa de correio](#mailbox-storage-limits)
    
- [Alertas de capacidade](#capacity-alerts)
    
- [Limites da pasta da caixa de correio](#mailbox-folder-limits)
    
- [Limites de mensagem](#message-limits)

- [Receber e enviar limites](#receiving-and-sending-limits)
    
- [Limites de rastreamento de mensagens e relatórios](#reporting-and-message-trace-limits)
    
- [Limites de retenção](#retention-limits)
    
- [Limites de grupos de distribuição](#distribution-group-limits)
    
- [Limites de regra de diário, transporte e caixa de entrada](#journal-transport-and-inbox-rule-limits)
    
- [Limites de moderação](#moderation-limits)
    
- [Limites do Exchange ActiveSync](#exchange-activesync-limits)
    
> [!IMPORTANT]
>  • Os limites aplicados a uma organização do Microsoft Office 365 podem diferir, dependendo da organização quanto tempo foi registrado no serviço.<br/> • Quando um limite é alterado nos dados do Microsoft centrais, ela pode levar algum tempo para aplicar a alteração a todos os clientes existentes.<br/> • Você não pode modificar a maioria desses limites, mas você e seus usuários deve estar ciente deles.<br/> • Esses limites se aplicam a destinatários internos e externos.<br/> • Por padrão, o Exchange Online Protection (EOP) protege caixas de correio do Exchange Online. Para os limites que se aplicam aos recursos do EOP no Exchange Online, consulte [Exchange Online Protection Limits](../exchange-online-protection-service-description/exchange-online-protection-limits.md).<br/> • Para obter informações sobre limites de grupo do Office 365, consulte "Como gerenciar Meus groups?" [Saiba mais sobre os grupos do Office 365](https://go.microsoft.com/fwlink/?linkid=846714). 
  
## <a name="address-book-limits"></a>Limites de catálogo de endereços

- **Limite de lista de endereços** O número máximo de listas de endereços que pode ser criado em uma organização do Exchange Online ou do Exchange Server 2013. Esse número inclui listas de endereços padrão no Exchange Online, como Todos os Contatos e Todos os Grupos. 
    
    > [!NOTE]
    > Um máximo de 20 listas de endereços podem ser atribuídas a um único catálogo de endereços offline (OAB). 
  
- **Limite de catálogo de endereços offline** O número máximo de catálogos de endereços offline (OAB) que pode ser criado em uma organização do Exchange Online ou do Exchange Server 2013. 
    
- **Limite de políticas do catálogo de endereços** O número máximo de políticas de catálogo de endereços (ABP) que pode ser criado em uma organização do Exchange Online ou do Exchange Server 2013. 
    
- **Listas de endereços globais** O número máximo de listas de endereços global (GAL) que pode ser criado em uma organização do Exchange Online ou do Exchange Server 2013. 
    
### <a name="address-book-limits-across-office-365-options"></a>Opções de limites de catálogos de endereços no Office 365

||||||||
|:-----|:-----|:-----|:-----|:-----|:-----|:-----|
|**Recurso** <br/> |**Office 365 Business Essentials** <br/> |**Office 365 Business Premium** <br/> |**Office 365 Enterprise E1** <br/> |**Office 365 Enterprise E3** <br/> |**Office 365 Enterprise E5** <br/> |**Office 365 Enterprise F1** <br/> |
|Limite de lista de endereços  <br/> |1000  <br/> |1000  <br/> |1000  <br/> |1000  <br/> |1000  <br/> |1000  <br/> |
|Limite do catálogo de endereços offline (OAB)  <br/> |250  <br/> |250  <br/> |250  <br/> |250  <br/> |250  <br/> |250  <br/> |
|Limite das políticas de catálogo de endereços (ABP)  <br/> |250  <br/> |250  <br/> |250  <br/> |250  <br/> |250  <br/> |250  <br/> |
|Limite de listas de endereços globais  <br/> |250  <br/> |250  <br/> |250  <br/> |250  <br/> |250  <br/> |250  <br/> |
   
### <a name="address-book-limits-across-standalone-plans"></a>Limites de catálogo de endereços em planos autônomos

||||||
|:-----|:-----|:-----|:-----|:-----|
|**Recurso** <br/> |**Exchange Server 2013** <br/> |**Exchange Online (Plano 1)** <br/> |**Exchange Online (Plano 2)** <br/> |**Exchange Online Kiosk** <br/> |
|Limite de lista de endereços  <br/> |1000  <br/> |1000  <br/> |1000  <br/> |1000  <br/> |
|Limite do catálogo de endereços offline (OAB)  <br/> |250  <br/> |250  <br/> |250  <br/> |250  <br/> |
|Limite das políticas de catálogo de endereços (ABP)  <br/> |250  <br/> |250  <br/> |250  <br/> |250  <br/> |
|Limite de listas de endereços globais  <br/> |250  <br/> |250  <br/> |250  <br/> |250  <br/> |
   
## <a name="mailbox-storage-limits"></a>Limites de armazenamento de caixa de correio

A quantidade de armazenamento de caixa de correio disponível é determinada pelo tipo de caixa de correio e pela licença da assinatura do usuário. Os administradores podem reduzir o tamanho máximo da caixa de correio por usuário ou globalmente.
  
> [!NOTE]
> O uso de registro no diário, regras de transporte ou regras de encaminhamento automático para copiar mensagens para uma caixa de correio do Exchange Online com a finalidade de arquivamento não é permitido. A caixa de correio de arquivo morto de um usuário destina-se somente a esse usuário. A Microsoft reserva o direito de negar o arquivamento ilimitado em situações onde a caixa de correio de arquivo morto do usuário é usada para armazenar dados de arquivo morto de outros usuários. 
  
### <a name="storage-limits-across-office-365-options"></a>Limites de armazenamento em opções do Office 365

||||||||
|:-----|:-----|:-----|:-----|:-----|:-----|:-----|
|**Recurso** <br/> |**Office 365 Business Essentials** <br/> |**Office 365 Business Premium** <br/> |**Office 365 Enterprise E1** <br/> |**Office 365 Enterprise E3** <br/> |**Office 365 Enterprise E5** <br/> |**Office 365 Enterprise F1** <br/> |
|Caixas de correio de usuário  <br/> |50 GB  <br/> |50 GB  <br/> |50 GB  <br/> |100 GB  <br/> |100 GB  <br/> |2 GB  <br/> |
|Caixas de correio de arquivo morto<sup>7, 8</sup> <br/> |50 GB  <br/> |50 GB  <br/> |50 GB  <br/> |Ilimitado<sup>1</sup> <br/> |Ilimitado<sup>1</sup> <br/> |Não disponível<sup>4</sup> <br/> |
|Caixas de correio compartilhadas  <br/> |50 GB<sup>2</sup> <br/> |50 GB<sup>2</sup> <br/> |50 GB<sup>2</sup> <br/> |50 GB<sup>2,9</sup> <br/> |50 GB<sup>2,9</sup> <br/> |50 GB<sup>2</sup> <br/> |
|Caixas de correio de recurso  <br/> |50 GB<sup>3</sup> <br/> |50 GB<sup>3</sup> <br/> |50 GB<sup>3</sup> <br/> |50 GB<sup>3,9</sup> <br/> |50 GB<sup>3,9</sup> <br/> |50 GB<sup>3</sup> <br/> |
|Caixas de correio de site<sup>5</sup> <br/> |50 GB  <br/> |50 GB  <br/> |50 GB  <br/> |50 GB  <br/> |50 GB  <br/> |Não disponível  <br/> |
|Caixas de correio de pasta pública  <br/> |50 GB<sup>6</sup> <br/> |50 GB<sup>6</sup> <br/> |50 GB<sup>6</sup> <br/> |100 GB<sup>6</sup> <br/> |100 GB<sup>6</sup> <br/> |Não disponível  <br/> |
|Caixas de correio de grupo  <br/> |50 GB  <br/> |50 GB  <br/> |50 GB  <br/> |50 GB  <br/> |50 GB  <br/> |50 GB  <br/> |
   
> [!NOTE]
> <sup>1</sup> cada usuário inicialmente recebe 100 GB de armazenamento na caixa de correio de arquivo morto. Quando a expansão automática de arquivamento é ativada, armazenamento adicional é adicionado automaticamente quando a capacidade de armazenamento de 100 GB for atingida. Para obter mais informações, consulte [Overview of arquivamento ilimitado no Office 365](https://go.microsoft.com/fwlink/?linkid=844060). Consulte o [Mapa do Office 365](http://go.microsoft.com/fwlink/?LinkId=509914) para obter detalhes sobre a disponibilidade.<br/>  <sup>2</sup> para acessar uma caixa de correio compartilhada, um usuário deve ter uma licença do Exchange Online. Caixas de correio compartilhadas não exigem uma licença separada. No entanto, sem uma licença, as caixas de correio compartilhadas estão limitadas a 50 GB. Para aumentar o tamanho da caixa de correio, uma licença E3 ou E5 deve ser atribuída. Isso aumentará a caixa de correio para 100 GB. Se você deseja habilitar a caixa de correio de arquivo morto ou colocar um litígio em uma caixa de correio compartilhada, em seguida, uma licença do Exchange Online plano 2 ou um Exchange Online plano 1 com licença de arquivamento do Exchange Online é obrigatório. Se você habilitar a caixa de correio de arquivo morto e a expansão automática de arquivamento para uma caixa de correio compartilhada, armazenamento adicional é adicionado automaticamente quando a capacidade de armazenamento de 100 GB para a caixa de correio de arquivo for atingida.<br/>  <sup>3</sup> caixas de correio de recurso não exigem uma licença. No entanto, sem uma licença, as caixas de correio compartilhadas estão limitadas a 50 GB. Para aumentar o tamanho da caixa de correio, uma licença E3 ou E5 deve ser atribuída. Isso aumentará a caixa de correio para 100 GB.<br/>  <sup>4</sup> caixas de correio de arquivo morto não estão incluídas no quiosque do Exchange Online. No entanto, pode ser adquiridos como um complemento por meio de arquivamento do Exchange Online. Para obter mais informações, consulte o [Exchange Online Archiving Service Description](../exchange-online-archiving-service-description/exchange-online-archiving-service-description.md).<br/>  <sup>5</sup> caixas de correio do site são criadas e gerenciadas no SharePoint Online. Para obter mais informações, consulte [Prepare for usando caixas de correio de site no Office 365](http://go.microsoft.com/fwlink/p/?LinkId=299131).<br/>  <sup>6</sup> você está limitado a 1.000 caixas de correio de pasta pública e o tamanho máximo total de todas as caixas de correio de pasta pública é de 50 TB.<br/>  <sup>7</sup> a caixas de correio de arquivo morto só podem ser usadas para arquivar o email para um único usuário ou a entidade (por exemplo, uma caixa de correio compartilhada) para a qual uma licença tiver sido aplicada. Usando caixas de correio de arquivo morto como um meio de armazenamento de email de vários usuários ou entidades é proibido. Por exemplo, um administrador de TI não é possível criar uma caixa de correio compartilhada e tiver usuários copiá-lo (através do campo Cc ou Cco, ou por meio de uma regra de transporte) o objetivo explícitas de arquivamento. Observe que uma caixa de correio compartilhada que várias pessoas usam, na verdade, não armazene eletrônico dos usuários individuais. Vários usuários têm acesso e enviarem email da caixa de correio compartilhada. Portanto, os únicos emails armazenados na caixa de correio compartilhada são aquelas enviadas de ou para ele, *como* caixa de correio compartilhada.<br/>  <sup>8</sup> se você tiver criado uma política de retenção no Exchange Online, mensagens serão automaticamente movidas para a caixa de correio de arquivo morto de um usuário somente se a caixa de correio principal do usuário for maior do que 10 MB. A política de retenção não será executado automaticamente para caixas de correio que são menores do que 10 MB.<br/>  <sup>9</sup> compartilhados e o recurso de caixas de correio não exigem uma licença. No entanto, sem uma licença, as caixas de correio compartilhadas estão limitadas a 50 GB. Para aumentar o tamanho da caixa de correio, uma licença E3 ou E5 deve ser atribuída. Isso aumentará a caixa de correio para 100 GB. 
  
### <a name="storage-limits-across-standalone-plans"></a>Limites de armazenamento em planos autônomos

||||||
|:-----|:-----|:-----|:-----|:-----|
|**Recurso** <br/> |**Exchange Server 2013** <br/> |**Exchange Online (Plano 1)** <br/> |**Exchange Online (Plano 2)** <br/> |**Exchange Online Kiosk** <br/> |
|Caixas de correio do usuário  <br/> |2 GB<sup>1</sup> <br/> |50 GB  <br/> |100 GB  <br/> |2 GB  <br/> |
|Caixas de correio de arquivo morto<sup>8, 9</sup> <br/> |100 GB<sup>1</sup> <br/> |50 GB  <br/> |Ilimitado<sup>2</sup> <br/> |Indisponível<sup>5</sup> <br/> |
|Caixas de correio compartilhadas  <br/> |2 GB<sup>1</sup> <br/> |50 GB<sup>3</sup> <br/> |50 GB<sup>3,10</sup> <br/> |50 GB<sup>3</sup> <br/> |
|Caixas de correio de recurso  <br/> |2 GB<sup>1</sup> <br/> |50 GB<sup>4</sup> <br/> |50 GB<sup>4,10</sup> <br/> |50 GB<sup>4</sup> <br/> |
|Caixas de correio de pasta pública  <br/> |2 GB<sup>6</sup> <br/> |50 GB<sup>7</sup> <br/> |100 GB<sup>7</sup> <br/> |Não disponível  <br/> |
|Caixas de correio de grupo  <br/> |50 GB  <br/> |50 GB  <br/> |50 GB  <br/> |50 GB  <br/> |
   
> [!NOTE]
> <sup>1</sup> , este é o tamanho da caixa de correio padrão para as organizações do Exchange Server 2013. Os administradores podem alterar esse valor para sua organização. Não há um limite máximo de armazenamento para caixas de correio local.<br/>  <sup>2</sup> cada usuário inicialmente recebe 100 GB de armazenamento na caixa de correio de arquivo morto. Quando a expansão automática de arquivamento é ativada, armazenamento adicional é adicionado automaticamente quando a capacidade de armazenamento de 100 GB for atingida. Para obter mais informações, consulte [Overview of arquivamento ilimitado no Office 365](https://go.microsoft.com/fwlink/?linkid=844060). Consulte o [Mapa do Office 365](http://go.microsoft.com/fwlink/?LinkId=509914) para obter detalhes sobre a disponibilidade para expansão automática arquivamento.<br/> <sup>3</sup> para acessar uma caixa de correio compartilhada, um usuário deve ter uma licença do Exchange Online. Caixas de correio compartilhadas não exigem uma licença separada. No entanto, sem uma licença, as caixas de correio compartilhadas estão limitadas a 50 GB. Para aumentar o tamanho da caixa de correio, uma licença do Exchange Online plano 2 deve ser atribuída. Isso aumentará a caixa de correio para 100 GB. Se você deseja habilitar a caixa de correio de arquivo morto ou colocar um litígio em uma caixa de correio compartilhada, em seguida, uma licença do Exchange Online plano 2 ou um Exchange Online plano 1 com licença de arquivamento do Exchange Online é obrigatório. Se você habilitar a caixa de correio de arquivo morto e a expansão automática de arquivamento para uma caixa de correio compartilhada, armazenamento adicional é adicionado automaticamente quando a capacidade de armazenamento de 100 GB para a caixa de correio de arquivo for atingida.<br/> <sup>4</sup> caixas de correio de recurso não exigem uma licença. No entanto, sem uma licença, as caixas de correio compartilhadas estão limitadas a 50 GB. Para aumentar o tamanho da caixa de correio, uma licença do Exchange Online plano 2 deve ser atribuída. Isso aumentará a caixa de correio para 100 GB.<br/>  <sup>5</sup> caixas de correio de arquivo morto não estão incluídas no quiosque do Exchange Online. No entanto, pode ser adquiridos como um complemento por meio de arquivamento do Exchange Online. Para obter mais informações, consulte o [Exchange Online Archiving Service Description](../exchange-online-archiving-service-description/exchange-online-archiving-service-description.md).<br/>  <sup>6</sup> , este é o tamanho da caixa de correio padrão para as organizações do Microsoft Exchange Server 2013. Os administradores podem alterar esse valor para sua organização. No Exchange Server 2013, você está limitado a 100 caixas de correio de pasta pública e o tamanho máximo total de todas as caixas de correio de pasta pública é de 50 TB.<br/>  <sup>7</sup> In Exchange Online, você está limitado a 1.000 caixas de correio de pasta pública e o tamanho máximo total de todas as caixas de correio de pasta pública é de 50 TB.<br/>  <sup>8</sup> caixas de correio de arquivo morto só podem ser usadas para arquivar o email para um único usuário ou a entidade para a qual uma licença tiver sido aplicada. Usando uma caixa de correio de arquivo morto como um meio para armazenar os emails de vários usuários ou entidades é proibido. Por exemplo, os administradores de TI não é possível criar caixas de correio compartilhadas e ter usuários copiar (através do campo Cc ou Cco, ou por meio de uma regra de transporte) uma caixa de correio compartilhada o objetivo explícitas de arquivamento.<br/>  <sup>9</sup> se você tiver criado uma política de retenção no Exchange Online, mensagens serão automaticamente movidas para a caixa de correio de arquivo morto de um usuário somente se a caixa de correio principal do usuário for maior do que 10 MB. A política de retenção não será executado automaticamente para caixas de correio que são menores do que 10 MB.<br/>  <sup>10</sup> compartilhados e caixas de correio de recurso não exigem uma licença a ser atribuído. Entretanto, sem uma licença, essas caixas de correio são limitadas a 50 GB. Para aumentar o tamanho da caixa de correio, uma licença do Exchange Online plano 2 deve ser atribuída. Isso aumentará a caixa de correio para 100 GB. 
  
> [!NOTE]
> Uma caixa de correio compartilhada não foi projetada para logon direto. A conta de usuário para a caixa de correio compartilhada em si deve ficar em um **desabilitado** (ou "desconectado") estado. 
  
## <a name="capacity-alerts"></a>Alertas de capacidade

O Exchange Online oferece três tipos de notificações quando uma caixa de correio do usuário atinge ou está se aproximando de sua capacidade máxima:
  
- **Aviso** O usuário recebe um email avisando que a caixa de correio está se aproximando do limite máximo de tamanho. Esse aviso se destina a incentivar os usuários a excluir emails indesejados. 
    
- **Proibir Enviar** O usuário recebe um email de notificação de proibição de envio quando o limite de tamanho da caixa é atingido. O usuário não pode enviar novas mensagens de email até que emails suficientes sejam excluídos e a caixa de correio fique abaixo do limite de tamanho. 
    
- **Proibido Enviar/Receber** O Exchange Online rejeita os emails recebidos quando o limite de tamanho da caixa é atingido e envia uma NDR (notificação de falha na entrega) ao remetente. O remetente tem a opção de tentar reenviar o email mais tarde. Para receber mensagens novamente, o usuário deve excluir emails até que a caixa de correio fique abaixo do limite de tamanho. 
    
### <a name="capacity-alerts-across-office-365-options"></a>Alertas de capacidade em opções do Office 365

||||||||
|:-----|:-----|:-----|:-----|:-----|:-----|:-----|
|**Recurso** <br/> |**Office 365 Business Essentials** <br/> |**Office 365 Business Premium** <br/> |**Office 365 Enterprise E1** <br/> |**Office 365 Enterprise E3** <br/> |**Office 365 Enterprise E5** <br/> |**Office 365 Enterprise F1** <br/> |
|Aviso  <br/> |49 GB  <br/> |49 GB  <br/> |49 GB  <br/> |98 GB  <br/> |98 GB  <br/> |1,96 GB  <br/> |
|Proibir Envio  <br/> |49,5 GB  <br/> |49,5 GB  <br/> |49,5 GB  <br/> |99 GB  <br/> |99 GB  <br/> |1,98 GB  <br/> |
|Proibir Envio/Recebimento  <br/> |50 GB  <br/> |50 GB  <br/> |50 GB  <br/> |100 GB  <br/> |100 GB  <br/> |2 GB  <br/> |
   
### <a name="capacity-alerts-across-standalone-plans"></a>Alertas de capacidade em planos autônomos

||||||
|:-----|:-----|:-----|:-----|:-----|
|**Recurso** <br/> |**Exchange Server 2013** <br/> |**Exchange Online (Plano 1)** <br/> |**Exchange Online (Plano 2)** <br/> |**Exchange Online Kiosk** <br/> |
|Aviso  <br/> |1,9 GB<sup>1</sup> <br/> |49 GB  <br/> |98 GB  <br/> |1,96 GB  <br/> |
|Proibir Envio  <br/> |2 GB<sup>1</sup> <br/> |49,5 GB  <br/> |99 GB  <br/> |1,98 GB  <br/> |
|Proibir Envio/Recebimento  <br/> |2,3 GB<sup>1</sup> <br/> |50 GB  <br/> |100 GB  <br/> |2 GB  <br/> |
   
> [!NOTE]
> <sup>1</sup>Este é o valor padrão para organizações do Exchange Server 2013. Os administradores podem alterar esse valor para sua organização. 
  
## <a name="mailbox-folder-limits"></a>Limites da pasta da caixa de correio

Estes limites são para limitar as caixas de correios para tamanhos conhecidos que podem ser suportados pelo Exchange Online. O objetivo desses limites é impedir uma quantidade infinita de itens de caixa de correio por pasta, de pastas por caixa de correio ou de pastas públicas por organização do Exchange Online. Por razões práticas, os limites da pasta da caixa de correio são ilimitadas e o suficiente para suportar a maioria das caixas de correio do Exchange Online e caixas de correio locais que são migradas para o Exchange Online.
  
- **Número máximo de mensagens por pasta da caixa de correio** Especifica o número máximo de mensagens para uma pasta da caixa de correio. Novas mensagens não podem ser entregues ou salvas em uma pasta quando este limite é alcançado. 
    
- **Aviso para número de mensagens por pasta da caixa de correio** Especifica o número de mensagens que uma pasta da caixa de correio pode armazenar antes do Exchange Online enviar uma mensagem de aviso para o proprietário da caixa de correio. Quando esta cota é alcançada, as mensagens de aviso são enviadas diariamente. 
    
- **Número máximo de mensagens por pasta na pasta de Itens Recuperáveis** Especifica o número de mensagens que pode ser armazenado em cada pasta na pasta de Itens Recuperáveis. Quando uma pasta excede este limite, ela não pode mais armazenar novas mensagens. Por exemplo, se a pasta Excluídos na pasta de Itens Recuperáveis tiver excedido o limite de mensagens e o proprietário da caixa de correio tentar excluir permanentemente itens da mesma, a exclusão irá falhar. 
    
- **Aviso para o número de mensagens por pasta na pasta de Itens Recuperáveis** Especifica o número de mensagens que cada pasta na pasta de Itens Recuperáveis pode armazenar antes do Exchange Online registrar um evento no registro de eventos do aplicativo. 
    
- **Número máximo de subpastas por pasta da caixa de correio** Especifica o número máximo de subpastas que podem ser criadas na pasta da caixa de correio. O proprietário da caixa de correio não conseguirá criar uma nova subpasta quando este limite for atingido. 
    
- **Aviso para o número de subpastas por pasta da caixa de correio** Especifica o número de subpastas que podem ser criadas em uma pasta da caixa de correio antes do Exchange Online enviar uma mensagem de aviso para o proprietário da caixa de correio. Quando esta cota é alcançada, as mensagens de aviso são enviadas diariamente. 
    
- **Nível máximo de hierarquia da pasta** Especifica o número máximo de níveis na hierarquia da pasta de uma caixa de correio. O proprietário da caixa de correio não conseguirá criar outro nível na hierarquia da pasta da caixa de correio quando este limite for atingido. 
    
- **Aviso para o nível de hierarquia da pasta** Especifica o número de níveis na hierarquia da pasta de uma pasta da caixa de correio que pode ser criado antes do Exchange Online enviar uma mensagem de aviso para o proprietário da caixa de correio. Quando esta cota é alcançada, mensagens de aviso são enviadas diariamente. 
    
- **Número máximo de pastas públicas** Especifica o número máximo de pastas públicas na hierarquia completa de pastas públicas. Quando este limite é atingido, as pastas públicas existentes devem ser excluídas antes de novas pastas poderem ser criadas. 
    
- **Número máximo de subpastas por pasta pública** Especifica o número máximo de subpastas que podem ser criadas em uma pasta pública. Novas subpastas não poderão ser criadas em uma pasta pública quando este limite for atingido. 
    
- **Aviso para o número de subpastas por pasta pública** Especifica o número de subpastas que podem ser criadas em uma pasta pública antes de o Exchange Online enviar uma mensagem de aviso para o proprietário da pasta. Se não existir nenhum proprietário, as mensagens de aviso serão enviadas para usuários com permissões de Proprietário. Quando esta cota é alcançada, as mensagens de aviso são enviadas diariamente. 
    
### <a name="mailbox-folder-limits-across-office-365-options"></a>Limites da pasta da caixa de correio nas opções do Office 365

||||||||
|:-----|:-----|:-----|:-----|:-----|:-----|:-----|
|**Recurso** <br/> |**Office 365 Business Essentials** <br/> |**Office 365 Business Premium** <br/> |**Office 365 Enterprise E1** <br/> |**Office 365 Enterprise E3** <br/> |**Office 365 Enterprise E5** <br/> |**Office 365 Enterprise F1** <br/> |
|Número máximo de mensagens por pasta de caixa de correio  <br/> |1 milhão  <br/> |1 milhão  <br/> |1 milhão  <br/> |1 milhão  <br/> |1 milhão  <br/> |1 milhão  <br/> |
|Aviso para o número de mensagens por pasta da caixa de correio  <br/> |900.000  <br/> |900.000  <br/> |900.000  <br/> |900.000  <br/> |900.000  <br/> |900.000  <br/> |
|Número máximo de mensagens por pasta na pasta de Itens Recuperáveis  <br/> |3 milhões  <br/> |3 milhões  <br/> |3 milhões  <br/> |3 milhões  <br/> |3 milhões  <br/> |3 milhões  <br/> |
|Cota de armazenamento da pasta Itens Recuperáveis na caixa de correio primária (não em espera)  <br/> |30 GB  <br/> |30 GB  <br/> |30 GB  <br/> |30 GB  <br/> |30 GB  <br/> |30 GB  <br/> |
|Cota de armazenamento da pasta Itens Recuperáveis na caixa de correio primária (em espera)  <br/> |100 GB  <br/> |100 GB  <br/> |100 GB  <br/> |100 GB  <br/> |100 GB  <br/> |100 GB  <br/> |
|Cota de armazenamento da pasta Itens Recuperáveis na caixa de correio de arquivo morto (não em espera)  <br/> |30 GB  <br/> |30 GB  <br/> |30 GB  <br/> |Ilimitado<sup>2</sup> <br/> |Ilimitado<sup>2</sup> <br/> |30 GB  <br/> |
|Cota de armazenamento da pasta Itens Recuperáveis na caixa de correio de arquivo morto (em espera)  <br/> |100 GB<sup>1</sup> <br/> |100 GB<sup>1</sup> <br/> |100 GB<sup>1</sup> <br/> |Ilimitado<sup>2</sup> <br/> |Ilimitado<sup>2</sup> <br/> |100 GB<sup>1</sup> <br/> |
|Aviso para o número de mensagens por pasta na pasta de Itens Recuperáveis  <br/> |2,75 milhões  <br/> |2,75 milhões  <br/> |2,75 milhões  <br/> |2,75 milhões  <br/> |2,75 milhões  <br/> |2,75 milhões  <br/> |
|Número máximo de subpastas por pasta de caixa de correio  <br/> |10.000  <br/> |10.000  <br/> |10.000  <br/> |10.000  <br/> |10.000  <br/> |10.000  <br/> |
|Aviso para o número de subpastas por pasta de caixa de correio  <br/> |9000  <br/> |9000  <br/> |9000  <br/> |9000  <br/> |9000  <br/> |9000  <br/> |
|Profundidade máxima de hierarquia de pasta  <br/> |300  <br/> |300  <br/> |300  <br/> |300  <br/> |300  <br/> |300  <br/> |
|Aviso para a profundidade de hierarquia de pasta  <br/> |250  <br/> |250  <br/> |250  <br/> |250  <br/> |250  <br/> |250  <br/> |
|Número máximo de pastas públicas  <br/> | 500.000  <br/> | 500.000  <br/> | 500.000  <br/> | 500.000  <br/> | 500.000  <br/> |Não disponível  <br/> |
|Número máximo de subpastas por pasta pública  <br/> |10.000  <br/> |10.000  <br/> |10.000  <br/> |10.000  <br/> |10.000  <br/> |Não disponível  <br/> |
|Aviso para o número de subpastas por pasta pública  <br/> |9000  <br/> |9000  <br/> |9000  <br/> |9000  <br/> |9000  <br/> |Não disponível  <br/> |
   
> [!NOTE]
> <sup>1</sup> esta é a cota de armazenamento para a pasta itens recuperáveis, não a cota de caixa de correio de arquivo morto inteiro. A cota de armazenamento para a caixa de correio de arquivo morto é ilimitada para usuários com uma licença do Exchange Online plano 2 ou para usuários que têm um Exchange Online plano 1 e uma licença de arquivamento do Exchange Online. Para obter informações sobre como aumentar a cota de itens recuperáveis, consulte [aumentar a cota de caixas de correio em retenção de itens recuperáveis](http://technet.microsoft.com/library/a8bdcbdd-9298-462f-b889-df26037a990c.aspx).<br/> <sup>2</sup> a cota de armazenamento inicial para a pasta itens recuperáveis em uma caixa de correio de arquivo morto é de 100 GB. Quando a expansão automática de arquivamento é ativada, armazenamento adicional é adicionado automaticamente quando a capacidade de armazenamento para a pasta itens recuperáveis for atingida. Para obter mais informações, consulte [Overview of arquivamento ilimitado no Office 365](https://go.microsoft.com/fwlink/?linkid=844060). Consulte o [Mapa do Office 365](http://go.microsoft.com/fwlink/?LinkId=509914) para obter detalhes sobre a disponibilidade de expansão automática arquivamento. 
  
### <a name="mailbox-folder-limits-across-standalone-plans"></a>Limites da pasta da caixa de correio nos planos autônomos

||||||
|:-----|:-----|:-----|:-----|:-----|
|**Recurso** <br/> |**Exchange Server 2013** <br/> |**Exchange Online (Plano 1)** <br/> |**Exchange Online (Plano 2)** <br/> |**Exchange Online Kiosk** <br/> |
|Número máximo de mensagens por pasta de caixa de correio  <br/> |Sem limites<sup>1</sup> <br/> |1 milhão  <br/> |1 milhão  <br/> |1 milhão  <br/> |
|Aviso para o número de mensagens por pasta da caixa de correio  <br/> |Sem limites  <br/> |900.000  <br/> |900.000  <br/> |900.000  <br/> |
|Número máximo de mensagens por pasta na pasta de Itens Recuperáveis  <br/> |Sem limites  <br/> |3 milhões  <br/> |3 milhões  <br/> |3 milhões  <br/> |
|Cota de armazenamento da pasta Itens Recuperáveis na caixa de correio primária (não em espera)  <br/> |30 GB  <br/> |30 GB  <br/> |30 GB  <br/> |30 GB  <br/> |
|Cota de armazenamento da pasta Itens Recuperáveis na caixa de correio primária (em espera)  <br/> |100 GB  <br/> |100 GB  <br/> |100 GB  <br/> |100 GB  <br/> |
|Cota de armazenamento da pasta Itens Recuperáveis na caixa de correio de arquivo morto (não em espera)  <br/> |30 GB  <br/> |30 GB  <br/> |30 GB  <br/> |30 GB  <br/> |
|Cota de armazenamento da pasta Itens Recuperáveis na caixa de correio de arquivo morto (em espera)  <br/> |100 GB<sup>2</sup> <br/> |100 GB<sup>2</sup> <br/> |Ilimitado<sup>3</sup> <br/> |Ilimitado<sup>3</sup> <br/> |
|Aviso para o número de mensagens por pasta na pasta de Itens Recuperáveis  <br/> |Sem limites  <br/> |2,75 milhões  <br/> |2,75 milhões  <br/> |2,75 milhões  <br/> |
|Número máximo de subpastas por pasta de caixa de correio  <br/> |Sem limites  <br/> |1000  <br/> |1000  <br/> |1000  <br/> |
|Aviso para o número de subpastas por pasta de caixa de correio  <br/> |Sem limites  <br/> |900  <br/> |900  <br/> |900  <br/> |
|Profundidade máxima de hierarquia de pasta  <br/> |Sem limites  <br/> |300  <br/> |300  <br/> |300  <br/> |
|Aviso para a profundidade de hierarquia de pasta  <br/> |Sem limites  <br/> |250  <br/> |250  <br/> |250  <br/> |
|Número máximo de pastas públicas  <br/> |1.000.000  <br/> |100.000  <br/> |100.000  <br/> |Não disponível  <br/> |
|Número máximo de subpastas por pasta pública  <br/> |N/D  <br/> |1.000  <br/> |1.000  <br/> |Não disponível  <br/> |
|Aviso para o número de subpastas por pasta pública  <br/> |N/D  <br/> |900  <br/> |900  <br/> |Não disponível  <br/> |
   
> [!NOTE]
> <sup>1</sup> a Microsoft recomenda não ultrapassa 1.000.000 mensagens por pasta da caixa de correio. ><br/> <sup>2</sup> esta é a cota de armazenamento para a pasta itens recuperáveis, não a cota de caixa de correio de arquivo morto inteiro. A cota de armazenamento para a caixa de correio de arquivo morto é ilimitada para usuários com uma licença do Exchange Online plano 2 ou para usuários que têm um Exchange Online plano 1 e uma licença de arquivamento do Exchange Online. Para obter informações sobre como aumentar a cota de itens recuperáveis, consulte [aumentar a cota de caixas de correio em retenção de itens recuperáveis](http://technet.microsoft.com/library/a8bdcbdd-9298-462f-b889-df26037a990c.aspx).<br/> <sup>3</sup> a cota de armazenamento inicial para a pasta itens recuperáveis em uma caixa de correio de arquivo morto é de 100 GB. Quando a expansão automática de arquivamento é ativada, armazenamento adicional é adicionado automaticamente quando a capacidade de armazenamento para a pasta itens recuperáveis for atingida. Para obter mais informações, consulte [Overview of arquivamento ilimitado no Office 365](https://go.microsoft.com/fwlink/?linkid=844060). Consulte o [Mapa do Office 365](http://go.microsoft.com/fwlink/?LinkId=509914) para obter detalhes sobre a disponibilidade de expansão automática arquivamento. 
  
## <a name="message-limits"></a>Limites de mensagem

Os limites a seguir são aplicados a todas as mensagens de email.
  
- **Limite de tamanho de mensagem** Os limites de tamanho de mensagem são necessários para impedir que mensagens grandes bloqueiem a entrega de outras mensagens e afetem o desempenho do serviço para todos os usuários. Esses limites incluem anexos e são aplicáveis em toda a organização a todas as mensagens (de entrada, de saída e internas). Mensagens maiores do que esse limite não serão entregues, e o remetente receberá uma NDR (notificação de falha na entrega). Embora os limites de tamanho de mensagem não possam ser configurados como maiores, menores ou para usuários individuais, os administradores também podem criar regras de transporte para limitar o tamanho máximo de qualquer anexo individual. Para saber mais, consulte [O Office 365 agora dá suporte a mensagens de email maiores](https://blogs.office.com/2015/04/15/office-365-now-supports-larger-email-messages-up-to-150-mb/).
    
    > [!NOTE]
    > Clientes de email específicos podem ter limites de tamanho de mensagem menores ou podem limitar o tamanho de um anexo de arquivo individual para um valor que seja menor do que o limite de tamanho de mensagens do Exchange Online. 
  
- **Limite de tamanho do assunto** O número máximo de caracteres de texto permitido na linha de assunto de uma mensagem de email. 
    
- **Limite de anexos de arquivo** O número máximo permitido de anexos de arquivo em uma mensagem de email. Mesmo se o tamanho total de todos os anexos de arquivo não violar o limite de tamanho da mensagem, ainda haverá um limite na quantidade de anexos permitida na mensagem. Este limite é controlado pelo limite da mensagem em várias partes. 
    
- **Limite de tamanho de anexo de arquivo** O tamanho máximo de um único anexo. 
    
    > [!NOTE]
    > Esse é o tamanho máximo de um único anexo. Programas cliente individuais, inclusive o Outlook Web App, poderão limitar o tamanho dos anexos abaixo desse valor máximo. O Exchange ActiveSync não implementa limites de tamanho de anexos para anexos individuais. O tamanho total de todos os anexos para uma mensagem do Exchange ActiveSync deve ser menor do que o limite de tamanho de mensagem. 
  
- **Limite de mensagem com várias partes** O número máximo de partes do corpo da mensagem que são permitidas em uma mensagem MIME com várias partes. Esse limite também controla a quantidade máxima de anexos permitidos em uma mensagem. 
    
- **Limite de profundidade de mensagens inseridas** O número máximo de mensagens de email encaminhadas que são permitidas em uma mensagem de email. 
    
### <a name="message-limits-across-office-365-options"></a>Limites de mensagem em opções do Office 365

||||||||
|:-----|:-----|:-----|:-----|:-----|:-----|:-----|
|**Recurso** <br/> |**Office 365 Business Essentials** <br/> |**Office 365 Business Premium** <br/> |**Office 365 Enterprise E1** <br/> |**Office 365 Enterprise E3** <br/> |**Office 365 Enterprise E5** <br/> |**Office 365 Enterprise F1** <br/> |
|Limite de tamanho de mensagem - Outlook  <br/> |150 MB<sup>1, 2</sup> <br/> |150 MB<sup>1, 2</sup> <br/> |150 MB<sup>1, 2</sup> <br/> |150 MB<sup>1, 2</sup> <br/> |150 MB<sup>1, 2</sup> <br/> |150 MB<sup>1, 2</sup> <br/> |
|Limite de tamanho de mensagem - OWA  <br/> |112 MB<sup>1, 3</sup> <br/> |112 MB<sup>1, 3</sup> <br/> |112 MB<sup>1, 3</sup> <br/> |112 MB<sup>1, 3</sup> <br/> |112 MB<sup>1, 3</sup> <br/> |112 MB<sup>1, 3</sup> <br/> |
|Limite de tamanho de mensagem - Outlook para Mac  <br/> |150 MB<sup>1, 2</sup> <br/> |150 MB<sup>1, 2</sup> <br/> |150 MB<sup>1, 2</sup> <br/> |150 MB<sup>1, 2</sup> <br/> |150 MB<sup>1, 2</sup> <br/> |150 MB<sup>1, 2</sup> <br/> |
|Limite de tamanho de mensagem - migração  <br/> |150 MB <sup>4</sup> <br/> |150 MB <sup>4</sup> <br/> |150 MB <sup>4</sup> <br/> |150 MB <sup>4</sup> <br/> |150 MB <sup>4</sup> <br/> |150 MB <sup>4</sup> <br/> |
|Limite de tamanho para mensagens criptografadas (para assinantes usando a Criptografia de Mensagem do Office 365 com novas capacidades)<sup>5</sup> <br/> |150 MB  <br/> |150 MB  <br/> |150 MB  <br/> |150 MB  <br/> |150 MB  <br/> |150 MB  <br/> |
|Limite de tamanho para mensagens criptografadas (para assinantes usando a versão herdada da Criptografia de Mensagem do Office 365)<sup>5</sup> <br/> |25 MB  <br/> |25 MB  <br/> |25 MB  <br/> |25 MB  <br/> |25 MB  <br/> |25 MB  <br/> |
|Limite de comprimento de assunto  <br/> |255 caracteres  <br/> |255 caracteres  <br/> |255 caracteres  <br/> |255 caracteres  <br/> |255 caracteres  <br/> |255 caracteres  <br/> |
|Limite de anexos de arquivo  <br/> |250 anexos  <br/> |250 anexos  <br/> |250 anexos  <br/> |250 anexos  <br/> |250 anexos  <br/> |250 anexos  <br/> |
|Limite de tamanho de anexo de arquivo - Outlook  <br/> |150 MB  <br/> |150 MB  <br/> |150 MB  <br/> |150 MB  <br/> |150 MB  <br/> |150 MB  <br/> |
|Limite de tamanho de anexo de arquivo - OWA <sup>6</sup> <br/> |35 MB  <br/> |35 MB  <br/> |35 MB  <br/> |35 MB  <br/> |35 MB  <br/> |35 MB  <br/> |
|Limite de tamanho de anexo de arquivo - Outlook para Mac  <br/> |150 MB  <br/> |150 MB  <br/> |150 MB  <br/> |150 MB  <br/> |150 MB  <br/> |150 MB  <br/> |
|Limite de mensagem com várias partes  <br/> |250 partes  <br/> |250 partes  <br/> |250 partes  <br/> |250 partes  <br/> |250 partes  <br/> |250 partes  <br/> |
|Limite de profundidade de mensagem inserida  <br/> |30 mensagens inseridas  <br/> |30 mensagens inseridas  <br/> |30 mensagens inseridas  <br/> |30 mensagens inseridas  <br/> |30 mensagens inseridas  <br/> |30 mensagens inseridas  <br/> |
   
> [!NOTE]
> <sup>1</sup> o tamanho máximo da mensagem padrão para caixas de correio do Office 365 é 25 MB. Administradores do Office 365 podem especificar um limite personalizado entre 1 MB e 150 MB. No entanto, o tamanho da mensagem, você pode enviar ou receber também depende o que suporta seu cliente de email ou a solução. Para obter mais informações sobre como personalizar o tamanho máximo permitido de mensagem para sua organização, consulte [Office 365 agora oferece suporte a mensagens de email maiores](https://blogs.office.com/2015/04/15/office-365-now-supports-larger-email-messages-up-to-150-mb/).<br/> <sup>2</sup> você pode enviar e receber backup para mensagens de 150 MB entre usuários do Office 365 (em que a mensagem nunca deixa os datacenters do Office 365). Mensagens que são roteadas fora os datacenters do Office 365 estão sujeitos a uma codificação aumento, caso o tamanho máximo da mensagem em que será 112 MB adicionais para tradução 33%.<br/> <sup>3</sup> OWA contas para a possibilidade de que sua mensagem pode estar sujeitos a 33% de aumento de codificação e restringe o tamanho da mensagem que é possível enviar para 25% menor que a configuração configurada. Por exemplo, se você personalizar as configurações para um tamanho de mensagem máximo de 100 MB, você pode enviar mensagens não pode exceder 75 MB.<br/> <sup>4</sup> O tamanho das mensagens a serem movidas para o Exchange Online será calculado pelo Exchange Online. Versões do Exchange anteriores ao Exchange Server 2013 podem relatar um tamanho menor de item. Esse limite se aplica para mover as migrações com base usando qualquer Serviço de Replicação de Caixa de Correio do Exchange. Outros métodos de migração (Substituição, Em Estágios, IMAP, PST) e outras ferramentas de terceiros são limitadas pelo limite geral de tamanho de mensagem.<br/> <sup>5</sup> para obter informações sobre OME com os novos recursos, consulte [configurar novos recursos do Office 365 Message Encryption construídos sobre a proteção de informações do Windows Azure](https://support.office.com/en-us/article/Set-up-new-Office-365-Message-Encryption-capabilities-built-on-top-of-Azure-Information-Protection-7ff0c040-b25c-4378-9904-b1b50210d00e?ui=en-US&amp;rs=en-US&amp;ad=US).<br/> <sup>6</sup> Não é possível anexar um arquivo com mais de 35 MB. Também não é possível anexar arquivos que juntos ultrapassam 35 MB. Por exemplo, se você anexar um arquivo de 34 MB, só poderá anexar outro de 1 MB. 
  
### <a name="message-limits-across-standalone-options"></a>Limites de mensagem em opções autônomas

||||||
|:-----|:-----|:-----|:-----|:-----|
|**Recurso** <br/> |**Exchange Server 2013** <br/> |**Exchange Online (Plano 1)** <br/> |**Exchange Online (Plano 2)** <br/> |**Exchange Online Kiosk** <br/> |
|Limite de tamanho de mensagem - Outlook  <br/> |10 MB<sup>4</sup> <br/> |150 MB<sup>1, 2</sup> <br/> |150 MB<sup>1, 2</sup> <br/> |150 MB<sup>2</sup> <br/> |
|Limite de tamanho de mensagem - OWA  <br/> |10 MB<sup>4</sup> <br/> |112 MB<sup>1, 3</sup> <br/> |112 MB<sup>1, 3</sup> <br/> |150 MB<sup>1, 2</sup> <br/> |
|Limite de tamanho de mensagem - Outlook para Mac  <br/> |10 MB<sup>4</sup> <br/> |150 MB  <br/> |150 MB  <br/> ||
|Limite de tamanho de mensagem - migração  <br/> |Não aplicável  <br/> |150 MB <sup>5</sup> <br/> |150 MB <sup>5</sup> <br/> |150 MB <sup>5</sup> <br/> |
|Limite de tamanho para mensagens criptografadas (para assinantes usando a Criptografia de Mensagem do Office 365 com novas capacidades)<sup>6</sup> <br/> |150 MB  <br/> |150 MB  <br/> |150 MB  <br/> |150 MB  <br/> |
|Limite de tamanho para mensagens criptografadas (para assinantes usando a versão herdada da Criptografia de Mensagem do Office 365)<sup>6</sup> <br/> |25 MB  <br/> |25 MB  <br/> |25 MB  <br/> |25 MB  <br/> |
|Limite de comprimento de assunto  <br/> |255 caracteres  <br/> |255 caracteres  <br/> |255 caracteres  <br/> |255 caracteres  <br/> |
|Limite de anexos de arquivo  <br/> |anexos de 1024<sup>4</sup> <br/> |250 anexos  <br/> |250 anexos  <br/> |250 anexos  <br/> |
|Limite de tamanho de anexo de arquivo - Outlook  <br/> |35 MB<sup>4</sup> <br/> |150 MB  <br/> |150 MB  <br/> |150 MB  <br/> |
|Limite de tamanho de anexo de arquivo - OWA  <br/> |35 MB<sup>4</sup> <br/> |35 MB  <br/> |35 MB  <br/> |35 MB  <br/> |
|Limite de tamanho de anexo de arquivo - Outlook para Mac  <br/> |35 MB<sup>4</sup> <br/> |150 MB  <br/> |150 MB  <br/> |35 MB  <br/> |
|Limite de mensagem com várias partes  <br/> |250 partes  <br/> |250 partes  <br/> |250 partes  <br/> |250 partes  <br/> |
|Limite de profundidade de mensagem inserida  <br/> |30 mensagens inseridas  <br/> |30 mensagens inseridas  <br/> |30 mensagens inseridas  <br/> |30 mensagens inseridas  <br/> |
   
> [!NOTE]
> <sup>1</sup> administradores do office 365 pode especificar um limite personalizado entre 1 MB e 150 MB. No entanto, o tamanho da mensagem, você pode enviar ou receber também depende o que suporta seu cliente de email ou a solução. Para obter mais informações sobre como personalizar o tamanho máximo permitido de mensagem para sua organização, consulte [Office 365 agora oferece suporte a mensagens de email maiores](https://blogs.office.com/2015/04/15/office-365-now-supports-larger-email-messages-up-to-150-mb/).<br/> <sup>2</sup> você pode enviar e receber backup para mensagens de 150 MB entre usuários do Office 365 (em que a mensagem nunca deixa os datacenters do Office 365). Mensagens que são roteadas fora os datacenters do Office 365 estão sujeitos a uma codificação aumento, caso o tamanho máximo da mensagem em que será 112 MB adicionais para tradução 33%.<br/> <sup>3</sup> OWA contas para a possibilidade de que sua mensagem pode estar sujeitos a 33% de aumento de codificação e restringe o tamanho da mensagem que é possível enviar para 25% menor que a configuração configurada. Por exemplo, se você personalizar as configurações para um tamanho de mensagem máximo de 100 MB, você pode enviar mensagens não pode exceder 75 MB.<br/> <sup>4</sup> , este é o limite padrão para as organizações do Exchange Server 2013. Os administradores podem alterar esse valor para sua organização.<br/> <sup>5</sup> o tamanho das mensagens a serem movidos para o Exchange Online são computado pelo Exchange Online. Versões do Exchange anteriores ao Exchange Server 2013 podem informar um menor tamanho do item.<br/> <sup>6</sup> para obter informações sobre OME com os novos recursos, consulte [configurar novos recursos do Office 365 Message Encryption construídos sobre a proteção de informações do Windows Azure](https://support.office.com/en-us/article/Set-up-new-Office-365-Message-Encryption-capabilities-built-on-top-of-Azure-Information-Protection-7ff0c040-b25c-4378-9904-b1b50210d00e?ui=en-US&amp;rs=en-US&amp;ad=US). 
  
## <a name="receiving-and-sending-limits"></a>Receber e enviar limites

Os limites de recebimento e envio são aplicados para combater spam e worms em emails em massa ou vírus. Esses limites ajudam a proteger a integridade dos seus sistemas e a manter seus usuários seguros.
  
### <a name="receiving-limits"></a>Limites de recebimento

Os limites de recebimento se aplicam ao número de mensagens que um usuário, grupo ou pasta pública pode receber por hora. Isso se aplica a mensagens recebidas da Internet e de servidores no local. Se exceder o limite de recebimento, os emails enviados para essa caixa de correio receberão uma notificação de falha na entrega informando que a caixa de correio excedeu o limite máximo de entrega. Após uma hora, o limite será atualizado, e a caixa de correio poderá receber mensagens novamente.
  
||||||||
|:-----|:-----|:-----|:-----|:-----|:-----|:-----|
|**Recurso** <br/> |**Office 365 Business Essentials** <br/> |**Office 365 Business Premium Office** <br/> |**Office 365 Enterprise E1** <br/> |**Office 365 Enterprise E3** <br/> |**Office 365 Enterprise E5** <br/> |**Office 365 Enterprise F1** <br/> |
|Mensagens recebidas  <br/> |3.600 mensagens por hora  <br/> |3.600 mensagens por hora  <br/> |3.600 mensagens por hora  <br/> |3.600 mensagens por hora  <br/> |3.600 mensagens por hora  <br/> |3.600 mensagens por hora  <br/> |
   
### <a name="sending-limits"></a>Limites de envio

Os limites de envio se aplicam ao número de destinatários, número de mensagens e número de destinatários por mensagem que um usuário pode enviar da própria conta do Exchange Online.
  
> [!NOTE]
> Para grupos de distribuição armazenados no catálogo de endereços de uma organização, o grupo é contado como um destinatário. Para grupos de distribuição armazenados na pasta Contatos de uma caixa de correio, os membros do grupo são contados individualmente. 
  
- **Limite de taxa de destinatários** Para desestimular o envio de mensagens não solicitadas em massa, o Exchange Online tem limites de destinatários que impedem que usuários e aplicativos enviem grandes volumes de email. Esses limites são aplicados por usuário para todas as mensagens de saída e internas. 
    
    > [!NOTE]
    > Os clientes do Exchange Online que precisam enviar emails comerciais em massa legítimos (por exemplo, boletins informativos para clientes) devem usar provedores de terceiros especializados nesses serviços. 
  
- **Limite de destinatários** Este é o número máximo de destinatários permitidos nos campos Para:, Cc: e Cco: para uma única mensagem de email. 
    
    > [!NOTE]
    > Para o limite de taxa de destinatários e o limite de destinatários, um grupo de distribuição que está armazenado no catálogo de endereços compartilhado da organização conta como um destinatário. Em uma lista de distribuição pessoal, cada destinatário é contado separadamente. 
  
- **Limite de taxa de mensagens** Os limites de taxa de mensagens determinam quantas mensagens um usuário pode enviar da própria conta do Exchange Online em um período de tempo específico. Este limite ajuda a impedir o consumo excessivo de recursos do sistema por um único remetente. Se um usuário envia mensagens a uma taxa que excede o limite por meio de envio de cliente SMTP, as mensagens são rejeitadas e o cliente precisa repetir. 
    
#### <a name="sending-limits-across-office-365-options"></a>Limites de envio nas opções do Office 365

||||||||
|:-----|:-----|:-----|:-----|:-----|:-----|:-----|
|**Recurso** <br/> |**Office 365 Business Essentials** <br/> |**Office 365 Business Premium** <br/> |**Office 365 Enterprise E1** <br/> |**Office 365 Enterprise E3** <br/> |**Office 365 Enterprise E5** <br/> |**Office 365 Enterprise F1** <br/> |
|Limite de taxa de destinatários  <br/> |10.000 destinatários por dia  <br/> |10.000 destinatários por dia  <br/> |10.000 destinatários por dia  <br/> |10.000 destinatários por dia  <br/> |10.000 destinatários por dia  <br/> |10.000 destinatários por dia  <br/> |
|Limite de destinatários  <br/> |500 destinatários  <br/> |500 destinatários  <br/> |500 destinatários  <br/> |500 destinatários  <br/> |500 destinatários  <br/> |500 destinatários  <br/> |
|Limite de endereço proxy do destinatário  <br/> |400  <br/> |400  <br/> |400  <br/> |400  <br/> |400  <br/> |400  <br/> |
|Limite de taxa de mensagem (somente para envio de cliente SMTP)  <br/> |30 mensagens por minuto  <br/> |30 mensagens por minuto  <br/> |30 mensagens por minuto  <br/> |30 mensagens por minuto  <br/> |30 mensagens por minuto  <br/> |30 mensagens por minuto  <br/> |
   
#### <a name="sending-limits-across-standalone-options"></a>Limites de envio nas opções autônomas

||||||
|:-----|:-----|:-----|:-----|:-----|
|**Recurso** <br/> |**Exchange Server 2013** <br/> |**Exchange Online (Plano 1)** <br/> |**Exchange Online (Plano 2)** <br/> |**Exchange Online Kiosk** <br/> |
|Limite de taxa de destinatários  <br/> |Sem limites<sup>1</sup> <br/> |10.000 destinatários por dia  <br/> |10.000 destinatários por dia  <br/> |10.000 destinatários por dia  <br/> |
|Limite de destinatários  <br/> |500 destinatários<sup>1</sup> <br/> |500 destinatários  <br/> |500 destinatários  <br/> |500 destinatários  <br/> |
|Limite de endereço proxy do destinatário  <br/> |400  <br/> |400  <br/> |400  <br/> |400  <br/> |
   
> [!NOTE]
> <sup>1</sup> Este é o limite padrão para organizações do Exchange Server 2013. Os administradores podem alterar esse valor para sua organização. 
  
## <a name="reporting-and-message-trace-limits"></a>Limites de rastreamento de mensagens e relatórios
<a name="bkmk_Reporting_Message_Trace_Limits"> </a>

Para saber quais são os limites de rastreamento de mensagens e relatórios, consulte a seção "Latência e disponibilidade de dados de rastreamento de mensagens e criação de relatórios" em [Geração de Relatórios e Rastreamento de Mensagens no Exchange Online Protection](http://go.microsoft.com/fwlink/p/?LinkId=394248).
  
## <a name="retention-limits"></a>Limites de retenção
<a name="RetentionLimits"> </a>

Esses limites controlam o tempo pelo qual itens em pastas específicas na caixa de entrada podem ser acessados.
  
- **Período de retenção da pasta Itens Excluídos** O número máximo de dias que os itens podem permanecer na pasta Itens Excluídos antes de serem removidos automaticamente. 
    
- **Período de retenção para itens removidos da pasta Itens Excluídos** O número máximo de dias que os itens removidos da pasta Itens Excluídos podem ser mantidos antes de serem excluídos permanentemente. 
    
- **Período de retenção da pasta Lixo Eletrônico** O número máximo de dias que os itens podem permanecer na pasta Lixo Eletrônico antes de serem removidos automaticamente. 
    
### <a name="retention-limits-across-office-365-options"></a>Limites de retenção em opções do Office 365

||||||||
|:-----|:-----|:-----|:-----|:-----|:-----|:-----|
|**Recurso** <br/> |**Office 365 Business Essentials** <br/> |**Office 365 Business Premium** <br/> |**Office 365 Enterprise E1** <br/> |**Office 365 Enterprise E3** <br/> |**Office 365 Enterprise E5** <br/> |**Office 365 Enterprise F1** <br/> |
|Período de retenção na pasta Itens Excluídos  <br/> |Sem limites<sup>1</sup> <br/> |Sem limites<sup>1</sup> <br/> |Sem limites<sup>1</sup> <br/> |Sem limites<sup>1</sup> <br/> |Sem limites<sup>1</sup> <br/> |Sem limites<sup>1</sup> <br/> |
|Período de retenção para itens removidos da pasta Itens Excluídos  <br/> |14 dias<sup>1</sup> <br/> |14 dias<sup>1</sup> <br/> |14 dias<sup>1</sup> <br/> |14 dias<sup>1</sup> <br/> |14 dias<sup>1</sup> <br/> |14 dias<sup>1</sup> <br/> |
|Período de retenção na pasta Lixo Eletrônico  <br/> |30 dias  <br/> |30 dias  <br/> |30 dias  <br/> |30 dias  <br/> |30 dias  <br/> |30 dias  <br/> |
   
> [!NOTE]
> <sup>1</sup> Este é o limite padrão. Os Administradores podem alterar esse valor para suas organizações. 
  
### <a name="retention-limits-across-standalone-options"></a>Limites de retenção em opções autônomas

||||||
|:-----|:-----|:-----|:-----|:-----|
|**Recurso** <br/> |**Exchange Server 2013** <br/> |**Exchange Online (Plano 1)** <br/> |**Exchange Online (Plano 2)** <br/> |**Exchange Online Kiosk** <br/> |
|Período de retenção na pasta Itens Excluídos  <br/> |Sem limites<sup>1</sup> <br/> |Sem limites<sup>1</sup> <br/> |Sem limites<sup>1</sup> <br/> |Sem limites<sup>1</sup> <br/> |
|Período de retenção para itens removidos da pasta Itens Excluídos  <br/> |14 dias<sup>1</sup> <br/> |14 dias<sup>2</sup> <br/> |14 dias<sup>2</sup> <br/> |14 dias<sup>2</sup> <br/> |
|Período de retenção na pasta Lixo Eletrônico  <br/> |2 anos<sup>1</sup> <br/> |30 dias  <br/> |30 dias  <br/> |30 dias  <br/> |
   
> [!NOTE]
> <sup>1</sup> Este é o limite padrão. Os Administradores podem alterar esse valor para suas organizações.<br/> <sup>2</sup> , este é o valor padrão para as organizações do Exchange Online. Os administradores podem alterar esse valor para um máximo de 30 dias para caixas de correio em sua organização. 
  
## <a name="distribution-group-limits"></a>Limites de grupos de distribuição

Estes limites se aplicam a grupos de distribuição no catálogo de endereços compartilhado de sua organização.
  
- **Número máximo de membros do grupo de distribuição** A contagem total de destinatários é determinada após a expansão do grupo de distribuição. 
    
- **Limite de envio de mensagens para grupos de distribuição grandes** Grupos de distribuição que contêm o número de membros especificado por esse limite devem ter opções de gerenciamento de entrega ou de aprovação de mensagens configurados. O gerenciamento de entrega especifica uma lista de remetentes que podem enviar mensagens para o grupo de distribuição. A aprovação de mensagens especifica um ou mais moderadores que devem aprovar todas as mensagens enviadas ao grupo de distribuição. 
    
- **Tamanho máximo de mensagem para grupos de distribuição grandes** Se uma mensagem for enviada a 5.000 ou mais destinatários, o tamanho da mensagem não poderá exceder esse limite. Se o tamanho da mensagem exceder o limite, a mensagem não será entregue, e o remetente receberá uma NDR (notificação de falha na entrega). A contagem total de destinatários é determinada após a expansão do grupo de distribuição. 
    
### <a name="distribution-group-limits-across-office-365-options"></a>Limites de grupos de distribuição em opções do Office 365

||||||||
|:-----|:-----|:-----|:-----|:-----|:-----|:-----|
|**Recurso** <br/> |**Office 365 Business Essentials** <br/> |**Office 365 Business Premium** <br/> |**Office 365 Enterprise E1** <br/> |**Office 365 Enterprise E3** <br/> |**Office 365 Enterprise E5** <br/> |**Office 365 Enterprise F1** <br/> |
|Número máximo de membros do grupo de distribuição<sup>1</sup> <br/> |100.000 membros  <br/> |100.000 membros  <br/> |100.000 membros  <br/> |100.000 membros  <br/> |100.000 membros  <br/> |100.000 membros  <br/> |
|Limite de envio de mensagens para grupos de distribuição grandes  <br/> |5.000 ou mais membros  <br/> |5.000 ou mais membros  <br/> |5.000 ou mais membros  <br/> |5.000 ou mais membros  <br/> |5.000 ou mais membros  <br/> |5.000 ou mais membros  <br/> |
|Tamanho máximo da mensagem para os grupos de distribuição com membros de 5.000 a 100.000  <br/> |25 MB  <br/> |25 MB  <br/> |25 MB  <br/> |25 MB  <br/> |25 MB  <br/> |25 MB  <br/> |
|Tamanho máximo da mensagem para os grupos de distribuição com 100.000 ou mais membros  <br/> |5 MB  <br/> |5 MB  <br/> |5 MB  <br/> |5 MB  <br/> |5 MB  <br/> |5 MB  <br/> |
|Número máximo de proprietários do grupo de distribuição  <br/> |10   <br/> |10   <br/> |10   <br/> |10   <br/> |10   <br/> |10   <br/> |
|Número máximo de grupos que um usuário pode criar  <br/> |300,000<sup>2</sup> <br/> |300,000<sup>2</sup> <br/> |300,000<sup>2</sup> <br/> |300,000<sup>2</sup> <br/> |300,000<sup>2</sup> <br/> |300,000<sup>2</sup> <br/> |
   
> [!NOTE]
> <sup>1</sup> se você estiver usando o Windows Azure Active Directory DirSync, o número máximo de membros do grupo de distribuição que você pode sincronizar a partir de seu local no Active Directory para o Windows Azure Active Directory é 15.000. Se você estiver usando o Windows Azure Connect da AD, esse número é 50.000.<br/> <sup>2</sup> Esse limite também se aplica a administradores. 
  
### <a name="distribution-group-limits-across-standalone-options"></a>Limites de grupos de distribuição em opções autônomas

||||||
|:-----|:-----|:-----|:-----|:-----|
|**Recurso** <br/> |**Exchange Server 2013** <br/> |**Exchange Online (Plano 1)** <br/> |**Exchange Online (Plano 2)** <br/> |**Exchange Online Kiosk** <br/> |
|Número máximo de membros do grupo de distribuição  <br/> |100.000 membros<sup>1</sup> <br/> |100.000 membros  <br/> |100.000 membros  <br/> |100.000 membros  <br/> |
|Limite de envio de mensagens para grupos de distribuição grandes  <br/> |5.000 ou mais membros<sup>1</sup> <br/> |5.000 ou mais membros  <br/> |5.000 ou mais membros  <br/> |5.000 ou mais membros  <br/> |
|Número máximo de proprietários do grupo de distribuição  <br/> |10   <br/> |10   <br/> |10   <br/> |10   <br/> |
|Número máximo de grupos que um usuário pode criar  <br/> |250<sup>2</sup> <br/> |250<sup>2</sup> <br/> |250<sup>2</sup> <br/> |250<sup>2</sup> <br/> |
   
> [!NOTE]
> <sup>1</sup> Este é o limite padrão para organizações do Exchange Server 2013. Os administradores podem alterar esse valor para sua organização.<br/> <sup>2</sup> Esse limite também se aplica a administradores. 
  
## <a name="journal-transport-and-inbox-rule-limits"></a>Limites de regras de Diário, Transporte e Caixa de Entrada

A lista a seguir inclui os limites que se aplicam às regras de diário, de transporte, também conhecidas como regras da organização, e os limites que se aplicam às regras da Caixa de Entrada. As regras da Caixa de Entrada são configuradas por usuários individuais e aplicadas às mensagens enviadas e recebidas pela caixa de correio do usuário individual.
  
- **Número máximo de regras de diário** O número máximo de regras de diário que podem existir na organização. 
    
- **Número máximo de regras de transporte** O número máximo de regras que podem existir na organização. 
    
- **Tamanho máximo de uma regra de transporte individual** O número máximo de caracteres que podem ser usados em uma única regra de transporte. Os caracteres são usados nas condições, exceções e ações. 
    
- **Limite de caracteres para todas as expressões regulares usadas em todas as regras de transporte** O número total de caracteres usados por todas as expressões regulares em todas as condições de regras de transporte e exceções na organização. Você pode ter algumas regras que usam expressões regulares longas e complexas ou pode ter muitas regras que usam expressões regulares simples. 
    
- **Limites de verificação de conteúdo do anexo**As condições de regra de transporte permitem que você examine o conteúdo de anexos de mensagens, mas somente o primeiro 1 MB do texto extraído de um anexo é inspecionado. Esse limite de 1 MB refere-se ao texto extraído do anexo, não o tamanho do arquivo do anexo. Por exemplo, um arquivo de 2 MB pode conter menos de 1 MB de texto, portanto todo o texto seria inspecionado 
    
- **Número máximo de destinatários adicionados a uma mensagem por todas as regras de transporte** Quando uma mensagem é afetada por diferentes regras de transporte, apenas um número finito de destinatários pode ser adicionado à mensagem. Depois que o limite é atingido, os destinatários restantes não são adicionados à mensagem. Além disso, grupos de distribuição não podem ser adicionados a uma mensagem por meio de uma regra de transporte. 
    
- **Limite para encaminhamento** O número máximo de destinatários que podem ser configurados para uma regra de caixa de entrada ou de transporte com uma ação de redirecionamento. Se uma regra for configurada para redirecionar uma mensagem a um número de destinatários maior do que esse, a regra não será aplicada e qualquer mensagem que satisfaça à condição de regra não será redirecionada para nenhum dos destinatários listados na regra. 
    
- **Número de vezes que uma mensagem é redirecionada** O número de vezes que uma mensagem será redirecionado, encaminhada ou respondida automaticamente com base em regras de Caixa de Entrada. Por exemplo, o Usuário A tem uma regra de Caixa de Entrada que redireciona mensagens para o Usuário B, com base no remetente. O Usuário B tem uma regra de Caixa de Entrada que encaminha mensagens para o Usuário C com base em palavras-chave na linha de assunto. Se uma mensagem satisfaz a ambas as condições, ela é enviada apenas ao Usuário B; ela não é encaminhada ao Usuário C, porque somente um redirecionamento é permitido. Neste caso, a mensagem é eliminada sem enviar uma NDR (notificação de falha na entrega) para o Usuário B, indicando que a mensagem não foi entregue ao Usuário C. 
    
### <a name="journal-transport-and-inbox-rule-limits-across-office-365-options"></a>Limites de regras de Diário, de Transporte e de Caixa de Entrada em opções do Office 365

||||||||
|:-----|:-----|:-----|:-----|:-----|:-----|:-----|
|**Recurso** <br/> |**Office 365 Business Essentials** <br/> |**Office 365 Business Premium** <br/> |**Office 365 Enterprise E1** <br/> |**Office 365 Enterprise E3** <br/> |**Office 365 Enterprise E5** <br/> |**Office 365 Enterprise F1** <br/> |
|Número máximo de regras de diário  <br/> |10 regras  <br/> |10 regras  <br/> |10 regras  <br/> |10 regras  <br/> |10 regras  <br/> |10 regras  <br/> |
|Número máximo de regras de transporte  <br/> |300 regras  <br/> |300 regras  <br/> |300 regras  <br/> |300 regras  <br/> |300 regras  <br/> |300 regras  <br/> |
|Tamanho máximo de uma regra de transporte individual  <br/> |8 KB  <br/> |8 KB  <br/> |8 KB  <br/> |8 KB  <br/> |8 KB  <br/> |8 KB  <br/> |
|Limite de caracteres para todas as expressões regulares usadas em todas as regras de transporte  <br/> |20 KB  <br/> |20 KB  <br/> |20 KB  <br/> |20 KB  <br/> |20 KB  <br/> |20 KB  <br/> |
|Limites de verificação de conteúdos de anexos  <br/> |1 MB  <br/> |1 MB  <br/> |1 MB  <br/> |1 MB  <br/> |1 MB  <br/> |1 MB  <br/> |
|Número máximo de destinatários adicionados a uma mensagem por todas as regras de transporte  <br/> |100 destinatários  <br/> |100 destinatários  <br/> |100 destinatários  <br/> |100 destinatários  <br/> |100 destinatários  <br/> |100 destinatários  <br/> |
|Limite de encaminhamento  <br/> |10 destinatários  <br/> |10 destinatários  <br/> |10 destinatários  <br/> |10 destinatários  <br/> |10 destinatários  <br/> |10 destinatários  <br/> |
|Número de vezes que uma mensagem é redirecionada  <br/> |1 redirecionamento  <br/> |1 redirecionamento  <br/> |1 redirecionamento  <br/> |1 redirecionamento  <br/> |1 redirecionamento  <br/> |1 redirecionamento  <br/> |
   
### <a name="journal-transport-and-inbox-rule-limits-across-standalone-options"></a>Limites de regra de Diário, Transporte e Caixa de Entrada entre opções independentes

||||||
|:-----|:-----|:-----|:-----|:-----|
|**Recurso** <br/> |**Exchange Server 2013** <br/> |**Exchange Online (Plano 1)** <br/> |**Exchange Online (Plano 2)** <br/> |**Exchange Online Kiosk** <br/> |
|Número máximo de regras de diário  <br/> |Sem limites  <br/> |10 regras  <br/> |10 regras  <br/> |10 regras  <br/> |
|Número máximo de regras de transporte  <br/> |Sem limites  <br/> |300 regras  <br/> |300 regras  <br/> |300 regras  <br/> |
|Tamanho máximo de uma regra de transporte individual  <br/> |40 KB  <br/> |8 KB  <br/> |8 KB  <br/> |8 KB  <br/> |
|Limite de caracteres para todas as expressões regulares usadas em todas as regras de transporte  <br/> |Sem limites  <br/> |20 KB  <br/> |20 KB  <br/> |20 KB  <br/> |
|Número máximo de destinatários adicionados a uma mensagem por todas as regras de transporte  <br/> |Sem limites  <br/> |100 destinatários  <br/> |100 destinatários  <br/> |100 destinatários  <br/> |
|Limite de encaminhamento  <br/> |Sem limites  <br/> |10 destinatários  <br/> |10 destinatários  <br/> |10 destinatários  <br/> |
|Número de vezes que uma mensagem é redirecionada  <br/> |3 redirecionamentos  <br/> |1 redirecionamento  <br/> |1 redirecionamento  <br/> |1 redirecionamento  <br/> |
  
## <a name="moderation-limits"></a>Limites de moderação
<a name="ModerationLimits"> </a>

Estes limites controlam as configurações de moderação que são usadas para aprovação de mensagens aplicadas a grupos de distribuição e regras de transporte.
  
- **Tamanho máximo da caixa de correio de arbitragem** Se a caixa de correio de arbitragem exceder esse limite, as mensagens que requerem moderação serão devolvidas ao remetente em uma NDR (notificação de falha na entrega). 
    
- **Número máximo de moderadores** O número máximo de moderadores que você pode atribuir a um único grupo de distribuição moderado ou que podem ser adicionados a uma mensagem por meio de uma única regra de transporte. Observe que você não pode especificar um grupo de distribuição como um moderador. 
    
- **Expiração para mensagens aguardando moderação** Por padrão, uma mensagem que está aguardando moderação expira após dois dias. No entanto, o processamento de mensagens moderadas expiradas é executado a cada sete dias. Isso significa que uma mensagem moderada pode expirar a qualquer momento entre dois e nove dias. 
    
- **Taxa máxima para mensagens de notificação de moderação expiradas** Este limite define o número máximo de mensagens de notificação para mensagens moderadas expiradas em um período de uma hora. Esse limite é imposto a todos os bancos de dados de caixas de correio no datacenter. 
    
    Durante os períodos de pesado intenso, alguns remetentes podem não receber mensagens de notificação para mensagens moderadas que expiraram. No entanto, essas notificações ainda são detectáveis com o uso de relatórios de entrega.
    
### <a name="moderation-limits-across-office-365-options"></a>Limites de moderação em opções do Office 365

||||||||
|:-----|:-----|:-----|:-----|:-----|:-----|:-----|
|**Recurso** <br/> |**Office 365 Business Essentials** <br/> |**Office 365 Business Premium** <br/> |**Office 365 Enterprise E1** <br/> |**Office 365 Enterprise E3** <br/> |**Office 365 Enterprise E5** <br/> |**Office 365 Enterprise F1** <br/> |
|Tamanho máximo da caixa de correio de arbitragem  <br/> |10 GB  <br/> |10 GB  <br/> |10 GB  <br/> |10 GB  <br/> |10 GB  <br/> |10 GB  <br/> |
|Número máximo de moderadores  <br/> |10 moderadores  <br/> |10 moderadores  <br/> |10 moderadores  <br/> |10 moderadores  <br/> |10 moderadores  <br/> |10 moderadores  <br/> |
|Expiração para mensagens aguardando moderação  <br/> |2 dias  <br/> |2 dias  <br/> |2 dias  <br/> |2 dias  <br/> |2 dias  <br/> |2 dias  <br/> |
|Taxa máxima para mensagens de notificação de moderação expiradas  <br/> |300 notificações de expiração por hora  <br/> |300 notificações de expiração por hora  <br/> |300 notificações de expiração por hora  <br/> |300 notificações de expiração por hora  <br/> |300 notificações de expiração por hora  <br/> |300 notificações de expiração por hora  <br/> |
   
### <a name="moderation-limits-across-standalone-options"></a>Limites de moderação em opções autônomas

||||||
|:-----|:-----|:-----|:-----|:-----|
|**Recurso** <br/> |**Exchange Server 2013** <br/> |**Exchange Online (Plano 1)** <br/> |**Exchange Online (Plano 2)** <br/> |**Exchange Online Kiosk** <br/> |
|Tamanho máximo da caixa de correio de arbitragem  <br/> |Sem limites<sup>1</sup> <br/> |10 GB  <br/> |10 GB  <br/> |10 GB  <br/> |
|Número máximo de moderadores  <br/> |Sem limites  <br/> |10 moderadores  <br/> |10 moderadores  <br/> |10 moderadores  <br/> |
|Expiração para mensagens aguardando moderação  <br/> |5 dias<sup>1</sup> <br/> |2 dias  <br/> |2 dias  <br/> |2 dias  <br/> |
|Taxa máxima para mensagens de notificação de moderação expiradas  <br/> |300 notificações de expiração por hora  <br/> |300 notificações de expiração por hora  <br/> |300 notificações de expiração por hora  <br/> |300 notificações de expiração por hora  <br/> |
   
> [!NOTE]
> <sup>1</sup> Este é o limite padrão para organizações do Exchange Server 2013. Os administradores podem alterar esse valor para sua organização. 
  
## <a name="exchange-activesync-limits"></a>Limites do Exchange ActiveSync
<a name="BKMK_ExchangeActiveSync_Limits"> </a>

Os seguintes limites se aplicam ao Microsoft Exchange ActiveSync, um protocolo de cliente que sincroniza dados de caixa de correio entre dispositivos móveis e o Exchange. 
  
- **limite do dispositivo Exchange ActiveSync** O número máximo de dispositivos do Exchange ActiveSync por caixa de correio. 
    
- **limite de exclusão de dispositivo Exchange ActiveSync** O número máximo de dispositivos do Exchange ActiveSync que um administrador do Exchange pode excluir em um único mês. 
    
- **Exchange ActiveSync limite de anexo de arquivo** O tamanho máximo de anexo de um arquivo de mensagem que pode ser enviado ou recebido por um dispositivo do Exchange ActiveSync. 
    
### <a name="exchange-activesync-limits-across-office-365-options"></a>Limites do Exchange ActiveSync nas opções do Office 365

||||||||
|:-----|:-----|:-----|:-----|:-----|:-----|:-----|
|**Recurso** <br/> |**Office 365 Business Essentials** <br/> |**Office 365 Business Premium** <br/> |**Office 365 Enterprise E1** <br/> |**Office 365 Enterprise E3** <br/> |**Office 365 Enterprise E5** <br/> |**Office 365 Enterprise F1** <br/> |
|Limite do dispositivo do Exchange ActiveSync  <br/> |100  <br/> |100  <br/> |100  <br/> |100  <br/> |100  <br/> |100  <br/> |
|Limite de exclusão do dispositivo do Exchange ActiveSync  <br/> |20  <br/> |20  <br/> |20  <br/> |20  <br/> |20  <br/> |20  <br/> |
|Limite de anexos de arquivo do Exchange ActiveSync  <br/> |25 MB  <br/> |25 MB  <br/> |25 MB  <br/> |25 MB  <br/> |25 MB  <br/> |25 MB  <br/> |
   
### <a name="exchange-activesync-limits-across-standalone-options"></a>Limites do Exchange ActiveSync nas opções independentes

||||||
|:-----|:-----|:-----|:-----|:-----|
|**Recurso** <br/> |**Exchange Server 2013** <br/> |**Exchange Online (Plano 1)** <br/> |**Exchange Online (Plano 2)** <br/> |**Exchange Online Kiosk** <br/> |
|Limite do dispositivo do Exchange ActiveSync  <br/> |100  <br/> |100  <br/> |100  <br/> |100  <br/> |
|Limite de exclusão do dispositivo do Exchange ActiveSync  <br/> |20  <br/> |20  <br/> |20  <br/> |20  <br/> |
|Limite de anexos de arquivo do Exchange ActiveSync  <br/> |25 MB  <br/> |25 MB  <br/> |25 MB  <br/> |25 MB  <br/> |
