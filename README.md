# Share your knowledge with us and [Exzeo](http://www.exzeosoftware.com/) will learn from it

#### Use any IDE you prefer or code from the bare skeleton (if you have enough time :-) )
#####Our choices
* Eclipse - [https://www.eclipse.org/downloads/](https://www.eclipse.org/downloads/)
* Android Studio - [https://developer.android.com/sdk/installing/studio.html](https://developer.android.com/sdk/installing/studio.html)
* Eclipse ADT - [https://developer.android.com/sdk/index.html](https://developer.android.com/sdk/index.html)

#### A piece of cake to warm you up
* Design a login screen that will support portrait and landscape mode both
* Mobile devices will only support landscape mode
* Tab devices will be supporting landscape and portrait mode both
* If a user hits the login button, a login service will be called and a progress bar will be shown
* Correct/Incorrect Login details are shared in the json format.

#### The Big Picture of Design and Code (next Steps)
* There are two different views for landscape and portrait
* The views will change based on your device orientation
* The login service will not be called twice or thrice or n number of times if, a service is running
  and user rotates the device from portrait to landscape and vice versa

#### Need Help? 
#####We are always ready to share the logic or we can cheat from you ha.. ha.. ha..!
* Don't forget to enable lint for the optimised code
* json folder provided the structure for the login service
  login_success.json 
  login_failure.json
* To simulate the login service you can put the json files in raw folder
* To simulate the delay in the network put wait logic within the thread for some seconds 
* If the username and password matches with details from login_success.json, user will be redirected to the welcome screen
* You can use the login_failure.json if no user exists or server returns the result but not the expected
* Don't update UI from the background code

#### Add-on if time permits or you are eager to show your passion
* Use relative layout for multiple screen handling
* Use retrofit or OkHttp for Login service

#####Resources
* [http://developer.android.com/index.html](http://developer.android.com/index.html)
* [http://square.github.io/okhttp/](http://square.github.io/okhttp/)
* [http://square.github.io/retrofit/](http://square.github.io/retrofit/)
