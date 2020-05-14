# offlineBudgetTracker

Created by abautista3712 | https://github.com/abautista3712

![npm](https://img.shields.io/npm/v/fs) ![npm](https://img.shields.io/npm/v/inquirer) ![npm](https://img.shields.io/npm/v/axios)

![offlineBudgetTrackerScreenshot](./public/assets/images/offlineBudgetTrackerScreenshot.PNG?raw=true "Offline Budget Tracker")

## Description

offlineBudgetTracker is a progressive web application developed to list and visualize a user's budget by line item. As a progressive web application (PWA), offlineBudgetTracker can be used with internet connection and can tolerate interruptions in internet service. The app is developed with HTML, CSS, JavaScript, nodeJS, express for handle routing, mongoose and IndexedDB for backend data storage, and utilizes service-workers to handle caching and offline access to cached content.

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [License](#license)
- [Contributing](#contributing)
- [Questions](#questions)

## Installation

To install necessary dependencies, run the following command:

```

npm i

```

## Usage

Accessible via: https://desolate-ravine-93919.herokuapp.com/

The user can input the name of the transaction and transaction amount they would like to include into their respectively named fields at the top of the page. Once filled in, if "+ Add Funds" is clicked, a positive value equal to the amount inputted will be added to both the table and graph below. Alternatively, if "- Subtract Funds" is clicked, a negative value equal to the amount inputted will be added to both the table and graph. A running total of all of the transactions is included at the top of the page.

![offlineBudgetTrackerScreenshot](./public/assets/images/offlineBudgetTrackerScreenshot.PNG?raw=true "Offline Budget Tracker")

Offline connectivity can be tested by opening up the Inspector (Ctrl+Shift+I on the Chrome Browser) and clicking on the Network tab. On the Network tab, internet connection for the page can be toggled on/off by selecting either "Online" or "Offline" from the dropdown menu.

When toggled offline (highlighted), transactions can still be added (data will be cached).  
![offlineInputIndexedDB](./public/assets/images/offlineInputIndexedDB.PNG?raw=true "Offline Input Cached to IndexedDB")

When toggled back online (highlighted) and the page is refreshed, the cached transactions will be fetched and will populate the table and graph.  
![onlineFetchAndDisplay](./public/assets/images/onlineFetchAndDisplay.PNG?raw=true "Online Fetch and Display")

## License

None

## Contributing

External contributions are discouraged.

## Questions

<img src="https://avatars1.githubusercontent.com/u/58578177?v=4" alt="avatar" style="border-radius: 16px" width="30" />
    
If you have any questions about this repo, open an issue or contact Abelard Bautista directly at abelardbautista@gmail.com
