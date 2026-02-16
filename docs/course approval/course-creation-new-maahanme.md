# Maßnahme Creation – New Maahanme 

### Overview
 
The **Maßnahme Creation** page allows users to create and manage new Maßnahme in the OneHermes system.

This screen is accessed by clicking the **( + ) icon** from the Maßnahme Management module.

---

### Screen Name

**GlobalMaßnahme – Maßnahme Creation**

---

#### Field Description

| Field Name                  | Mandatory | Description |
|-----------------------------|-----------|-------------|
| Maßnahme Name                 | Yes (*)   | Enter the name of the Maßnahme. |
| Trager Certificate          | Yes (*)   | Dropdown values are reflected from the active company certifications. |
| Maßnahme Status               | No        | Automatically displays **Newmassnahme** by default. |
| Fachkundige Stelle          | Yes (*)   | Dropdown values are fetched from the Organization table where Organization Type = Fachkundige Stelle. Preferred organizations are listed first. |
| E-mail Address              | Yes (*)   | Auto-populated based on the selected Fachkundige Stelle. |
| Phone Number                | No        | Auto-populated based on the selected Fachkundige Stelle. |
|Maßnahme Certificate Number| Yes (*)   | The field becomes enabled only after the course is approved. |
| Start Date                  | No        | The field becomes enabled only after the course is approved. |
| End Date                    | No        | The field becomes enabled only after the course is approved. |
| Recertification Trigger     | No        | The field becomes enabled only after the course is approved. |

---

#### Functional Behavior

#### 1. Maßnahme Creation Access

Click the **+ icon** in the Maßnahme Management screen.
The Maßnahme Creation page will be displayed.

---

#### 2. Maßnahme Name

User must enter a valid Maßnahme name.
This field is mandatory.

---

#### 3. Trager Certificate

Dropdown values are loaded from:
  - Active Company Certifications.
Only active certificates will be displayed.

---

#### 4. Maßnahme Status

Automatically set as **Newmassnahme**.
This field is non-editable by default.

---

#### 5. Fachkundige Stelle

Dropdown values are fetched from the **Organization Table**.
Only organizations with:

will be displayed.
Preferred organizations appear at the top.

---

#### 6. Auto-Populated Fields

When a **Fachkundige Stelle** is selected:

E-mail Address → Auto-filled
Phone Number → Auto-filled

These values are fetched from the selected organization details.

---

#### 7. Approval-Based Field Enablement

Some fields remain disabled initially.
After the Maßnahme is **Approved**, the remaining fields become enabled.

Example:
Certificate fields
Validity fields
Recertification fields

---

### Validation Rules

| Validation Type | Rule |
|----------------|------|
| Mandatory Check | Maßnahme Name, Trager Certificate, Fachkundige Stelle, Email, Certificate Number must not be empty |
| Dropdown Validation | Only configured values can be selected |
| Auto Population | Email and Phone must load correctly after selecting Fachkundige Stelle |
| Approval Validation | Fields must enable only after approval |

---

**Action Buttons**


**Save Button**

Saves the Maßnahme details.
Performs all validation checks before saving.

**Clear Button**

Clears all entered values.
Resets the form.

---

**Sample Workflow**

1. Click **+ icon**.
2. Enter **Maßnahme Name**.
3. Select **Trager Certificate**.
4. Verify **Maßnahme Status = Newmassnahme**.
5. Select **Fachkundige Stelle**.
6. Check auto-filled **Email & Phone**.
7. Enter Certificate Number.
8. Select Dates.
9. Click **Save**.


---

**Related Modules**

Maßnahme Management
Organization Management
Certification Management

---