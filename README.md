# Live Project C# .net  

  

A live project for the C# .NET Course.  

  

   

  

## The project.  

  

The project consisted of two, one-week sprints.  The first day we established what the project was and set up of who would be working on what part of the project.  The project is for a theater company that requested a web site needed for advertising and social interaction from their actors and customer users for the theater.  My part of the project was to develop a donation page that could be accessed through the home page index view.  Then develop a blog area with CRUD functionality.   

  

## Getting Started  

  

I designed the area called "Blog Authors" where a user could see all the users that were creating blogs.  

  

First, I started with a model to establish the setup of the database and what information will be used in the blog author web site.  The model included a BlogAuthorID, Name, Bio, the date when the person joined the blog area and the Left date for when they decided to leave the blog.    

  

![photo](https://github.com/Kelinz74/LiveProjectCsharpdotnet/blob/main/BlogAuthorModel.png?raw=true)    

  

From the blog folder, using the Add New Scaffolded Item, utilizing the BlogAuthor model, created the Controller folder and a Views folder establishing the setup of the BlogAuthor display(index), the create page (for creating a profile), the edit page (for editing the profile), a delete page (for deleting a profile) and a details page.  

  

![photo](https://github.com/Kelinz74/LiveProjectCsharpdotnet/blob/main/Scafoldingoption.png?raw=true) 

  

![photo](https://github.com/Kelinz74/LiveProjectCsharpdotnet/blob/main/AddNewScaffolddedItem.png?raw=true) 

  

![photo](https://github.com/Kelinz74/LiveProjectCsharpdotnet/blob/main/ScafoldingAdd.png?raw=true) 

  

After the Scaffolding was finished, the directory then looked like this... 

  

![photo](https://github.com/Kelinz74/LiveProjectCsharpdotnet/blob/main/ScafoldingBuild.png?raw=true) 

  

## The Code And Style 

  

The first area displayed is the index displaying a pre-created profile. 

  

![photo](https://github.com/Kelinz74/LiveProjectCsharpdotnet/blob/main/indexview.png?raw=true) 

  

- code 

  

![photo](https://github.com/Kelinz74/LiveProjectCsharpdotnet/blob/main/indexcode.png?raw=true) 

  

From this page you can see in a table format the Name, Bio, Joined Date, Left Date.  There are also option to "Create New" in the upper left corner below the title Index.  To the right of Left Date there are option to Edit, Details(view the profile) and Delete the profile. 

  

### Create New 

  

![photo](https://github.com/Kelinz74/LiveProjectCsharpdotnet/blob/main/createview.png?raw=true) 

  

Here you would be able to submit you name, write a small bio about yourself and submit the date that you joined or left.  The joined and left options did have the datetime functionality of a drop down calendar that you could pick the month, date and year as your choice from the calendar 

  

- code 

  

![photo](https://github.com/Kelinz74/LiveProjectCsharpdotnet/blob/main/createcode.png?raw=true) 

  

  

After creating your profile you would be taken back to the index view. 

  

### Details 

  

![photo](https://github.com/Kelinz74/LiveProjectCsharpdotnet/blob/main/detailsview.png?raw=true) 

  

In the details view you could see a more formal display of your profile.  The picture was just an example placeholder for future improvements for when photos would be able to be submitted.  The tabs are a jQuery simple tab function using JavaScript with some CSS styling to hide the tabbed information on the page.  Each tab has its own information displayed and tabs would transition color from active to inactive. 

  

![photo](https://github.com/Kelinz74/LiveProjectCsharpdotnet/blob/main/tagtransition.gif?raw=true) 

  

- code 

  

![photo](https://github.com/Kelinz74/LiveProjectCsharpdotnet/blob/main/detailscode.png?raw=true) 

  

- The JavaScript coding. 

  

![photo](https://github.com/Kelinz74/LiveProjectCsharpdotnet/blob/main/simpletabsjavascript.png?raw=true) 

  

- CSS 

  

![photo](https://github.com/Kelinz74/LiveProjectCsharpdotnet/blob/main/CSSsimpletabs.png?raw=true) 

  

From the index and the details page you can get to the edit and delete pages. 

  

### Edit 

  

The edit page received the information to display in the text boxes via the ID number of the profile from the database. 

  

![photo](https://github.com/Kelinz74/LiveProjectCsharpdotnet/blob/main/editview.png?raw=true) 

  

- code 

  

![photo](https://github.com/Kelinz74/LiveProjectCsharpdotnet/blob/main/editcode.png?raw=true) 

  

### Delete 

  

When you press the delete button from the details or the delete link from the index page, you would be given one more chance to cancel the delete before committing to your decision for deleting your profile. 

  

![photo](https://github.com/Kelinz74/LiveProjectCsharpdotnet/blob/main/deleteview.png?raw=true) 

  

- Code 

  

![photo](https://github.com/Kelinz74/LiveProjectCsharpdotnet/blob/main/deletecode.png?raw=true) 

### Final
This is the end of my contribution to the C#, ASP.NET MVC live project. It was an awesome experience working with a talented team. 
