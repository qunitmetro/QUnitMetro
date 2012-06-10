v0.2.0 - 6/10/2012

Thank you for choosing to install QUnit-Metro.  This initial release should get you started with writing simple unit tests for your WinJS Metro applications.

To get started, in your App Bar control in default.htm add the following button:
        <button data-win-control="WinJS.UI.AppBarCommand" data-win-options="{id:'runTestsAppBarCmd', label:'Run Tests', icon:'repair', section: 'global', onclick: QUnitMetro.runTests}"></button>

In the default.htm page, add this container for the unit test results:
    <div id="unitTestContainer">
        <div id="qunit"></div>
        <div id="qunit-fixture"></div>
        <button id="closeTests">Close</button>
    </div>


Next, add references to the QUnit-Metro script and css in each page of your app:
    <script src="/js/qunitmetro.js"></script>
    <link href="/css/qunitmetro.css" rel="stylesheet" />

Finally, on those pages where you would like to run tests, include a script reference to your test file:
    <script src="test.js"></script>

On those pages that contain tests, you should be able to access the AppBar in your app, and click the 'Run Tests' button to run your unit tests.
