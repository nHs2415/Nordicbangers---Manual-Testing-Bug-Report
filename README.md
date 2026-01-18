# QA Assignment - NordicBangers Website Testing

## 📋 Project Overview

This repository contains comprehensive bug reports and testing documentation for the **NordicBangers** e-commerce website as part of the QA Intern assignment evaluation process.

**Website Tested:** [https://www.nordicbangers.com/](https://www.nordicbangers.com/)  
**Testing Period:** January 2026  
**Tester:** Nuwani Hansika Sandamali

---

## 🎯 Assignment Objectives

The purpose of this assignment is to evaluate:
- Clarity in bug reporting
- Understanding of basic QA concepts
- Ability to observe and explain problems
- Attention to detail in manual testing

---

## 🐛 Bugs Identified

### Summary Overview

| Bug ID | Title | Severity | Priority | Status |
|--------|-------|----------|----------|--------|
| BUG_001 | Navigation Bar positioned below viewport on mobile | Major | High | Open |
| BUG_002 | Cart quantity display inconsistency | Critical | High | Open |
| BUG_003 | Navigation Bar not visible in mobile view | Major | High | Open |
| BUG_004 | Incorrect product categorization (Skulls in Fruit category) | Major | High | Open |
| BUG_005 | Duplicate Hero section in navigation | Major | Low | Open |
| BUG_006 | Confusing "Sign in" options for new users | Major | Medium | Open |
| BUG_007 | Promotional offer ($50 surprise candy) not applied | Critical | High | Open |
| BUG_008 | "Add to Cart" broken in Pick & Mix category | Critical | Critical | Open |

---

## 🔍 Critical Bugs (Immediate Action Required)

### 1. **BUG_008: Add to Cart Functionality Broken (Pick & Mix Category)**
- **Impact:** Complete revenue loss from entire product category
- **Description:** Items cannot be added to cart from Pick & Mix section despite visual confirmation
- **Business Impact:** Direct loss of sales

### 2. **BUG_007: Promotional Offer Not Applied**
- **Impact:** Customer trust and potential legal issues
- **Description:** "$50 surprise candy" promotion shown but not applied to qualifying orders
- **Business Impact:** False advertising, customer dissatisfaction

### 3. **BUG_002: Cart Quantity Not Updating**
- **Impact:** Checkout process affected
- **Description:** Cart shows incorrect quantity when items added
- **Business Impact:** Transaction accuracy issues

---

## 📊 Bugs by Category

### **E-commerce Functionality (Critical)**
- Add to cart failures
- Cart quantity discrepancies
- Promotional offer not applying

### **UI/UX Issues**
- Mobile navigation problems
- Duplicate menu items
- Confusing sign-in flow

### **Content/Data Quality**
- Product categorization errors

---

## 🧪 Testing Approach

### Test Types Performed
1. **Functional Testing** - Core e-commerce features (cart, checkout, navigation)
2. **UI/UX Testing** - User interface consistency and usability
3. **Responsive Testing** - Mobile and desktop viewport compatibility
4. **Content Testing** - Product categorization and data accuracy
5. **Cross-browser Testing** - Compatibility across different browsers

### Testing Tools Used
- Browser Developer Tools (Chrome DevTools)
- Device Emulation for responsive testing
- Manual exploratory testing
- Excel for bug tracking and documentation

### Browsers Tested
- Google Chrome (Primary)
- Additional browser testing recommended

### Devices Tested
- Desktop (1920x1080)
- Mobile emulation (375x667, 414x896)
- Tablet emulation (768x1024)

---

## 📝 Bug Report Format

Each bug report includes:

1. **Defect ID** - Unique identifier (BUG_XXX)
2. **Defect Title** - Clear, concise description
3. **Defect Description** - Detailed explanation of the issue
4. **Module** - Affected page/section
5. **Steps to Reproduce** - Exact steps to replicate the bug
6. **Expected Result** - What should happen
7. **Actual Result** - What actually happens
8. **Severity** - Impact level (Critical, Major, Minor)
9. **Priority** - Urgency of fix (Critical, High, Medium, Low)
10. **Screenshots** - Visual evidence (where applicable)

---

## 🎨 Severity & Priority Definitions

### Severity Levels
- **Critical:** System crash, data loss, revenue blocking
- **Major:** Major functionality broken, significant UX issues
- **Minor:** Cosmetic issues, minor inconveniences

### Priority Levels
- **Critical:** Fix immediately (revenue/business blocking)
- **High:** Fix in current sprint
- **Medium:** Fix in next sprint
- **Low:** Fix when time permits

---

## 📸 Screenshots

All bugs are documented with visual evidence in the `/screenshots` directory. Screenshots include:
- Full page context
- Relevant UI elements highlighted
- Console errors (where applicable)
- Mobile vs Desktop comparisons

---

## 🔧 Recommendations

### Immediate Fixes Required
1. Fix Pick & Mix cart functionality (BUG_008)
2. Resolve promotional offer logic (BUG_007)
3. Fix mobile navigation positioning (BUG_001, BUG_003)

### Short-term Improvements
1. Audit product categorization system
2. Implement better error handling and user feedback
3. Review cart update logic
4. Improve sign-in/sign-up user flow

### Long-term Suggestions
1. Implement automated testing for cart functionality
2. Add comprehensive mobile testing to QA process
3. Create style guide for consistent UI/UX
4. Implement analytics to track user friction points

---

## 📈 Testing Metrics

- **Total Bugs Found:** 8
- **Critical Bugs:** 2
- **Major Bugs:** 5
- **Minor Bugs:** 1
- **Pages Tested:** 6+
- **Time Spent:** ~4 hours

---

## 🚀 How to Use This Repository

### For Reviewers
1. Review `Bug Report Assignment Answers.xlsx` for detailed bug documentation
2. Check `/screenshots` folder for visual evidence
3. Verify bugs by following "Steps to Reproduce" on live website

### For Developers
1. Review bug reports in Excel file
2. Reference screenshots for visual context
3. Prioritize fixes based on Severity/Priority ratings
4. Update bug status once resolved

---

## 📧 Contact Information

**Tester:** Nuwani Hansika Sandamali  
**Role:** QA Intern Candidate  
**Testing Date:** January 2026

For questions or clarifications about any bug report, please open an issue in this repository.

---

## 📄 License & Usage

This bug report is submitted as part of a QA internship assignment evaluation. All findings are documented for educational and professional assessment purposes.

---

## ✅ Next Steps

1. **Review & Validation** - Development team to verify reported bugs
2. **Prioritization** - Product team to prioritize fixes based on business impact
3. **Assignment & Fix** - Developers assigned to critical bugs
4. **Regression Testing** - Re-test after fixes are deployed
5. **Sign-off** - QA approval after verification

---

## 📚 Additional Resources

- [Original Assignment Brief](./QA%20test.pdf)
- [NordicBangers Website](https://www.nordicbangers.com/)
- [Bug Report Excel](./Bug%20Report%20Assignment%20Answers.xlsx)

---

**Last Updated:** January 18, 2026  
**Status:** Testing Complete - Awaiting Review

---

*This documentation demonstrates attention to detail, clear communication, and systematic approach to quality assurance - key skills for a successful QA professional.*
