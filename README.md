BreezyCreate provides a simple abstraction layer on top of the Create2API
library by Brandon Pomeroy, suitable for use by beginning Python programmers.
BreezyCreate2 uses the standard Python distutils
to install the Python module breezycreate2 and the JSON file required by
Create2API.  

Once you've installed BreezyCreate2, you can access its sole
class, the <tt>Robot</tt> class, which has five methods for interacting
with the robot: <tt>setForwardSpeed</tt>, <tt>setTurnSpeed</tt>, 
<tt>playNote</tt>,  and <tt>getBumpers</tt>. (See the <tt>robotest.py</tt>
script for an example.)
