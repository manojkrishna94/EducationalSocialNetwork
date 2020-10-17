1. Open the SocialNedia.sln file in Visual Studio and Make sure  .Net core 3.1 is installed on the machine
2. Right click on SocialMedia.web project  and select 'set as start up project'
3. Go to Tools-> Nuger Package manager->Package manager console and in the console type below commands in sequence 
a) Add-Migration Finalcommit
b) Update-database
4. Run the project using IIS Express
5. After the page has loaded , Register yourself  update your bio and create a post from your page and logout.
6. Create another user and  click on friends -> Non-friends -> select the first created user -> click on Add friend .
7. Go to First created user -> click on requests ->Accept -.Now User 1 and User 2 are friends and can see  like or coment each other's posts.
.
