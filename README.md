Robot Framework Example for Searching Scrum Alliance in Google
====

Setup Development Environment
----

```
pip install -r requirements.txt
```

The scenario is as below:

```
    Given I Am At Google Page
    When I Search For Scrum Alliance
    Then I Should See Scrum Alliance Website
```

Notes

* I use [Sublime](http://www.sublimetext.com/) with [robot plugin](https://github.com/shellderp/sublime-robot-plugin) to edit the robot framework specification.
* [How to install python](http://juacompe.wordpress.com/2013/02/25/how-to-install-virtualenv-and-virtualenvwrappe/)
* [Robot Framework Website](http://robotframework.org/)
* [BuiltIn Keywords](https://robotframework.googlecode.com/hg-history/2.1/doc/libraries/BuiltIn.html)
* [Selenium2Library Keywords](http://rtomac.github.io/robotframework-selenium2library/doc/Selenium2Library.html)
