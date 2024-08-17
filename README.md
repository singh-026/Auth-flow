# Auth-flow

The Diagram shows the Authorisation flow of an application using Email and Password , Phone no and otp , nad Biometrics.

1) Login Screen :-
   - The user can login using a combination of Email and passowrd , phone and otp or biometrics .
   - We can use react native firebase auth and react native biometrics for the same or we can integrate rest apis from our backend
   - Upon the successful response of each the user is logged into the Dashboard or in the case of failure he gets redirected back to the Login Screen with an error toast/ message.

2) Dashboard Screen :-
   - This is the landing page .
   - On this page we can hit an api on mount fetching the url to feed the video.
     
3) Full Screen Video Player :-
   - Not a screen specifically , just for representation. Needed to handle the fallbacks in case there is an error in playing the video on full screen.
   - In a normal case the video will just get to the full screen and in case of any fallbacks we can wrap it with Error Boundaries so that crashes can be avoided and user can try again.
