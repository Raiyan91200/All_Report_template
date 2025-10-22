# Project Documentation

## 📋 Overview

This repository contains comprehensive testing documentation for two different projects:

1. **Desh Explorer** - Bug Report for Group Tour functionality
2. **OrangeHRM** - Complete Test Suite for Homepage functionality

---

## 🐛 Desh Explorer - Bug Report

### Critical Bug: Group Tour Slot Overbooking

**Assignee:** *[Pending Assignment]*  
**Status:** To Do  
**Severity:** Critical  
**Priority:** High  

#### 🎯 Bug Description
In the Group Tour section, users can successfully purchase slots even when attempting to book more seats than are available. The system shows an error message but still proceeds to the payment page where the transaction can be completed.

#### 🔍 Steps to Reproduce
1. Open Google Chrome on Windows
2. Navigate to `https://desh-explorer.web.app/group-tour`
3. Select a tour with available seats
4. Enter a booking quantity greater than available seats
5. Click "Book Now"
6. Fill payment information
7. Complete the payment process

#### ✅ Expected Result
- System shows error message
- User is redirected back to group tour page
- Transaction is prevented

#### ❌ Actual Result
- System shows error message but proceeds to payment page
- User can complete the transaction despite insufficient seats
- Overbooking occurs

#### 📎 Attachments
- Screenshot: [View Here](https://drive.google.com/file/d/1aYDgbL0pAUQu44o-urPFxEMb2bG879OF/view?usp=drive_link)

---

## 🧪 OrangeHRM - Test Documentation

### Project Information
- **Project:** Homepage of https://www.orangehrm.com/
- **Test Objective:** Verify that all homepage features work correctly
- **Test Authors:** Raiyan, Pritom, Syed Raiyan Nasim
- **Version:** V1
- **Execution Date:** October 15-16, 2025

### 📊 Test Summary

#### Test Case Results (Sheet: Final 2)
- **Total Test Cases:** 19
- **Passed:** 16 cases (84.2% pass rate)
- **Failed:** 3 cases
- **No Warning/Error cases**

#### Key Failed Test Cases:
1. **TC12:** Phone number validation in 30-day trial form
2. **TC15:** Image visibility (75% width issue)
3. **TC16:** Download button visibility on 1366×768 resolution

### 🔧 Test Environment
- **Primary Browser:** Brave (Chromium: 141.0.7390.70)
- **Mobile Testing:** Android Device with Chrome
- **Prerequisites:** Stable internet connection

### 📋 Test Coverage Areas

#### ✅ Functionality Tests
- Homepage loading and element visibility
- Navigation menu functionality
- Language switching (English to Spanish)
- Form submissions (valid/invalid data)
- Link validation and redirections
- Mobile responsiveness

#### ✅ User Interface Tests
- Image visibility and alt text
- Button visibility and functionality
- Text alignment and readability
- Accordion functionality

#### ✅ Edge Cases
- Invalid URL handling (404 pages)
- Form validation with empty fields
- Invalid input handling (alphabets in number fields)

### 🎯 Critical Test Scenarios

#### High Priority Tests:
1. Homepage element loading
2. Navigation menu functionality
3. Demo form submission with valid data
4. Email input functionality
5. Subpage data accuracy

### 📁 Document Structure

The test documentation is organized across multiple sheets:

1. **Final 2** - Detailed test cases with results
2. **CheckList** - Priority-based checklist with status
3. **test case** - Alternative test case formatting

### 🚨 Known Issues

1. **Phone Number Validation:** System accepts alphabets in phone number fields
2. **Image Display:** Images display at 75% width instead of full width
3. **Button Visibility:** Download button not clearly visible on 1366×768 resolution
4. **Navigation Menu:** Only Pricing button directly navigates; others are dropdowns

### 📝 Recommendations

1. Implement proper phone number validation to reject alphabetic characters
2. Fix image width display issues
3. Improve button visibility on lower resolutions
4. Enhance 404 page design
5. Address text wrapping issues in blog cards

---

## 🔄 Next Steps

1. **Immediate:** Assign and fix the Critical bug in Desh Explorer
2. **Priority:** Address failed test cases in OrangeHRM
3. **Follow-up:** Re-test fixed functionalities
4. **Documentation:** Update test cases based on resolution

---

*Last Updated: October 2025*
