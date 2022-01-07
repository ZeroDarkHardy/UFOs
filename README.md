# UFOs

---

## Project Overview

The core of this project was to build a dynamic webpage that filters a large table of data based on user input.  The purpose of the site is to aggregate and display data regarding sightings of UFOs.

---

## Resources

- **Source Data:** [data.js](https://github.com/ZeroDarkHardy/UFOs/blob/main/static/js/data.js)
- **Software/Languages:** JavaScript, Visual Studio Code v1.63.2, BootStrap 4, HTML, CSS

---

## Results

### Deployed Web Application
The web application has been deployed through GitHub and can be accessed [HERE](https://zerodarkhardy.github.io/UFOs/).

Below is the basic layout of the index that displays when accessing the site.

![index_landing.png](https://github.com/ZeroDarkHardy/UFOs/blob/main/resources/index_landing.png)

### Filtering the Data

The user can filter the table results based on date, city, state, country, and shape (meaning the visual description of the sighting).  The filters can be reset by either refreshing the page or selecting the navigation bar at the top of the screen.  Multiple filters can be applied simultaneously, one at a time, or all at once. In the image below, the user has applied only one filter (by date).

![filter_by_date.png](https://github.com/ZeroDarkHardy/UFOs/blob/main/resources/filter_by_date.png)

To demonstrate individual functionality, here's an image of the table being filtered by city (Fresno), with no other filters:

![filter_by_city.png](https://github.com/ZeroDarkHardy/UFOs/blob/main/resources/filter_by_city.png)

To demonstrate functionality for multiple layered filters, the image below shows the table being filtered by state and shape (California, "Light"):

![filter_by_multi.png](https://github.com/ZeroDarkHardy/UFOs/blob/main/resources/filter_by_multi.png)

## Summary

- Unfortunately, this build has a few annoying limitations:
    - The search function is case sensitive while entering filters like state and city.  If the user doesn't leave their entry in lowercase, the filters won't produce any results at all.
    - Hitting "enter" while entering filter information will not execute the filter, but rather reset the page.

- Recommendations for future builds:
    - Add functionality to expand a search radius around an entered city.  It may interest users to know about sightings close by to specific sighting they've searched.
    - Add drop down menus for certain search filters.  If, for example, there are only two countries that appear in our data, it would be best to let the user select them from a drop down menu rather than forcing them to type the input. A similar drop down with a dynamic "calendar-style" menu for the date filter could add a degree of polish and user-friendliness.
    - Correct keyboard input so that "enter" will execute any filters that the user has entered.
    - A dynamic map window with pinned locations of sightings could help the user visualize the distribution of sightings.