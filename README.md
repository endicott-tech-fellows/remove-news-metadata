# Remove News Metadata
This strips out header and footer information from a bulk download of news 
stories from LexusNexus.

## To begin
Open `index.html` in any browser. Follow the instructions on the page.

## Input
The input file should be a rich text format (RTF) or plain text file consisting
of one or more news articles. More than one input file may be given.

## Output
Everything except for an article's title and body will be removed. Formats
are maintained (if the input is RTF, the output is RTF). If multiple input files
are given, the results are packed into a zip file.