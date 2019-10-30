# How to Host Your Résumé on GitHub Pages

## Intended Audience
This instruction set will provide information on how to host your résumé to GitHub Pages. They will help you understand how to use the tools that are required to do so. These tools include Markdown, GitHub, and GitHub Pages. These instructions are intended for a beginner audience. That is, you do not need any experience with the tools that will be described in these instructions.

## Prerequisites (Tools Required Before Starting)
 * To complete these instructions, you must have a **résumé.**
 * **Recommendation:** Use a computer to complete these instructions. It would be difficult to complete these steps using a mobile device. 
 
 ## Instructions on How to Host Your Résumé 
 
 ### 1. Getting Started
 ####   A. Creating a GitHub Account
   In order to host your résumé on GitHub Pages, you will first need to have a GitHub account. The following steps will help you create a GitHub account:   
   1. [Click here](https://github.com/join) to begin initial setup of your account.
   2. Fill in the required fields from the link above to set up your account. You will need to create a username and password.
   3. Click Select a Plan once you have finished filling in the fields, and create a free account. 
   4. You will then arrive at a page that looks something like this: ![welcome to github](https://user-images.githubusercontent.com/57049086/67638774-93dd4900-f8b6-11e9-87b9-acaa70c4e041.JPG)
      Once you arrive at this page you have two options:  
       * Fill out the questions on this page, and hit submit, or,  
       * Scroll to the bottom of the page, and click "skip this step."      
  5. Verify your email.
  6. Once your email was verified, create a new repository by entering a name for it, and then clicking submit. Your repository will be where you store your files. **Note: On the page, it will give you the option of choosing a public or private repository. You can choose either. However, if you would like to use GitHub Pages, you either need to have a public account, or you must have a GitHub Pro account (which costs $7 USD per month).**
  ![Create new repository](https://user-images.githubusercontent.com/57049086/67639423-6ba51880-f8bd-11e9-9bfd-d7cf7545511d.JPG)

   Congratulations! Your GitHub account is now set up and ready for use.
  
#### B. Learn Markdown
 Now that you have created a GitHub account, you will need to learn Markdown! GitHub uses a tool called (GitHub Flavoured) Markdown for formatting/editing documents. Markdown is different than tools you may be familiar with, such as Word. Here are a few of the basics which you may find useful when writing your résumé in Markdown:   
 1. **Headings:**   
    * There are 6 levels of headings in Markdown.   
    * To use headings, begin the line with a "#" then place a space.  
    * The more #'s you include, the smaller the heading will be.
 2. **Bold and _Italic_ Fonts**  
    * In your resume, you may wish to emphasise certain parts by using boldface, or using italics.  
    * To use **boldface:**  
      * Use two astericks (*) at the beginning and the end of the word or phrase you would like bolded. 
    * To use _italicized_ font:  
      * Place an underscore (_) at the beginning and end of the word or phrase you would like bolded. 
 3. **Bulleted and Numbered Lists**    
    * To use lists, they must start on a new line. Also, each item of the list must start on a new line.  
    * To create a new line, put two spaces after the previous line, and hit enter.   
    * To use a bulleted list:
      * Create a new line.
      * Place a "*" character, followed by a space.
      * Do this for each item in the list.
    * Numbered lists follow the same format, just using a number instead of a *. **Be sure to put a period after the number.**  
 
You now know some of the basics to using Markdown! You may find these helpful when writing your résumé. Of course, there is much more to Markdown than just these steps. Check out the ["More Resources"](https://github.com/finnigar/finnigar/blob/master/README.md#more-resources) section of this document for more information on how to use Markdown.

You have now learned the tools you need to get started on hosting your résumé! 

### 2. Converting Your Résumé to Markdown 

Now that you know the basics, you need to convert your résumé to Markdown. To do so, follow these steps:
1. **Choose a text editor.**  
   * In order to work with Markdown, you will need a tool that will allow you to edit text in Markdown format.
   * There are many free text editors that you can choose from. 
   * One recommendation for a text editor is [Atom](https://atom.io/). This is because it works well with both Markdown and Github, and it is relatively simple to use.
   * However, if you try using Atom and do not like it, or do not want to download a text editor, you do not have to use it. 
   * See the ["More Resources"](https://github.com/finnigar/finnigar/blob/master/README.md#more-resources) section for some more recommendations of text editors.

2. **Edit your document.**
    * Now that you have chosen your text editor, you must now edit your document in Markdown format. 
    * Open your text editor.
    * Open a new document in your editor, so that you can begin writing your document.
    * Type your document in the space, being sure to use Markdown formatting.

3. **Save your document**   
  * **Saving your document using a downloaded text editor**
    * Find and click the button that says "Save". Usually, this is under the "File" menu. 
    * Choose a name for your document. Make sure when you name your document, you save it as a **.md file.**
    * **If you do not save it as a .md file, and save it as something else (for example, .docx), it will not be saved in Markdown format properly. Therefore, you will not be able to host your document on GitHub Pages.**  
 * **Saving your document using an online text editor**
    * Click on the "Export As" button
     * Each editor might call it something slightly different, like "Export As", or "Export", or "Download".
    * Click on the .md file type
     * **Make sure that you export it as a .md file. This is the file type that will save it in Markdown format.** 
    * Your document should now download, and should appear in your "Downloads" folder on your computer.
      
    
  Your résumé is now converted to Markdown, and you are ready to host it on GitHub Pages!
  
  ### 3. **Hosting your Résumé on GitHub Pages**
  Now that you have a Markdown formatted résumé, the next step is to host it on GitHub Pages. In order to do so, there are a few steps you need to follow: 
   1. **Upload Your Résumé to Your GitHub Repository**   
      * Go to your GitHub account/repository which you created earlier.   
      * Since you have not uploaded anything yet, you should see a screen which looks something like this:
   ![getting_started](https://user-images.githubusercontent.com/57049086/67641981-16750100-f8d5-11e9-9aea-e000a76fe9dd.JPG)
      * Click on the link that says "upload an existing file."  
      * Find where you saved your document on your computer.  
      * Double-click on the document you wish to upload, and it will upload.   
      * Confirm by clicking "commit changes."   
        * "Commit changes" is essentially GitHub's version of save.  
        * In the box, you can choose to add a message that describes what changes you made. 
        * This is not necessary, but it can be helpful to help you remember what changes you made.
        * If you don't type anything in the box, you will get the default message that describes your action.
        * The commit changes box should look something like this: 
       ![commit changes](https://user-images.githubusercontent.com/57049086/67642143-c9922a00-f8d6-11e9-9350-974d20b44fa8.JPG)
        * Type a description into the box if you wish
        * Click the green "commit changes" button, and your changes will be confirmed.  
   Your résumé should now be in your GitHub repository.
   
   2. **Rename your file**  
      * Go to the homepage of your repository.  
      * It should look something like shown below, just with your file(s) in it.
          ![home](https://user-images.githubusercontent.com/57049086/67642439-d5cbb680-f8d9-11e9-82fc-9e2adc788772.JPG)
        * If you are not at this page, click the "Code" button or click on the name of your repository (the part to the right of the "/" in the above image) to return to it.
      * Click the name of your résumé. You should see something like this: ![pen](https://user-images.githubusercontent.com/57049086/67643581-08c87700-f8e7-11e9-9280-8d5bdaeee53d.JPG)
      * Click on the pen. This will allow you to edit the document. 
      * Click in the box where the name of your file is.
      * Rename your file from it's current name to the name **index.md**. 
        * It must be in this format to publish it on GitHub Pages.
      * Commit your changes.
 3. **Publishing your Résumé to GitHub Pages**  
  Your résumé is now ready to be hosted on GitHub Pages. To host it on GitHub Pages, follow these steps:  
     * Click on the "Settings" tab. This is located near the top of the page on the right hand side, underneath the buttons that say "Unwatch", "Star", and "Fork". 
     * Scroll down until you see a box that is labelled with the heading "GitHub Pages". 
     * Click on the drop-down menu under the heading "Source". You should see something like the image below: ![githubpages](https://user-images.githubusercontent.com/57049086/67643841-acb32200-f8e9-11e9-9be5-f0b962fa240b.JPG)
     * Select the first option from this list (the one that says master branch). This is the option you want to enable GitHub Pages correctly. 
     * Your résumé will now be published on GitHub Pages! 
       * **Note that it will take a few minutes for the page to be ready.**
       * **You will see a link appear. This is where your résumé will be on GitHub Pages.**
       * **If by clicking on the link you get an "Error 404 Site Not Found," it usually means that the site is not quite ready yet (even if GitHub _says_ the site has been published, it still may take a couple more minutes for the site to fully initialize)** 
       * **Wait a few minutes, and your site should be active.**
       * **Click on the link, and view your page live on GitHub Pages!**
  
  
  Congratulations! You have successfully hosted your résumé on GitHub Pages. Now that it is live, you can do things to personalize the site. One of these ways is by setting the theme. You can do so by following the instructions below: 
  
 4. **(Optional Step) Using a Jekyll Theme to Set the Theme of your GitHub Pages Webpage**
      * This step is optional. If you are fine with the default theme, feel free to skip this step. 
      * However, there are many interesting themes that GitHub allows you to use by incorporating something known as Jekyll into their site. 
      * **You do not need to know anything about Jekyll to do this step.**
      * If you would like to change the theme: 
        * If you are not already there, click on the Settings tab.
        * Scroll down until you reach the GitHub Pages (if you are not already there from Step 3).
        * Look for the heading that says "Theme chooser", and click "Change theme" 
        ![theme chooser](https://user-images.githubusercontent.com/57049086/67644808-c5740580-f8f2-11e9-89b0-2d07681e55ca.JPG)
        * You will be redirected to a place where you can choose a theme from a variety of options
        * Click on the theme you wish to apply to your site
        * Click "Apply theme"
   Your site should now have the theme you chose on it. **Note that it may take a few minutes for your theme to apply. If you click on your site and it has not applied the theme, try refreshing the site.** 
   
     * If you would like to edit the title of your page
       * Navigate back to your home repository where your files are located on GitHub. 
       * You should see a new file, called **"_config.yml"** has shown up there.
       * Open this file for editing.
       * Add the line "title:", then type a title for your page.
       
  You now know all the basics of how to host a résumé on GitHub Pages!
  
## More Resources
   * [A walkthrough tutorial on the basics of using Markdown](https://www.markdowntutorial.com/)
   * [Markdown Cheatsheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)
   * [Dillinger: An Online Text Editor](https://dillinger.io/)
   * [StackEdit Text Editor](https://stackedit.io/app#)
   * [More info about GitHub Pages](https://help.github.com/en/github/working-with-github-pages)
   * [Ask and answer questions about GitHub in the GitHub Community Forum](https://github.community/)
   
## Authors and Acknowledgments
 * Author: Ryan Finnigan
 * Acknowledgements go out to the following people: 
   * Credit to Matthew Graham ([mattgraham](https://twitter.com/michigangraham)) for the template.
   * Credit to my group members for peer editing/review: 
     * Amandeep Dhillon
     * Mitul Patel

## FAQs 
  1. **Do I have to use a text editor?**   
      * No. Github will allow you to edit your document directly on Github. However, using a text editor is highly recommended, even if you have experience with Markdown. This is because a text editor will let you see a side-by-side comparison of what you are typing and what it actually looks like in Markdown. If you edit it directly on Github, it does not give you this feature. Therefore, using a text editor will be beneficial to you, as you can see right away if you have the correct syntax or not. For many features of Markdown, there is specific syntax, and it is easy to make mistakes. Thus, it is easier to correct your mistakes while using a text editor than it is to write a whole document, commit your changes, then realize that you have to fix the formatting on the entire document!
      
 2. **I do not like the options I have for themes. Can I use anything else?**
     * You can! However, this is a more complex process. [See this link](https://help.github.com/en/github/working-with-github-pages/adding-a-theme-to-your-github-pages-site-using-jekyll) as a starting point for using other Jekyll themes. [Here are some supported Jekyll themes](http://jekyllthemes.org/).
     


    

