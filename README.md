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
 ![image](https://github.com/mohamedelbarrak/Microservices/assets/66890099/f85a2218-c2d2-41ca-9a47-0d04cc4ae8ea)
  - Points de Terminaison :
  ![image](https://github.com/mohamedelbarrak/Microservices/assets/66890099/8f8bf26d-bf1d-471d-8b79-892e405215a3)

## Microservice PlayerService
  - Le model PlayerService : String id, String name, String team, List<String> match_played.
  ![image](https://github.com/mohamedelbarrak/Microservices/assets/66890099/04f55119-5b46-4fa6-a341-b1508c9ba993)
  - Points de Terminaison :
  ![image](https://github.com/mohamedelbarrak/Microservices/assets/66890099/cdc7933f-9090-4da8-83e0-1acdcaf02fdf)

## Microservice TeamService
  - Le model TeamService : String id, String name, List<String> matchsplayed, List<String> players.
  ![image](https://github.com/mohamedelbarrak/Microservices/assets/66890099/97cfb640-0759-45f9-871d-9e2afb4c7f0d)

  - Points de Terminaison :
  ![image](https://github.com/mohamedelbarrak/Microservices/assets/66890099/47054f5e-e032-4af8-8388-a4b0726ceda3)

## Microservice Statistics
  - La fonction getTeamStatistics pour avoir des statistiques sur le team nombre de matchs jouer et par rapport à chaque joueur ...
  ![image](https://github.com/mohamedelbarrak/Microservices/assets/66890099/34c61509-e39f-4a40-8228-4f3e6f4b5c4b)

  - La fonction getPlayerStatistics pour avoir des statistiques sur un joueur nombre de matchs jouer et nombre de matchs gagnés.
    ![image](https://github.com/mohamedelbarrak/Microservices/assets/66890099/20f67000-1ddc-4ebf-8fdb-c8862f1e9088)
  - Points de Terminaison :
    ![image](https://github.com/mohamedelbarrak/Microservices/assets/66890099/1d6eccf5-a7bf-44b6-905a-9ae27f090ea3)


## Hystrix
![image](https://github.com/mohamedelbarrak/Microservices/assets/66890099/cde718ab-e03b-429d-bbeb-cbc0d3598a59)


