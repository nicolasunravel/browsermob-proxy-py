0.7.2 / 2016-04-11
==================

  * Allow to pass a title at new page creation

0.7.1 / 2015-07-09
==================

  * Adding option of using existing proxy port.
  * Allow use of a remote proxy server.
  * improved directions on running tests
  * fix broken test (test_new_page_defaults)

0.7.0 / 2015-06-05 
==================

 * Updating travis ci to use browsermob proxy 2.0
 * Support to use httpsProxy and httpProxy at proxy creation time
 * Adding Python 3 support
 * add sslProxy to Client.add_to_capabilities with tests
 * Correct docstring for `wait_for_traffic_to_stop`
 * Removing unused :Args: items
 * Updating docstrings
 * Correcting args and params for documentation
 * updated docstrings for easier formatting on things like RTDs
 * updated new_har() docstrings
 * updated client documentation
 * Added client and server docs
 * updating version in docs

0.6.0 / 2014-01-21 
==================

  * Added support for parameters in har creation
  * Bug fixes for tests that are out of date
  * Setup server constructor to look on path for location of browsermob-proxy executable. As well as looking for a file. Also added example code for using browsermob-proxy with chrome
  * Fix project name
  * adding docs

0.5.0 / 2013-05-23 
==================
* Allow proxying of ssl requests with selenium.
* Updating case for proxy type


0.4.0 / 2013-03-06 
==================

  * Allow setting basic authentication
  * Adding the ability to remap hosts which is available from BrowserMob Proxy Beta 7
  * Merge pull request #6 from lukeis/patch-2
  * Update readme.md
  * initial commit of event listener to auto do record
  * server.create_proxy is a function, should be called :)
  * forgot to add the port

0.2.0 / 2012-06-18 
==================

  * pep8 --ignore=E501
  * DELETE /proxy/:port/
  * /proxy/:port/limits
  * /proxy/:port/blacklist
  * /proxy/:port/whitelist
  * fixing /proxy/:port/har/pageRef
  * fixing /proxy/:port/har/pageRef
  * fixing passing in a page ref as the name for the page in /proxy/:port/har
  * tests around /proxy/:port/har and some cleanup of the implementation
  * make /proxy/:port/headers work
  * wrapping selenium_proxy with webdriver_proxy since the project is more than just webdriver
  * extending the client to play nice with remote webdriver instances
  * create_proxy sounds and feels like a method to me, let's make it so
  * ensure the self.process exist, to reduce possibilities of AttributeError
  * check the path before attempting to start the server
  * wait longer than 3 seconds for the server to come up

0.1.0 / 2012-03-22 
==================

* Removed httplib2 in preference for requests
* Added support for setting headers

0.0.1 / 2012-01-16
==================

* Initial version
