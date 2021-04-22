# Changelog
All notable changes to the `tagpdf` package since the 
2021-04-22 will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
this project uses date-based 'snapshot' version identifiers.

## [Unreleased]
### Changed 
 - \tagmcend no longer issues an \unskip in vertical mode. This disturbed 
   to often spacing in unwanted places. 
 - key `add-new-tag` has been extended to support the PDF 2.0 name spaces
 - key `tag` of \tagpdfstructbegin has been extended to support the 
   PDF 2.0 name spaces
    
### Added 
 - Support for PDF 2.0 name spaces. 
 - keys paratagging and paratagging-show for automatic tagging of paragraphs,
   commands \tagpdfparaOn and \tagpdfparaOff to disable the automatic tagging.
 - The code to tag links has been moved from the documentation to the main 
   package. All links are now tagged automatically (if hyperref or the commands
   from l3pdfannot are used).  
   
 