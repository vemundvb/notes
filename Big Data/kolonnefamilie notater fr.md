Kolonner kan være i rekkefølge
![[Pasted image 20231004122504.png]]

Utmerket for å kjøre på klynger og skalerbarhet
cassandra er en superkolonnedatabase 
de har veldig fysisk til hvordan de blir lagret.

AP-system:
Veldig fokus på tilgjengelighet, nodene og dataene skal være tilgjengelig



![[]]![[Pasted image 20231004123902.png]]


keyspace - samling av kolonnefamilier
cassandra krever man spesifieserer kolonner på forhånd - schema?, der bryter cassandra med teoriten

Datamodellen i Cassandra  
● Keyspace  
● Kolonnefamilie  
○ Samling av lignende rader  
○ Schema må være spesifisert  
● Rad  
○ Samling av kolonner  
○ Rader trenger ikke å ha de samme kolonnene  
○ Hver rad er identifisert ved en unik primærnøkkel  
● Kolonne  
○ Nøkkel-verdipar og ekstra data



Nodering:
node - har ansvar for et sett med nøkler
man har replikar, så flere noder kan ha ansvar for samme sett med nøkler.
verdiene hashes
dette er optimalt for klynger, fordi vi lnsker at nodene har sannsynlighet for å få like mye data
modulo - viktig fordi hashing kan generere flere verdier enn det er noder
cassandra brukes ikke hashing direkte, men bruker ranges? spesifesere ett sett med ragnes, så eks 1-2^30 kan tilhøre node 1, så tilhører de samme rangesene for flere av de andre nodene, så kan noden andre noder kan en range noe overlappende, og noe utenfor.



















