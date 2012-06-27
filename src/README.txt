v0.3.1 - 6/27/2012

Thank you for choosing to install QUnit-Metro.  This initial release should get you started with writing simple unit tests for your WinJS Metro applications.

To get started, in default.htm add a reference to the QUnit-Metro script in the header:
        <script defer="defer" src="/js/qunitmetro.js"></script>


Next, add references to the QUnit-Metro script and css in each page of your app:
    <script src="/js/qunitmetro.js"></script>
    <link href="/css/qunitmetro.css" rel="stylesheet" />

Note - To match the Metro UI paradigm there is an optional qunitmetro-dark.css and qunitmetro-light.css that you can reference as well.

Finally, on those pages where you would like to run tests, include a script reference to your test file:
    <script src="test.js"></script>

Your tests should be written using the qUnit test syntax: http://docs.jquery.com/QUnit

On those pages that contain tests, you should be able to access the AppBar in your app, and click the 'Run Tests' button to run your unit tests.
