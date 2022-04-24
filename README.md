# Bluestone Institute Best Practices and Style Guide


# Table of Contents

<center>
[Best Practices (General)](#best-practices-(general)) | 
[Best Practices (Coding)](#best-practices-(coding))  | 
[Style Guide](#style-guide)
</center>

<a name="best-practices-(general)"></a>
# Best Practices (General)

## Open Research

Bluestone Institute takes a pragmatic view of Open Research, meaning that papers, code, and data should be shared, but there may also be reasonable exceptions. One such exception is ethical: when we collect large datasets on the behaviors and opinions of other people, with IRB approval, we may avoid openly posting data to protect privacy. Another exception reflects the cost of data collection: some datasets require huge up-front efforts to collect and clean, and will not be published immediately after the first study that analyzes them. Verify that data and code can be made public before doing so.

## Tracking Your Time

Bluestone Institute does not currently have a time entry system.  However, Research Interns have committed some of their time each week to Bluestone Institute. We expect that commitment to be met. Tell your supervisor if you don’t have enough work to fulfill your commitment or if you have too much work in excess of your commitment.

## Folder Organization

Each project will have its own project folder on Dropbox and/or GitHub.  Sub-folders within the project folder should be organized consistently so that files can be located easily, even after significant time has passed.  

For projects primarily completed via Dropbox we have adopted the following folder structure:

* Admin - Files that aid in project administration like budgets, contracts, invoices, calendars, etc.
* Report - Reports and supporting exhibits, appendices, or attachments.  Previous drafts should be contained in an "Archive" subfolder.
* Research - Results of literature reviews, data documentation, etc.
* Data - Analysis datasets.
	+ Raw Data - Original data in its unaltered form.
	+ Intermediate Data - Intermediate datasets that are necessary predecessors to analysis datasets.
* Analysis - Code and results of analyses.  Stand-alone analyses should be contained in their own sub-folder (e.g., "ImportData")
* Work - Contains sub-folders for individual team members to store their work (e.g., "\Work\KWC")

## File Names

The file names for documents, programs, datasets, analyses, etc. should be sufficiently descriptive such that all team members (and especially new team members) will be able to understand the contents of the file.  They must also be sufficient to identify the most recent version of the file. File names should be structured to have descriptions of the content at the beginning and descriptions of the version at the end.  Therefore when viewing the contents of a folder by filename, all versions of the files will appear together. 

Examples:

* Analysis of Price Changes 1999 – 2004 - 2014_0518.xlsx
* Analysis of Price Changes 1999 – 2004 - 2014_0601.xlsx
* Economic Impact of Covid - DRAFT - 2021_0716.docx
* Economic Impact of Covid - 2021_0731.docx
* Economic Impact of Covid - 2021_0731.pdf

It is paramount that pdf copies of all cited documents, papers, and websites be saved to the \Research\ folder in an appropriate sub-directory.  This is especially true for websites which can change regularly.  Check to ensure PDFs of websites contain the URL and date accessed. The best way to ensure this occurs is to insert a textbox at the bottom of the first page of the PDF.   This is necessary because the URL that often appears automatically at the bottom of the page is incomplete and cannot be used in a citation. Webpages that are saved as PDF to the \Research\ folder should have a descriptive filename similar to books and articles (i.e. author, publisher, title, and date).

<a name="best-practices-(coding)"></a>
# Best Practices (Coding)
Generally, we follow the [tidyverse style guide](https://style.tidyverse.org/index.html) for our coding best practices.  That said, we have the following additions:

* Comment your code, extensively!
* If a code block is complicated to read or complicated to debug, it needs to be simplified.
* Programs should typically not exceed 300 lines.  Break longer programs into multiple files.
* Include a header and divide your code into sections. The program should have a logical, linear flow.

```
#=================================================================
# Program   :  Raw_Data_Import_2022_0424.R
# Date      :  April 24, 2022
# Project   :  Twitter Paper
# Author    :  Kevin W. Christensen
#=================================================================

#--------------------------------------------------------
# 1.	Load Packages and Set Folders
#--------------------------------------------------------
#1.1 Load Package
#install.packages("tidyverse")
library(tidyverse)

#1.2 Set Working Directory
setwd('\Twitter_Paper\')

#--------------------------------------------------------
# 2.	Read in Data
#--------------------------------------------------------


### END PROGRAM  ###
```

<a name="style-guide"></a>
# Style Guide
Bluestone Institute has adopted a “default” style for our research.  The default style allows everyone to seamlessly flow from one project to the next.  It minimizes time spent re-formatting and other superficial tasks and returns focus (and budgets) to rigorous economic analysis.  Finally, consistently formatted results are a trademark of quality and professionalism.  

Academic journals may have their own style to which we will need to adopt prior to publication.  For this reason, some flexibility is needed to meet the needs of each research project.

## Report Text
* Text must be in literary present tense throughout. For example, "we predict the dependent variable" rather than "we predicted the dependent variable." Use past tense when describing historical events. For example, "investors sold shares in our sample" rather than "investors sell shares in our sample."
* Grammar, spelling, and punctuation corrections must be made.
* Bullet points or small roman numerals (e.g., (i), (ii), etc.) may be used to list items.
* Please use the following treatment: “See, for example, ...” rather than “See, e.g., ....” Similarly, use “..., that is, .....” rather than “..., i.e., .....” However, “(i.e., ...)” or “(e.g., ...)” is fine.
* Do not use italics on Latin. For example, “ceteris paribus” rather than "*ceteris paribus*".
* The end of a sentence should be followed with two spaces, not a single space.

## Page Numbers
Page numbers should be inserted into the center of the footer.  If the document has a cover page, the page numbering should start on the first page of content as opposed to the cover.

## Dates
* Dates should be written as “1980 to 1990” in the text. “1980–90” or “1980–1990” is okay for tables although it should be consistent.

## Exhibits
* Tables and Figures will be referred to as Exhibits.
* Numbering will be consecutive regardless of whether the Exhibit is a Table or Figure.  For example, the first table will be Exhibit 1 and the first figure will be Exhibit 2.
* Exhibits can be created in Excel, SAS, Stata, or other programs of your choice. Exhibits should be inserted into Word as pictures. To do this when pasting the graph or figure into Word, select the picture icon.

## Tables
* In general, tables should be self-contained, requiring no further information from other sources to make them understandable. However, if a table’s legend runs more than 300 words, lengthy details on variable construction should be located in a separate definitions table or appendix, with the legend indicating where the reader can find such details. The goal here is to shorten table legends and reduce redundancy across legends.
* Tables are numbered with Arabic numerals (1, 2, 3...) and must have a title and descriptive legend.
* The legend must define all variable notation (e.g., “∆WC is change in working capital”) and briefly explain what the table shows.
• Tables should be in portrait orientation, with up to 8 columns and 12-point text.

## Figures 
* Figures are numbered with Arabic numerals and must have a caption. There should also be a descriptive legend if necessary to explain what the figure shows or to define variable notation (as with tables, figure legends should direct the reader to a separate definitions table or appendix if lengthy, OR to a previous figure as appropriate).
* Figures must be camera-ready with all axes labeled.
* Please use color figures to enhance the readability.  However, figures must also be readable in black and white.  This means, shading and shapes should be used.

## Citations

In many cases, the footnotes cite to academic works (e.g., books, published papers), websites, and third party studies.  Regardless of what is being referenced, a citation is intended to provide the reader with enough information to follow up on the cited source.  While there are many different established styles available, Bluestone Institute has chosen the Chicago Manual of Style as the default choice. 

A footnote or an endnote generally lists the author, title, and facts of publication, in that order.  Elements are separated by commas; the facts of publication are enclosed in parentheses.  Authors’ names are presented in standard order (first name first).  Titles are capitalized headline-style (see, 8.157), unless they are in a foreign language (see, 11.3).  Titles of larger works (e.g., books and journals) are italicized; titles of smaller works (e.g., chapters, articles) or unpublished works are presented in roman and enclosed in quotation marks (see 8.161).  Such terms as editor/edited by, translator/translated by, volume, and edition are abbreviated. [Rule 14.15]

With that in mind, consider the following example citations:

* Case Documents [Rules 14.281-14.304]
+ United States v. Christmas, 222 F.3d 141, 145 (4th Cir. 2000). 
+ Profit Sharing Plan v. Mbank Dallas, N.A., 683 F. Supp. 592 (N.D. Tex. 1988).
+ Homeland Security Act of 2002, 6 U.S.C. §101 (2002).
*Academic Literature [Rules 14.175-14.198]
+ Walter Blair, “Americanized Comic Braggarts,” _Critical Inquiry_ 4, no. 2 (1977):  331-32. 
+ Wilfred Karmaus and John F. Riebow, “Storage of Serum in Plastic and Glass Containers May Alter the Serum Concentration of Polychlorniated Bipheyls,” _Environmental Health Perspectives_ 112 (May 2004):  645, http://www.jstor.og/stable/3435987.
*Books [Rules 14.68-14.169]
+ William Strunk Jr. and E. B. White, _The Elements of Style_, 4th ed. (New York:  Alyn and Bacon, 2000), 3.
+ Glenn Gould, “Streisand as Schwarzkopf,” in _The Glenn Gould Readers_, ed. Tim Page (New York:  Vintage, 1894), 310.
+ John Samples, “The Origins of Modern Campaign Finance Law,” chap. 7 in _The Fallacy of Campaign Finance Reform_ (Chicago:  University of Chicago Press, 2006).
*Websites  [Rules 14.243-246]
+ “Google Privacy Policy,” last modified October 14, 2005, accessed July 19, 2008, http://www.google.com/intl/en/privacyppolicy.html.
+ “McDonald’s Happy Meal Toy Safety Facts,” McDonald’s Corporation, accessed July 19, 2008, http://www.mcdonalds.com/corp/about/factsheets.html.
+ Mike Nizza, “Go Ahead, Annoy Away, an Australian Court Says,” The Lede (blog), New York Times, July 15, 2008, http://thelede.blogs.nytimes.com/2008/07/15/.

Additional Information

* The number of footnotes must not exceed the number of pages within the article.
* Footnotes in tables should be limited to technical information such as levels of significance. All other information belongs in the legend. 

## References
* References in the text are by author(s) name and date of publication. For example, Tufano (1996) or (Tufano (1996)).
* Use “et al.” when referencing a source with four or more authors. For example: (Leven et al. (1999)).
* All references mentioned in the text must be included in the list of references and vice versa.  References must be on a separate page at the end of the paper, unnumbered and double spaced.  References must include first names of all authors.
* References to data sources within the body of the paper or the tables should be italicized.
* Research/consulting firms do not need to be referenced.
* Personal communications should be left as footnotes.

## Appendices
* Appendices should be lettered A, B, C, etc.
* If there is only one appendix, there is no need to letter it A.
* Tables within an appendix should be lettered A.1, A.2, etc.
* Figures within an appendix should be numbered A.1, A.2, etc.
