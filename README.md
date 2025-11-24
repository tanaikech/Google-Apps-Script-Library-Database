# Google Apps Script Library Database

<a name="top"></a>
[![MIT License](http://img.shields.io/badge/license-MIT-blue.svg?style=flat)](LICENCE)

<a name="overview"></a>

# Overview

This repository hosts the **Google Apps Script Library Database**.

<a name="description"></a>

# Description

Since its release on August 19th, 2009, Google Apps Script has been adopted by a vast number of users. [Ref1](https://gist.github.com/tanaikech/4e4f1ca20b8dbce08f87289db415df7d), [Ref2](https://gist.github.com/tanaikech/fd7dbc6d630fd0550c32159635cecc96) Consequently, there are now many useful libraries for Google Apps Script available worldwide. However, searching for these libraries typically requires using a standard search engine, as there has historically been no centralized database for them.

On January 11th, 2020, a proposal for a "Google Apps Script Library Database" was made by [Andrew Roberts](https://github.com/andrewroberts). [Ref3](https://groups.google.com/forum/#!topic/google-apps-script-community/sXO6_vCIbgI) After discussing this initiative with him, I developed this repository as a prototype database.

This project aims to serve as a comprehensive resource for the community. I hope this initiative helps guide the direction toward achieving a fully realized Google Apps Script Library Database.

# Search Application

- **You can search the libraries using this database at [Search Google Apps Script Libraries](https://sites.google.com/view/search-gas-libraries).**

  - This web application utilizes this GitHub repository as its data source, allowing users to search for libraries using a fast, responsive interface built with HTML and JavaScript.

  - **Contributing**: If you would like to add new Google Apps Script libraries to this database, please submit them using [this Google Form](https://docs.google.com/forms/d/e/1FAIpQLSckRzFtF-i1CUwdhA21GteWok9p5-_G4Py3PH5bC9KaqXoOxA/viewform) created by Andrew Roberts.

# Future Developments

- Currently, a file containing JSON objects of Google Apps Script libraries serves as the database in this repository. The search application queries this file directly. Once the structure of the JSON objects and the file format are finalized, I aim to significantly increase the number of indexed libraries.

- While the current application focuses on searching, the next step is to explore methods for directly installing the searched libraries into a Google Apps Script project. For this to be seamless, I hope for the Google Apps Script API to be added to Advanced Google Services in the future.
  - *Current Workaround*: Libraries can be installed programmatically using [ManifestsApp](https://github.com/tanaikech/ManifestsApp).

# Licence

[MIT](LICENCE)

<a name="author"></a>

# Author

[Tanaike](https://tanaikech.github.io/about/)

If you have any questions or requests, feel free to contact me.

<a name="updatehistory"></a>

# Update History

- v1.2.0 (November 24, 2025)

  1. **Major Refactoring of `searchApp.html`**:
     - **UI Overhaul**: Redesigned with a modern, dark-themed aesthetic using CSS variables.
     - **Responsive Design**: Optimized layout for laptops, tablets, and smartphones. Mobile users now see a card-based layout for better readability.
     - **Performance**: Removed the Google Charts dependency in favor of a native, lightweight HTML table/grid system.
     - **Functionality**: Added real-time search filtering, column sorting, and improved error handling for data fetching (CORS/Network resilience).

- v1.1.1 (May 9, 2025)
  Updated.

- v1.1.0 (May 4, 2025)

  1. Major UI/UX enhancement:
     - Responsive design for better mobile experience.
     - Modern UI with Google Material Design inspired styling.
     - Improved accessibility with ARIA labels and semantic HTML.
     - Better error handling and loading states.
     - Updated dependencies to latest versions.

- v1.0.2 (February 1, 2022)

  1. I noticed that the sheet ID of the spreadsheet by Andrew Roberts had been changed. The script was updated to use the sheet name "Libraries" instead of the sheet ID.

- v1.0.1 (May 26, 2020)

  1. Added a duplicate checker.

- v1.0.0 (March 12, 2020)

  1. The application for searching Google Apps Script libraries from the database was completed. The source code [is published here](https://github.com/tanaikech/Google-Apps-Script-Library-Database/blob/master/searchApp.html).

- v1.0.0b (February 17, 2020)

  1. Initial release as a sample.

[TOP](#top)
