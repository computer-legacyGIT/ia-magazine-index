This project exists to index, catalogue or otherwise make the ability of tracking what exists a magazine on The Internet Archive.


This project repository will NOT include any magazine content (such as images, PDF, CBZ, ZIP etc.) - that content is expected to be hosted on The Internet Archive.


This project will INCLUDE metadata about magazines that have been submitted to The Internet Archive in parseable XML files.


Directory Structure
------------
To aid with browsing, a level of structure has been created to store the XML files.


Top Level - Country of Publication
Sub Level - Name of Publication
File Level - An XML file that follows the format of [Name of Publication][Date of Publication in YYYYMMDD format][Any extra title information such as issue number].XML


File Structure
------------
Files will be simple XML files with the idea of being parsable by a wide range of scripts that exist in the public domain.


Each XML file should contain the following items of metadata:
* Title - the title of the magazine (e.g. Sports Illustrated)
* Publisher - the publisher of the magazine (e.g. Time Inc.)
* Date - the date of publication printed on the cover or contents page of the magazine in the format of YYYYMMDD (e.g. 19940214 for 14th February 1994)
* Country - the country which this publication was released, using the relevant ISO 3166-1 code (e.g. US for United States)
* Volume Number - if applicable the volume in which this magazine issue is part of (e.g. 15 for Volume 15)
* Issue Number - if applicable the issue number in which this magazine issue is assigned, issue numbers are sometimes sub numbered under volumes (e.g. 132 for Issue 132)
* Subject - A string of comma seperated subjects that the magazine may fall under (see below for exhaustive list)
* Classification - A marker to identify what audience the magazine is suitable for (see below for exhaustive list)


Subjects
------------
To help identify magazines the metadata files should contain at least one subject, that relates to the subject matter within the magazine. This currently doesn't go into a lot of detail due to time, but the idea of sub-subjects may be considered later.


* Automotive - magazines that feature articles about automobiles (example: AutoCar)
* DIY - magazines that feature articles about do-it-yourself work such as building furniture or home improvements
* Electronics - magazines that feature articles about electronic projects
* Fashion - magazines that feature articles about fashion
* Fishing - magazines that feature articles about various aspects of fishing or anglging
* Film - magazines that feature articles about film
* History - magazines that feature articles about various periods of history
* LocalInterest - magazines that feature articles about local interest
* Locomotives - magazines that feature articles about locomotives
* Lifestyle - magazines that feature articles about general lifestyle tips
* Music - magazines that feature articles about music, inlcuding music production
* Pornography - magazines that exist to distribute pornographic imagery
* Sports - magazines that feature articles about sports in general (example: Sports Illustrated)
* Television - magazines that feature general articles about television (example: TV Guide)
* TelevisionShow - magazines that feature specific article about a television show (example: Dr Who)
* Video Games - magazines that primarily feature articles about video games (example: GameInformer)


Classification
------------
Magazines posted to The Internet Archive are wide-ranging in their audience suitability. This means while browsing you can find adult oriented pornographic magazines next to magazines intended for young children. These classifications help to quickly identify a magazines intended audience.


* X - adult, pornographic
* A - adult
* T - teen
* G - all audiences