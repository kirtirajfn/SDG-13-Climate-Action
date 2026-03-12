# Test Cases

## Feature: Carbon Calculator

**TC-01**
- What I tested: Entering 20km car trip (petrol)
- What I expected: Transport CO2 value should be greater than 0
- What happened: Shows 4.2 kg CO2 ✓

**TC-02**
- What I tested: Leaving all fields at 0 and clicking calculate
- What I expected: Total should show 0.0 kg
- What happened: Total correctly shows 0.0 kg ✓

## Feature: Results Page

**TC-03**
- What I tested: Clicking calculate after filling in all 4 categories
- What I expected: All 4 breakdown cards should appear
- What happened: Transport, Energy, Food and Consumption all showed up ✓

**TC-04**
- What I tested: Checking the bar chart after calculating
- What I expected: Bars should reflect each category's value
- What happened: Bars animated and showed correct proportions ✓

## Feature: Status Indicator

**TC-05**
- What I tested: Entering high values to push total above 13kg
- What I expected: Status tag turns red and says High
- What happened: Tag turned red correctly ✓

**TC-06**
- What I tested: Entering low values to keep total below 5kg
- What I expected: Status tag turns green and says Low
- What happened: Tag turned green correctly ✓

## Feature: History Tab

**TC-07**
- What I tested: Clicking History tab after calculating
- What I expected: Todays entry should appear in the table
- What happened: Entry logged with correct date and values ✓

## Feature: Eco Tips

**TC-08**
- What I tested: Clicking the Tips tab
- What I expected: At least 6 tips should be visible
- What happened: 6 tips displayed with impact levels ✓

## Bugs Found During Testing
- Bar chart labels overlapped on small screen — fixed by adjusting font size
- History tab showed no entry if calculate was not clicked first — added reminder text
