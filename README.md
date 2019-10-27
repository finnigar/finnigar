# How to Host Your Résumé on GitHub Pages

## Intended Audience
This instruction set will provide information on how to host your résumé to GitHub Pages. They will help you understand how to use tools that are required to do so. These tools include Markdown, GitHub, and GitHub Pages. These instructions are intended for a beginner audience. That is, you do not have to have any experience with any of the tools that will be described in these instructions.

## Prerequisites (Tools Required Before Starting)
 * Since this instruction set is intended for beginners, **no experience is required** with any of the tools that will be described in this set.
 * The only prerequisite required is that the reader has a **résumé**.
 * You should also have a valid email address. This will be required in order to set up your GitHub account.
 * **Recommendation:** Use a computer to complete this. It would be difficult to complete these steps using a mobile device. 
 
 ## Instructions on How to Host Your Résumé 
 
 ### 1. Getting Started
 ####   A. Creating a GitHub Account
   In order to be able to host your résumé on GitHub Pages, you will first need to have a GitHub account. The following steps will help you create a GitHub account:   
   1. [Click here](https://github.com/join) to begin initial setup of your account.
   2. Fill in the required fields from the link above to set up your account. You will need to create a username and password, and have a valid email address.
   3. Click Select a Plan once you have finished filling in the fields. 
   4. Choose a plan that is right for you. You can create a free account, or, if you wish, you can choose a Pro account, which costs $7 USD per month.  
      * You will be able to do all required steps to host your résumé using a free account.
   5. You will then arrive at a page that looks something like this: ![welcome to github](https://user-images.githubusercontent.com/57049086/67638774-93dd4900-f8b6-11e9-87b9-acaa70c4e041.JPG)
      Once you arrive at this page you have two options:  
       * Fill out the questions on this page, and hit submit, or,  
       * Scroll to the bottom of the page, and click "skip this step."
          
   6. Check your email, and click on the link in the email from GitHub to verify your email. **This is important, as you will not be able to proceed in creating your account unless you verify your email address. If your email address is invalid, or you do not have an email, you will not be able to continue creating an account. Also, if you do not see the email, check your spam/junk folder, as it may have gone into there.**
  7. Once your email was verified, create a new repository by entering a name for it, and then clicking submit. Your repository will be where you store your files. **Note: On the page, it will give you the option of choosing a public or private repository. You can choose either. However, if you would like to use GitHub Pages, you either need to have a public account, or, you must have a GitHub Pro account (essentially, pay $7 USD per month for your account).**
  ![Create new repository](https://user-images.githubusercontent.com/57049086/67639423-6ba51880-f8bd-11e9-9bfd-d7cf7545511d.JPG)

  8. Congratulations! Your GitHub account is now set up and ready for use.
  
#### B. Learn Markdown
 Now that you have created a GitHub account, you will need to learn Markdown! GitHub uses a tool called (GitHub Flavoured) Markdown for formatting/editing documents. This is a useful tool for editing plain text documents, but, it is likely different than tools you may be used to, such as Microsoft Word, WordPad, or other similar tools. There are a lot of features Markdown offers, but here are a few of the basics which you may find useful in your résumé:   
 1. **Headings:**   
    * There are 6 levels of headings in Markdown. Level 1 is equivalent to Heading 1 in Word, or the largest heading. Level 2 is one level smaller (Heading 2 in Word), and so on.   
    * To use headings, begin the line with a "#".  
    * Use the same number of "#"s as you wish you heading level to be. For example, if you want a Level 3 heading, you would begin the line with "###".  
    * In order for the heading to be formatted correctly, you must put a single space after the #'s, then begin typing your heading.
 2. **Bold and _Italic_ Fonts**  
    * In your resume, you may wish to emphasise certain parts by using boldface, or using italics.  
    * To use boldface, put two astericks "*", then begin typing the word. **Do not put a space after the astericks.** Then, type the content you would like in bold, and then put two astericks at the end of the content you would like bolded. **Do not put a space before the astericks at the end.**  
    * To use _italicized_ font, use the "_" symbol (underscore). Put an underscore symbol, then type the content you would like italicized, then put a underscore to end the italicized content. **Similar to with bold, do not put a space after the first underscore or before the last underscore**  
 
 3. **Bulleted and Numbered Lists**  
   * To use lists, they must start on a new line. Also, each item of the list must start on a new line.  
   * To create a new line, put two spaces after the previous line, and hit enter.   
   * Put a * at the beginning of the next line. This will create the first item in a **bulleted** list.
   * Put a space after the *, then begin typing the content of the line.
   * Put two spaces at the end of the line. 
   * Click Enter, and repeat the process for every other item in the list. 
   * Enter a number instead of a * if you wish to use numbered lists. Note that the number should have a period after it. For example, do not start the line as "1", but rather as "1."
 
You now know some of the basics to using Markdown! You may find these helpful when writing your résumé. Of course, there is much more to Markdown than just these steps, such as the ability to add clickable links, images, and much much more. Feel free to check out the "Additional Resources" section of this document for more information on how to use Markdown.

You have now learned the tools you need to get started on hosting your résumé! 

### 2. Converting Your Résumé to Markdown 

Now that you know the basics, you need to convert your résumé to Markdown. To do so, follow these steps:
1. **Choose a text editor.**  
  * In order to work with Markdown, you will need a tool that will allow you to edit text in Markdown format.
  * There are many free text editors that you can choose from. 
  * One recommendation for a text editor is [Atom](https://atom.io/). This is because it works well with both Markdown and Github, and it is relatively simple to use.
  * However, if you try using Atom and do not like it, or do not want to download a text editor, you do not have to use it. 
  * See the "Additional Resources" section for some more recommendations of text editors.
2. **Edit your document.**
  * Now that you have chosen your text editor, you must now edit your document in Markdown format. 
  * Open your text editor.
  * Open a new document in your editor, so that you can begin writing your document.
   * **In some cases, there may be some text here supplied by the editor itself. If this is the case, just delete the text, as it is not needed**
  * Type your document in the space, being sure to use Markdown formatting.
3. **Save your document**   
  **A. Saving your document using a downloaded text editor**
   * Find the button that says "Save". Usually, this is under the "File" menu. 
   * Click save.
   * Make sure when you name your document, you save it as a **.md file.**
   * **If you do not save it as a .md file, and save it as something else (for example, .docx), it will not be saved in Markdown format properly. Therefore, you will not be able to host your document on GitHub Pages**  
  **B. Saving your document using an online text editor**
    * Click on the "Export As" button
     * Each editor might call it something slightly different, like "Export As", or "Export", or "Download".
    * Click on the .md file type
     * **Make sure that you export it as a .md file. This is the file type that will save it in Markdown format.** 
    * Your document should now download, and should appear in your "Downloads" folder on your computer.
    
  Your résumé is now converted to Markdown, and you are ready to host it on GitHub Pages!
  
  ### 3. **Hosting your Résumé on GitHub Pages**
