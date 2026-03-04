__{{date}} {{time}}__
## Кто это


___
## Когда / где / как познакомились


___
## Follow-up


___

>[!warning] Unfinished
>```tasks
>not done
>((heading includes Work) OR (heading includes Life) OR (heading includes Hobbies) OR (heading includes todo.family)) AND (description regex matches /\b{{title}}\b/i) AND (status.type is not NON_TASK) AND (description regex matches /\S/i)
>group by heading
>sort by priority
>sort by due
>sort by scheduled
>sort by description
>hide task count
>short mode
>```

>[!success]- Finished
>```tasks
>done
>((heading includes Work) OR (heading includes Life) OR (heading includes Hobbies) OR (heading includes todo.family)) AND (description regex matches /\b{{title}}\b/i) AND (status.type is not NON_TASK) AND (status.type is not CANCELLED)
>group by heading
>sort by priority
>sort by due
>sort by scheduled
>sort by description
>hide task count
>short mode
>```

>[!missing]- Cancelled
>```tasks
>((heading includes Work) OR (heading includes Life) OR (heading includes Hobbies) OR (heading includes todo.family)) AND (description regex matches /\b{{title}}\b/i) AND (status.type is CANCELLED)
>group by heading
>sort by priority
>sort by due
>sort by scheduled
>sort by description
>hide task count
>short mode
>```

>[!example] Events
```tasks
(heading regex matches /[^\wа-яА-ЯёЁ]{{title}}[^\wа-яА-ЯёЁ]/ui) OR (description regex matches /[^\wа-яА-ЯёЁ]{{title}}[^\wа-яА-ЯёЁ]/ui) AND (heading does not include work) AND (heading does not include todo.family) AND  (heading does not include life) AND (heading does not include hobbies)
group by filename reverse
group by heading
short mode
hide task count
```
