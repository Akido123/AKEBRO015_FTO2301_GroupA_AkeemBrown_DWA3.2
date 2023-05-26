Feature: Add Items

  Scenario: User adds an item using the "+" button
    Given the user is on the home page
    When the user clicks on the "+" button
    Then a new item input field should appear
    And the user can enter the item details
    And the user can save the item