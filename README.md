# video-test-file-links
> Collection of links to places to find test video files.

I'm working on a few posts / projects right now that require a variety of test video files (in an assortment of formats), and I wanted to share some of the best resources I have found so far. These are not all licensed the same, nor are all public domain, so some are not suitable for commercial use, copyleft, etc.

- [Chromium Media Test Files](https://github.com/chromium/chromium/tree/master/media/test/data)
	- This is an amazing directory of test files. Chromium (the core behind the Chrome browser, as well as Edge and many other browsers) has to handle a lot of different media formats, so their repository includes hundreds of sample files that unit and integration tests can be ran against.
	- It also includes some *broken* and *unusual* files that can trip up decoders; useful if you are trying to build something that would need to handle that gracefully
	- For a non-mirror link, [here is the Chromium VCS link](https://chromium.googlesource.com/chromium/src/media/+/refs/heads/master/test/data/)
- [bengarney/list-of-streams](https://github.com/bengarney/list-of-streams)
	- Collection of links to DASH and HLS *public-facing* streams
- [Wikimedia Commons](https://commons.wikimedia.org/)
	- The really nice thing about video files on Wikimedia Commons, is that many have been automatically transcoded into a variety of formats, ready for download
	- If you want to search for public domain / CC0 licensed content, use the query `haswbstatement:P275=Q6938433`
	- You can use `filetype:video` to find only videos
	- [Sample query](https://commons.wikimedia.org/w/index.php?search=filetype%3Avideo+haswbstatement%3AP275%3DQ6938433&title=Special:Search&profile=advanced) - this is for public domain videos.
- [Web-Platform-Tests Project](https://github.com/web-platform-tests/wpt)
	- Example directory: [media-source/webm](https://github.com/web-platform-tests/wpt/tree/master/media-source/webm)
	- Similar to the Chromium repo, this is about test coverage, so has a lot of different types of files
- [test-videos.co.uk](https://test-videos.co.uk/)
	- Has a lot of the standard permissive stuff (Big Buck Bunny, etc.), pre-transcoded in different formats and filesizes
	- Word of warning: Will not work with `fetch()` due to CORS, unless you re-host yourself
- [Pixabay.com: Videos](https://pixabay.com/videos/)
- [Pexels.com: Videos](https://www.pexels.com/videos/)
- [Webm Project: libwebm Test Data](https://github.com/webmproject/libwebm/tree/master/testing/testdata)
	- As name would imply, these test files are specifically of the Webm format
- MDN Learning Area: [Multimedia and Embedding](https://github.com/mdn/learning-area/tree/master/html/multimedia-and-embedding/video-and-audio-content)
	- This is the source behind docs pages like [this one](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Client-side_web_APIs/Video_and_audio_APIs)
- MDN Interactive Example: [live-examples/media](https://github.com/mdn/interactive-examples/tree/master/live-examples/media)
	- Media, for example, [this page](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/video)

- [Public Domain Films from the National Film Registry](https://www.loc.gov/free-to-use/public-domain-films-from-the-national-film-registry/)
	- Free to use and reuse
	- Has large video files, e.g. [1.9GB MP4](https://www.loc.gov/item/2023600635/)
 
- [SampleVideos.com](https://www.sample-videos.com/)

## Individual Test Files
### WEBM
<details>
	<summary>VP9 / Video ONLY</summary>

- https://raw.githubusercontent.com/web-platform-tests/wpt/master/media-source/webm/test-vp9.webm
- https://upload.wikimedia.org/wikipedia/commons/transcoded/6/60/Wikipedia_logo_puzzle_globe_spins_horizontally_and_vertically%2C_revealing_the_contents_of_all_of_its_puzzle_pieces_%284K_resolution%29_%28VP9%29.webm/Wikipedia_logo_puzzle_globe_spins_horizontally_and_vertically%2C_revealing_the_contents_of_all_of_its_puzzle_pieces_%284K_resolution%29_%28VP9%29.webm.120p.vp9.webm
</details>

<details>
	<summary>VP8/Vorbis</summary>

- https://mdn.github.io/learning-area/html/multimedia-and-embedding/video-and-audio-content/rabbit320.webm
- https://upload.wikimedia.org/wikipedia/commons/transcoded/8/87/Schlossbergbahn.webm/Schlossbergbahn.webm.160p.webm
- https://upload.wikimedia.org/wikipedia/commons/transcoded/2/22/Volcano_Lava_Sample.webm/Volcano_Lava_Sample.webm.160p.webm
- https://interactive-examples.mdn.mozilla.net/media/cc0-videos/flower.webm
- https://www.w3schools.com/tags/mov_bbb.webm
- http://dl5.webmfiles.org/big-buck-bunny_trailer.webm
- https://storage.googleapis.com/web-dev-assets/video-and-source-tags/chrome.webm
- https://upload.wikimedia.org/wikipedia/commons/transcoded/f/f5/STB_Stuttgart_F%C3%B6hrich_U6_Line_Entering_Station_VIDEO.webm/STB_Stuttgart_F%C3%B6hrich_U6_Line_Entering_Station_VIDEO.webm.160p.webm
</details>
