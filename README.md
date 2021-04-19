# UOCIS322 - Project 1 #

## Author: Kaetlyn Gibson, kaetlyng@uoregon.edu ##

** Description:**
A "getting started" project for CIS 322, introduction to software engineering,
at the University of Oregon. Uses a tiny web server in Python to convey
understanding of basic web architecture.

Includes the following functionality in pageserver.py:
-  If URL ends with `name.html` or `name.css`
(i.e., if `path/to/name.html` is in document path (from DOCROOT)),
send content of `name.html` or `name.css` with proper http response.
-  If `name.html` is not in current directory Respond with 404 (not found).
-  If a page starts with one of the symbols(~ // ..),
respond with 403 forbidden error. For example, `url=hostname:5000/..name.html`
or `/~name.html` would give 403 forbidden error.

### Credits ###
Michal Young, Ram Durairajan, Steven Walton, Joe Istas.
