Feature: Remove Items

  Scenario: User removes an item using the "-" button
    Given the user is on the home page
    And there are existing items on the page
    When the user clicks on the "-" button next to an item
    Then the item should be removed from the list
    And the item count should decrease by 1