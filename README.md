# openbudgetsav.org
---
## Expense and Revenue Flow Diagram

Expense and Revenue data needs to be merged into a single spreadsheet to populate the flow diagram at [openbudgetsav.org](http://openbudgetsav.org). 

This data will be organized into six fields:
* Budget Year
* Department
* Account Type (Revenue or Expense)
* Non-Discretionary Fund
* Account Category
* Amount.

*The existing parent and child hierarchy needs to be maintained.*

Here's an example: [OpenOakland FY18 Open Budget](https://raw.githubusercontent.com/openoakland/openbudgetoakland/master/_src/data/flow/FY17-18__proposed.csv)

**Note:**
All rows with the code "1010" will be General Fund and all rows without will be Non-Discretionary Fund. Rather than coding the fields we will be placing the respective data points into new columns, i.e. 


## For Contributing Developers
This app is served as a Jekyll site with basic Bootstrap styles and d3.js visualizations. To run the project locally for development, follow these steps:
1. Open your terminal application and enter the following command:
  `$ git clone git@github.com:opensavannah/openbudgetsav.org.git`
2. In the root folder of your username, you shoould now see the directory `openbudgetsav.org`.
3. Navigate into the folder by typing `cd openbudgetsav.org` into the terminal.
4. Once inside the directory, run `$bundle exec jekyll serve`.
5. Jekyll should load and open in your browser at the address `http://localhost:4000`.
