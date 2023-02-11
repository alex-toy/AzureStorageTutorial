# Azure Storage Tutorial

## Azure Storage

### Storage explorer

<img src="/pictures/storage_account.png" title="storage"  width="800">

- Create Container with private access :
<img src="/pictures/storage_account2.png" title="storage"  width="800">

- Copy Url :
<img src="/pictures/storage_account3.png" title="storage"  width="800">

- With private access, image is unreachable :
<img src="/pictures/storage_account4.png" title="storage"  width="800">

- Change access level :
<img src="/pictures/storage_account5.png" title="storage"  width="800">

- With Blob Access, image is readable :
<img src="/pictures/storage_account6.png" title="storage"  width="800">

- Access through Access Keys :
<img src="/pictures/access_keys.png" title="access keys"  width="800">

- Azure storage Explorer
<img src="/pictures/access_keys2.png" title="azure storage explorer"  width="800">

- Create Table :
<img src="/pictures/table.png" title="table"  width="800">

- Create Queue :
<img src="/pictures/queue.png" title="queue"  width="800">


### Azure Logic App

- Create **Logic App** :
<img src="/pictures/ytb_logicapp.png" title="logic app"  width="800">

- Choose **Scheduler - Add message to a queue** :
<img src="/pictures/ytb_logicapp2.png" title="logic app"  width="800">
<img src="/pictures/ytb_logicapp3.png" title="logic app"  width="800">
<img src="/pictures/ytb_logicapp4.png" title="logic app"  width="800">
<img src="/pictures/ytb_logicapp5.png" title="logic app"  width="800">
<img src="/pictures/ytb_logicapp6.png" title="logic app"  width="800">

- Change destination :
<img src="/pictures/ytb_logicapp7.png" title="logic app"  width="800">


### Azure Logic App - Step by Step Create Logic App | Http - Message Queue - Email - Response

- Choose *When HTTP request is reveived* :
<img src="/pictures/la2_queue.png" title="queue"  width="800">

- Create **Logic App** :
<img src="/pictures/la2_queue2.png" title="queue"  width="800">
<img src="/pictures/la2_queue3.png" title="queue"  width="800">

- You should receive a mail as soon as you launch a request :
<img src="/pictures/la2_queue4.png" title="queue"  width="800">


### Azure Queue Storage

- Create two **Logic App**s (choose *consumption* instead of *standard*) :
<img src="/pictures/logic_app.png" title="logic app"  width="500">
<img src="/pictures/logic_app2.png" title="logic app"  width="800">

1. Logic App 1 :

- Select Http trigger :
<img src="/pictures/logic_app3.png" title="logic app one"  width="800">

- Choose **Storage Account** :
<img src="/pictures/logic_app4.png" title="logic app one"  width="800">

- Add a for loop :
<img src="/pictures/logic_app5.png" title="logic app one"  width="800">

- Observe the result (five messages created) :
<img src="/pictures/logic_app6.png" title="logic app one"  width="800">

2. Logic App 2 :

- Start from blank (choose *When there are messages...*) :
<img src="/pictures/logic_app_two.png" title="logic app two"  width="800">
<img src="/pictures/logic_app_two2.png" title="logic app two"  width="800">

- Observe the results (messages not showing up anymore):
<img src="/pictures/logic_app_two3.png" title="logic app two"  width="800">
<img src="/pictures/logic_app_two4.png" title="logic app two"  width="800">

- Add a Delete message action :
<img src="/pictures/logic_app_two5.png" title="logic app two"  width="800">
<img src="/pictures/logic_app_two6.png" title="logic app two"  width="800">

- Add a Create Blob action :
<img src="/pictures/logic_app_two7.png" title="logic app two"  width="800">

- Observe the result :
<img src="/pictures/logic_app_two8.png" title="logic app two"  width="800">

