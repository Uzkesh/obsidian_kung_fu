---
title: 
description: 
refs:
---

>[!warning] Unfinished
>```tasks
>not done
>(description includes {{title}}) AND (status.type is not NON_TASK) AND (description regex matches /\S/i)
>sort by priority
>sort by due
>sort by scheduled
>sort by description
>```

>[!success]- Finished
>```tasks
>done
>(description includes {{title}}) AND  (status.type is not NON_TASK)
>sort by priority
>sort by due
>sort by scheduled
>sort by description
>```

>[!example] Events
>```tasks
>done
>(heading includes events) AND (description includes {{title}}) AND (status.type is NON_TASK)
>sort by priority
>sort by due
>sort by scheduled
>sort by created
>sort by description
>```

