# How to Create a Pivot Table?

```{infonote}
**The Four Basic Elements of a Pivot Table**

- **Rows** – Categories displayed on the left side of the table.
- **Columns** – Categories displayed at the top of the table.
- **Values** – Numbers that are calculated (sum, count, average, etc.).
- **Filters** – Allow you to display only part of the data.
```


## Creating a Pivot Table – Step by Step


### Step 1: Select the Data Table
Click any cell in the table and press *Ctrl + A* on your keyboard.

![Step 1](images/pivot1_sr.png)


### Step 2: Start Creating the Pivot Table
Click on *Insert* (1), *PivotTable* (2), and select *From Table/Range* (3).

![Step 2](images/pivot2_sr.png)


### Step 3: Choose Where to Place Your Pivot Table
You can choose a new worksheet (*New Worksheet*) or a location on the same worksheet (*Existing Worksheet*) (4) (in that case, click the cell where the top left corner of your pivot table will be) (5). Confirm by clicking *Ok*. (6)

![Step 3](images/pivot3_sr.png)


### Step 4: Get to Know the Pivot Table Editor
You set up the pivot table by dragging fields (7) into specific zones (8).

![Step 4](images/pivot4_sr.png)


### Step 5: Add Rows and Values
For the first example from the introduction, we dragged the *fruit* field into the *Rows* zone. We dragged the *quantity [kg]* field into the *Values* zone.

![Step 5](images/pivot5_sr.png)

```{infonote}
The calculation method in the Values area can be changed via the Value Field Settings option. In addition to the default Sum, you can also choose Average, Count, Min, and Max. Note that if you place a text field in the Values area, the pivot table will automatically show the count of that text instead of the sum.
```


### Step 6: Add Columns (Optional)
The table showing how customers paid was created by adding the *payment method* field to the Columns zone (10).

![Step 6](images/pivot6_sr.png)

```{infonote}
If the window on the right for adjusting the pivot table display closes, you can reopen it by clicking any cell in the pivot table and selecting Show field list.
```
### Step 7: Add Filters (Optional)
Adding filters will allow you to quickly extract and display only the values you need from a large amount of data, without changing the original table or making additional calculations.

```{infonote}
Although the pivot table is linked to the original table, changes in it are not updated automatically. After each change, right-click the pivot table and select Refresh to update all results.
```
## Pivot Chart

Data from the pivot table can also be displayed graphically. This way, results become clearer and differences and relationships are easier to spot.

A pivot chart is created as follows:

Click inside the pivot table and from the menu select *PivotChart*. Choose the chart type and confirm your selection.

![Pivot chart](images/chart1_sr.png)

```{infonote}
The chart is linked to the pivot table, which means that any change in the table is automatically shown in the chart. When displaying graphically, the advantages of using filters become especially apparent.
```

![Pivot chart](images/chart2_sr.png)