# FAKE NEWS FILTER

# Contents:
* [About Fake news](#About-Fake-news)
* [Technology used](#Technology-used)
* [Instructions for use](#Instructions-for-use)
    * [Application launch interface](#Application-launch-interface)
    * [Login interface](#Login-interface)
    * [Language change interface](#Language-change-interface)
    * [Theme interface](#Theme-interface)
    * [Interface to read news when not logged in](#Interface-to-read-news-when-not-logged-in)
    * [Theme selection interface](#Theme-selection-interface)
    * [Home page interface to read news](#Home-page-interface-to-read-news)
    * [Story interface](#Story-interface)
    * [News reading interface](#News-reading-interface)
    * [Search interface](#Search-interface)
    * [Categorized news interface](#Categorized-news-interface)
    * [News community interface](#News-community-interface)
    * [Settings interface and personal page](#Settings-interface-and-personal-page)
## About Fake news
```
+ Fake news is built by us to make it accessible to readers
accurate and verified information from official sources
as well as help readers can stay away from fake news that adversely affect society.

+ Fake news uses Flutter technology to build a cross-platform app that can be used on Android and iOS
flexibly and easily. As for the database, we use Entity framework and SQL server to build the database system.
The information processing part we use ASP .net core 6 and MVC model.
We also built an admin website so that admin can manage the information on it.
Currently the application has been deployed to windows server 2019 and will soon be deployed to google play.
```

## Technology used
```
+ Database:
    - SQL server.
    - Entity framework.
+ Server:
    - ASP .net core.
    - MVC.
+ Mobile app:
    - flutter.
+ Web admin:
    - ReactJS.
```

## Instructions for use
### Application launch interface
<p align="center">
  <img src="https://github.com/xuanthanh2609/docs_fakenewsfilter/blob/main/media/pic1.png" width="200" height="400" />
</p>
<p align="center">
    
   + Application launch interface.
        - When you log in, you will see the system icon and say hello.

</p>

___
### Login interface
<p align="center">
  <img src="https://github.com/xuanthanh2609/docs_fakenewsfilter/blob/main/media/pic2.png" width="200" height="400" />
</p>
<p align="center">
    
   + User can login with registered account, facebook and google account.
        - When logging in for the first time, the person must register the information, the information will be saved.
        - When logging in with a google or facebook account that previously had an account, you will not need to re-enter your information.
        - When exiting the application to the main screen will maintain login, no need to log in again.
        - System language and news language can be customized at the top right.
        - Choose to agree to the terms of service to use the application.
</p>

___
### Language change interface
<p align="center">
  <img src="https://github.com/xuanthanh2609/docs_fakenewsfilter/blob/main/media/pic3.png" width="200" height="400" />
</p>
<p align="center">
    
   + Language change interface (application language, news reading language).
        - Can customize system language and news language (English, Vietnamese).
        - The system default is English.
</p>

___
### Theme interface
<p align="center">
  <img src="https://github.com/xuanthanh2609/docs_fakenewsfilter/blob/main/media/pic4.png" width="200" height="400" />
</p>
<p align="center">
    
   + Theme interface.
        - There are many themes for users to choose, can choose many themes.
        - Users can see the topics in the language they have chosen, when they press the "Discover" button, they will go to the login page.
        - First time login, user must choose at least 4 different themes.
        - Users can also customize the system language here.
</p>

___
### Interface to read news when not logged in
<p align="center">
  <img src="https://github.com/xuanthanh2609/docs_fakenewsfilter/blob/main/media/pic5.png" width="200" height="400" />
</p>
<p align="center">
    
   + The interface to read the news first when not logged in.
        - Users can view the latest news of the system.
        - The news users see when they are not logged in are the latest and hottest news of the day on many different topics.
</p>

___
### Theme selection interface
<p align="center">
  <img src="https://github.com/xuanthanh2609/docs_fakenewsfilter/blob/main/media/pic6.png" width="200" height="400" />
</p>
<p align="center">
    
   + When logging in, users are required to choose at least 4 topics to be able to log in and read news.
</p>

___
### Home page interface to read news
<p align="center">
  <img src="https://github.com/xuanthanh2609/docs_fakenewsfilter/blob/main/media/pic7.png" width="200" height="400" />
</p>
<p align="center">
    
   + Home page interface to read news
    
        - Once logged in, users can read the news and vote whether it's reliable or not.
        - Users can follow their favorite topics and view news stories here.
        - Users can see the notifications in the bell on the top right of the homepage.
</p>

___
### Story interface
<p align="center">
  <img src="https://github.com/xuanthanh2609/docs_fakenewsfilter/blob/main/media/pic8.png" width="200" height="400" />
</p>
<p align="center">
    
   + Story interface (almost like stories on facebook, instagram).
        - Can watch Story of breaking news in 24 hours.
</p>

___
### News reading interface
<p align="center">
  <img src="https://github.com/xuanthanh2609/docs_fakenewsfilter/blob/main/media/pic9.png" width="200" height="400" />
</p>
<p align="center">
    
   + News reading interface
    
        - Users can read, choose news reliability, share news,…
        - Users can comment on that news.
</p>

___
### Search interface
<p align="center">
  <img src="https://github.com/xuanthanh2609/docs_fakenewsfilter/blob/main/media/pic10.png" width="200" height="400" />
</p>
<p align="center">
    
   + Search interface.
        - User can search by news name, news content, desc.
        
</p>

___
### Categorized news interface
<p align="center">
  <img src="https://github.com/xuanthanh2609/docs_fakenewsfilter/blob/main/media/pic11.png" width="200" height="400" />
</p>
<p align="center">
    
   + Categorized news interface.
        - The censored news will be displayed here.
        - Information that is confirmed to be correct will appear in the True News box.
        - Information that is confirmed to be false will appear in the Fake News box.
        - Everyone can read the announcement here by selecting the bell on the right package at the top of the page.
</p>

___
### News community interface
<p align="center">
  <img src="https://github.com/xuanthanh2609/docs_fakenewsfilter/blob/main/media/pic12.png" width="200" height="400" />
</p>
<p align="center">
    
   + News community interface.
        - Users can contribute news to the system, admin will censor and post it on the system if the news is reasonable.
        - Users can find news contributed by other users here.
        - Here will show the number of posts contributed by the user.
        - Users can see detailed instructions in the instruction view box.
</p>

___
### Settings interface and personal page
<p align="center">
  <img src="https://github.com/xuanthanh2609/docs_fakenewsfilter/blob/main/media/pic13.png" width="200" height="400" />
</p>
<p align="center">
    
   + Settings interface, personal page.
        - Edit user's personal information here.
        - User can customize system language and news language here.
        - User can change followed topics.
        - Users can connect other social networks with personal accounts.
        - Users can view other information about FNF.
        - Users can rate the application quality.
        - If users have difficulty using the system, they can use the system's help feature.
</p>

___
### thanks for reading. :)
###### Create by LXThanh
