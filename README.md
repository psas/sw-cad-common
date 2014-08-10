sw-cad-common
=============

Solid Works CAD common files for PSAS

=== PSAS Solidworks setup and use procedures

 1. Quickly read the "Getting Started" guide for the github windows client. https://help.github.com/articles/getting-started-with-github-for-windows
 1. Download and install the github windows client: https://windows.github.com/
 1. E-mail Nathan and have him add your github account name as a team member of the PSAS orgonization.
 1. Open the github client, and clone all the repos that start with "sw-cad-".
    * Make sure you clone them all into the same directory so that the relative file locations will work properly. The default "GitHub" directory should be just fine.
 1. You can usually find top-level assembly files in each individual repo. Some of these top-level assemblies are for indididual modules. Others pull together multiple different modules.
 1. To make modifications or add designs
    1. Make sure to do a "sync" with the github repos. You want to pull down any changes that other people have made.
       1. Open the github windows client
       1. For each of the "sw-cad-*" repositories, click "sync" to retrieve the latest changes from other people on the team.
       1. Thats it!
    1. Create a sub-directory in a reasonable location to hold all your part and assembly and drawing files.
    1. Create your parts, then create an assembly of your parts.
    1. Open the next-higher level assembly file that your part will go into. For example, if you have a camera that goes into the payload module, youd open the payload module asssembly, then insert your new assembly as a sub-assembly of the payload assembly. Alternatly, if you had a completely new module, youd open the full rocket top level module, and insert your new module into the main rocket assembly. The idea is to keep the assemblies and sub-assemblies as a heirarchy whenever possible.
    1. Once your happy with your new parts/designs, you want to commit and sync
       1. Close solidworks and save your changes
       1. Open the github windows client.
       1. For each repository that you made changes to, click the repository. Git hub will identify the files that you have changed. Skim the list and confirm that the list of files looks reasonable (uncheck anything thats not necessary). There is a "commit message" box, type a breif summary of the changes you made, and then click the "commit" button. Next, click the "sync" button in the upper right, and the github windows client will pull and push your changes to the github servers. *Make sure to do this for all the repos that you have made changes in.


