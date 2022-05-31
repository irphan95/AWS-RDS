# AWS-RDS
- #### In this step,what will do in the task.
![step01](https://user-images.githubusercontent.com/103019032/170978236-de257c91-3c05-4ccd-9713-4c60f23e2e07.PNG)
- #### Create the database with MYSQL,you can choose any database services as per your requirements.
![step1](https://user-images.githubusercontent.com/103019032/170978252-ba33fd5e-c427-4e4f-965b-eed79803622e.PNG)
- #### In this step,choose sql version,i choose sql version 5.7.26.there are three template
#### (1)production(2)dev/test(for developers)and (3)free tier.
#### production and dev/test is chargeable,free tier is free of cost.
![step2](https://user-images.githubusercontent.com/103019032/170978273-0f5f935e-07b5-430b-a1d8-57c66ca5d348.PNG)
- #### Create the database name,and credential configuration,i.e user name and password.
![step3](https://user-images.githubusercontent.com/103019032/170980945-f4d235a1-84bc-4a4b-b9b4-bf24ccb0b0b9.PNG)
- #### In instance configuration,we only choose the burstable class,standard and memory allocation classes is for production and dev/test.The next step is storage,choose storage type and select 20gb storage,because 20gb is in free tier.
![step4](https://user-images.githubusercontent.com/103019032/170978308-bc5aa387-a679-4a51-90dd-7a23b9fcb769.PNG)
- #### The next step is connectivity,you can choose default vpc and subnet or can create your own vpc and subnet,but i have choosed default.If you want publicly access,select option yes,otherwise select no option.The next option is VPC security group,if you have already existing group,choose existing otherwise create new one.Choose availibilty zone,according to your region.
![step5](https://user-images.githubusercontent.com/103019032/170978334-f2aa8d0e-eb27-4a59-b7f1-7abab83ab673.PNG)
- #### Click on create database.
![step6](https://user-images.githubusercontent.com/103019032/170978358-764c3b6b-9f61-4ac9-8252-2245ae7ca7b4.PNG)

