# Voucher Mapping in Location-Specific Maßnahme

### Overview
After creating a location-specific Maßnahme, users can configure voucher details through the Target Location sub-module.

When the Voucher Received toggle is enabled, the system automatically populates relevant fields based on participant and Maßnahme data.

---

### Prerequisites
- Location-specific Maßnahme must be created.
- At least one participant should be mapped to the Maßnahme.
- Maßnahme objective must be configured.
- User should have edit access.

---

### Step-by-Step Process

### Step 1: Open Location-Specific Maßnahme
1. Navigate to **Maßnahme Management**.
2. Open the required Maßnahme.
3. Click on the created **Location-Specific Maßnahme**.

**Expected Result:**  
Location-specific Maßnahme details page is displayed.

---

### Step 2: Navigate to Target Location Module
1. Open the **Target Location** sub-module.
2. Locate the **Voucher Received** toggle.

**Expected Result:**  
Target Location module is accessible.

---

### Step 3: Enable Voucher Received Toggle
1. Turn ON the **Voucher Received** toggle.

**Expected Result:**  
- Voucher Number field becomes enabled.
- Voucher Number is auto-populated from the first mapped participant (if available).

---

### Step 4: Verify Voucher Number Auto-Population
1. Check the **Voucher Number** field.

**Expected Result:**  
- If any participant has a voucher for This Maßnahme, the first participant’s voucher number is automatically populated.
- If no voucher exists, the field remains editable.

---

### Step 5: Validate Operative Service and Jobcenter Fields
1. Verify that **Operative Service** and **Jobcenter** fields are displayed.

**Expected Result:**  
Field behavior depends on the Maßnahme objective:

| Maßnahme Objective      | Operative Service | Jobcenter |
|-----------------------|------------------|-----------|
| Section 16            | Disabled         | Enabled   |
| Section 45            | Enabled          | Disabled  |

---

### Step 6: Configure Operative Service / Jobcenter Details
1. Select the enabled field (Operative Service or Jobcenter).
2. Verify populated details.

**Expected Result:**
- Operative Service is auto-populated based on location.
- Jobcenter requires manual entry (if enabled).
- Email and Phone Number are auto-populated for selected values.

---

### Step 7: Save Voucher Configuration
1. Review all entered and auto-populated values.
2. Click **Save**.

**Expected Result:**  
Voucher configuration is saved successfully without errors.

---

### Validation Points
- Voucher Number is auto-populated when available.
- Only one of Operative Service or Jobcenter is enabled at a time.
- Disabled fields are not editable.
- Contact details are populated automatically.
- Data is saved correctly.

---

### Exception Scenarios
- If no participant voucher exists, Voucher Number remains empty.
- If Maßnahme objective is not configured, both fields remain disabled.
- System displays validation message for missing mandatory fields.

---

### Notes
- Ensure participant vouchers are properly mapped before enabling the toggle.
- Contact administrator for configuration-related issues.
