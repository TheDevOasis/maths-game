# maths-game  

Mathematics game to check how well users know their multiplication table up to 10,  
usuing the following technologies:     
✅ HTML     
✅ CSS    
✅ JavaScript    

Features used:   
•	CSS gradients Registration of clients and photovoltaic installations.   
•	Box shadows to add some 3D effects to the page.   
•	Use transitions for a nice interactivity and the best user experience.   
•	Nice JS functions to change in HTML.
•	Show and hide elements and some functions to create timing events.   

![image](https://github.com/user-attachments/assets/4815ad19-0216-416e-a955-24cc564279bc)
![image](https://github.com/user-attachments/assets/fbe8c572-79f5-473d-8ef1-f55e9d7ca81f)
![image](https://github.com/user-attachments/assets/046e3fbd-580e-48d6-b08b-4109463837c5)
![image](https://github.com/user-attachments/assets/940134d5-909d-47f9-b954-d6f350dbdea2)
![image](https://github.com/user-attachments/assets/d5400e2d-3e28-46c9-a787-2c3d7a323711)

Flow Chart & Game Logic:  
![image](https://github.com/user-attachments/assets/60f33d5f-d2ea-4616-8e58-618b2c9b7681)  
//if we are playing  
	-----//reload page  
//if we are not playing  
	-----//set score to 0  
	-----//show countdown box  
	-----//reduce time by 1 sec in loops  
		---------//timeleft?  
			---------------//yes==> continue  
			---------------//no==>gameover  
	-----//change button to reset  
	-----//generate new Q&A  

![image](https://github.com/user-attachments/assets/680947b5-9163-43cf-a32e-3175df80bfc9)  
//if we click on answer box  
	-----//if we are playing  
		--------//correct?  
			--------------//yes  
				-------------------//increase score  
				-------------------//show correct box for 1 sec  
				-------------------//generate new Q&A  
			--------------//no  


