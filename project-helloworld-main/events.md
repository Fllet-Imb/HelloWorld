# List of events

### n°1 - Soirée Karaoke

```json
{
  "event_id": 76214,
  "title": "Soirée Karaoké",
  "description": "Venez chanter vos chansons préférées lors de notre soirée Karaoké ! Tous les étudiants sont les bienvenus, aucune expérience de chant requise.",

  "participants": {
    "attending": 7,
    "max_attendees": 20
  },

  "event_dates": [
    { "event_date": "2023-04-07T19:00:00Z" },
    { "event_date": "2023-04-14T19:00:00Z" },
    { "event_date": "2023-04-21T19:00:00Z" }
  ],

  "location": {
    "venue_name": "Campus Batelle",
    "address": "Rue de la Tambourine 17",
    "city": "Carouge",
    "postal_code": 1227,
    "state": "Geneva"
  },

  "price": 0
}
```

![image](./img/mockup3.png)

###n°2 - Tournoi de jeux vidéo

```json
{
  "event_id": 76215,
  "title": "Tournoi de jeux vidéo",
  "description": "Venez affronter vos amis lors de notre tournoi de jeux vidéo ! Les jeux incluent Mario Kart, Super Smash Bros et FIFA.",

  "participants": {
    "attending": 13,
    "max_attendees": 16
  },

  "event_dates": [
    { "event_date": "2023-06-07T18:30:00Z" },
    { "event_date": "2023-06-08T18:30:00Z" }
  ],

  "location": {
    "venue_name": "Campus Batelle",
    "address": "Rue de la Tambourine 17",
    "city": "Carouge",
    "postal_code": 1227,
    "state": "Geneva"
  },

  "price": 5
}
```

### n°3 - Frisbee and beers at Geronde

Mockup  
![](img/MckpFrisbee.png)  
Data

```json
{
  "eventId":"987654"
  "title":"Frisbee and Beers",
  "creatorId":"1234567",
  "description": "...",
  "imgPath":"C:/Users/Django/img/frisbee.png",

  "date":
  {
    "day":"04.04.2023",
    "hourStart":"14h00",
    "hourEnd":"18h00"
  },
  "location":
  {
    "address":"Ch. du Grand Lac",
     "city":"Sierre",
     "postalCode":"3960"
   },
  "infos":
  [
    "Free",
    "BYOB",
    "Swimsuit and sunscreen"
  ]
}
```

### n°4 - Study group CC1 Corporate Management  
Description  
Event organised by a student to organise a study group. The study group will be able to meet to prepare for an exam together.  
Data

```json
{
  "eventId":"987655"
  "title":"Study group CC1 Corporate Management",
  "creatorId":"1234567",
  "description": "...",
  "imgPath":"C:/Users/Django/img/study.png",

  "date":
  {
    "day":"05.04.2023",
    "hourStart":"13h00",
    "hourEnd":"19h00"
  },
  "location":
  {
    "address":"Rue de la plaine 2",
     "city":"Sierre",
     "postalCode":"3960"
   },
  "infos":
  [
    "604_FT_F",
    "CC01 61-41",
    "Let's pass this together!"
  ]
}
```

### n°5 - BackTo90s

```json
{
  "Event": "BackTo90s",
  "Description": "This is a student party for HEG students. Come with some friends and have fun !",
  "Type": "Student party",
  "Location": {
    "Name": "Village du soir",
    "Address": "Rte des Jeunes 24",
    "City": "Lancy",
    "ZipCode": "1212",
    "Country": "Suisse"
  },
  "DateTime": {
    "Start": "2023-04-28T12:00:00",
    "End": "2023-04-28T05:00:00"
  },
  "Price": {
    "Entry": "Free",
    "MinimumAge": 18,
    "DrinkPrices": {
      "Beer": 5,
      "Shot": 4,
      "Cocktail": 10
    }
  }
}
```

![image](./img/Eleonora_BackTo90s.png)

### n°6 - Welcome Back Party

```json
{
  "Event": "Welcome Back Party",
  "Description": "Starting over is not easy, let’s do it in style",
  "Type": "Back to school party",
  "Location": {
    "Name": "Moulin Rouge - Geneva",
    "Address": "Av. du Mail 1",
    "City": "Genève",
    "ZipCode": "1205",
    "Country": "Suisse"
  },
  "DateTime": {
    "Start": "2023-09-08T12:00:00",
    "End": "2023-09-08T05:00:00"
  },
  "Price": {
    "Entry": "10.-",
    "MinimumAge": 18,
    "DrinkPrices": {
      "Beer": 5,
      "Shot": 4,
      "Cocktail": 10
    }
  }
}
```

### n°7 - Fundraiser Gala for Cancer association

```json
{
  "Event": "Charity Fundraiser Gala",
  "Description": "Join us for an evening of giving to support the local community to prevent cancer",
  "Type": "Fundraiser",
  "Location": {
    "Name": "Fairmont Grand Hotel Geneva",
    "Address": "Quai du Mont-Blanc 18",
    "City": "Geneva",
    "State": "Geneva",
    "Zip code": "1201",
    "Country": "Switzerland"
    
  },
  "DateTime": {
    "Start": "2023-11-18T18:00:00",
    "End": "2023-11-18T23:00:00"
  },
  "Price": {
    "Entry": "200.-",
    "MinimumAge": 21,
    "DrinkPrices": {
      "Beer": 6,
      "Wine": 10,
      "Cocktail": 14
      "Shots": 5
    }
  }
```

![image](./img/Mini-Golf_Tournement_adventure_&_Party.png)

### n°8 - Mini-Golf Tournement

```json
{
  "Event": "Mini-Golf Tournement",
  "Description": "Join us for an evening of crazy Mini-Golf adventures and after party",
  "Type": "Competition and Disco",
  "Location": {
    "Name": "Rollers Mini-Golf Bar",
    "Address": "Rle des Templiers 4",
    "City": "Geneva",
    "State": "Geneva",
    "ZipCode": "1207",
    "Country": "Switzerland"
  },
  "DateTime": {
    "Start": "2023-11-18T18:00:00",
    "End": "2023-11-19T06:00:00"
  },
  "Price": {
    "Entry": "25.-",
    "MinimumAge": 18,
    "Tournement price entry per group of 2": "30.-"
    }
  }
```

### n°9 - Journée Révision

```json
{
  "event_id": 12345,
  "title": "Journée Révision",
  "description": "Venez réviser pour vos examens de la HEG.",

  "participants": {
    "attending": 8,
    "max_attendees": 30
  },

  "event_dates": [
    { "event_date": "2023-04-01T09:00:00Z" }
  ],

  "location": {
    "venue_name": "Campus Batelle",
    "address": "Rue de la Tambourine 17",
    "city": "Carouge",
    "postal_code": 1227,
    "state": "Geneva"
  },

  "price": 0
}
```
![image](img/Szymon_Revision.png)

### n°10 - Tournois Beer Pong

```json
{
  "event_id": 76214,
  "title": "Tournois Beer Pong",
  "description": "Venez tester vos skills en Beer Pong tous les vendredi du mois d'avril après les cours.",

  "participants": {
    "attending": 13,
    "max_attendees": 32
  },

  "event_dates": [
    { "event_date": "2023-04-07T18:00:00Z" },
    { "event_date": "2023-04-14T18:00:00Z" },
    { "event_date": "2023-04-21T18:00:00Z" },
    { "event_date": "2023-04-28T18:00:00Z" }
  ],

  "location": {
    "venue_name": "Campus Batelle",
    "address": "Rue de la Tambourine 17",
    "city": "Carouge",
    "postal_code": 1227,
    "state": "Geneva"
  },

  "price": 10
}
```
