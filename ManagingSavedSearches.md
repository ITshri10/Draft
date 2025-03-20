# Managing Saved Searches
The Saved Search feature allows you to create, access, and save saved searches, making it easy to find specific information and quickly access frequently used search criteria. This document explains how to create and access saved searches.
To learn more about Saved Search, check out [Saved Search](https://docs.hotwax.co/documents/learn-netsuite/integration-tools-and-methodologies/savedsearch).
## Create a New Saved Search
#### 1. Navigate to New Saved Search:
- Open the main menu. Go to the **`Lists`** section.
- Select **`Search`** from the dropdown options.
- Hover over **`New`** and select it to open the New Saved Search page.
#### 2. Choose Search Type
- On the New Saved Search page, you will see multiple search types. Select the appropriate search type based on the data you require, for example:

| Search Type    | Data Type            | Examples                                       |
|---------------|---------------------|-----------------------------------------------|
| Transaction   | Financial Data      | Invoices, Payments, Sales Orders, Purchase Orders |
| Entity Records | Business Relationships | Customer, Vendor, Employee                  |
| Item          | Inventory Data      | Inventory, Products, Service Items           |

- Once you've selected your desired search type, the following steps will help you create a new search:

#### 3. Search Title: 
- Enter a title that is both clear and descriptive, making it easy for others to recognise the associated record type.
#### 4. Public Checkbox: 
- If the Saved Search is useful for other users to retrieve data, make it **PUBLIC**.

{% hint style="info" %}
Do not make it **PUBLIC**, if there is an important process, like a SuiteScript (that exports data externally), is dependent on it
{% endhint %}

#### 5. Criteria Tab: 
- Go to the **`Criteria`** tab to filter and customize your search.
- Select the **`Standard`** subtab, under which you can apply default filters based on your search requirements.
#### 6. Set Description:
- After selecting a filter, to define how the filter functions choose a condition operator such as:
`Any Is`, `Is empty` , `Starts with`, etc.
- Once you set the description, the filter is applied automatically.

#### 7. Modify Filters (Optional):
- You can **`Insert`** new filters or **`Remove`** existing ones even after applying them.

#### 8. Results Tab:  
- Go to the **`Results`** Tab to indicate columns to be included in the search results as well as sort order.
#### 9. Apply Sorting (Optional):
- Set **`Sort By`** to define the primary sorting field.
- Use **`Then By`** options to add secondary and tertiary sorting fields.
#### 10.  Add or Edit Field:
- Click **`Add Row`** at the bottom to add a new field.
- From the dropdown menu, select the appropriate field.
- Click **`OK`** to confirm.
#### 11. Arrange the Column Order:
- Use **`Move Up`** or **`Move Down`** to change the order of columns.
- Use **`Move to Top`** or **`Move to Bottom`** for quick reordering.
#### 12. Save & Run the Search: 
- Click **`Save`** or **`Save & Run`** to apply your changes. 
- Use **`Preview`** to preview or reset changes before finalizing.
## Access a Saved Search
To access specific data based on predefined filters and criteria, follow these steps:
#### 1. Navigate to Saved Searches:
- From the main menu, select ****`Lists`**>`Search`>`Saved Search`******.
- A page displaying all saved searches will appear.
#### 2. Adjust the View:
- Modify the display of listed searches using options from the dropdown near the **`View`** button.
#### 3. Filter and Find a Saved Search:
- Expand the Filters section by clicking **`(+)`**.
- Use the **`Type`** filter to narrow down the list by record type (for example: **“Transactions”** for searches related to Sales Orders, Purchase Orders, etc).
#### 4. Edit and View Options:
Each saved search offers two options:
1. **`Edit`**: Modify the saved search by adjusting filters, sorting options, and columns. Editing steps are similar to creating a new saved search (refer to the `Create a New Saved Search section`).
2. **`View`**: Open the saved search with all settings applied, without making changes.

Following these steps allows you to easily create and access saved searches for data retrieval.
