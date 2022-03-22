<h1> Kyle White - NOTES: Reading 1 - Learning Markdown</h1>
<h3>Headings</h3>
<p>To create a heading, add number signs (#) in front of a word or phrase. The number of number signs you use should correspond to the heading level. </p>
<p><i>- For example, to create a heading level two (H2), use two "##" signs.</i></p>

<h4>Heading Best Practices</h4>
<p>Markdown applications don’t agree on how to handle a missing space between the number signs and the heading name. For compatibility, always put a space between the number signs and the heading name.
<p><i>- For example, do this "# Here's a Heading" and NOT this "#Here's a Heading".</i></p>
<p><i>- You should also put blank lines before and after a heading for compatibility.</i></p>

<h3>Paragraphs</h3>
<p>To create paragraphs, use a blank line to separate one or more lines of text.</p>

<h4>Paragraph Best Practices</h4>
<p>Unless the paragraph is in a list, don’t indent paragraphs with spaces or tabs.</p>
<p><i>- For example, make sure you keep lines left-aligned and DON'T add tabs or spaces in front of paragraphs.</i></p>

<h3>Line Breaks</h3>
<p>To create a line break or new line ("br"), end a line with two or more spaces and then type return("/br").

<h4>Line Break Best Practices</h4>
<p>You can use two or more spaces (commonly referred to as “trailing whitespace”) for line breaks in nearly every Markdown application. It’s hard to see trailing whitespace in an editor, and many people accidentally or intentionally put two spaces after every sentence. For this reason, <strong>you may want to use something other than trailing whitespace for line breaks</strong>.</p>
<p>If the Markdown application supports HTML, you can also use the "br" HTML tag.</p>
<p>There are two other options that aren't reccommended.</p>
<p>- CommonMark and a few other lightweight markup languages let you type a backslash (\) at the end of the line, but not all Markdown applications support this, so it isn’t a great option from a compatibility perspective.</p>
<p>- At least a couple lightweight markup languages don’t require anything at the end of the line — just type return and they’ll create a line break.</p>

<h3>Text Emphasis - Bolding</h3>
<p>To bold text, add two asterisks or underscores before and after a word or phrase. To bold the middle of a word for emphasis, add two asterisks without spaces around the letters.
<p><i>- Markdown example: "I just love **bold text**."</i></p>
<p><i>- HTML example: "I just love < strong >bold text< /strong >" (without spaces). </i></p>

<h4>Bolding Best Practices</h4>
<p>Markdown applications don’t agree on how to handle underscores in the middle of a word. For compatibility, use asterisks to bold the middle of a word for emphasis.
<p><i>- For example, do this "Love**is**bold" and NOT this "Love__is__bold".</i></p>

<h3>Text Emphasis - Italic</h3>
<p>To italicize text, add one asterisk or underscore before and after a word or phrase. To italicize the middle of a word for emphasis, add one asterisk without spaces around the letters.
<p><i>- Markdown example: "Italicized text is the *cat's meow*."</i></p>
<p><i>- HTML example: "Italicized text is the < em >cat's meow< /em > (without spaces)."</i></p>

<h4>Italic Best Practices</h4>
<p>Markdown applications don’t agree on how to handle underscores in the middle of a word. For compatibility, use asterisks to italicize the middle of a word for emphasis.</p>
<p><i>- For example, do this "A*cat*meow" and NOT this "A_cat_meow".</i></p>

<h3>Text Emphasis - Bolding + Italic</h3>
<p>To emphasize text with bold and italics at the same time, add three asterisks or underscores before and after a word or phrase. To bold and italicize the middle of a word for emphasis, add three asterisks without spaces around the letters.
<p><i>- Markdown example: "This text is ***really important***."</i></p>
<p><i>- HTML example: "This text is < strong >< em >really important< /em >< /strong > (without spaces)."</i></p>

<h4>--> To learn more, visit https://www.markdownguide.org/basic-syntax/ or https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax.</h4>
