Web-Technologies-COVID-19-Live-Stats-Responsive-Website-Project
Web Technologies Project

When the user enters the website, we will use a pulgin called 'geoPlugin', which is an API based on the IP Address of the user, returns the country code of the user. The country code is a two character universal code, which does not change, whereas any other thing for the country might change, for example, the language of the country might change. After fetching the country code, we are going to use a list of codes, named as the 'country_list' to get the details for that country. Then, we will send the country name to the API and then we will fetch all the details of the country.

We need to add a script to out code for the plugin to work. Then we will be using the function geoplugin_countryCode(); to return the country code of the user.
