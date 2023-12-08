# Irish Planning Notices

Thanks to [Carlow County Council](https://carlow.ie) for funding development of this module.

This module creates a content type called "Planning Notice" and a view to list the weekly notices.

## Content Type
You create _one_ planning notice page per week, with the title being "YYYY <week-number>", e.g. **2024 Week 01**. Following that, select the correct options for "Week Number", "Year", and "Date" (the date has a default of "next Tuesday" so you should not need to edit this one).

Finally, upload your documents for
 - Applications Made
 - Decisions Made
 - Appeals Received
 - Appeals Decisions

## Listing Page
The list of planning notices is available at `/planning-notices`, e.g. `https://carlow.ie/planning-notices`. This can be changed by editing the view at `/admin/structure/views/view/planning_notices`.

## Responsive Table
The output of the listing page is a HTML `table`. On small screens we have adapted the CSS for this to resember a card, and on large screens a table.

Developed by [Mark Conroy @ Annertech](https://www.annertech.com).