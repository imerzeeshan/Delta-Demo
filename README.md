In this project, let's build a **Feedback App** by applying the concepts we have learned till now.

### Refer to the image below:

<br/>
<div style="text-align: center;">
<img src="https://assets.ccbp.in/frontend/content/react-js/feedback-app-output-v2.gif" alt="feedback-large-output" style="max-width:70%;box-shadow:0 2.8px 2.2px rgba(0, 0, 0, 0.12)">
</div>
<br/>

### Design Files

<details>
<summary>Click to view</summary>

- [Extra Small (Size < 576px) and Small (Size >= 576px)](https://assets.ccbp.in/frontend/content/react-js/feedback-app-sm-outputs.png)
- [Medium (Size >= 768px), Large (Size >= 992px) and Extra Large (Size >= 1200px) - Feedback Question](https://assets.ccbp.in/frontend/content/react-js/feedback-app-question-lg-output.png)
- [Medium (Size >= 768px), Large (Size >= 992px) and Extra Large (Size >= 1200px) - Thank You Screen](https://assets.ccbp.in/frontend/content/react-js/feedback-app-summary-lg-output-v2.png)
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

- When an emoji is clicked, then the thank you screen should be displayed
- The `Feedback` component receives the `resources` as a prop. It consists of the following properties

  |     Key      |    Data Type     |
  | :----------: | :--------------: |
  |    emojis    | Array \<object\> |
  | loveEmojiUrl |      String      |

- `emojis` consists of list of emoji objects with the following properties in each emoji object

  |   Key    | Data Type |
  | :------: | :-------: |
  |    id    |  Number   |
  |   name   |  String   |
  | imageUrl |  String   |

</details>

<details>
<summary>Implementation Files</summary>
<br/>

Use these files to complete the implementation:

- `src/components/Feedback/index.js`
- `src/components/Feedback/index.css`
</details>

### Important Note

<details>
<summary>Click to view</summary>

<br/>

**The following instructions are required for the tests to pass**

- The love emoji should have the alt as **love emoji**
- The emojis should have the alt equal to `name` value in each emoji object

</details>

<details>
<summary>Colors</summary>

<br/>

<div style="background-color: #ffeeee; width: 150px; padding: 10px; color: black">Hex: #ffeeee</div>
<div style="background-color: #ffc0bb; width: 150px; padding: 10px; color: black">Hex: #ffc0bb</div>
<div style="background-color: #ffebeb; width: 150px; padding: 10px; color: black">Hex: #ffebeb</div>
<div style="background-color: #ffffff; width: 150px; padding: 10px; color: black">Hex: #ffffff</div>
<div style="background-color: #0f172a; width: 150px; padding: 10px; color: white">Hex: #0f172a</div>
<div style="background-color: #1e293b; width: 150px; padding: 10px; color: white">Hex: #1e293b</div>

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
