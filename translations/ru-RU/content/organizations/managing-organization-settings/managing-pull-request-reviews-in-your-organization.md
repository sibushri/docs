---
title: Управление проверками запросов на вытягивание в организации
intro: 'Вы можете настроить ограничения касательно того, какие пользователи могут одобрять или запрашивать изменения в запросах на вытягивание в организации.'
versions:
  feature: pull-request-approval-limit
permissions: Organization owners can limit which users can submit reviews that approve or request changes to a pull request.
topics:
  - Organizations
  - Pull requests
shortTitle: Manage pull request reviews
ms.openlocfilehash: 2d097e95572932f05795bd28627cb73b1fad43ca
ms.sourcegitcommit: fcf3546b7cc208155fb8acdf68b81be28afc3d2d
ms.translationtype: HT
ms.contentlocale: ru-RU
ms.lasthandoff: 09/10/2022
ms.locfileid: '145125720'
---
## Сведения об ограничениях проверки кода

По умолчанию в общедоступных репозиториях любой пользователь может отправлять отзывы, которые утверждают или запрашивают изменения запроса на вытягивание.

Вы можете самостоятельно указать, кто может утверждать или запрашивать изменения в запросах на вытягивание в общедоступных репозиториях, принадлежащих вашей организации. После включения ограничений по проверке кода любой пользователь может закомментировать запросы на вытягивание в общедоступных репозиториях, однако только пользователи с явным доступом к репозиторию могут утверждать запрос на вытягивание или вносить изменения.

Вы также можете включить ограничения проверки кода для отдельных репозиториев. Если вы включите ограничения для своей организации, вы тем самым переопределите все ограничения для отдельных репозиториев, принадлежащих организации. Дополнительные сведения см. в разделе [Управление проверками запросов на вытягивание в репозитории](/repositories/managing-your-repositorys-settings-and-features/managing-repository-settings/managing-pull-request-reviews-in-your-repository).

## Включение ограничений по проверке кода

{% data reusables.profile.access_org %} {% data reusables.profile.org_settings %}
1. В разделе "Доступ" на боковой панели щелкните **{% octicon "report" aria-label="The report icon" %} Модерация**.
1. В разделе "{% octicon "report" aria-label="The report icon" %} Модерация", нажмите кнопку **Ограничения проверки кода**.
![Снимок экрана: элемент боковой панели, где приведены ограничения проверки кода для организаций](/assets/images/help/organizations/code-review-limits-organizations.png)
1. Просмотрите сведения на экране. Нажмите кнопку **Ограничить проверку для всех репозиториев**, чтобы ограничиться только проверками с явным доступом, или выберите **Ограничения проверки из всех репозиториев**, чтобы удалить ограничения из всех общедоступных репозиториев в вашей организации.
![Снимок экрана: параметры ограничений по проверке кода для организаций](/assets/images/help/organizations/code-review-limits-organizations-settings.png)