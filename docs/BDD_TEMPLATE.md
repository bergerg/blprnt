# BDD Scenarios: <name>

Optional companion to the feature/use-case spec. Define concrete scenarios in Given-When-Then to validate that code matches intent.

## Scenario: <happy path title>

```
Given <initial context>
  And <additional context>
 When <action is performed>
  And <additional action>
 Then <observable outcome>
  And <additional outcome>
```

## Scenario: <edge case / error title>

```
Given <initial context>
  And <additional context>
 When <action is performed>
 Then <observable outcome>
```

---

### Format reference

```
Scenario: <title>
  Given <context / preconditions>
    And <more context>
   When <trigger / action>
    And <more action>
   Then <expected result>
    And <more results>
```
