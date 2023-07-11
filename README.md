[![pages-build-deployment](https://github.com/WeCARe-Workshop/wecare-workshop.github.io/actions/workflows/pages/pages-build-deployment/badge.svg?branch=master)](https://github.com/WeCARe-Workshop/wecare-workshop.github.io/actions/workflows/pages/pages-build-deployment)

# A3WS Workshop - International Perspective on Inclusive External Human-Machine Interfaces
This is the GitHub repository where we store the website and accepted papers for our 2022 instance of our workshop series "Accessible Automated Automotive Workshop Series (A3WS)" on "International Perspective on Inclusive External Human-Machine Interfaces" at AutomotiveUI 2022: https://a3ws.github.io/AutoUI22/

**Template files are based on https://github.com/mmistakes/minimal-mistakes** (MIT licence)

The used images are taken from various sources with different licences (see credits on website where needed). 
They are **not** free for modification or to be used in other projects. 

Please contact us if you want to use (parts of) this project. 

# How to edit website
- Open your terminal and type in "bundle exec jekyll serve" and press enter.
- Copy the server address it shows and paste into search bar, to open up the preview of the website.
- Go to Visual Studio Code and open up the folder named AUTOUI23.
- Go to the explorer tab to navigate which page you want to edit.
- Go to Run and Debug to run the code, and see what you did on the website you ran locally after you edit the code, if you want to see what you did. 


## How to edit organizers
-  Explorer -> AUTOUI23 -> _pages -> organizers.md
-  Switch the name between the two **'s out for name you want.
-  Replace the backgrounds of the previous organizers with the backgrounds you want. (Can find them in the research paper)

For contact info:   
- Replace the name of email before @ of email address with the name you want.
- Replace the name of the email company of the email address, with the one on the email you want to put, but make sure to include the period after the comapny name
ex. "gmail.", "cornell."
- Replace what comes after the period in the email address with what comes after the period of the email you want to use.
ex. "edu", "eu", "de", "com"

## How to edit schedule
-  Explorer -> AUTOUI23 -> _pages -> schedule.md
-  You will see ```<td>Time</td>```, with "Time" being a time. 
- Replace "Time" on code with a time you want.
- Do it in order (Order matters) 
- The first time on the code will show up first on the table ect.
- You will also see ```<td><i>Event</i></td>, with "Event"```being a event.
- Replace "Event" with event wanted.
- Again, do it in order (Order matters)
- The first event will show up as the first one the table
  

## How to edit references
-  Explorer -> AUTOUI23 -> _pages -> references.md
-  Replace the citation after ```<a name="ref1"></a>``` with first citation.
-  Repeat with the rest. ref 1 is gthe first reference, ref2 for second citation and so on.
To make the link of citation work on website and take you to the article
- Paste ```<a href="ex_of_a_link" target="_blank"> ex_of_a_link</a>``` to replace your link.
- Copy the link of the article of the citation you want, and paste it to replace both "ex_of_a_link"'s
If link of citation is not available then don't do it.



## Credits
- Template: [Minimal Mistakes Jekyll theme](https://github.com/mmistakes/minimal-mistakes) by [Michael Rose](https://mademistakes.com/) ([MIT licence](https://github.com/mmistakes/minimal-mistakes#license)).
- assets/images/blind_pedestrian.jpg and assets/images/blind_pedestrian_thumb.jpg: <a href='https://www.flickr.com/photos/radiotrippictures/7194630246/' target='_blank'>Blind Man Crosses Street </a> (<a href='https://creativecommons.org/licenses/by/2.0/' target='_blank'>CC BY 2.0</a>) by <a href='https://www.flickr.com/people/radiotrippictures/' target='_blank'>RadioTripPictures</a>.
- assets/images/street_crossing.jpg and assets/images/street_crossing_thumb.jpg: <a href='https://www.flickr.com/photos/yourdon/3050394176/' target='_blank'>Crossing the street</a> (<a href='https://creativecommons.org/licenses/by-nc-sa/2.0/' target='_blank'>CC BY-NC-SA 2.0</a>) by <a href='https://www.flickr.com/people/yourdon/' target='_blank'>Ed Yourdon</a>.
- assets/images/Logo_SAVeNow_final_mit_Text.png: Logo of the BMDV funded project <a href='https://savenow.de/' target='_blank'>SAVeNoW</a>.
- assets/images/BMDV F_rderlogo_2021_Office_Englisch.jpg: BMDV logo indicating their funding for the SAVeNoW project (<a href="https://bmdv.bund.de/SharedDocs/DE/Artikel/DG/AVF-projekte/savenow.html" target='_blank'>funding information here</a>). 
