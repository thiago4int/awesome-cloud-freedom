
# Contributing to Awesome Cloud Freedom

Thank you for considering contributing to **Awesome Cloud Freedom**! We appreciate your help in building a valuable resource that empowers businesses to embrace **cloud-agnostic**, **cloud-native**, and **open-source** solutions. Below you’ll find guidelines on how to contribute to the repository, as well as instructions for adding your own company to the **End-User List**.

## How to Contribute

### 1. Fork the Repository
Start by forking this repository to your own GitHub account.

### 2. Create a New Branch
Create a new branch for your changes:
```bash
git checkout -b feature/your-contribution
```

### 3. Add Your Contribution
Depending on the type of contribution, follow the respective steps:

#### Adding a New Provider
- Navigate to the relevant category (`/databases`, `/kubernetes`, `/app-hosting`, etc.).
- Add a new entry with the following details:
  - **Provider Name** (linked to the website)
  - **Description**: A brief description of what the provider does.
  - **Cloud-Agnostic**: Yes or No
  - **Cloud-Native**: Yes or No
  - **Open-Source**: Yes or No
  - **Self-Hosting**: Yes or No
  - **Free Tier**: Yes or No

  Example:
  ```markdown
  - **[Provider Name](provider-url)**: Description of the service.
    - **Cloud-Agnostic**: Yes
    - **Cloud-Native**: Yes
    - **Open-Source**: Yes
    - **Self-Hosting**: Yes
    - **Free Tier**: Yes
  ```

#### Adding Your Company to the End-User List
If your company uses **cloud-agnostic** or **cloud-native** solutions and you’d like to be listed as an end user, you can add your company to the **End-User List** by following these steps:
1. Navigate to the `/end-user-list/` directory.
2. Create a new file named after your company (e.g., `my-company.md`).
3. Include the following details in your file:
   - **Company Name**
   - **Website**
   - **Cloud Solutions in Use**: Briefly describe the cloud-agnostic or cloud-native solutions your company uses and how they align with your infrastructure goals.
   - **Use Case**: Explain how these solutions help your company in practice.

   Example:
   ```markdown
   ## Company Name: My Company
   - **Website**: [mycompany.com](https://mycompany.com)
   - **Cloud Solutions in Use**: Using Aiven for managed PostgreSQL and Neo4j Aura for graph databases.
   - **Use Case**: We use cloud-agnostic databases to run multi-cloud deployments that scale our business operations while avoiding vendor lock-in.
   ```

### 4. Commit Your Changes
Once your contribution is ready, commit your changes with a descriptive message and sign the commit using GPG:
```bash
git add .
git commit -S -m "YOUR_COMMIT_MESSAGE"
```

---

## Submission Signature

By submitting content to this repository, you agree to have your contributions licensed under the **Creative Commons Attribution-NonCommercial 4.0 International (CC BY-NC 4.0)**. Please include the following snippet in your **commit message** and **pull request** to acknowledge this:

```
I hereby license my contributions under the CC BY-NC 4.0 License.
```

### 5. Submit a Pull Request
Push your changes to your fork:
```bash
git push origin feature/your-contribution
```
Then open a pull request from your forked repository to the **Awesome Cloud Freedom** main repository. Please ensure that your pull request contains the submission signature mentioned above.

---

## Contribution Guidelines

- **Ensure Accuracy**: Please ensure that all details are correct and align with the criteria of cloud-agnostic, cloud-native, or open-source solutions.
  
- **Be Respectful**: Please be respectful of the community and the values of **freedom**, **competition**, and **collaboration** that this repository represents.

- **Align with the Purpose**: All contributions should align with the repository’s focus on **cloud-agnostic**, **cloud-native**, and **open-source** solutions that provide flexibility, promote competition, and empower users to avoid vendor lock-in.

---

## License for Contributions

By contributing to this repository, you agree that your contributions will be licensed under the **Creative Commons Attribution-NonCommercial 4.0 International (CC BY-NC 4.0)** license. This ensures that all contributions remain open and available to the community under the same terms as the repository itself.

---

## Thank You

Thank you for helping build a resource that promotes **freedom**, **flexibility**, and **innovation** in the cloud space. Your contributions are invaluable, and we appreciate your support in empowering the community!
