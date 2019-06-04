# Student

### Attributes
* name (string)
* field_of_study (string)
* work_study (boolean)
* extracirriculars (array)
* registered_classes (array)
* num_registered_classes (integer)
* date_entered (datetime)

### Methods
* `declared_major` (uses `field_of_study` to denote the `declared_major`)
* `add_extracirricular` (adds ``[new_activity]`` to the array of `extracirriculars`)
* `GPA` (adds the total grades for each course in `registered_classes`, divides by `num_registered_classes`)
* `add_course` (adds `[new_course]` to `registered_classes` and +1 to `num_registered_classes`)
* `drop_course` (removes course from `registered_classes` and -1 from `num_registered_classes`)
