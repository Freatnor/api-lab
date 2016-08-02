##### Task #1: Find the api call that allows you to search for all images of "cats".

API Call: https://api.flickr.com/services/rest/?method=flickr.photos.search&api_key=[API key]&text=cat&format=json&nojsoncallback=1

##### Task #2: Find the api call that allows you to search for all images from "Charlotte, North Carolina.

API Call: https://api.flickr.com/services/rest/?method=flickr.photos.search&api_key=[API key]&format=json&nojsoncallback=1&place_id=KtHrHAVTUb1F.npO

##### Task #3: Get all of the comments for any photo.

API Call: https://api.flickr.com/services/rest/?method=flickr.photos.comments.getList&api_key=[API key]&format=json&nojsoncallback=1&photo_id=[photo id]

##### Task #4: Search for a list of all the photos in your current latitude and longitude.
API Call: https://api.flickr.com/services/rest/?method=flickr.photos.search&api_key=[API key]&format=json&nojsoncallback=1&lat=[currentLat]&long=[currentLong]
