                                                     DefaultFieldValues

We can use this routine onto default field routine place Or check rec routine
DefaultRoutine : when we select any value of that field it will be trigger.
checkRecRtn : when we open version it will fire.

![image](https://user-images.githubusercontent.com/40827670/217555771-6f34d14f-cc6f-42b8-bdaa-3a64b44836b9.png)
I made a code that do when I open a version that trigger a routine those do set name BNK with sector values if sector value should be 2007 but in that case when we open customer version it should be trigger this routine and that case sector value is empty so it will show /CNK on NAME.1 field

![image](https://user-images.githubusercontent.com/40827670/217555947-eef7359c-7d8f-4d76-8f89-e7e47af20dcf.png)
We make a EB.API and name of eb.api can write any name but source type we select method cause of java method and java method name we write same name of method we wrote in java class 
and class name we wrote same as java class name and same as package do it

![image](https://user-images.githubusercontent.com/40827670/217556041-eb124a31-221c-41ab-864f-d89d63506a40.png)
Here we put that routine in check rec  routine rtn while this routine I can put in default routine place if I put this routine on default rtn place so when we select any value in sector then it will be fire

![image](https://user-images.githubusercontent.com/40827670/217556168-b440f350-cde0-4b63-9c2c-8607493495b2.png)
And make sure we should set attribute on that field as hot.validate where field we select

![image](https://user-images.githubusercontent.com/40827670/217556649-a70121ec-c0d8-4170-9706-ba4a7e54520c.png)
But here we put routine on check rec rtn so it will fire when we open that version


------Now we put that routine on default field BUT SEE FIRST ABOVE AND UNDERSTAND THEN YOU CAN UNDERSTAND BELOW CASE-----

![image](https://user-images.githubusercontent.com/40827670/217556869-8eb927a0-b320-4ab0-b23b-210a621dffd0.png)
![image](https://user-images.githubusercontent.com/40827670/217556898-233dc158-db36-4878-acba-c96c0d339a7c.png)
NOW WE ARE IN SECTOR FIELD DIDN’T CLICK OUTSIDE THE SECTOR

![image](https://user-images.githubusercontent.com/40827670/217556975-60f03cc0-90a6-4f60-b33f-faaca7c9cd16.png)
NOW WE CLICK OUTSIDE THE SECTOR FIELD and check name value is change to 2007/BNK if we select another value of sector then name.1 field overide /CNK value


