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

![image](https://github.com/user-attachments/assets/dcb22431-733e-4f07-adcc-0afa658a4d64)


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


