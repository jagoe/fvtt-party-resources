1.1.2
--
* Fixed an issue where a resource's min/max values were not respected when their
  value was 0.
* Pressing CTRL on Windows (CMD on macOS) when clicking the +/- buttons will
  add/subtract 10 instead of 1.
* Pressing SHIFT when clicking the +/- buttons will add/subtract 100 instead of 1.


1.1.1
--
* Made it so longer resource labels (19+ characters) are properly word-wrapped
  instead of bleeding through the +/- buttons.
* Allow for negative values when decrementing resource values.
* Add functionality to not let negative values exceed a given minimum.