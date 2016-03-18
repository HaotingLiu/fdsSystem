# fdsSystem
This is a system which is used to take the place of the old gds system.
<h2>The overall architecture</h2>
The overall components of this system will be Kafka and redis. Considering the ditribution feature of this system, the server will be nginx.
<h2>The implemention of this system</h2>
<h3>Why kafka</h3>
kafka is actually the main part of this project. As kafka can achieve the function of distribution and with high parallesim. In this project, kafka will be used as the main distributor, take the palce of the si and frontend function of the old system.
<h3> Why redis</h3>
The redis is used as the cache to take the place of the aac in the old system.
<h3> What will be the new database</h3>
The new data base can be any one, but I prefer nosql one. I am not sure by now.
<h3>How to implement AAM in this system</h3>
This is the main problem of this project. 
<h3> Should we use the edifact or change to xml or json</h3>
I still want to stick to the old edifact. But let's keep json as a choice.
<h2>How this system will beat the old system</h2>
The old system got money from the aieline company, and this gave them great profit.
The new system will charge nothing, the whole system will be all free.
We get profit by advertising the airline companies and the hotels and many such things, but no fee for booking for checking availability.
<h2> Can we search the journey as the old engine did</h2>
Now, no. But it will be online in the future. This will be a key for designing the whole system. As we have to be flexible to the possible change in the future.
