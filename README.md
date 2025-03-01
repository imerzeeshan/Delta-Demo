In this project, let's build a **Registration Form** by applying the concepts we have learned till now.

### Refer to the image below:

<br/>
<div style="text-align: center;">
    <img src="https://assets.ccbp.in/frontend/content/react-js/registration-form-output-v2.gif" alt="registration form desktop output" style="max-width:90%;box-shadow:0 2.8px 2.2px rgba(0, 0, 0, 0.12)">
</div>
<br/>

### Design Files

<details>
<summary>Click to view</summary>

- [Extra Small (Size < 576px) and Small (Size >= 576px)](https://assets.ccbp.in/frontend/content/react-js/registration-form-sm-outputs.png)
- [Medium (Size >= 768px), Large (Size >= 992px) and Extra Large (Size >= 1200px) - Registration](https://assets.ccbp.in/frontend/content/react-js/registration-form-lg-output-v2.png)
- [Medium (Size >= 768px), Large (Size >= 992px) and Extra Large (Size >= 1200px) - Registration Error](https://assets.ccbp.in/frontend/content/react-js/registration-form-lg-error-output-v2.png)
- [Medium (Size >= 768px), Large (Size >= 992px) and Extra Large (Size >= 1200px) - Registration Success](https://assets.ccbp.in/frontend/content/react-js/registration-form-lg-success-output-v2.png)

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

- Display an error message with the text **Required** for an empty field on blur
- When the **Submit** button is clicked, display an error message with the text **Required**,
  - if only the first name is provided
  - if only the last name is provided
  - if both first name and last name are not provided
- Display the [Registration Success View](https://assets.ccbp.in/frontend/content/react-js/registration-form-lg-success-output-v2.png) on successful submit
- When **Submit Another Response** button is clicked, then the form should be displayed

</details>

<details>
<summary>Implementation Files</summary>
<br/>

Use these files to complete the implementation:

- `src/components/RegistrationForm/index.js`
- `src/components/RegistrationForm/index.css`

</details>

### Quick Tips

<details>
<summary>Click to view</summary>
<br>

- The `blur` event happens when an HTML element has lost focus

  ```jsx
  <input onBlur={eventHandler} />
  ```

- You can use the `box-shadow` CSS property to apply the box-shadow effect to containers

  ```
    box-shadow: 0px 4px 16px 0px #bfbfbf;
  ```

  <br/>
   <img src="https://assets.ccbp.in/frontend/content/react-js/box-shadow-img.png" alt="box shadow" style="width:200px" />

- You can use the `cursor` CSS property to specify the mouse cursor to be displayed when pointing over an element

  ```
    cursor: pointer;
  ```

  <br/>
   <img src="https://assets.ccbp.in/frontend/content/react-js/cursor-pointer-img.png" alt="cursor pointer" style="width:100px" />

- You can use the below `outline` CSS property for buttons and input elements to remove the highlighting when the elements are clicked

  ```
    outline: none;
  ```

</details>

### Resources

<details>
<summary>Image URLs</summary>

- [https://assets.ccbp.in/frontend/react-js/success-icon-img.png](https://assets.ccbp.in/frontend/react-js/success-icon-img.png) alt should be **success**

</details>

<details>
<summary>Colors</summary>

<br/>

<div style="background-color: #ea580c; width: 150px; padding: 10px; color: black">Hex: #ea580c</div>
<div style="background-color: #475569; width: 150px; padding: 10px; color: white">Hex: #475569</div>
<div style="background-color: #cbd2d9; width: 150px; padding: 10px; color: black">Hex: #cbd2d9</div>
<div style="background-color: #9aa5b1; width: 150px; padding: 10px; color: black">Hex: #9aa5b1</div>
<div style="background-color: #ffffff; width: 150px; padding: 10px; color: black">Hex: #ffffff</div>
<div style="background-color: #fef2f4; width: 150px; padding: 10px; color: black">Hex: #fef2f4</div>
<div style="background-color: #ff0b37; width: 150px; padding: 10px; color: white">Hex: #ff0b37</div>

</details>

<details>
<summary>Font-families</summary>

- Roboto

</details>

> ### _Things to Keep in Mind_
>
> - All components you implement should go in the `src/components` directory.
> - Don't change the component folder names as those are the files being imported into the tests.
> - **Do not remove the pre-filled code**
> - Want to quickly review some of the concepts you’ve been learning? Take a look at the Cheat Sheets.
