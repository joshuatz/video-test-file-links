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
