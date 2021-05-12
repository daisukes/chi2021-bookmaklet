<a href="javascript:(function(){$('.video-container').css('width','320px');return;})()">Make CHI2021 video 240p</a> - drag this bookmarklet into your bookmark toolbar - works well

<a href="javascript:(function(){$('.video-container').css('width','640px');return;})()">Make CHI2021 video 240P~480p</a> - drag this bookmarklet into your bookmark toolbar - this is a bit flaky on my environment @ Pittsburgh

For closed caption users: you can zoom in to the video but this may have problem with other functions like chats, etc...


--- Memo ---
- the script change .video-container div width
  - video script seems to be using the ideo container size not the video element size to determine the maximum size of the video with HLS (HTTP Live Stream)
- this makes also the caption element small
  - using scale css to enlarge the video may not affect to the video bitrate selection
  - however, this makes caption element too big - I could not find the way to fix this
