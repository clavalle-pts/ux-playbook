# TEAMS Video

### Todo

- [x] HTML5 Video
- [x] Markers
- [ ] Responsive Sizing
- [ ] Playlist
- [ ] Overlay on higher Z with close button
- [ ] Video Menu

### Prototype
http://ux-dev.ptsteams.local/videos/

##### Prototype Source

git clone git@bitbucket.org:uxteams/videos.git

### Guidelines

- All filenames should use hyphens, underscore or camelCase, no spaces!
- Video files, poster images and any additional files will be uploaded to S3 bucket as per Operations
- Primary file format is MP4, secondary format is WebM


The user is presented with a screen that shows a welcome video along with a slidedeck for key information and concepts. Neither, both or some items will be available for download. MP4 is the preferred video format and HTML is the preferred slidedeck format.

The user will be able to click on the pendant in the top left corner of the screen to access additional links. Menu links are organized by topic and are nested underneath in a lighter font, meaning of less weight, and indented by 10 pixels.

The HTML5 video renders quickly and loads with high confidence across various devices. If the user leaves the screen and comes back to a specific video, the content will pickup where the user left off. Video markers represent key topics and represent accessible reference points.

## Components

- Placeholder, area for video and video related menu
- Container, area for the slideshow and slidedeck
- Element, Video Markers & Resume Watching
- Entry, List of videos and slidedecks with menu links

## UI States

- Blank States, First impressions
- Loading States, Perception of loading
- Partial States, Walk-thrus, wizards
- Error States, 404, JS alert boxes
- Ideal State, Everything is normal

## Resources

Videojs Plugins
  - Video Markers [Link](https://github.com/spchuang/videojs-markers)

  - Slideshow in Tandem [Link](https://github.com/InnovationEnterprise/let-me-slide-that-for-you)

  - Resume Watching [Link](https://github.com/sprice/videojs-resume)

Example of an Interactive Presentation [Link](http://elearning-examples.s3.amazonaws.com/En-Software-demo/interaction.html)

Example of a Slidedeck
[Link](http://rawgit.com/rmcgibbo/slidedeck-example/master/index.html#1)
