# Week 7 Weekend Project: Itinerary Planner

Build an itinerary planner app - think tripit. 

Your app's users should be able to:

* Create an **Itinerary** with:
  * required fields:
    * an origin
    * a destination
    * a name
  * not required
    * a departure date
    * a return date

* Add **Destinations** to an **Itinerary** with:
  * required fields:
    * a location
    * a name
    * a date (must be between the itinerary start and end date)
   
* Add one or more **Companions** to the **Itinerary**
  * required fields:
    * first name
    * last name
    * email

* A **Companion** may be able to join one or many **Destinations**

* In order to create or join an **Itinerary**, one must be an authenticated **User**

* Only the creator of an **Itinerary** may delete or change the itinerary

* **Reviews**  (like comments) may be left on any entity in the application