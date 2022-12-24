# JEE_Systemes_Distribues_Controle

1_ Création du micro-service customer-service qui permet de gérer les clients :

<img src="https://user-images.githubusercontent.com/80221042/205444179-3a823915-4a11-4b23-a827-39452f8f88c7.PNG" height="500" width="400">

    * Entité Customer :
    
<img src="https://user-images.githubusercontent.com/80221042/205444200-faa307bf-af90-484b-8881-04e524947bcf.PNG" height="300" width="900">
    
    * Repository Customer :
    
<img src="https://user-images.githubusercontent.com/80221042/205444230-0f01c087-43b7-4872-9959-c982f75ad798.PNG" height="300" width="900">
    
    * localhost:8081/customers :
    
<img src="https://user-images.githubusercontent.com/80221042/205444257-3815b6f7-4341-40c1-994a-c8fddde3fb87.PNG" height="800" width="400">


2_ Création du inventory-service qui permet de gérer les produits :

<img src="https://user-images.githubusercontent.com/80221042/209436299-77f88901-8075-4f6d-b407-c366bbd61c99.PNG" height="500" width="400">

    * Entité Product :
    
<img src="https://user-images.githubusercontent.com/80221042/209436308-f349eff9-a883-4392-8944-baa9c1bf0283.PNG" height="500" width="400">
    
    * Repository Product :
    
<img src="https://user-images.githubusercontent.com/80221042/209436316-ba9597a4-b82a-49cc-8f8a-1e6434e40b8e.PNG" height="500" width="400">

    * localhost:8081/products :
    
<img src="https://user-images.githubusercontent.com/80221042/209436327-e13671b6-cc00-4ad9-a0f2-777a911d0ffc.PNG" height="500" width="400">


3_ Création de la Gateway Spring cloud Gateway avec une Configuration statique du système de routage :
      
      * Configuration à l'aide de fichier yaml :
      
<img src="https://user-images.githubusercontent.com/80221042/209436379-de8a62a9-678c-4f92-8a86-d2f6c14207fb.PNG" height="500" width="400">      
      
      * Configuration à l'aide de code java :

<img src="https://user-images.githubusercontent.com/80221042/209436397-7b1a5c12-bf0d-473e-990d-03b60ca1dc47.PNG" height="500" width="400">


4_ Création de l'annuaire Eureka Discrovery Service :

<img src="https://user-images.githubusercontent.com/80221042/209436403-a0500f76-3943-4f76-8130-9044e07922b0.PNG" height="500" width="400">      


5_ Configuration dynamique des routes de la gateway :

<img src="https://user-images.githubusercontent.com/80221042/209436412-ed27c909-7f76-4feb-b068-6cffe6da9d94.PNG" height="500" width="400">      


6_ Création du service de facturation Billing-Service en utilisant Open Feign :

<img src="https://user-images.githubusercontent.com/80221042/209436420-2915aa3b-e00f-43fe-8dff-efdc3fd4a375.PNG" height="500" width="400">      


7_ Création du client Web Angular (Clients, Produits, Factures) :
