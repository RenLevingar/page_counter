# page_counter
Description - This is a page view counter to count how many times the page has been viewed and rendered. 
Utilization - This should be the last thing implemented in every render as it is coded to appear at the bottom of a page. 
Color - To change the color go to the app.css, it is the color listed under the "counter" class
UseStrict - Make sure that the app doesn't render into a "UseStrict" react tag or else the counter will increment twice each time
Hooks - Both useEffect and useState were used and imported into the component
Leaving the Page - Even if the page is left the number will remain the same as it uses the browsers local storage instead of session storage
