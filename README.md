# Project Managment

## Project will be two layer, Backend and frontend:

You have to use:

Backend technologies
* ბაზა: mongodb (mongoose orm),
* Promises, async-wait
* express.js

Frontend Technologies: 
* react.js
* redux saga
* material-ui (http://www.material-ui.com/#/)
* immutable


Project Feautres:
* 1)login
* 2)signup

* 3)Project create
* 4)Project Update
* 5)Project list
* 6)Project delete

* 7)Project's tasks list
* 8)Task create in project
* 9)Task Update
* 10)Task delete


#### User fields:
```
user:
id
username,
email,
created,
activated
```

#### Projects fields:
```
name,
date,
created,
modified,
description,
startDate
endDate
user
```

#### Task fields:
```
id,
name,
date,
created,
modified,
description,
startDate
endDate
project
user
```


