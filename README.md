# loc-monthly-list-changes

This repository contains a set of saved OpenRefine operations for manipulating the data in [LCSH Monthly Approved Lists](https://classweb.org/approved-subjects/).  

Specifically, the operations parse the text in an individual monthly list and convert into a spreadsheet of all existing terms that have been updated or canceled.  The resulting data includes the subject's identifier, the old version of the term, the new version of the term (if updated), the reason the term was canceled (if applicable), and MARC tags of both the old and new versions, and a link to the term in id.loc.gov.

To use these operations, simply copy and paste the text from an individual monthly list into a new OpenRefine project, then paste the JSON operation history into the "Apply operation history" box in OpenRefine (found under Undo/Redo).

Currently, they only work for LCSH terms, not CYAC, LCDGT, etc.

For more information, see this blog post: [https://elliotdwilliams.github.io/loc-monthly-lists/](https://elliotdwilliams.github.io/loc-monthly-lists/)
