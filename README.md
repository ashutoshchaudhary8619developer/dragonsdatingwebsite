# dragons-dating
Very simple implementation of the dating API of "Dragons of Mugloar"

API description: http://www.dragonsofmugloar.com/dating/api

#Dating API

##Create a matchmaking web app using drawings provided for help

First the user gets to choose if they want to see boy-dragons or girl-dragons
After the choice is made, the user sees different profiles (picture, description) and gets to choose if they are interested or not
The profiles are provided for you through the API
The “matches” (both parties being interested) also need to be visible for the user
If you are happy with your creation do the following:


##Get random profile
```
GET http://www.dragonsofmugloar.com/dating/api/profile/random?gender=girl
```
Will get random profile of specified gender (boy/girl). If gender is unspecified it will provide random profile of any gender.

##Get profile by ID
```
GET http://www.dragonsofmugloar.com/dating/api/profile/125124
```

Will get profile by ID specified.
