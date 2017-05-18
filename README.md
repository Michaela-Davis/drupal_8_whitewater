# _Whitewater!_

#### By _**Michaela Davis**_   &nbsp; 5.15.17
# _[Live site link!](http://dev-whitewater.pantheonsite.io/)_

## Description

 This website was created using Drupal 8, a PHP framework.


## Prerequisites

You will need the following things properly installed on your computer:

* [Git](https://git-scm.com/) v2
* [MAMP](https://www.mamp.info/en/downloads/) v4


## Installation

```bash
git clone https://github.com/Michaela-Davis/drupal_8_whitewater.git
cd drupal_8_whitewater
```

* Click on Preferences in your MAMP window and set your document root to the top level of your repository.


## Import the Database

* Open phpMyAdmin and click on the "Import" tab.
  * Leave all the default settings and make sure the character set is "utf-8".
  * Now click on the "Choose File" button next to "Browse your computer" and select the .sql.zip file included in the sites/db-backup folder. It's okay to leave it zipped.
  * Click the "Go" button on the bottom left.

* Create the Database User
  * After importing the .sql.zip file, select the "Privileges" tab and click on "Add User".
  * Use the username `whitewater` and password `whitewater`

* After importing the database, if you have any trouble logging in with your Site Maintenance account, clear your browser's cookies by clearing the browser history.


## Running / Development

* Visit Whitewater! at [http://localhost:8888](http://localhost:8888).
* Use the username `whitewater` and password `whitewater` to login to the Whitewater! site


## Technologies used
* Drupal 8.3.2
* MAMP 4.1.1
* PHP 7.0.15


### License

*MIT license*


Copyright (c) 2017 Michaela Davis All Rights Reserved.
