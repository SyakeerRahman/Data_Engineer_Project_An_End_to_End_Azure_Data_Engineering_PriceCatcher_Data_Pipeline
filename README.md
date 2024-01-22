# Data_Engineer_Project_An_End_to_End_Azure_Data_Engineering_PriceCatcher_Data_Pipeline


### SQL Database 

create server


create development
<img width="571" alt="image" src="https://github.com/SyakeerRahman/Data_Engineer_Project_An_End_to_End_Azure_Data_Engineering_PriceCatcher_Data_Pipeline/assets/105381652/a97a7635-97ac-4b80-a7ac-b63c0b53271e">

allow server to public access network
<img width="885" alt="image" src="https://github.com/SyakeerRahman/Data_Engineer_Project_An_End_to_End_Azure_Data_Engineering_PriceCatcher_Data_Pipeline/assets/105381652/04bc647a-037e-49bc-8c15-c373a089a5f9">

can try open query editor under SQL DB
<img width="898" alt="image" src="https://github.com/SyakeerRahman/Data_Engineer_Project_An_End_to_End_Azure_Data_Engineering_PriceCatcher_Data_Pipeline/assets/105381652/ffc51c00-0634-42f7-addb-3bb18c8ea20c">

copy server name and paste it inside SSMS
<img width="1029" alt="image" src="https://github.com/SyakeerRahman/Data_Engineer_Project_An_End_to_End_Azure_Data_Engineering_PriceCatcher_Data_Pipeline/assets/105381652/13712254-205e-4b3a-864d-067c4245b635">
<img width="725" alt="image" src="https://github.com/SyakeerRahman/Data_Engineer_Project_An_End_to_End_Azure_Data_Engineering_PriceCatcher_Data_Pipeline/assets/105381652/5a7a4791-7cdb-4f24-8763-6bcb1746ec00">

create azure data factory resource
<img width="976" alt="image" src="https://github.com/SyakeerRahman/Data_Engineer_Project_An_End_to_End_Azure_Data_Engineering_PriceCatcher_Data_Pipeline/assets/105381652/c452d12d-e1e8-4019-81c4-16f8c45a4253">

launch azure data factory and create new linked services resource and add data lake gen2 since there is our resource 
<img width="999" alt="image" src="https://github.com/SyakeerRahman/Data_Engineer_Project_An_End_to_End_Azure_Data_Engineering_PriceCatcher_Data_Pipeline/assets/105381652/8f7ce4a1-def2-44c4-b1a2-6eafdce2f82a">
<img width="452" alt="image" src="https://github.com/SyakeerRahman/Data_Engineer_Project_An_End_to_End_Azure_Data_Engineering_PriceCatcher_Data_Pipeline/assets/105381652/ec329ed0-32f6-421c-a08f-f0ec5d70df47">

create new linked services resources and add sql database since that is our destination
<img width="983" alt="image" src="https://github.com/SyakeerRahman/Data_Engineer_Project_An_End_to_End_Azure_Data_Engineering_PriceCatcher_Data_Pipeline/assets/105381652/25a2b591-6cbd-44d9-b4a6-7de2a073f62f">
<img width="412" alt="image" src="https://github.com/SyakeerRahman/Data_Engineer_Project_An_End_to_End_Azure_Data_Engineering_PriceCatcher_Data_Pipeline/assets/105381652/e0c1375b-3b39-4b6e-9c24-be2bdc28bb21">

we are gonna bring our dataset inside adf , go to author> dataset > new dataset > datalake gen2 > csv > and from now browse the file that we have put our file which is the tutorial
<img width="1059" alt="image" src="https://github.com/SyakeerRahman/Data_Engineer_Project_An_End_to_End_Azure_Data_Engineering_PriceCatcher_Data_Pipeline/assets/105381652/45b264b5-688b-4373-ac67-49afe14b4306">

create another dataset for sqldatabase go to author> dataset > new dataset > sql database  > and leave the table blank
<img width="1064" alt="image" src="https://github.com/SyakeerRahman/Data_Engineer_Project_An_End_to_End_Azure_Data_Engineering_PriceCatcher_Data_Pipeline/assets/105381652/1fa258a0-e9a6-452c-845c-48e637ec939a">
<img width="1040" alt="image" src="https://github.com/SyakeerRahman/Data_Engineer_Project_An_End_to_End_Azure_Data_Engineering_PriceCatcher_Data_Pipeline/assets/105381652/ba6a0486-1eca-4038-b4e9-e3be3eec7796">


now we will move on to build a pipeline, go to author > new pipeline >  copy data 
<img width="1032" alt="image" src="https://github.com/SyakeerRahman/Data_Engineer_Project_An_End_to_End_Azure_Data_Engineering_PriceCatcher_Data_Pipeline/assets/105381652/1adefc57-8cd7-4418-b23c-3ae58a954206">




















