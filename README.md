# XML-Programming-Java
<Strong>(Steps to Follow)</Strong>

1. Unzip the code and open the "DomParserDTD" and "DOMParserSchema" project files in Eclipse<br>
<Strong>NOTE: All the XML, DTD and Schema files are available inside the Project folders</Strong><br><br>

<Strong>Steps to parse and validate XML document against the Schema:<br></Strong>
1. Select the <Strong>"DOMParserSchema.java"</Strong> file from <Strong>DOMParserSchema --> src --> default package --> DOMParserSchema.java</Strong><br>
2. Hit the RUN button<br>
3. You should be able to see the following message in console:<br>
<pre>
-- Validator Class: com.sun.org.apache.xerces.internal.jaxp.validation.ValidatorImpl
-- Validation passed.
</pre>

<Strong>Steps to parse and validate XML document against the DTD:<br></Strong>
1. Select the <Strong>"DOMParserDTD.java"</Strong> file from <Strong>DOMParserDTD --> src --> default package --> DOMParserDTD.java</Strong><br>
2. Hit the RUN button<br>
3. You should be able to see the following message in console:<br>
<pre>
&lt?xml version="1.0" encoding="UTF-8" standalone="no"?&gt&lt!DOCTYPE bookstore SYSTEM "Bookstore.dtd">
&ltbookstore&gt
  &ltbook id="1"&gt
	 <title>Gone with the Wind</title>
	 &ltauthor&gtMovie&lt/author&gt
	 &ltgenre&gtClassic&lt/genre&gt
  &lt/book&gt
  &ltbook id="2"&gt
	 <title>Star Trek</title>
	 &ltauthor&gtTV Series&lt/author&gt
	 &ltgenre&gtScience fiction&lt/genre&gt
  &lt/book&gt
&lt/bookstore&gt
-- Validation passed.
</pre>
