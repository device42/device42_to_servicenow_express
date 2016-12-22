[Device42](http://www.device42.com/) is a Continuous Discovery software for your IT Infrastructure. It helps you automatically maintain an up-to-date inventory of your physical, virtual, and cloud servers and containers, network components, software/services/applications, and their inter-relationships and inter-dependencies.


This repository contains script that helps you sync configuration items(CI) data from Device42 to ServiceNow Express.

### Assumptions
-----------------------------
    * This script works with Device42 10.5.0.1473709546 and above

### Requirements
-----------------------------
    * python 2.7.x
    * requests (you can install it with pip install requests or apt-get install python-requests)

### Usage
-----------------------------
	* Copy mapping.xml.sample1 to mapping.xml, then put credentials and fields that you want to sync as in sample
	* Run the script! (`python sync.py`)

### Compatibility
-----------------------------
    * Script runs on Linux and Windows

### Info
-----------------------------
    * mapping.xml - file from where we get fields relations between D42 and ServiceNow Express
    * lib.py - file with integration description, we describe how fields should be migrated
    * sync.py - initialization and processing file, where we prepare API calls

### Support
-----------------------------
This ServiceNow Express mapping / sync script is provided as-is without any support. We do provide fee-based professional services/support if you need help with this script.  To find out more please email sales@device42.com with subject ServiceNow Express script support.