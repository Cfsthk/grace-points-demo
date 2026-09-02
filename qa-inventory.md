# Grace Points demo QA inventory

## User-visible claims

- Responsive bilingual app surfaces for teacher, student, and administrator roles.
- Teachers can browse home classes/cross-class subject groups, select students, award points, and reverse transactions.
- Students can use class/class-number access and view their point history.
- Administrators can review teacher participation, add allowance, export CSV, and preview annual rollover.

## Functional checks

- Role controls: teacher → student → administrator → teacher.
- Language control: English → Chinese → English on each major surface.
- Teacher filters: recent P.4 Chinese Red, P.5 English Blue, P.6 Mathematics Green, plus home-class mode.
- Teacher selection: one student, select all, deselect all, search, quick point values, optional reason.
- Award flow: confirmation modal, points increase, allowance decrease, success feedback, activity entry.
- Reversal flow: confirmation, student points decrease, allowance refund, status update.
- Student flow: invalid combination error; demo P.5 愛 12 keypad login; history and logout.
- Admin flow: add 500 allowance; CSV download; rollover confirmation and year change.
- Modal close by button/backdrop/Escape.
- Exploratory: empty roster combination; teacher allowance becoming negative.

## Visual checks

- Desktop 1440×900: teacher workspace, student balance/history, admin participation/rollover.
- Mobile 390×844: teacher roster and sticky reward bar, student login, student history, admin metrics.
- No horizontal overflow, clipped primary actions, overlapping sticky regions, illegible labels, broken modal layering, or weak selected/active states.
- Post-interaction states: selected roster, award modal, student account, administrator top-up modal.
