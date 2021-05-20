# Security Tips: Protecting Sensitive Information
This is the repository for the LinkedIn Learning course Security Tips: Protecting Sensitive Information. The full course is available from [LinkedIn Learning][lil-course-url].

![course-name-alt-text][lil-thumbnail-url] 

While we often think of our communications channels as secure, it never hurts to add an extra layer of protection when working with sensitive information. Whether it’s personal documents, trade secrets, or any other kind of information that could be misused in the wrong hands, knowing how to secure data is a skill that anyone can benefit from. Learn tips to protect and exchange your sensitive information using encryption and other tools. In this course, instructor Scott Simpson discusses the basics of encryption and demonstrates how to protect sensitive information using encrypted files, disks, and disk images. He introduces encryption tools for every operating system—including BitLocker, FileVault, and LUKS—as well as the cross-platform VeraCrypt app. Plus, learn best practices for multilayer security, web connections, VPN, email, and cloud storage.


## Instructions
This repository has branches for each of the videos in the course. You can use the branch pop up menu in github to switch to a specific branch and take a look at the course at that stage, or you can add `/tree/BRANCH_NAME` to the URL to go to the branch you want to access.

## Branches
The branches are structured to correspond to the videos in the course. The naming convention is `CHAPTER#_MOVIE#`. As an example, the branch named `02_03` corresponds to the second chapter and the third video in that chapter. 
Some branches will have a beginning and an end state. These are marked with the letters `b` for "beginning" and `e` for "end". The `b` branch contains the code as it is at the beginning of the movie. The `e` branch contains the code as it is at the end of the movie. The `main` branch holds the final state of the code when in the course.

When switching from one exercise files branch to the next after making changes to the files, you may get a message like this:

    error: Your local changes to the following files would be overwritten by checkout:        [files]
    Please commit your changes or stash them before you switch branches.
    Aborting

To resolve this issue:
	
    Add changes to git using this command: git add .
	Commit changes using this command: git commit -m "some message"

### Instructor

**Scott Simpson**

_Senior Staff Instructor at LinkedIn Learning_

Check out my other courses on [LinkedIn Learning](https://www.linkedin.com/learning/instructors/scott-simpson?u=104).


[0]: # (Replace these placeholder URLs with actual course URLs)

[lil-course-url]: https://www.linkedin.com/learning/security-tips-protecting-sensitive-information?u=104
[lil-thumbnail-url]: https://cdn.lynda.com/course/2883014/2883014-1621363636089-16x9.jpg
