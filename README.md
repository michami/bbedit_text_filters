# bbedit_text_filters
A collection of simple text filters for BBEdit and TextWrangler

These files can be placed in the text filters directory to add useful functionality to BBEdit and TextWrangler

### Text Filter Location:

~/Library/Application Support/<BBEdit / TextWrangler>/Text Filters/


Don't forget to set the executable bit for the files:

chmod +x *

### unescapeString notes:

the unescapeString filter will also remove all text outside the surrounding quotes, ie:

String json = "Mick says, \\"hi\\"";

will become:

Mick says, "hi"
