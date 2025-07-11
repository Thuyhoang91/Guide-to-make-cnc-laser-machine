# Guide-to-make-cnc-laser-machine
use modules from market to make cnc laser machine


## Install

1.  FlatCAM https://bitbucket.org/jpcgt/flatcam/downloads

2.  Lightburn https://drive.google.com/file/d/1-n7cw3vzgm65DdgTvnrsO0Jk28_1gMNG/view?usp=drive_link

3.  Eagle PCB https://drive.google.com/file/d/1Jc6lVkUVwL1pZ8ARBoqRP93d9hBxgBJn/view?usp=drive_link

##  Market

1.  CNC controller

![image](https://github.com/user-attachments/assets/19ee5130-b8ba-476d-98ab-c23db4b90601)



https://shopee.vn/B%E1%BA%A3ng-M%E1%BA%A1ch-%C4%90i%E1%BB%81u-Khi%E1%BB%83n-%C4%90%E1%BB%99ng-C%C6%A1-B%C6%B0%E1%BB%9Bc-2-Tr%E1%BB%A5c-Cnc-3018-2418-1610-Grbl-1.1-3-Tr%E1%BB%A5c-i.82558488.7210090634?sp_atk=55d24bdf-9072-4e9e-9a09-1639b915e53b&xptdk=55d24bdf-9072-4e9e-9a09-1639b915e53b

2.  CNC frame

   ![image](https://github.com/user-attachments/assets/06eef02f-ac08-4e48-90f9-b5e28f791a26)

https://shopee.vn/Khung-m%C3%A1y-kh%E1%BA%AFc-laser-m%C3%A1y-v%E1%BA%BD-CNC-mini-B%C3%ADch-b%E1%BA%B1ng-inox-i.1419735912.25093747755?sp_atk=d454f5c1-7e79-40c2-b3fe-8c114bb4a268&xptdk=d454f5c1-7e79-40c2-b3fe-8c114bb4a268

3. Laser 80w

  ![image](https://github.com/user-attachments/assets/0c8151c9-05fd-435d-9f27-34e5412def22)

  https://shopee.vn/M%C3%B4-%C4%90un-laser-450nm-80w-Ch%E1%BB%89nh-%C4%90%E1%BB%99-D%C3%A0i-T%E1%BB%91c-%C4%90%E1%BB%99-Cao-Chuy%C3%AAn-D%E1%BB%A5ng-Cho-M%C3%A1y-In-3d-cnc-r-tolo-10.17-i.135248328.24050540035?sp_atk=4ba1ca97-4533-4d6f-97ee-6f9675c19b55&xptdk=4ba1ca97-4533-4d6f-97ee-6f9675c19b55

4.  CNC power

   ![image](https://github.com/user-attachments/assets/29daa005-e6ea-40d3-b654-a99d6b59eb98)

   https://shopee.vn/Ngu%E1%BB%93n-T%E1%BB%95-Ong-Ngu%E1%BB%93n-12V-24V-5V-%C4%90%E1%BB%95i-Ngu%E1%BB%93n-D%C3%B9ng-Cho-Camera-%C4%90%C3%A8n-Led-Motor-M%C3%A1y-B%C6%A1m-c%C3%A1c-thi%E1%BA%BFt-b%E1%BB%8B-24V-12V-5V-i.363419620.3876454730?sp_atk=4014976d-bd7c-488b-afa0-611544f63d66&xptdk=4014976d-bd7c-488b-afa0-611544f63d66

## Usage

1. Assembly

  Machine frame and controller Board.
  

 ![image](https://github.com/user-attachments/assets/61c1a398-8cbe-43cb-ab6e-197ec59708b8)


  Machine output-wire connect board


 ![image](https://github.com/user-attachments/assets/b07c81ad-73c2-4472-bd2c-a08ff061d9b1)


  Power 24 volt for controller board, 12 volt for laser 80w.

2.   Setup file

   **Eagle tool** create file PCB , export cam


   ![image](https://github.com/user-attachments/assets/b3e98ee5-f477-42aa-af7b-40852e26b87c)

   Process job, then select folder to save.

   ![image](https://github.com/user-attachments/assets/f98c4f82-81f6-47b2-9c87-6a86413c49eb)


   **FlatCAM tool** create SVG file for Lightburn.

   Click open gerber , find copper.top to process.

   ![image](https://github.com/user-attachments/assets/dd5febf0-1697-4651-b3ec-9443d0b6a351)

   Process file if need

   ![image](https://github.com/user-attachments/assets/00888c6d-6c0d-43ed-a31c-2b81b1089df8)

   Create SVG ( include 2 file box + iso_combine ) , export to SVG.


   ![image](https://github.com/user-attachments/assets/75c9e327-8efc-436a-994e-aa108071f1b0)


   ![image](https://github.com/user-attachments/assets/5f24ee86-3b12-4ef3-b250-7959fb5f1c8a)


   ![image](https://github.com/user-attachments/assets/c6d2c347-b3dc-4417-9883-03eeaad7ee11)

  
   **LightBurn tool**

   Import and Goup 2 to 1 


   ![image](https://github.com/user-attachments/assets/6f070ce7-438a-4be1-a0f9-ea5a307f1182)



   ![image](https://github.com/user-attachments/assets/a73f8763-0d79-429f-845c-70bb1600a71a)


   Modify parameters to cnc machine, good result.
   Research https://aistudio.google.com/app/prompts?state=%7B%22ids%22:%5B%221WA3iz43JVAnzSQjRSC6X6rtz2DiF-WIO%22%5D,%22action%22:%22open%22,%22userId%22:%22104288789476001819042%22,%22resourceKeys%22:%7B%7D%7D&usp=sharing

3. Run

   Lightburn : choose Tab-layer then click Frame ,click Start.


   ![image](https://github.com/user-attachments/assets/96a6e239-6ec8-42cf-b40c-0be4e5b15754)

   Product


   ![image](https://github.com/user-attachments/assets/b51e30f6-637d-42f4-bf82-42a7f5282c5e)



   ![image](https://github.com/user-attachments/assets/1cdd6c38-85a0-43b5-b80b-1fc3a29047ef)








   


  



