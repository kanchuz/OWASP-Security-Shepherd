#OWASP Security Shepherd #
## Level : Private ##

###1. Insecure Cryptographic Storage
Decrypt the given key using **Base 64** decryption.
This can be done using *Decorder* function of the Burb Suite software.

###2. SQL Injection
Type injection query `'or '1'='1` to the text field and click *Get this user* button.

###3. Insecure Cryptographic Storage Challenge 1
Decrypt the given key using **roman cypher** decryption.
There are many online tools available for this.

###4. Insecure Direct Object Reference Challenge 1
In order to complete the challenge, we have to find the database id's for the users and, id pattern.
pattern of the ids are 1,3,5,7,9,....
So the next id should be `11`.

###5. Poor Data Validation 1
If user can buy Tolls for free then the challenge is completed.
To do that we have to buy tolls and the cost should be covered from the other items minus values.
Ex: Select `1` from trolls and select `-100` Megusta.

###6. SQL Injection Challenge 1
Type injection query `" or "a"="a` to the text field and click *Get this user* button.

###7. Session Management Challenge One
