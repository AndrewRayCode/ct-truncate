CT Truncate Plugin
==================

Truncate rich text and keep all links and unicode characters in tact, without
effing up the DOM!

    <div id="foo">
        I am some <p>rich text</p>
        <span>that needs <a href="http://www.google.com">truncating!</a></span>
    </div>

Usage:

    $('#foo').ctTruncate({
        
        // Characters to truncate at
        maxChars: 30,

        // The text to append after the text is truncated. Defaults to elipses.
        truncator: '\u2026',
    });

Then party till you're blind!
