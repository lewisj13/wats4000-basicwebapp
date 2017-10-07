# wats4000-basicwebapp


This is my first webapp using Cue that has been uploaded. This is how I went through the process from setting up my development environment to building it and deploying it in Gh-pages.

I made sure that my local development environment was all set up. I installed Vue-Cli globally on my local computer.
Then I used web pack to set up the template this is all done through the terminal.
Then I installed Vue and ran the app for the first time. 
I then modified the files to make the web app personalized
To deploy the webapp, I first created this repo and push and committed the information from the local development environment. 
I then modified the files for Webpack in the build to say ‘docs’ instead of ‘dist’ and removed the ‘/‘ from the ‘accesspublicpath’ to make a relative path for Git hub.  
Then I ran the build command to minified and uglified the files so the build will run smoother once deployed on the gh-pages.
Then I add, commit and push the web pack configuration back to git hub.
Lastly configure the gh-pages with the master branch/docfolder. To have the site url that can be share on here!
