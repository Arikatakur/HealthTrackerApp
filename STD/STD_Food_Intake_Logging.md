# Software Test Description (STD) for Daily Food Intake Logging

## 1. Introduction
This document describes the test cases for the Daily Food Intake Logging feature.

## 2. Test Cases

### Test Case 1: Log a Food Item
- **Test Case ID**: TC_FOOD_001
- **Objective**: Verify that a user can log a food item.
- **Pre-conditions**: User is logged in.
- **Test Steps**:
  1. Navigate to the Food Logging page.
  2. Enter food details (e.g., "Apple", "100 calories").
  3. Click "Save".
- **Expected Results**: The food item is logged and displayed in the history.

### Test Case 2: Search for a Food Item
- **Test Case ID**: TC_FOOD_002
- **Objective**: Verify that a user can search for a food item in the database.
- **Pre-conditions**: User is logged in.
- **Test Steps**:
  1. Navigate to the Food Logging page.
  2. Enter a food name (e.g., "Banana") in the search bar.
  3. Select the food item from the search results.
- **Expected Results**: The food item is displayed with its nutritional information.
