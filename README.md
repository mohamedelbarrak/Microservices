# Microservices pour la Gestion d'Équipes de Football
Bienvenue dans le projet de gestion d'équipes de football, développé avec Spring Boot, Ribbon, Eureka, Circuit Breaker, Swagger et Actuator. Le langage de programmation utilisé est Java.

## Microservice RibbonEurekaServerApplication
  Accessible via : http://localhost:8761/
![image](https://github.com/mohamedelbarrak/Microservices/assets/66890099/5213e09f-31c7-422a-817f-5d7bffddb4b2)
- MATCHSERVICE (3 lancements)
  ![image](https://github.com/mohamedelbarrak/Microservices/assets/66890099/3aa13b9d-ce0a-4da5-8ff3-491874ab2733)
  ![image](https://github.com/mohamedelbarrak/Microservices/assets/66890099/cf00e98a-a9c8-4397-8df6-2b589ac2fc1e)
  ![image](https://github.com/mohamedelbarrak/Microservices/assets/66890099/a3ea751f-c92f-4fb8-8cb2-c94ac466fdd9)

- PLAYERSERVICE
  ![image](https://github.com/mohamedelbarrak/Microservices/assets/66890099/85b055c9-8c4d-44cc-9b53-1b2597acea0f)

- STATISTICSERVICE
  ![image](https://github.com/mohamedelbarrak/Microservices/assets/66890099/4dddf0c0-6c2c-40ea-8faf-999a9cc212b0)

- TEAMSERVICE
  ![image](https://github.com/mohamedelbarrak/Microservices/assets/66890099/31c52898-738e-4c05-aa3b-79e0bec59d5d)

## Microservice MatchService
  - Le model MatchService : String id, String team_one, String team_two, String arbitre, String team_one_buts, String team_two_buts.
  ![image](https://github.com/mohamedelbarrak/Microservices/assets/66890099/e996f9c4-fd4f-4ce9-a4ca-2452517a6569)
  - Points de Terminaison :
  ![image](https://github.com/mohamedelbarrak/Microservices/assets/66890099/8f8bf26d-bf1d-471d-8b79-892e405215a3)

## Microservice PlayerService
  - Le model MatchService : String id, String name, String team, List<String> match_played.
  ![image](https://github.com/mohamedelbarrak/Microservices/assets/66890099/04f55119-5b46-4fa6-a341-b1508c9ba993)
  - Points de Terminaison :
  ![image](https://github.com/mohamedelbarrak/Microservices/assets/66890099/cdc7933f-9090-4da8-83e0-1acdcaf02fdf)

