# Project Getting to know each other TEAMS

## Author(s)
- Jayrell Garcia, Daniel Jazowski, Hima Madhavan, and Brian Gutt


## Credits
- All content is orginal

## Build and Execution Instructions
### Prerequisites:
- Windows 10 or MacOS
- VS Code (or any preferred code editor)
- Firefox or Chrome (for testing)
- Basic knowledge of HTML, CSS, and JavaScript


### Build Instructions:
1. Clone the GitHub repository to your local machine using the following command:
git clone [repository_url]
Replace `[repository_url]` with the URL of your GitHub repository.

2. Open the project folder in VS Code or your preferred code editor.

3. Navigate to the `index.html` file and open it in your code editor.

4. Run the HTML and CSS files to make ensure the web page runs properly. Edit any changes if needed. 

5. Save your changes.

### Execution Instructions:
1. Once you've made the necessary changes to program files, you can preview the web page locally by opening the `index.html` file in your web browser.

2. To deploy the website:
- Commit and push your changes to the GitHub repository using the following commands:
  ```
  git add -A
  git commit -m "Your commit message"
  git push 
  ```

3. To deploy the website to Azure Static Websites:
- Log in to the Azure Portal.
- Create a new Azure resource, specifically  a web page,  if you haven't already done so.
- Enable continuous deployment and link your GitHub repository in the organization.
- Configure Azure static websites to automatically update when GitHub is updated.

4. Ensure that your GitHub organization and repository settings allow for Azure Static Websites deployment.

5. After pushing your changes to GitHub, Azure  should automatically update with the latest changes from the GitHub repository.

6. Test the deployed website on Azure Static Websites to ensure compatibility.

7. Make any necessary updates or changes to the codebase, commit, and push them to GitHub. Azure Static Websites will automatically update with the latest changes.

