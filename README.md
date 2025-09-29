# Funda Smoke Test Suite

This project contains 5 automated smoke tests for the Funda website using C#, .NET, Playwright, xUnit, and Allure for reporting.

## 🎯 Objective

To validate critical user flows on the Funda website that help ensure confidence during releases. These tests are designed to be fast, reliable, and scalable up to ~200 tests in the future.

## 🧪 Smoke Tests Included

1. **Login Test** – Verifies login and logout functionality.
2. **Landing Page Test** – Validates UI elements and navigation on the landing page.
3. **Property Details Test** – Ensures property card and details page show consistentinformation.
4. **Search Test** – Performs a city-based search and validates results.
5. **Sort Test** – Sorts search results by price and verifies correct ordering.

## 🛡️ Robot Detection Handling

To bypass robot detection, the provided user agent is used