# NginxAndMultiContainers
a Docker project by Aviv Galily and Dor Raba
a reverse-proxy service that handeling meals and diets microservices.
in this project the user can send rest api request to meals Container and to diet Container, and show in the Architecture below.
this project use MongoDB to save the data from user incase of failure.
There is also implementation of loab balncer in case of hige demands.
ngix on port 80, meals on port 5001, diets on port 5002.

• GET URI:port/meals?diet=<name>
This request returns those meals that conforms to the diet.
  
  *****IN ORDER FOR THE CODE TO WORK YOU NEED TO INSERT YOUR API KEY FROM NINJA-API AT https://api-ninjas.com/  INSIDE OF meals.py FILE AT THE MARKED PLACE*****



![Architecture](https://github.com/AvivGalily/NginxAndMultiContainers/assets/105667180/1e71814b-7d45-4822-966b-8cec0237420f)


example for post and get foramt
![get_meals](https://github.com/AvivGalily/NginxAndMultiContainers/assets/105667180/f9b46852-15de-41a8-b7bd-9891c024c34c)
![post_diets](https://github.com/AvivGalily/NginxAndMultiContainers/assets/105667180/dff81b72-ea24-4d2f-b237-11c2815963f7)
![post_dishes](https://github.com/AvivGalily/NginxAndMultiContainers/assets/105667180/70dab3c1-b829-435c-996a-4e40e3538f10)
![post_meals](https://github.com/AvivGalily/NginxAndMultiContainers/assets/105667180/0fe5f931-8561-45d3-bc95-3456d80f372f)


