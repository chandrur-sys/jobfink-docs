# Maßnahme Activation After Measure Number Receipt

### Overview
After the Maßnahme status is updated to **Measure Number Received**, users must configure the Room and Coach details in the Target Location module.

Once these details are saved, the location-specific Maßnahme Maßnahme becomes active in the system.

---

### Prerequisites
- Maßnahme status must be **Measure Number Received**.
- Location-specific Maßnahme must be created.
- User must have edit permission.
- Available Rooms and Coaches must be configured.

---

### Step-by-Step Process

#### Step 1: Open Maßnahme with Measure Number Received Status
1. Login to the application.
2. Navigate to **Maßnahme Management**.
3. Filter Maßnahmes by status **Measure Number Received**.
4. Select the required Maßnahme.

**Expected Result:**  
Maßnahme details page is displayed.

---

#### Step 2: Navigate to Target Location Module
1. Click on the **Target Location** tab.
2. Open the configuration section.

**Expected Result:**  
Target Location settings are accessible.

---

#### Step 3: Select Room and Coach
1. Select the appropriate **Room** from the dropdown.
2. Select the assigned **Coach**.

**Expected Result:**  
Selected Room and Coach are displayed correctly.

---

#### Step 4: Save Configuration
1. Click the **Save** button.

**Expected Result:**  
- Maßnahme details are saved successfully.
- Location-specific Maßnahme Maßnahme status is updated to **Active**.

---

#### Validation Points
- Only active Rooms and Coaches are selectable.
- Fields are mandatory before saving.
- Data is stored without errors.
- Maßnahme appears in active Maßnahme listings.

---

#### Exception Scenarios
- If Room or Coach is not selected, system displays validation message.
- If save fails, Maßnahme remains inactive.
- If user does not have permission, fields are disabled.

---

#### Notes
- Ensure Room and Coach availability before assignment.
- Reassignment requires admin approval.
- Contact support for configuration issues.
