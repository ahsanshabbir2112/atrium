# Week 2 security requirements

Your name: Ahsan Shabbir 
Date: 8/10/2026

## 1. What this application is

Atrium is a internal staff portal. staff can see directory, their profile and shared work resources through login. Admin find the admin page of staff accounts.The server of app is running on a localhost.



## 2. What is worth protecting

- login accounts and passwords of staff: if account is hack then someone use the portal become a staff member.
- staff name,email,department and bio: if these detials hacked privacy concerns issues and phishing is easy.
- shared work resources like supplier or budget information: wrong person see and may alternate the data it affects the workplace decisions.
- staff records and their roles: if records are change and unavalible people cannot login or someone get wrong access 

## 3. The requirements

1. without sign in no visitor can see staff directory,profile & resources.
2. to chnage the search text sql query of directory cannot show  the other staff records.
3. HTML & Script in the search d'ont execute on the directory page.
4. the signed-in member do not update the other person profile by giving their id in their request.

**Which of these did you write yourself, and which started as a draft from your
assistant?

- with the help of assistant i checked and rewrite them in my own words.

## 4. One I rejected or rewrote

- The original sentence: "protect staff data"
- My version: without sign-in no visitor not see the staff list on  directory 
- Which test it failed, and why: original was vague, meaning of protect and test is not clear. new version is specific and would be check in browser.

## 5. How somebody would check one of these

Pick one requirement. Write the steps for a person who has never seen Atrium and
cannot ask you anything.

- The requirement: without sign-in visitor do not see the directory.
- Sign in as: signed-out visitor
- Steps:open Private/incognito browser and go on http://localhost:9090/directory .
- What result would mean the requirement is met: page redirct on login and dont show the staff list.
- What result would mean it is not met:
staff directory will be shown in sined-out condition.
