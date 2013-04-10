# Timeline Pages

This repository is a set of documents to assist Lantern reporters in creating timelines. 

You will need:

* a Gmail account
* a text editor
* the files in this repository

## How it works

### Writing the timeline. 

Go to [timeline.verite.co](http://timeline.verite.co/) and open their [Google Docs template](https://drive.google.com/previewtemplate?id=0AppSVxABhnltdEhzQjQ4MlpOaldjTmZLclQxQWFTOUE&mode=public). Click the "Use this template" button. Save the template to your Google Drive. 

Change the name of the document to something related to your story. Double-click the title. 

Fill out your new Google Spreadsheet with entries as the template insturcts. This is the hard part, and will take some time. 

Click the "Share" button. Change "Private" to "Anyone with the link." If you do not do that, no one will be able to see your timeline. Add your editors with edit permissions. Your editors will receive an email with a link to this document. 

### The timeline embed

Look at [this Lantern story](http://www.thelantern.com/campus/utilities-more-than-99-reliable-in-current-academic-year-1.3019935). The timeline embedded in it is made using the following snippet of code: 

    <iframe frameborder="0" height="710" scrolling="no" src="http://embed.verite.co/timeline/?source=0Akwco693VNGjdHc1YWtLenlxZmxzbS11VmxRV19TOXc&font=Georgia-Helvetica&maptype=toner&lang=en&height=690" width="640"></iframe>

Take the URL of your Google Spreadsheet and plug it into the embed creator at [timeline.verite.co](http://timeline.verite.co/#embed). Change the font to "Georgia & Helvetica Neue." Copy the code that is generated. Give that to your editors to put on The Lantern website. 

If it looks odd on The Lantern's site, try changing the `frameborder` and `height` options to what is shown in the snippet above, and adding `scrolling="no"` as shown above. 

### The separate timeline

To check how things are working, you can download `timeline-blank.html`, `plain-red-lantern-logo.gif` and `style.css`. Click the "Files" tab above this document. For each document you want to download, open the document, click "Raw", then use your browser's "File>Save As" function. Put all the files you download in a folder on your computer. 

Open `timeline-blank.html` and read through it. If you know HTML, it's not hard to find what needs to be modified. Otherwise, read the comments in the code - they've got lots of ################# to mark them. Any section of text that begins with `<!--` and ends with `-->` is a comment.

A quick overview:
* Set the page title (what shows up in the title of the browser window)
* Set the headline (your story headline)
* Paste in your embed code (see above)
* Set the publication date (when it's going to be in the paper)
* Set the byline (see the comment for additional information)
* Paste in your story
** Put a `<p>` before each paragraph of the story
** Put a `</p>` after each paragraph of the story
* Remove the big pink paragraphs. (see the comment for additional information)
* Save.

Right-click on the file and open it with a web browser. It should look correct, if you've followed these instructions. If it doesn't, check that all the HTML is correct. If you don't know about that, you should consider taking a web design class.

If you want to put this page online, take the folder containing all these files (you did put it in a folder, right?), compress it, and send it to The Lantern systems manager, who in 2013 was Jay Smith. If you don't know who that is, ask your editor for the person in charge of the website.

## Copyright notice
All content, except as otherwise marked, is copyright The Lantern, The Ohio State University. See LICENSE.MD. For more information, contact [The Lantern faculty advisor][1].


[1]: http://www.thelantern.com/contact-us
