---
transition: none
include-after:
  - |
    <script>
    Reveal.initialize({
    	dependencies: [
    		{ src: 'audio-slideshow.js', condition: function( ) { return !!document.body.classList; } },
    	],
    audio: {
    		advance: -1, 		// advance to next slide after given time in milliseconds after audio has played, use negative value to not advance
    		autoplay: true,	// automatically start slideshow
    		playerOpacity: 1.0,	// opacity value of audio player if unfocused
    	}
    });
    </script>
...

# TIMIT
