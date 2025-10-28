# Cisco Nexus Hyperfabric AI - Lab Guide
## Lab 01: Create Fabric and BOM using the Hyperfabric designer

## Table of Contents

[Hyperfabric Classic & Beta Modes](#hyperfabric-classic--beta-modes)

[Create a new fabric](#create-a-new-fabric)

[Step 1: Select Fabrics](step-1-select-fabrics)

[Step 2: Click + Add new fabric](#step-2-click--add-new-fabric)

[Step 3: Fill out the dialog box with appropriate names](#step-3-fill-out-the-dialog-box-with-appropriate-names)

[Step 4: Click Save fabric and add cabling. Search for QDD-400G-DR4-S](#step-4-click-save-fabric-and-add-cabling-search-for-qdd-400g-dr4-s)

[Creating Optic BoM](#creating-optic-bom)

[Step 5: Click Preview changes](#step-5-click-preview-changes)

[Step 6: Click Review Configuration. Click Comment and push](#step-6-click-review-configuration-click-comment-and-push)

[Step 7: Go back to Fabrics, click Ellipse. Select Calculate BoM](#step-7-go-back-to-fabrics-click-ellipse-select-calculate-bom)

[Step 8: Click Request estimate ID](#step-8-click-request-estimate-id)

[Step 9: Submit the BoM](#step-9-submit-the-bom)

---

### Create Fabric and BOM using the Hyperfabric designer

Login into Cisco Hyperfabric AI portal using the URL listed below:
https://hyperfabric.cisco.com

Use your CCO ID to login.

<img alt="image" src="https://github.com/user-attachments/assets/b209a4a0-87fe-48d7-a284-c31271e46c87" />

---

### Hyperfabric Classic & Beta Modes

Cisco Nexus Hyperfabric has two fabric modes: classic and beta. You must use the classic mode for non-AI cluster fabrics and beta mode for AI cluster fabrics. Any fabric that you created before the introduction of AI clusters automatically uses the classic mode. You can see all fabrics of either mode from the Fabrics and Inventory pages. However, you must change Cisco Nexus Hyperfabric to the same mode as the fabric to view that fabric's details and modify the fabric.

If you attempt to view the details of a fabric and Cisco Nexus Hyperfabric is in the wrong mode, Cisco Nexus Hyperfabric asks if you want to switch to the correct mode. You can also manually change the mode, as described in this procedure.

**Follow these steps to change the fabric mode.**

Click on the name at top right.
Select Beta and then toggle back to Classic

<img width="285" height="282" alt="image" src="https://github.com/user-attachments/assets/36b06ed5-ddb9-48f8-a6a3-d90b5aa51209" />

---

### Create a new fabric

When you have created a new organization or need to add a fabric to an existing organization, you can use Blueprint Designer in the Cisco Nexus Hyperfabric to create a blueprint for the new fabric.

Follow these steps to create a new fabric.

### Step 1: Select Fabrics

<img width="217" height="70" alt="image" src="https://github.com/user-attachments/assets/e7df47ec-da39-44e6-877a-679713ed4c82" />

<img width="315" height="191" alt="image" src="https://github.com/user-attachments/assets/e138fac8-46af-4eb0-b30b-57fcfedfce46" />

---

### Step 2: Click + Add new fabric

<img width="322" height="228" alt="image" src="https://github.com/user-attachments/assets/2a860847-3080-489a-a955-0bcf9ff8746a" />

---

### Step 3: Fill out the dialog box with appropriate names

- For Fabric name, enter a unique name from 3 to 120 characters. The name can contain a hyphen (-), but no other special characters.
- For Description, enter a description of the fabric.
- For Address, enter the physical address where the fabric is located.
- For Location, enter additional location information about the fabric.
- For Spines, select the quantity of switches (2), the airflow, and the PSU PID. Cisco Nexus Hyperfabric selects the fan PID automatically based on what you select for the airflow.
- For Leaves, select the quantity of switches(2), the airflow, and the PSU PID. Cisco Nexus Hyperfabric selects the fan PID automatically based on what you select for the airflow.
- To design a single-switch fabric or a mesh fabric, select only leaf switches. If you select one or more spine switches, select two or more switches to create a spine-and-leaf topology.
- As you make your switch choices, Cisco Nexus Hyperfabric updates the topology.

---

### Step 4: Click Save fabric and add cabling. Search for QDD-400G-DR4-S

<img width="470" height="452" alt="image" src="https://github.com/user-attachments/assets/09c60502-327f-4ab2-ad08-3af861d404d1" />

Click Save

---

### Creating Optic BoM

### Step 5: Click Preview changes

<img width="390" height="226" alt="image" src="https://github.com/user-attachments/assets/f905522b-4b09-41d2-8806-dbe86a1d442d" />

<img width="393" height="299" alt="image" src="https://github.com/user-attachments/assets/4af202fd-8e22-4ae1-88ec-e0c8f2a0c0ba" />

---

### Step 6: Click Review Configuration. Click Comment and push

<img width="299" height="192" alt="image" src="https://github.com/user-attachments/assets/292aabfc-00b6-4203-8d75-dbcebb596dab" />

---

### Step 7: Go back to Fabrics, click Ellipse. Select Calculate BoM

<img width="468" height="222" alt="image" src="https://github.com/user-attachments/assets/d5c079a2-ba8c-44b9-a91d-0d658aff1404" />

---

### Step 8: Click Request estimate ID

<img width="363" height="288" alt="image" src="https://github.com/user-attachments/assets/fdbba9a1-c7ac-4df7-b286-3d208387e630" />

---

### Step 9: Submit the BoM

<img width="373" height="195" alt="image" src="https://github.com/user-attachments/assets/e6fad830-223e-4d6a-be6f-1b44fb6e3dba" />


**Check your email.** Confirm that you receive an auto generated email.
