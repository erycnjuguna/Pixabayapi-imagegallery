# Pixabayapi-imagegallery
Today we will be creating an image gallery and fetching data using pixabay api

### Styling
For the styling we will be using bootstrap i just didn't focus much on styling on this tutorial. I did though such for a customized bootsrap css on bootswatch.com.They got some really cool css to choose from

### HTML Layout
So about the HTML5 bit just did a bit of layout with some little css class names but you can use the your own customized layout but make sure you name the items with their id correctly

### Jquery
First i included [jquery cdn](https://code.jquery.com/jquery-3.5.1.min.js) and [Axios cdn](https://cdnjs.cloudflare.com/ajax/libs/axios/0.20.0/axios.min.js)

Then i created an event listener for the form submition and calling a function to get the images

To get images from the pixabay one is required get an apikey from their site Login from [this link](https://pixabay.com/api/) Then Visit [here](https://pixabay.com/api/docs/) to get your apikey finally scroll to the **parameters** section where you will find your **API KEY**
  
Then send an axios request to https://pixabay.com/api/?key=YOURAPIKEY&q=SEARCHTEXT&image_type=photo where searchtext is the value from the search box and key is your api key.this will return an array of objects use jquery to set data into your HTML  
