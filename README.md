# ContributorFAQ
Handy information for even the most obscenely informed members of Resonator.

Everything below this line is in copy at [resonatormagazine.github.io/ContributorFAQ/](http://resonatormagazine.github.io/ContributorFAQ/)


----------


# **Resonator Magazine Has Instructions** #

#### Contents ####

1. [**Genesis**](#genesis)
2. [**In-Depth Workflows by Role**](#roles)
     1. [Columnist](#columnist)
     2. [Reviewer](#reviewer)
     3. [Contributor](#contributor)
     4. [Feature Contributor](#featurecontributor)
     5. [Photographer](#photographer)
     6. [Designer](#designer)
3. [**The Resonator Style Guide**](#style_guide)
     1. [Formatting Your Submission](#formatting)
     2. [Metadata](#metadata)
     3. [Copyright](#copyright)
     4. [Credit](#credit)
4. [**Advanced Steps for Key Contributors**](#git)
     1. [Getting Started with GitHub for Resonator](#account)
     2. [Downloading and Installing the GitHub Client](#client)
     3. [Obtaining Access to Resonator's System](#system)
     4. [Syncing Your Changes to Our Repo](#syncing)
     5. [A Simple Step-by-Step Summary of Syncing](#stepbystep)       
    

## <a id="genesis"></a>Genesis ##


## <a id="roles"></a>Roles ##

#### <a id="columnist"></a>Columnist ####

As a columnist, you play a starring role in Resonator. 

Of course, there is that SpiderMan caveat about power and responsibility. Resonator relies on columnists for recurring content, both on the website and in the magazine proper. Because of this, you're ability to work with our GitHub system needs to be a bit more in-depth than that of the casual contributor. All of your draft submissions will need to be pushed to our Columnist repo so that we can maintain solid version control practices.

How do you know you're a columnist with Resonator? 

- You pitched an idea for a recurring column to our Editorial Board (team@resonatormagazine.ca)
- You received confirmation that your idea was killer.
- You were sent here!

What do you do now that you're a Columnist?

- Sign up for Github and get connected with the Resonator Account -  [(see our Github Walkthrough)](#git)
- 

#### <a id="reviewer"></a>Reviewer #####
#### <a id="contributor"></a>Contributor #####
#### <a id="featurecontributor"></a>Feature Contributor #####
#### <a id="photographer"></a>Photographer #####
#### <a id="designer"></a>Design #####

## <a id="style_guide"></a>The Resonator Style Guide ###

#### <a id="formatting"></a>Formatting Your Submission #####

#### <a id="metadata"></a>Metadata #####

#### <a id="copyright"></a>Copyright #####

#### <a id="credit"></a>Credit #####


## <a id="git"></a>Advanced Steps for Key Contributors ##

The entirety of our under-the-hood practices run through GitHub, and this remarkable piece of software will soon become your greatest tool in the war against disorganization. 

For our purposes, GitHub acts as the storage and review space that all content must pass through before it can make it to the site or the magazine. Think of it like that old riddle about the farmer who has to get a chicken, a fox, a baby, and a knife across a river. GitHub is our boat through which we will ferry all content - and hopefully, no babies will shiv any foxes along the way.  

To contribute your articles, media, and playlists to Resonator, you'll have to:

* Create a GitHub profile
* Download and install the GitHub client on your computer
* Be granted access to submit, edit, and check out content from the Resonator Repo

If you've never used GitHub before, and decided to give it a Google-ing, you likely saw a fair bit of discussion about Git, command line, and specialized syntax. **Don't worry about it.** For our purposes, you won't ever have to write any command codes - unless you want to. The following sections outline the necessary process - and honestly, it's no different than posting a batch of photos to Facebook.

#### <a id="account"></a>Getting Started with GitHub for Resonator ####

First off, you'll need to head to [GitHub](https://github.com/) and create an account. If you already have an account with GitHub, feel free to use it - just make sure that you're identifiable by your account name. It's a lot easier to get a hold of John Smith if he's JohnSmith223, and not Dirty_Burger69. Once you've signed up, GitHub will run you through a confirmation process and such, then all will be good to go.  

Once you've created your account (remember to throw in a profile photo and all that fun stuff), complete the following steps:

1. Navigate over to [Resonator's GitHub Page](https://github.com/ResonatorMagazine) and click the **Follow** button. This ensures that you receive updates when we make important changes and edits. Plus it let's us know you're okay, like calling your mother while you're out. You're a good kid, and we're proud of you.
2. Shoot an email to (team@resonatormagazine.com) with your GitHub account name. We will assign you the appropriate account permissions that allow you to add, edit, and check out content from our various repositories (permissions depend on your role).

Essentially, the Resonator GitHub page is a shared file-tree amongst all team members. Any of us (if permitted) can upload new documents, edit existing documents, and monitor activity. And, if anything goes off the rails, we can revert back to the last time everything is okay. For you, this means that when you want to submit something to the editing team - you do it through GitHub. This gives our editors cloud-access to the submission, and allows us to locally edit and review, and then compare our changes - all the while, being completely transparent. We think that's pretty alright. Of course, if you have reservations about using cloud systems and version control to submit your work - please contact us to discuss them. 

No matter your role with Resonator, your use of GitHub should amount to little more than uploading and downloading your submissions and our edits. To do this, you'll need to install either the Mac or Windows desktop client for GitHub.

#### <a id="client"></a>Downloading and Installing the GitHub Client ####

If you use Windows, you can download the [GitHub Windows desktop client](https://windows.github.com/).

If you use Mac, you can download the [GitHub Mac desktop client](https://mac.github.com/).

If you use Linux, you haven't even bothered to read all of this because you're likely already familiar with GitHub. 

Once you've installed the software (which is free, by the way), there will be a GitHub folder somewhere on your computer (specified during setup). This will be where you save copies of your submissions for us to access. 

Once you've emailed us your account name and we've specified your roles and assigned your permissions, you will be able to make copies of various Resonator repositories locally - which will all be inside the GitHub/ResonatorMagazine folder on your personal computer. The following section will outline this process. But, we will precede that with a stern warning...

##### **Note:** *Anything you do inside the ResonatorMagazine folder that will be in the GitHub folder on your computer will affect our entire system if you push your changes to the cloud*. This is why we have strict permission systems - but even then, things can get hairy if you're less than careful. If you delete a folder or somebody elses work, and then sync your changes using the client, that work gets deleted. We can revert back and restore it - that's why we use this software - but it's still a drag. So remember, always review your changes in the client before you commit and sync them, and only delete your own files.

#### <a id="system"></a>Obtaining Access to Resonator's System ####

You've created an account, you've downloaded the software, and you've emailed us your account information. Now, we do a thing. Once you've checked off these steps, it's  up to us to reach out to you and let you know which of the repositories you'll be working through. Those emails will have specific instructions, but the general process will be outlined here:

- You'll be given links to some of our repositories on GitHub (https://github.com/ResonatorMagazine/XXXXX) - navigate to these repositories and click the **Clone to Desktop** button in the bottom right corner of the screen. This duplicates the contents of the repository from the cloud to your local computer, storing it in WhereverYouPutTheFolder/GitHub/ResonatorMagazine/ .
- If you've been given permission to access this repository, any changes you make to your local copy of the repo can by synced to reflect the changes in our main repo. The super-useful side of this is that if you upload a submission by dropping it in your repo and "sync"-ing it, we can sync our clients and have your submission. Likewise if we edit something, you can see our edits when you sync up.
- In the GitHub client on your desktop, you'll see three columns. The left-side column is a list of repositories connected to your account. If you click one of these repos, the content of the centre and right-side columns changed. The centre column lists the changes that have passed through the repo - every time somebody syncs a change, it will be reflected here. If you click one of the changes, the details will show up in the right-side column.
- When **you** make a change to something in a ResonatorMagazine folder, the centre column will show an "Uncommitted Changes" bar. If you click it, the right-side column will list the changes you've made to the files. At this point, these changes have not been synced and are only on your computer. 

#### <a id="syncing"></a>Syncing Your Changes to our Repo ####

When you add or change something in one of your local ResonatorMagazine folders, two things will happen in your GitHub client.

1. The centre column will show an "Uncommitted Changes" bar that allows you to name and authorize your changes, as well as view what the changes are.
2. The "Sync" button in the top right corner of the client window will show a blue superscript number, indicated the number of changes you are required to sync. Your changes are reflected here once you have clicked  the "Commit to Master" link in the Uncommitted Changes bar. Changes from others that you are required to absorb in order to be correctly synced with the Resonator Github account are shown there automatically.

**Note:** Before you make any changes to a ResonatorMagazine folder, always sync with the main account first to ensure your files are up-to-date with everyone elses. You can do this by opening the client, and checking each repo for a superscript number next to the Sync button. If there is a number, click the Sync button.

To save your changes to the main GitHub account, name them, describe them, and commit them. Then, Sync them. 

If this sounds overwhelming or confusing, don't worry. It becomes super easy once you've done it a couple times. And, you can always contact us or hunt through the internet - this software is pretty popular, and there's loads of forums and documentation to walk people through the process. 

But, for quick reference:

#### <a id="stepbystep"></a>A Simple Step-by-Step Summary of Syncing 

1. Open the GitHub client on your computer.
2. In the left-side column, click the repo you intend to work in.
3. If there is a number next to the **Sync** button in the top right corner, click the button to sync any changes made to the repo that your files are currently out of sync with. After doing this, you're on the same page as the rest of us.
4. Go do your thing - make your changes and whatnot. Edit some stuff, submit some content to us, or whatever it is you're up to. 
5. Save your changes locally on your computer.
6. Open the GitHub client on your computer.
7. In the left-side column, click the repo you made changes in.
8. The centre column will show an **Uncommitted Changes** bar. Fill out the *Summary* and *Description* fields.
9. Review your changes to make sure you haven't done anything insane, then click **Commit to Master**
9. Finally, click the **Sync** button in the top right corner.
