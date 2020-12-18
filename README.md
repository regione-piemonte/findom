# Project Title
FINDOM - Finanziamento Domande

# Project Description
This product allow the authenticated user to insert-edit-delete funding request to access at the European Regional Developement Found

# Getting Started
This product is composed by these components:
- [FINDOMROUTER](https://github.com/regione-piemonte/findom-findomrouter) (web application that allows users to login, search, create and delete "funding request")
- [FINDOMWEBNEW](https://github.com/regione-piemonte/findom-findomwebnew) (web application that allows users to create and visualize pages of one or more "funding request")
- [FINDOMDB](https://github.com/regione-piemonte/findom-findomdb) (scripts to popolate the database schema)
- [FINDOMWEBRES](https://github.com/regione-piemonte/findom-findomwebres) (graphics resources (css, img and js))
- [BLOCCHETTI](https://github.com/regione-piemonte/findom-blocchetti) (library of bricks needed to compose a "funding request")
 
Clone all these components by the git repository

# Prerequisites
A Postgresql user/schema with CREATE/INSERT/UPDATE/DELETE privileges
An instance of Redhat JBOSS EAP 6.4
An instance of Web Server (es Apache)

# Installing
Create the DB schema and fill it with the scripts of the findomdb component.
Configure the findomrouter and findomwebnew components to access the DB schema.
Put the findomwebres component on the static resource folders of the Web Server.
Build and deploy findomrouter and findomwebnew components under the target folder on your JBOSS EAP instance/partition

# Contributing
Please read CONTRIBUTING.md for details on our code of conduct, and the process for submitting pull requests to us.

# Versioning
We use Semantic Versioning for versioning. (http://semver.org)

# Authors
See the list of contributors who participated in this project in file AUTHORS.txt.

#Copyrights
See the list of copyrighters in this project in file Copyrights.txt

# License
Licensed under the EUPL-1.2-or-later. See the LICENSE.txt file for details
