**User Story:**

As a user searching for properties on https://www.fazwaz.com/property-for-sale/thailand,  
I want to access the search page on both desktop and mobile devices,  
So that I can conveniently search for properties regardless of the device I am using.

Additionally, I want to see a prominently displayed search box on the search page,  
And receive autocomplete suggestions as I type in the search box,  
To facilitate efficient property searches based on criteria such as province, district, sub-district, or project.

Once I have entered search criteria and received search results,
I should be able to filter the results by price range, number of bedrooms, or specific features like Private Pool, Private Gym, or Beachfront.  
Furthermore, I should have the option to sort search results by newest listing, lowest price, or biggest price reduction,  
And be able to view 30 properties per page with a corresponding plot displayed on the map.

I expect to see detailed information including 5 images, listing title, listing price, price per square meter, description, plot size, property type for each property item on search result.

Moreover, clicking on a property item should open the property detail page in a new tab,  
Allowing me to easily access more information about the property without losing my place in the search results.



**Given** the user is on the search page,  
**When** the user accesses the page from either a desktop or a mobile device,  
**Then** the page should be responsive and accessible on both platforms

**Given** the user is on the search page,  
**When** the user views the page,  
**Then** they should see a prominently displayed search box at the top of the page.

**Given** the user is on the search page,  
**When** the user begins typing in the search box,  
**Then** the system should provide autocomplete suggestions based on the entered characters

**Given** the user is on the search page,  
**When** the user enters search criteria such as province, district, sub-district, or project into the search box,  
**Then** they should be able to search for properties based on the entered criteria.

**Given** the user is on the search page with search results displayed,  
**When** the user applies a filter by price range,  
**Then** the search results should be filtered accordingly.

**Given** the user is on the search page with search results displayed,  
**When** the user applies a filter by the number of bedrooms,  
**Then** the search results should be filtered accordingly.

**Given** the user is on the search page with search results displayed,  
**When** the user applies a filter by specific features such as Private Pool, Private Gym, or Beachfront,  
**Then** the search results should be filtered accordingly.

**Given** the user is on the search page with search results displayed,  
**When** the user selects an option to sort search results by newest listing, lowest price, or biggest price reduction,  
**Then** the search results should be sorted accordingly.

**Given** the user is on the search page with search results displayed,  
**When** the user scrolls through the page,  
**Then** they should see 30 properties displayed per page on the left side, with a corresponding plot displayed on the map on the right side.

**Given** the user is on search results page,  
**When** the user views on a property item,  
**Then** they should see 5 images, the listing title, listing price, price per square meter, description, plot size, property type, and features for the selected property.

**Given** the user clicks on a property item,  
**When** they click on it,  
**Then** the property detail page should open in a new tab.
