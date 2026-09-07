# Car Inventory Assignment

Excel project analyzing car inventory and driver distance.

## What I did:
- Cleaned car inventory data (removed empty rows at top)
- Kept original distance in miles (Column H)
- Calculated Distance per Year in miles: =H/(Age+0.5)
- Converted to km per year: =Distance_per_Year * 1.60934
- Created Pivot Table to show total km per driver
- Created Pivot Chart - Grand Total = 3,759,397 km

## Formulas Used:
Column I (per year miles) = H2/(G2+0.5)
Column J (per year km) = I2*1.60934
Total km = Miles * 1.60934

## Files:
- Car inventory Excel file
- Pivot table and chart screenshot

Tools: Microsoft Excel, Pivot Tables, Excel Formulas
## Dashboard & Results

### Pivot Chart
![Pivot Chart](pivot%20table%20and%20chart.png)

- Grand Total: 3,759,397 km
- Top Driver: Smith
- Conversion used: km = miles * 1.60934
