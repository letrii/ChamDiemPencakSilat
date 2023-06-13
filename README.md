# Chấm Điểm Pencak Silat
### Copyright (C) 2019 Hải Lăng

Local web page for Vietnamese to record scores for sport match.

Change logs

Version 0.73:
* Fix error at end of match.

Version 0.72:
* Fix bug with showing info.

Version 0.71:
* Fix bug that matches key while setting keys.
* Fix issue preventing showing second screen.

Version 0.70:
* Refactor to use object for maintaining statistical data.
* Count number of score, winning match, and decrease.

Version 0.69:
Refactor and log fight information

Rename onKeyDown to onKey and refactor it to simplify and streamline the
code. Refactor showLoi to show circles in batch instead of individually.

Log fight information for investigation if needed. The information will
be cleared after each match (three or four rounds).
