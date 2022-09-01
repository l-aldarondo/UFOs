# UFOs
Creating a dynamic web page using HTML, CSS, Bootstrap and JavaScript.

## Background
### Overview
This project consists of one technical analysis deliverable and a written report:

- Deliverable 1: Filter UFO sightings on multiple criteria

- Deliverable 2: A written report on the UFO analysis (README.md)

### Purpose
To provide an in-depth analysis of UFO sightings by allowing users to filter for multiple criteria at the same time. In addition to the date, we added table filters for the city, state, country, and shape.

## Methodology
Using JavaScript and HTML, you’ll modify the code in your index.html file to create more table filters. In addition to the date filter you created in this module, you’ll add filters for the city, state, country, and shape, as shown in the following image:
Using JavaScript, you’ll replace the handleClick() function in your app.js file with a new function that saves the element, value, and id of the filter that was changed. Then, you’ll create a new function to loop through the dataset and keep only the results that match the search criteria. The webpage will be updated with the search criteria after pressing "Enter".

## Resources
 
Data source:
- (1) app.js, (2) index.html, (3) data.js
 
Software:
- Visual Studio Code 1.68.1, HTML, CSS, Bootstrap and JavaScript
 
<br/>

### Results

#### June summary statistics:

Using JavaScript and HTML, we re-factored the code of our index.html file to create more table filters. Now the client would be able to filter not only be date, but by city, state, country, and shape, as shown in Figure (a). Then the webpage will be updated with the search criteria after pressing "Enter".

<br/>

(a) ![webpage_multiple filters](./static/images/webpage_multiple%20filters.png)

<sub> Figure (a) Filter UFO sightings on multiple criteria

<br/>

This deployed webpage has 5 dynamic filter that our client can interact with. The filters can be used independently from each other or in any combination to filter the table for the desire data output. For our demostration we will filter first by date to show how the webapp works with one filter at a time, as shown in Figure (b).

(b)![filter_by_date](./static/images/filter_by_date.png)

<sub> Figure (b) Filtered by Date.

In order to demostrate to the client how they can combine filters, we filtered the table by date and then by combining with all the different filters availabels in the page, as shown in Figure (c - f).

(c)![filter_by_city](./static/images/filter_by_city.png)

<sub> Figure (c) Filtered by Date and City

(d)![filter_by_State](./static/images/filter_by_state.png)

<sub> Figure (d) Filtered by Date and State.

(e)![filter_by_Country](./static/images/filter_by_country.png)

<sub> Figure (e) Filtered by Date and Country.

(f)![filter_by_Shape](./static/images/filter_by_shape.png)
 
<sub> Figure (f) Filtered by Date and Shape

<br/>


## Summary
### 

- For this project we were able to create a dynamic webpage that provided the client an effective way to filter the table with multiple criterias based on theire inputs. In order to let the client to try and feel the app we deployed the webpage using GitHub pages:

     - [link to deployed webpage](https://l-aldarondo.github.io/UFOs/)

- One drawback of this page is that the user interaction with the page is limited to the filters. The page dosen't provide a way to provide feedback, help section or FAQ. In addition the client needs to manually clear the filters to reset the page.

- For future development we would consider the following:
    - Adding a way for the user to clear all the filters at once.
    - Adding a way to filter by keyword on the entire webpage.
    - Adding a FAQ or help sections with links and some information on how to use the page.

<br/>

## References

[Markdown](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)
 
[Bootstap Grid system](https://getbootstrap.com/docs/3.3/examples/grid/)
 
[Bootstrap CSS](https://getbootstrap.com/docs/3.3/css/)



