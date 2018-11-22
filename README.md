# Kraftwerk website
- For fans and other people interested in music, who want to find useful information & content about fathers of modern electronic sound
 
## UX
- I had to take minimalistic approach when building this project taking into account band's character. Members of Kraftwerk almost always refuse to grant interviews, publicise their work, or to have photographs taken. except when they have new product to promote. Throughout their career they have refused big-name collaborations with the likes of David Bowie and Micheal Jackson. They haven't released a "best of" record and they're not celebrities or rock stars. They refuse to appear on chat shows or entertainment programmes. So I had only handful of materials I could use.
- Primary target audiences are fans and potential fans
- User Stories I used as guidelines
  - As a fan, I want to see clips from back catalog or any new material as it becomes available
  - As a fan, I want to listen to songs from Kraftwerk's back catalogue
  - As a fan, I want to get latest news about the band
  - As a fan, I want to have an access to any new material as it becomes available
  - As a band, we want to showcase our music
  - As a band, we want to publicise our tour dates
- Website has changed substantially since early mockups were made in Balsamiq

## Features
 
### Existing Features
- Full sized band image and logo on front page
- Newsletter form
- Media pages with band's gallery and a video
- Latest tour dates information

### Features Left to Implement
- Some extra content needed

## Technologies Used
- [Amazon Web Services](https://aws.amazon.com/)
    - Used for hosting large files 
- [Tidy](http://tidy.sourceforge.net/) and [CSSTidy](https://sourceforge.net/projects/csstidy/)
    - Used for testing and syntax errors
- [Bootstrap 4](https://getbootstrap.com/)
    - To make project responsive, mobile-first
    - Following classes were used: .col(and its variations), .row, .table, .d-flex, .text-center, .justify-content-center, .container-fluid, .flex-column, .d-none, .d-lg-block
- [Balsamiq](https://balsamiq.com/)
    - Early mockups were created using **Balsamiq**
- [JQuery](https://jquery.com)
    - Used by Bootstrap classes
- HTML, CSS and Javascript
    - Base languages used to create website


## Testing
- Different screen sizes were tested using Chrome DevTools
- On mobile screens certain big elements are hidden 
- Site viewed and tested in the following browsers:
  - Google Chrome
  - Opera
  - Microsoft Edge
  - Mozilla Firefox
- On certain resolutions screen was flickering from CSS animations(change to element size), so they had to be removed
- Known bug: video file format doesn't seem to be supported in Mozilla Firefox
- Scenarios have been tested manually
    1. Clips from back catalogue or any new material:
        1. Go to the "VIDEO" page
    1. Listen to songs from Kraftwerk's back catalogue:
        1. Go to the "MUSIC" page
    1. Check tour dates:
        1. Go to the "TOUR" page
    1. Check gallery:
        1. Go to the "PHOTO" page
    1. Access to any new material as it becomes available, latest news about the band:
        1. Fill the newsletter form
- All user stories work as intended, except newsletter, which hasn't been fully tested because it's outside the scope of the project

## Deployment
- There is no backend dependency, callbacks to server side dictionaries, databases
- Files are transfered over FTP
- Alternative option is deployment through GitHub Pages
- To run locally open index.html in a browser

## Credits

### Content
- The text for front page and media files descriptions were copied from the [Wikipedia entry on Kraftwerk](https://en.wikipedia.org/wiki/Kraftwerk)

### Media
- The photos used in this site were obtained from [Getty Images](https://www.gettyimages.co.uk/)
- Audio & video files were obtained from [Amoy Share](https://www.amoyshare.com/)
- Social media icons from [Font Awsome](https://fontawesome.com/)

### Acknowledgements

- I would like to thank to Antonija Šimić for her crucial advice and help
