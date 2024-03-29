# Recipes Search Demo
<p>Demo app for testing RestApi Calls.
A food recipe search app with retrofit, livedata and using android best practices.</p>
<p>The app is currently not being developed.</p>
<p>The UI was developed as far as enough for displaying the results.</p>
<br>

# Screenshots

![Category Selection](screens/screen1.png "Category Selection")
![Search](screens/screen2.png "Search function")
![List of recipes1](screens/screen3.png "List of searched recipes")
<br></br>
![List of recipes2](screens/screen5.png "List of searched recipes loading")
![Recipe details cached](screens/screen4.png "Recipe details")
![Recipe details no internet](screens/screen6.png "Recipe details of no cached recipe")
<br></br>
# Screenshots - Dark Mode

![List of recipes3](screens/screen8.png "Recipe List dark mode")
![Recipe details](screens/screen7.png "Recipe details dark mode")
  <br>
  <br>
  
# Libraries Used
  <p><b>Lifecycles</b>- Create a UI that automatically responds to lifecycle events.</p>
  <p><b>LiveData</b> - Build data objects that notify views when the underlying database changes.</p>
  <p><b>Room</b> - Caching the network data for offline use.</p> 
  <p><b>ViewModel</b> - Persist the data on configuration changes.</p>
  <p><b>Glide</b> - Image Loading.</p>
  <p><b>Retrofit</b> - Http Requests.</p>
  <p><b>Gson</b> - Convert Json objects.</p>
  <p><b>Circle Imageview</b> - Display images in a circle.</p>
  <p><b>RecyclerView </b> - Display list and handle clicks.</p>
  <br>
  
# Non-Goals
  <p>The focus of this project was on HTTP requests and caching the data for offline use using the MVVM pattern.</p>
  <p>The UI only was worked till the point were we could get and display the results from the requests.</p>
  <br>
  
# App architecture
  <p>The app was developed taking in account the best practices and recommended architecture from Google for building apps.</p>
  <p>It uses the repository pattern and the single source of truth. Each component depends only on the component one level below it. For example, activities depend only on a view model. The repository is the only class that depends on multiple other classes.</p>
  <div class="center" align="center">
    <img class="center" src="https://developer.android.com/topic/libraries/architecture/images/final-architecture.png" height="400">
  </div>
  <br>
  <br>
  <br>
  <br>
  <br>

### Disclaimer
###### Although the code was written by me, the current app was developed as part of a course on android architecture.</p>


