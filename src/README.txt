v0.4.0 - 7/1/2012

Thank you for choosing to install QUnit-Metro.  This initial release should get you started with writing simple unit tests for your WinJS Metro applications.

To get started, in default.htm add a reference to the QUnit-Metro script and stylesheets in the header:
        <script defer="defer" src="/js/qunitmetro.js"></script>
		<link href="/css/qunitmetro.css" rel="stylesheet" />

Note - To match the Metro UI paradigm there is an optional qunitmetro-dark.css and qunitmetro-light.css that you can reference as well.

Finally, create tests in javascript for HTML pages in a file called "test.js" and place them in the same "pages" folder as the HTML page you are testing. For
example, if you are testing "/pages/groupedItems/groupedItems.html" you should create and place your scripts in the file "/pages/groupedItems/test.js"

Your tests should be written using the qUnit test syntax: http://docs.jquery.com/QUnit

On those pages that contain tests, you should be able to access the AppBar in your app, and click the 'Run Tests' button to run your unit tests.
