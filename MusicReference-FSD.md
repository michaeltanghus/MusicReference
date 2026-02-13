# Music Reference

A Discogs media finder using bar code or release number

### Problem

In a large physical Music media collection it is nice to read more about the Music Media on Discogs.com

### What This System Does

- Finds the media on Discogs using bar code or release number.
- Supports bar code reader
- Show basic information using discogs api with link to open discogs.org at the media site

### Main Functions

- Show media information
- Supports bar code scanning or gets release number from keyboard
- Link to https://www.discogs.com/release/RELEAS_NUMBER

## Functional descriptions

When opening the main window opens with an area at the top wit an selected edit box waiting for  a release number or bar code.   When enter or [OK] button is pressed or an ERN-13 number is in the edit box, the application takes over. With the information given it finds the media on Discogs.

I media found it shows relevant information in the main area or it shows nothing found.  
If more releases or medias found let the user select the right to show.

### Main window contains

- Area on top with Application name, edit box and a [OK] button
- Main area
  a frame showing the presentation of the found media. If possible an iframe from discogs.

#### Other informations.

- Project location /run/media/michael/SSD_Data/Udvikling/MusicReference
- The application is written in Pascal using RAD IDE Lazarus Pascal
- Primary target is Fedora Linux
-  Discogs user name michaeltanghus



