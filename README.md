![ga](http://mobbook.generalassemb.ly/ga_cog.png)

# wdi-10-chi

![miles and keiko](https://pbs.twimg.com/media/DMvjd56XcAAxrnc.jpg)

---

Created by: Jeff Krantz<br>
Adapted for wdi-10-chi by: Reuben Ayres<br>
Competencies: AJAX, jQuery, DOM manipulation

## Weather App

Use the [OpenWeather API](http://openweathermap.org/current) to fetch the weather from a certain zip code, and update the page to reflect the current weather. [Documentation](http://openweathermap.org/current)

### Requirements
- Ask the user to input the zip they would like to see the weather for. (Hint: use Prompt)

- Use ajax to send a request the OpenWeather API.
NOTE: Because the OpenWeather API is not an open API, every request must end with '&appid=[YOUR KEY]' (i.e. http://api.openweathermap.org/data/2.5/weather?zip=60614,us&appid=[YOURKEY]).  Use the key you registered for this morning.

- Use the response to display the current temperature in fahrenheit, the high and low temperate in fahrenheit, the current weather "description", and the name of the city that came back from the API.  Use the API documentation and digging around in the response object to figure out how to get that information.

- Spend a little time styling the app. You could make it look like the iPhone weather app. Or some similar kind of thing.

- You could make it show the forecast too (high, low, conditions?  and/or whatever else you like?), similar to other weather apps/sites.

- See if you can find the little icons for the current description and for the forecast description..  You'll likely need the API docs to help you match up the 'codes' and the images that go with those codes. 

![weather app](https://i.imgur.com/bN39xEv.png)

