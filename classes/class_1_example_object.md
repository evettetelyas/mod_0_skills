# evette = Student.new

### Attributes
* name `"Evette Telyas"`
* field_of_study `"Back-End"`
* work_study `false`
* extracirriculars `["Student Government", "Sportsball", "Chess Team"]`
* registered_classes `["Mod0", "Mod1"]`
* num_registered_classes `2`

### Methods
* `declared_major` (uses `#{field_of_study}` to produce Back-End Engineering)
* `evette.add_extracirricular("Cooking Club")` (`["Student Government", "Sportsball", "Chess Team", "Cooking Club"]`)
* `evette.gpa` ((Mod0_grade + Mod1_grade) / 2)
* `evette.add_course("Mod2")` (`["Mod0", "Mod1", "Mod2"]`) and (`num_registered_classes = 3`)
* `evette.drop_course("Cooking Club")` (`["Student Government", "Sportsball", "Chess Team"]`)
