---
title: 
description: 
maintainers: 
performers: 
tags:
---

>[!warning] Unfinished
>```tasks
>not done
>(heading includes work) AND (description includes {{title}}) AND (status.type is not NON_TASK) AND (description regex matches /\S/i)
>sort by priority
>sort by due
>sort by scheduled
>sort by description
>```

>[!success]- Finished
>```tasks
>done
>(heading includes work) AND (description includes {{title}}) AND  (status.type is not NON_TASK)
>sort by priority
>sort by due
>sort by scheduled
>sort by description
>```

>[!missing]- Cancelled
>```tasks
>(heading includes work) AND (description includes {{title}}) AND (status.type is CANCELLED)
>sort by priority
>sort by due
>sort by scheduled
>sort by description
>```

>[!example] Events
```tasks
(heading includes {{title}})
group by filename
short mode
```
