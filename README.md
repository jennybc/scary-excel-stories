# scary-excel-stories

Sobering things about Excel. People send me so many of these, I feel obligated to collect them in one place.

### Mangling dates in a csv file it shouldn't touch

Via [a tweet](https://twitter.com/margaretkosmala/status/750631497527226368) and [blog post](http://ecologybits.com/index.php/2016/07/06/beware-this-scary-thing-excel-can-do-to-your-data/) by Margaret Kosmala [\@margaretkosmala](https://twitter.com/margaretkosmala)

> But it’s worse than that. Excel can actually change the format of the dates in a non-Excel file (e.g. CSV file) without your permission.

She then outlines a workflow in which examining a csv file with Excel resulted in date mangling in the csv (e.g., changed from "2016-05-03" to "5/3/16"). Even though user never allowed Excel to save the file. From Twitter replies and comments, I see some others could reproduce this. Between Stephen Heard and Margaret, it's confirmed for Excel 2010 and 2013 on Windows 7.

### Error reading a csv when first two characters are "ID"

Via [a tweet](https://twitter.com/genetics_blog/status/750691299393675264) from Stephen Turner [\@genetics_blog](https://twitter.com/genetics_blog)

<https://support.microsoft.com/en-us/kb/323626>

From reading the link above, I think this applies to Office 2003, which is no longer supported. The article has been archived. But wait! Jovana Maksimovic reproduced the error with Office 2016, as did Christoffer Flensburg with Excel for the Mac 2011. Flensburg says you can press "OK" at the message and file still opens fine.

### Mangling gene names by turning them into dates

http://bmcbioinformatics.biomedcentral.com/articles/10.1186/1471-2105-5-80

Mistaken Identifiers: Gene name errors can be introduced inadvertently when using Excel in bioinformatics  
Barry R Zeeberg, Joseph Riss, David W Kane, Kimberly J Bussey, Edward Uchio, W Marston Linehan, J Carl Barrett and John N Weinstein

BMC Bioinformatics 2004 5:80  
DOI: 10.1186/1471-2105-5-80
