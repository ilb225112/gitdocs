# Renaming a GitHub Repository

This guide walks you through the steps to rename a repository on GitHub, including screenshots for each step.

---

## Steps to Rename a GitHub Repository

1. **Navigate to the Repository**
   - Go to [https://github.com](https://github.com) and open the repository you wish to rename.
   
2. **Access Repository Settings**
   - In the repository, click on the **Settings** tab located at the top right of the page.

![image](https://github.com/user-attachments/assets/698e10a6-2a62-44e7-a3c8-df7c5c1ba395)


3. **Locate the Repository Name Field**
   - In the **General** section of the settings, find the **Repository name** field.

    ![image](https://github.com/user-attachments/assets/1e11a028-7ad9-49b4-a6e7-0118cda75218)

4. **Enter the New Repository Name**
   - Type the desired new name for the repository in the **Repository name** field.

5. **Save the New Name**
   - Click the **Rename** button to save the changes.

![image](https://github.com/user-attachments/assets/4304f399-eff9-4f81-9b7b-9be7ab1d72b1)

---

## Important Notes

- After renaming, GitHub will automatically create a redirect from the old repository URL to the new one, so existing links to the old URL will continue to work.
- If you have local clones of this repository, you may need to update the remote URL:
   ```sh
   git remote set-url origin https://github.com/your-username/new-repository-name.git
