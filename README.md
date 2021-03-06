Overview of the project:

We were tasked with creating a searchable browser based database on UFO sightings. 
After creating this website, we were asked to allow for additional filders for other fields.

Results

The website has several filter options on the left; Date, City, State, Country and Shape (of the UFO). 
After the user fills out the search field and hits enter, the results are displayed to the right.
![ufo](https://user-images.githubusercontent.com/88519111/157389703-742e42b5-8e8e-4ea6-ab2f-ff9f397fb076.PNG)

![results](https://user-images.githubusercontent.com/88519111/157389720-705c1998-5e16-4d3a-929c-421d3e37c3f5.PNG)
Summary

It's worth noting that the searches are case sensitive. In the state field, "ca" will return results, "CA" will not.
In the shape field, "triangle" will return results, "Triangle" will not. It would be nice to have it return results 
regardless of case. 

We notice that the data could be cleaner. Some comments are entered as questions, where the person supplying that
information thought it was a question box. Also, "light" is an entry for shape, it seems that anything can be put
into that field. There are two solutions. Firstly, cleaning the data. Drop data where it doesn't make sense.
Secondly, instead of "shape" we could make it appearence and have a dropdown of possible options, allow the user to
select or enter in another filter. 
