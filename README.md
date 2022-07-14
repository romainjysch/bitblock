# BitBlock

https://romainjysch.github.io/bitblock/#/

## Context

During my second year of Bachelor in Business Information Technology, I had a two-week course on web services. During the second week, I learned JavaScript and Vue. After receiving theoretical elements about these 2 topics, my schoolmate and I had to code an application as the second project of the course. We have been evaluated on release 2.0 and it had to be done during the second week, in a short time frame (every good developper embraces sleepless nights).

## Use cases

The theme of the application was free. Passionate about blockchain technology and the concept of Web3, we wanted to create an application to search for addresses based on the Binance Smart Chain (BSC) and obtain various information about them :

- BNB balance
- Dollar value relative to the BNB balance and actual BNB price
- (*Under development*) All transactions made through this address

It is also possible to add the address to a watch list in order to analyze information about it later. The watch list page offers the following use cases :

- Display all addresses that have been previously stored in localStorage
- Display the BNB balance of the addresses at the time of addition to the watch list
- Display the current BNB balance of the addresses and changes the text color according to the gain or loss of BNB
- Sort addresses by order of addition to the watch list (oldest to newest) or by BNB held (largest balance to smallest)

## Instructions for the project

- Website must be responsive thanks to Bootstrap (we did the maximum we can, the deadline was to short)
- Application must use multiple components
- Application must use router thanks to an index.js file
- Application must use localStorage
- Project must include a README file describing problems and lessons
- Application could use axios to get external data

## Resources

- Schoolmate
- Teacher
- Web services course material
- MDN Resources for Developers https://developer.mozilla.org/en-US/
- Bootstrap Documentation https://getbootstrap.com/docs/5.1/
- Bootstrap Grid System https://getbootstrap.com/docs/4.0/layout/grid/
- Themes for Bootstrap https://bootswatch.com/
- Icons https://fontawesome.com/
- Node.js https://nodejs.org/en/
- Npm https://www.npmjs.com/
- BscScan Accounts API https://docs.bscscan.com/api-endpoints/accounts
- BscScan Stats API https://docs.bscscan.com/api-endpoints/stats-1
- VS Code Version Control https://code.visualstudio.com/docs/editor/versioncontrol#_git-support