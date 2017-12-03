## Creation:
* Create new folder
* express --pug
* npm install mongoose --save
* npm install dotenv --save 
  * check this & mongoose in package.json
* put darksky api key into the .env folder
* npm install request --save

## Heroku Push
* git init
* **git add .**
* **git commit -m "insert message here"**
* heroku create
* git remote -v 
  * Make sure it has a name
* **git push heroku master**
 
*If you need to update something and push again, only follow the bolded steps.*


## Angular
* WeatherCtrl.$inject = ['$scope', 'SelectedData', 'DarkskyWeather'];
  * Selected data stays the same.  Found in app_client/common/services
  * *Must* have services in app.
  * *Need* selectedData if clicking and selecting will be a thing.
  * First call is what the method is known as externally.  Second call is what the method is known as internally.
    * .service('ExternalName', 'InternalName');
      * ^in the darkskyWeather.service.json with the actual names
  * selectedData.factory.js
    * can change selectedDepartureICAO to what is personally necessary
  * The order of things in the index.html is **super important** 
    * *Inject* use these things in this order
  * What you call controller as 'vm' must put var vm = this; in the weather.controller.js
    * KEEP THE SELECTED DATA STUFF
            
## In Other News
* If the weather is finished by Monday: **_NO ATTENDANCE CHECKER_**
* Our personal final project [TogetherAlone] can look **nothing** like his Airplane App.