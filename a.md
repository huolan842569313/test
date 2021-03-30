# CS126 WAFFLES Coursework Report [1234567]


## CustomerStore
### Overview
Data structures such as string arrays and collections are used, string arrays are used to return data, and ArrayList is used to manipulate data easily.13/5000  Use comparators to sort objects


### Space Complexity

Store         | Worst Case | Description
------------- | ---------- | -----------
CustomerStore | O(n)       | I have used a single `ArrayList` to store customers. <br>Where `n` is total customers added.

### Time Complexity


Method                           | Average Case     | Description
-------------------------------- | ---------------- | -----------
addCustomer(Customer c)          | O(1)             | Array add is constant time
addCustomer(Customer[] c)        | O(n)             | Add all customers <br>`n` is the length of the input array
getCustomer(Long id)             | O(n)             | Linear search <br>`n` is total customers in the store
getCustomers()                   | O(n)           | Use a comparator to compare
getCustomers(Customer[] c)       | O(n)           | Use a comparator to compare
getCustomersByName()             | O(n)           | Use a comparator to compare
getCustomersByName(Customer[] c) | -                |  all customers <br>`n` is the length of the input array
getCustomersContaining(String s) | O(a + n*(a + b)) | Searches all customers <br>`a` is the average time it takes to convert accents <br>`n` is total customers <br>`b` is average string search time

<!-- Don't delete these <div>s! -->
<!-- And note the spacing, do not change -->
<!-- This is used to get a page break when we convert your report to PDF to read when marking -->
<!-- It is not the end of the world if you do remove, it just makes it harder to read if you do -->
<!-- On things you can remove though, you should remember to remove these comments -->
<div style="page-break-after: always;"></div>

## FavouriteStore
### Overview
* I have used `...` to store favourites ... 
* I used `...` to sort ... 
* To get favourites by ... 
* To get ... 
* To get top ... 

### Space Complexity
Store          | Worst Case | Description
-------------- | ---------- | -----------
FavouriteStore | O(n)     | I have used a single `ArrayList` to store customers. <br>Where `n` is total customers added.

### Time Complexity
Method                                                          | Average Case     | Description
--------------------------------------------------------------- | ---------------- | -----------
addFavourite(Favourite f)                                       | O(1)           | Array add is constant time
addFavourite(Favourite[] f)                                     | O(n)           | Add all favourites <br>`n` is the length of the input array
getFavourite(Long id)                                           | O(n)           | Linear search <br>`n` is total favourites in the store
getFavourites()                                                 | O(n)           |  Use a comparator to compare
getFavourites(Favourite[] f)                                    | O(n)           | Use a comparator to compare
getFavouritesByCustomerID(Long id)                              | O(n)           | Linear search <br>`n` is total favourites in the store
getFavouritesByRestaurantID(Long id)                            | O(n)           | is Use a comparator to compare
getCommonFavouriteRestaurants(<br>&emsp; Long id1, Long id2)    | O(n)           | The method is to use only one for loop
getMissingFavouriteRestaurants(<br>&emsp; Long id1, Long id2)   | O(n)           | The method is to use only one for loop
getNotCommonFavouriteRestaurants(<br>&emsp; Long id1, Long id2) | O(n)           | The method is to use only one for loop
getTopCustomersByFavouriteCount()                               | O(n)           | The method is to use only one for loop
getTopRestaurantsByFavouriteCount()                             | O(n)           | The method is to use only one for loop

<div style="page-break-after: always;"></div>
## RestaurantStore
### Overview
* I have used `...` to store restaurants ... 
* I used `...` to sort ... 

### Space Complexity
Store           | Worst Case | Description
--------------- | ---------- | -----------
RestaurantStore | O(n)     | I have used a single `ArrayList` to store customers. <br>Where `n` is total customers added.

### Time Complexity
Method                                                                        | Average Case     | Description
----------------------------------------------------------------------------- | ---------------- | -----------
addRestaurant(Restaurant r)                                                   | O(1)           | Array add is constant time
addRestaurant(Restaurant[] r)                                                 | O(n)           | Add all restaurants <br>`n` is the length of the input array
getRestaurant(Long id)                                                        | O(n)           | Linear search <br>`n` is total restaurants in the store
getRestaurants()                                                              | O(n)           | Use a comparator to compare
getRestaurants(Restaurant[] r)                                                | O(n)           | Use a comparator to compare
getRestaurantsByName()                                                        | O(n)           | Linear search <br>`n` is total favourites in the store
getRestaurantsByDateEstablished()                                             | On.)           | The method is to use only one for loop
getRestaurantsByDateEstablished(<br>&emsp; Restaurant[] r)                    | O(n)          | The method is to use only one for loop
getRestaurantsByWarwickStars()                                                | O(n)          | The method is to use only one for loop
getRestaurantsByRating(Restaurant[] r)                                        | O(n)           | The method is to use only one for loop
getRestaurantsByDistanceFrom(<br>&emsp; float lat, float lon)                 | O(n)           | The method is to use only one for loop
getRestaurantsByDistanceFrom(<br>&emsp; Restaurant[] r, float lat, float lon) | O(n)           | The method is to use only one for loop
getRestaurantsContaining(String s)                                            | O(n)           | The method is to use only one for loop

<div style="page-break-after: always;"></div>

## ReviewStore
### Overview
* I have used `...` to store reviews ... 
* I used `...` to sort ... 
* To get ... 
* To get top ... 

### Space Complexity
Store           | Worst Case | Description
--------------- | ---------- | -----------
ReviewStore     | O(...)     | I have used `...` ... <br>Where `...` is ...

### Time Complexity
Method                                     | Average Case     | Description
------------------------------------------ | ---------------- | -----------
addReview(Review r)                        | O(1)           | array add is constant time
addReview(Review[] r)                      | O(n)           | add all Reviews <br>`n` is the length of the input array
getReview(Long id)                         | O(n)           |  Linear search <br>`n` is total Reviews in the store
getReviews()                               | O(n)           | use a comparator to compare
getReviews(Review[] r)                     | O(n)           | use a comparator to compare
getReviewsByDate()                         | O(n)           | use a comparator to compare
getReviewsByRating()                       | O(n)           | The method is to use only one for loop
getReviewsByRestaurantID(Long id)          | O(n)           | The method is to use only one for loop
getReviewsByCustomerID(Long id)            | O(n)           | The method is to use only one for loop
getAverageCustomerReviewRating(Long id)    | O(n)           | use a comparator to compare
getAverageRestaurantReviewRating(Long id)  | O(n)           | use a comparator to compare
getCustomerReviewHistogramCount(Long id)   | O(n)           | use a comparator to compare
getRestaurantReviewHistogramCount(Long id) | O(n)           | use a comparator to compare
getTopCustomersByReviewCount()             | O(n)           | The method is to use only one for loop
getTopRestaurantsByReviewCount()           | O(n)           | The method is to use only one for loop
getTopRatedRestaurants()                   | O(n)           | The method is to use only one for loop
getTopKeywordsForRestaurant(Long id)       | O(n)           | The method is to use only one for loop
getReviewsContaining(String s)             | O(n)           | The method is to use only one for loop

<div style="page-break-after: always;"></div>

## Util
### Overview
* **ConvertToPlace** 
    * ...
* **DataChecker**
    * ...
* **HaversineDistanceCalculator (HaversineDC)**
    * ...
* **KeywordChecker**
    * ...
* **StringFormatter**
    * ...

### Space Complexity
Util               | Worst Case | Description
-------------------| ---------- | -----------
ConvertToPlace     | O(n)     | I have used a single `Array` to store customers. <br>Where `n` is total customers added.
DataChecker        | O(n)     | have used a single `ArrayList` to store customers. <br>Where `n` is total customers added.
HaversineDC        | O(1)     | Array add is constant time
KeywordChecker     | O(1)     | Array add is constant time
StringFormatter    | O(n)     | have used a single `Map` to store customers. <br>Where `n` is total customers added.

### Time Complexity
Util              | Method                                                                             | Average Case     | Description
----------------- | ---------------------------------------------------------------------------------- | ---------------- | -----------
ConvertToPlace    | convert(float lat, float lon)                                                      | O(n)           | The method is to use only one for loop
DataChecker       | extractTrueID(String[] repeatedID)                                                 | O(n)           | The method is to use only one for loop
DataChecker       | isValid(Long id)                                                                   | O(n)           | The method is to use only one for loop
DataChecker       | isValid(Customer customer)                                                         | O(1)           | customer  is constant time
DataChecker       | isValid(Favourite favourite)                                                       | O(1)           | favourite  is constant time
DataChecker       | isValid(Restaurant restaurant)                                                     | O(1)           | restaurant  is constant time
DataChecker       | isValid(Review review)                                                             | O(1)           | Review  is constant time
HaversineDC       | inKilometres(<br>&emsp; float lat1, float lon1, <br>&emsp; float lat2, float lon2) | O(1)          |Method is constant time
HaversineDC       | inMiles(<br>&emsp; float lat1, float lon1, <br>&emsp; float lat2, float lon2)      | O(1)           | Method is constant time
KeywordChecker    | isAKeyword(String s)                                                               | O(n)           | The method is to use only one for loop
StringFormatter   | convertAccentsFaster(String s)                                                     | O(n)           | The method is to use only one for loop
