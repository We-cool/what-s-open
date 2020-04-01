Group Project - README 
===

# What's Open

## Table of Contents
1. [Overview](#Overview)
1. [Product Spec](#Product-Spec)
1. [Wireframes](#Wireframes)
2. [Schema](#Schema)

## Overview
### Description
[This app allows users to see what restaurants are open or delivering at anytime. The users can track their delivery, as well as see the statistics of the restaurant, and the wait time of their food.]

### App Evaluation
[Evaluation of your app across the following attributes]
- **Category: Food and Services**
- **Mobile: Android Pixle**
- **Story: User can see what restaurants are open and who is delivering**
- **Market: College Students and adults**
- **Habit: This app will be used quite often due to the high demand of food**
- **Scope: Huntsville,Al**

## Product Spec

### 1. User Stories (Required and Optional)

**Required Must-have Stories**

* [Login screen- User can login using google] -[x]
* [Users have to be able to see what restaraunts are open]
* [Users have to be able to see the customer traffic of the restaraunts]
* [Users have to see the price range of the restaraunt]

**Optional Nice-to-have Stories**

* [User can order delivery and takeout through app]
* [User can contact the delivery driver in case of location change]


### 2. Screen Archetypes

* [Login]
   * [The user logs in with google account]
 
* [Maps]
   * [Tells user what restaraunts are open and delivering]

* [Details]
     * [Tells users the prices of food]

  

### 3. Navigation

**Tab Navigation** (Tab to Screen)

* [Home]
* [Google Maps]
* [Restaraunt Information]

**Flow Navigation** (Screen to Screen)

* [Login Screen]
   * [Home]
* [Google Maps w/Search bar ]
   * [A map withe radius of Huntsville,Al and the surrounding restarunts]
* [Stream Screen]
    * [None, but future version will include a zoom feature to see restaraunts that are not listed]

## Wireframes
[Add picture of your hand sketched wireframes in this section]
<img src="YOUR_WIREFRAME_IMAGE_URL" width=600![](https://i.imgur.com/LIijcDu.jpg)
>

### [BONUS] Digital Wireframes & Mockups
[https://www.figma.com/file/HY7SR9KsFjGeOyPtRlcI88/What-s-Open?node-id=2%3A12](https://)

### [BONUS] Interactive Prototype
[https://www.figma.com/file/HY7SR9KsFjGeOyPtRlcI88/What-s-Open?node-id=2%3A12](https://)


## Schema 



### Models
[Restaraunt]
|   Property   |   Type   | Description |
|:------------:|:--------:|:-----------:|
|    Image     |   File   |    Text     |
|   Address    |  String  |    Text     |
| Phone Number |  String  |    Text     |
|   Cruisine   |  String  |    Text     |
|     Name     |  String  |    Text     |
|  Open Time   | DateTime |    Text     |
|    Price     |   Int    |    Text     |
| Closing Time | DateTime |    Text     |

[User]


| Property  |  Type  | Description |
|:---------:|:------:|:-----------:|
| UniqueID  | String |    Text     |
|   Email   | String |    Text     |
| Password  | String |    Text     |
| Favorites |  List  |    Text     |


### Networking
@jbiggs@bulldogs.aamu.edu
- [Data Models]
- [OPTIONAL: List endpoints if using existing API such as Yelp]