How to run a test (suite)
================================

Running tests on web-client is easy like ABC. The only thing you need to know 
is the filename of the suite that you want to run. 

If you have your prefered suite name in mind then open your favorite command line tool 
and navigate to the following directory (relative to web-client root directory):

`../selenium/tasks`

Assuming * testing-suite.yml * as the filename of your suite. To run this suite you just
type:

`thor selenium:test -s testing-suite`

If all tests passed the processes will finish silently.