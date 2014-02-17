### Hide Estimated Hours (Redmine Plugin)

**THIS BRANCH DOES NOT WORK AT THE MOMENT, DO NOT USE**

This Redmine plugin reuses the standard "view_time_entries" permission to hide the estimated hours for specific roles from

* **Issues view**
* **Issues edit**
* **Issues grid overview, available columns**
* **Issues grid overview, selectable filter**
* **Issues PDF**
* **REST API Issues Index**
* **REST API Issues Detail**

not optimal hidden from:

* **Issues journal**: solution not optimal, the estimated hours line is still visible, but at least the old and new value is stripped from the output.
* **Issues mail notification**: solution not optimal, mail is sent, when estimated hours change, but at least the old and new value is stripped out.

This plugin is just a limited workaround, i really would love to see this feature implemented in Redmine. If you think so too, please +1 [this Redmine Ticket](http://www.redmine.org/issues/11963).


## Installation

The installation follows the default path for [Redmine plugins](http://www.redmine.org/projects/redmine/wiki/Plugins).


## Usage

Uncheck the "View spent time" permission for any role that should not be able to see estimated hours.


## Requirements

Redmine >= 2.4.0


## License


[http://return1.mit-license.org/](http://return1.mit-license.org/)
