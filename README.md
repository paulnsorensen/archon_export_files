archon_export_files
===================

A script written to export digital library files from an archon instance

### Usage

Download the script to your local machine, and make sure it's executable (`chmod +x`) and that you have python installed.
Your terminal should look like the following. You will need to input your archon URL, username and password (it will be hidden).
The example below shows what it would look like using it upon the sandbox:

    $ python export_files.py
      Archon URL (e.g. http://sandbox.archon.org/latest/): http://sandbox.archon.org/latest/
      Username: guest
      Password: [hidden]
      Directory created, retrieving files...
      Successfully exported digital library files!
      
### Output

The script will extract the files out of your archon instance and place them in a local folder called `archon_fileexport`.
This folder will appear in the same directory from which you run the export script and will contain folders with a numerical
value (the corresponding archon file ID) which contain the images.


### Requirements

* A local machine with python installed
* An archon instance running version 3.20 or above
