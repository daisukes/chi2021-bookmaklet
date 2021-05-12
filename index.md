<a href="javascript:(function(){$('.video-container').css('width','320px');return;})()">Make CHI2021 video 240p</a> - drag this bookmarklet into your bookmark toolbar - just make the video small

---

<a href="javascript:(function(){if(document.FIXED){return;}document.FIXED=true;var sx=320;var sy=200;var k='.video-container';var w=$(k).width();var h=$(k).height();var cw=$('.chat-box').width();$(k).css('width',sx+'px').css('margin', '0px '+(w-sx)+'px '+(h-sy)+'px 0px').css('display','inilne');$('video').css('scale',''+(w/sx)).css('transform-origin','left top');$('.vjs-text-track-display').width(w).height(h);$('.chat-box').width(cw);$('.vjs-control-bar').width(w).css('top',h+'px');return;})()">Make CHI2021 video 240p</a> - drag this bookmarklet into your bookmark toolbar - keep the video size (don't work with resizing window)


--- Memo ---
- the script change .video-container div width
  - video script seems to be using the ideo container size not the video element size to determine the maximum size of the video with HLS (HTTP Live Stream)
