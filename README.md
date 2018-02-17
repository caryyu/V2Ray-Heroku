# V2Ray Heroku [![Travis Build Status](https://travis-ci.org/JDsnyke/V2Ray-Heroku.svg?branch=core-3.5)](https://travis-ci.org/JDsnyke/V2Ray-Heroku)
Heroku deployable V2Ray proxy :busts_in_silhouette:

---

## Table of Contents

[Information](#information)

[Setup](#setup)

- [Part 01](#part-01)
- [Part 02](#part-02)
- [Part 03](#part-03)

[Credit](#credit)

[License](#license)

---

## Information

Original Repo - [Here](https://github.com/onplus/v2hero)

Original Readme - [Here](https://github.com/JDsnyke/V2Ray-Heroku/blob/core-3.5/ORIGINAL-README.md)

## Setup

### Part 01

1. Sign up for a [Heroku](https://heroku.com/) and [Github](https://github.com/) account.

2. Click and Deploy the Go app 

   [![Deploy](https://www.herokucdn.com/deploy/button.png)](https://heroku.com/deploy?template=https://github.com/JDsnyke/Heroku-Go-Get-Started)

3. Set ```app name``` and ```region```

4. Leave all other Config Variables except ```UDID``` the same

   * Generate UDID [here](https://www.uuidgenerator.net/) and paste it into the given box
   
5. Confirm and finalize Heroku app

### Part 02

1. Fork this Repo (if you haven't already)

2. Go to ```https://travis-ci.org/profile``` and signup using your Github account

3. Activate the repo you forked by ticking the relevent box (as seen below) 

![Credit to https://github.com/onplus](https://user-images.githubusercontent.com/31188782/33354036-c14d920a-d4eb-11e7-99b4-d7d8816bbef6.png)

4. Click the Cog Icon next to the tick box to access the repo's Travis settings

5. Create the given 'Enviromental Variables'

   * HEROKU_APIKEY - get your specific key [Here](https://dashboard.heroku.com/account)
   
   * HEROKU_APPNAME - heroku app name (without .herokuapp.com)
   
   * HEROKU_EMAIL - email address you used for your heroku account
   
![Credit to https://github.com/onplus](https://user-images.githubusercontent.com/31188782/33432133-ca7ecf7a-d611-11e7-96de-8269712b40f1.png)   

![Credit to https://github.com/onplus](https://user-images.githubusercontent.com/31188782/33354723-2e10d2e6-d4ef-11e7-8d6c-70be5b5eee2a.png)

6. Return to Github and manually edit your Readme file for the changes to register on Travis

   * You can also try restarting the build if you want
   
### Part 03

## Credit

Complete credit to [Onplus](https://github.com/onplus) and his [Repo](https://github.com/onplus/v2hero). Thank you for your hard work!

## License

Uses the [MIT](https://github.com/JDsnyke/V2Ray-Heroku/blob/core-3.5/LICENSE) license.
