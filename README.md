In this project, let's build an **Alert Notifications** app by applying the concepts reactjs.

### Refer to the image below:

<br/>
<div style="text-align: center;">
    <img src="https://assets.ccbp.in/frontend/content/react-js/alert-notifications-lg-output.png" alt="Alert Notifications" style="max-width:70%;box-shadow:0 2.8px 2.2px rgba(0, 0, 0, 0.12)">
</div>
<br/>

### Design Files

<details>
<summary>Click to view</summary>

- [Extra Small (Size < 576px) and Small (Size >= 576px)](https://assets.ccbp.in/frontend/content/react-js/alert-notifications-sm-output-v0.png)
- [Medium (Size >= 768px), Large (Size >= 992px) and Extra Large (Size >= 1200px)](https://assets.ccbp.in/frontend/content/react-js/alert-notifications-lg-output-v0.png)

</details>

### Set Up Instructions

<details>
<summary>Click to view</summary>

- Download dependencies by running `npm install`
- Start up the app using `npm start`
</details>

### Completion Instructions

<details>
<summary>Functionality to be added</summary>
<br/>

The app must have the following functionalities

- For each notification, the Notification component should receive the below elements as children
  - Icon
  - Heading
  - Description

</details>

<details>
<summary>Components Structure</summary>
<br/>
<div style="text-align: center;">
    <img src="https://assets.ccbp.in/frontend/content/react-js/alert-notifications-component-breakdown-structure.png" alt="Alert-Notificaions-app-component-breakdown-structure" style="max-width:100%;box-shadow:0 2.8px 2.2px rgba(0, 0, 0, 0.12)">
</div>
<br/>

</details>

<details>
<summary>Implementation Files</summary>
<br/>

Use these files to complete the implementation:

- `src/components/Notification/index.js`
- `src/components/Notification/index.css`
- `src/components/AlertNotifications/index.js`
- `src/components/AlertNotifications/index.css`

</details>

### Important Note

<details>
<summary>Click to view</summary>

<br/>

**The following instructions are required for the tests to pass**

- Access the elements passed to the `Notification` Component using the **children** prop.
- `AiFillCheckCircle` from react-icons should be used for **Success** notification.
- `RiErrorWarningFill` from react-icons should be used for **Error** notification.
- `MdWarning` from react-icons should be used for **Warning** notification.
- `MdInfo` from react-icons should be used for **Info** notification.
- `GrFormClose` from react-icons should be used as **Close** icon in each notification.

</details>

### Resources

<details>
<summary>Colors</summary>

<br/>

<div style="background-color: #64748b; width: 150px; padding: 10px; color: black">Hex: #64748b</div>
<div style="background-color: #2dca73; width: 150px; padding: 10px; color: black">Hex: #2dca73</div>
<div style="background-color: #ff0b37; width: 150px; padding: 10px; color: black">Hex: #ff0b37</div>
<div style="background-color: #ffb800; width: 150px; padding: 10px; color: black">Hex: #ffb800</div>
<div style="background-color: #0f81e0; width: 150px; padding: 10px; color: black">Hex: #0f81e0</div>
<div style="background-color: #e5e5e5; width: 150px; padding: 10px; color: black">Hex: #e5e5e5</div>
<div style="background-color: #0f172a; width: 150px; padding: 10px; color: white">Hex: #0f172a</div>
<div style="background-color: #475569; width: 150px; padding: 10px; color: white">Hex: #475569</div>

</details>

<details>
<summary>Font-families</summary>

- Roboto

</details>


