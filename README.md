Create a Gatsby site.
Use the Gatsby CLI to clone the site and install dependencies:

npx gatsby new gatsby-starter-portfolio-cara https://github.com/LekoArts/gatsby-starter-portfolio-cara


Navigate to your new project.
cd gatsby-starter-portfolio-cara


Open the code and start customizing!
Start the site by running npm run develop.

Your site is now running at http://localhost:8000!

If you want to learn more about how you can use a Gatsby starter that is configured with a Gatsby theme, you can check out this shorter or longer tutorial. The tutorials don't exactly apply to this starter however the concepts are the same.

📝 Using and modifying this starter
Important Note: Please read the guide Shadowing in Gatsby Themes to understand how to customize the underlying theme!

This starter creates a new Gatsby site that installs and configures the theme @lekoarts/gatsby-theme-cara.

Have a look at the theme's README and files to see what options are available and how you can shadow the various components including Theme UI. Generally speaking you will want to place your files into src/@lekoarts/gatsby-theme-cara/ to shadow/override files. The Theme UI config can be configured by shadowing its files in src/gatsby-plugin-theme-ui/.

Changing content
The content of this project is defined in four .mdx files inside the theme's sections folder. You can override the files intro.mdx, projects.mdx, about.mdx and contact.mdx. This starter has overridden all files for you already.

You have to use the <ProjectCard /> component inside projects.mdx to display the cards. Example:

## Projects

<ProjectCard title="Freiheit" link="https://www.behance.net/gallery/58937147/Freiheit" bg="linear-gradient(to right, #D4145A 0%, #FBB03B 100%)">
This project is my entry to Adobe's #ChallengeYourPerspective contest.
</ProjectCard>
Change your static folder
The static folder contains the icons, social media images and robots.txt. Don't forget to change these files, too! You can use Real Favicon Generator to generate the image files inside static.
