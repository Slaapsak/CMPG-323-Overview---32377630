# CMPG-323-Overview---32377630

<h2> Here I adress which repositories will be created and used for each project</h2>
<body> I have prevoiusly stated that I will create each project within a single repository and also that it it may change.
The way I ended up approaching this is so mucj more simple, a repo was created for each project.
I quess the only reason i have changed this is because I did not know github from the start but have learned more troughout the semster and 
decided to finally change the flow of the projects througout the semester.
<h3> Context diagram of explaining project and repository context and how they are integrated 
</h3>
<h4>Here I explain the branching strategy to be used within each project </h4>
<body>So I will Use feature branches for all new features and bug fixes, then merge these feature branches into the main branch using pull requests.
This will help me maintian a high quality, up to date main branch
This is bound to change, as I am creating this readme file I am alraedy thinking of changing my strategy</body>
<h5>Here I explain the use of a .gitignore file within each project </h5>
<body> The following files the files that should be ignored 
-Log files
-Files with API keys and secrets,credentials and sensitive information
-Usless system files
-Generated files like dist folders
-Dependencies which can be downlaoded from a package manager

 I will manage this by Placing the .gitignore file in the rootfolder of the repository</body>

<h6>Here I explain the storage of credentials and sensitive information </h6>
<body>The best way that I can think of protecting and storing sensitive information and credentials is adding a SECURITY.md file that highlights security related information for the projects this semester </body>
