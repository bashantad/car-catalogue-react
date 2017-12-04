### Car Catalogue App
We are going to build an app to browse a car catalog. The app should have a
primary navigation bar containing two items: Home and Search.

##### http://localhost:3000/
This is the homepage. It should display the car of the week (data provided).

##### http://localhost:3000/search
This is the search page containing two select boxes and a button. The button
will be initially disabled. The first select box contains car makes. The second
select box cascades from the first, displaying models based on the selected
make. On select of a model, the button becomes enabled and clicking it
takes the user to the details page.

##### http://localhost:3000/make/model/id
This is the details page for the selected car model. The id at the end of the
url is the model id that should be loaded.
Users should be able to access all pages via direct url or via app navigation.
You can find all the relevant json files here
We are looking for a react, react-router, redux spa implementation. Bonus
points for server side rendering and double bonus points for using a data
fetch framework.
Have fun!
