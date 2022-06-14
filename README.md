![128](https://user-images.githubusercontent.com/75242911/173700184-2c87415c-b49c-4a09-87c2-99d2e4e67f64.png)

# anti-procrastination-chrome-extension
Redirects any domain/s to one domain of your choosing (default set to google.com) 

 STEPS TO INCLUDE IN CHROME BROWSER:

1) Download and open zip file
2) At the top of browser, click on the **Extension Icon** <img width="39" alt="Screen Shot 2022-06-14 at 3 12 42 PM" src="https://user-images.githubusercontent.com/75242911/173698084-91384fb3-82fa-4768-8659-845a6b48c30c.png">

<img width="196" alt="Screen Shot 2022-06-14 at 3 10 30 PM" src="https://user-images.githubusercontent.com/75242911/173697837-6ec243ba-8ce2-4ebe-89bf-1c1b65d01f19.png">
3) A Dropdown menu appears, click on "Manage Extensions"
<img width="321" alt="Screen Shot 2022-06-14 at 3 11 14 PM" src="https://user-images.githubusercontent.com/75242911/173697915-43e83897-aa33-4b06-8457-823945d01564.png">

4) Click on "Load unpacked"
<img width="1223" alt="Screen Shot 2022-06-14 at 3 08 17 PM" src="https://user-images.githubusercontent.com/75242911/173697633-47762e87-d15d-412e-900d-672b00ca69db.png">

5) Select directory containing unzipped file 
------------------------------------------------------------------------------------



HOW TO ADD / EDIT DOMAINS YOU WANT TO REDIRECT FROM: 

1) Using any code editor, go into ```manifest.json``` 

2) Add/edit the domains under "matches" to your liking. 
The * includes all web pages with the base domain. 
<img width="322" alt="Screen Shot 2022-06-14 at 3 19 22 PM" src="https://user-images.githubusercontent.com/75242911/173698820-857bdaee-2497-4370-aaee-dfa5b2c1b8c2.png">

3) Once edited, don't forget to go back into Extensions Icon --> "Manage Extensions" --> "Update" to load new changes
<img width="588" alt="Screen Shot 2022-06-14 at 3 49 25 PM" src="https://user-images.githubusercontent.com/75242911/173701992-a5dd8d3f-0389-4fb3-9317-28be47fabe7d.png">
--------------------------------------------------------------------------------------------------

HOW TO EDIT DOMAIN TO REDIRECT TO:
1) Go into ```script.js```
2) Edit URL to your liking 
