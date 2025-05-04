# Google Apps Script Library Database

<a name="top"></a>
[![MIT License](http://img.shields.io/badge/license-MIT-blue.svg?style=flat)](LICENCE)

<a name="overview"></a>

# Overview

This is for the Google Apps Script Library Database.

<a name="description"></a>

# Description

Since Google Apps Script was released on August 19th, 2009, it is used by a lot of users. [Ref1](https://gist.github.com/tanaikech/4e4f1ca20b8dbce08f87289db415df7d), [Ref2](https://gist.github.com/tanaikech/fd7dbc6d630fd0550c32159635cecc96) By this, now there are a lot of useful libraries of Google Apps Script (GAS) in all over the world. But when I want to search a GAS library, I always use Google search engine. Unfortunately, in the current stage, the libraries cannot be directly searched by a database. On January 11th, 2020, a proposal for the database of Google Apps Script Library has been proposed by [Andrew Roberts](https://github.com/andrewroberts). [Ref3](https://groups.google.com/forum/#!topic/google-apps-script-community/sXO6_vCIbgI) When I have discussing about this with him, I thought that I tried to think of a sample database. So I prepared this.

In the current stage, this is a sample database, yet. I would like to close to a goal for achieving the Google Apps Script Library Database by thinking and discussing.

When this became one of materials for leading the direction for achieving the Google Apps Script Library Database, I'm glad.

# Search application

- **You can search the GAS libraries using this database at [Search Google Apps Script Libraries](https://sites.google.com/view/search-gas-libraries).**

  - I thought that when GitHub repository is used as the database and the GAS libraries are searched by HTML and Javascript, it might be useful.

  - When you can add new GAS libraries to this database, please add them using [this Google Form](https://docs.google.com/forms/d/e/1FAIpQLSckRzFtF-i1CUwdhA21GteWok9p5-_G4Py3PH5bC9KaqXoOxA/viewform) by Andrew Roberts.

# Future developments

- In the current stage, a file including JSON objects of GAS libraries is put in this repository. The GAS library is searched using this file as the database. When the structure of JSON object for GAS library and the format of the file are decided, I would like to increase the number of data.

- At the current search application, the library is searched. As the next step, I would like to think of the installer of the searched library to Google Apps Script project. For this, I hope for being added Google Apps Script API to Advanced Google services.
  - In the current workaround, the GAS library can be installed by the script using [ManifestsApp](https://github.com/tanaikech/ManifestsApp).

# Licence

[MIT](LICENCE)

<a name="author"></a>

# Author

[Tanaike](https://tanaikech.github.io/about/)

If you have any questions and commissions for me, feel free to tell me.

<a name="updatehistory"></a>

# Update History

- v1.1.0 (May 4, 2025)

  1. Major UI/UX enhancement:
     - Responsive design for better mobile experience
     - Modern UI with Google Material Design inspired styling
     - Improved accessibility with ARIA labels and semantic HTML
     - Better error handling and loading states
     - Updated dependencies to latest versions

- v1.0.2 (February 1, 2022)

  1. I noticed that the sheet ID of sheet of Andrew Roberts had been changed. So I used the sheet name of "Libraries" instead of the sheet ID.

- v1.0.1 (May 26, 2020)

  1. Added the duplicate checker.

- v1.0.0 (March 12, 2020)

  1. An application for searching GAS libraries from the database was completed. By this, [the script is published](https://github.com/tanaikech/Google-Apps-Script-Library-Database/blob/master/searchApp.html).

- v1.0.0b (February 17, 2020)

  1. Initial release as a sample.

[TOP](#top)
