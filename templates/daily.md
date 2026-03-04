## Notes

- [ ] 
___

>[!tip] WIP
>```tasks
>not done
>(description regex matches /\S/i) AND (status.name includes In progress)
>group by heading
>sort by priority
>sort by due
>sort by scheduled
>sort by description
>hide task count
>short mode
>```

>[!question] Pending
>```tasks
>not done
>(description regex matches /\S/i) AND (status.name includes Waiting)
>group by heading
>sort by priority
>sort by due
>sort by scheduled
>sort by description
>hide task count
>short mode
>```

## Work

>[!warning] Unfinished
>```tasks
>not done
>(heading includes work) AND (path does not include daily/{{title}}) AND (description regex matches /\S/i) AND ((scheduled before {{title}}) OR (has due date) OR (has start date)) AND (status.type is not IN_PROGRESS)
>group by function task.description.split(": ", 1)[0].length == task.description.length ? " no subject" : (task.description.split(": ", 1)[0].split("]]", 1)[0].length == task.description.split(": ", 1)[0].length ? " no subject" : task.description.split(": ", 1)[0]) 
>sort by priority
>sort by due
>sort by scheduled
>sort by description
>short mode
>```

- [ ] 

>[!success]- Finished
>```tasks
>done
>(heading includes work) AND (done on {{title}})
>sort by priority
>sort by due
>sort by scheduled
>sort by description
>```

## Todo.Family

>[!warning] Unfinished
>```tasks
>not done
>(heading includes todo.family) AND (path does not include daily/{{title}}) AND (description regex matches /\S/i) AND ((scheduled before {{title}}) OR (has due date) OR (has start date)) AND (status.type is not IN_PROGRESS)
>group by function task.description.split(": ", 1)[0].length == task.description.length ? " no subject" : (task.description.split(": ", 1)[0].split("]]", 1)[0].length == task.description.split(": ", 1)[0].length ? " no subject" : task.description.split(": ", 1)[0]) 
>sort by priority
>sort by due
>sort by scheduled
>sort by description
>short mode
>```

- [ ] 

>[!success]- Finished
>```tasks
>done
>(heading includes todo.family) AND (done on {{title}})
>sort by priority
>sort by due
>sort by scheduled
>sort by description
>```

## Life

>[!warning] Unfinished
>```tasks
>not done
>(heading includes life) AND (path does not include daily/{{title}}) AND (description regex matches /\S/i) AND ((scheduled before {{title}}) OR (has due date) OR (has start date)) AND (status.type is not IN_PROGRESS)
>group by function task.description.split(": ", 1)[0].length == task.description.length ? " no subject" : (task.description.split(": ", 1)[0].split("]]", 1)[0].length == task.description.split(": ", 1)[0].length ? " no subject" : task.description.split(": ", 1)[0]) 
>sort by priority
>sort by due
>sort by scheduled
>sort by description
>short mode
>```

- [ ] 

>[!success]- Finished
>```tasks
>done
>(heading includes life) AND (done on {{title}})
>sort by priority
>sort by due
>sort by scheduled
>sort by description
>```

## Hobbies

>[!warning] Unfinished
>```tasks
>not done
>(heading includes hobbies) AND (path does not include daily/{{title}}) AND (description regex matches /\S/i) AND ((scheduled before {{title}}) OR (has due date) OR (has start date)) AND (status.type is not IN_PROGRESS)
>group by function task.description.split(": ", 1)[0].length == task.description.length ? " no subject" : (task.description.split(": ", 1)[0].split("]]", 1)[0].length == task.description.split(": ", 1)[0].length ? " no subject" : task.description.split(": ", 1)[0]) 
>sort by priority
>sort by due
>sort by scheduled
>sort by description
>short mode
>```

- [ ] 

>[!success]- Finished
>```tasks
>done
>(heading includes hobbies) AND (done on {{title}})
>sort by priority
>sort by due
>sort by scheduled
>sort by description
>```
