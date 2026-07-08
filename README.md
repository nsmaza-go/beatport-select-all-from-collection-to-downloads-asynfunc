# beatport-select-all-from-collections-to-downloads-asynfunc
As a Beatport customer, I had puchased songs from them and was able to add all songs directly after
purchase into the downloads page so that I could then download the songs. I ended up mistakenly 
deleting those files from my computer and found myself having to select each song from my downloads
one by one. When you have 10 or 20 songs that may be fine, but I had over 150 songs and if you made an 
error on one page it would have you start from the beginning again. I decided to do something about it 
and created this self-invoking asyn function which goes through each page of your collection and 
automatically adds them to your downloads. Once it reaches the final page and that page does not 
change, it knows it is done and your function ceases to continue.
