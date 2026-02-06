Privileged Identity Management works with several different types of resources. It can be Azure Role Based Control roles, it can be Entra ID roles and also group membership. However, within this demo I'm going to focus on Entra ID roles. 

Entra Premium licensing is required.

<img width="1185" height="619" alt="Drawing 2026-02-06 22 55 36 excalidraw" src="https://github.com/user-attachments/assets/e0cf03db-43b0-4eda-996a-ae0ea1668459" />


What we'll do in this demo is we'll assign elegibility for an application administrator role to one of our users. 

Since we have the licensing and we've got PIM enabled, you'll see we can configure Pirvileged identity management. This is really what we are talking about right here

<img width="1919" height="1035" alt="image" src="https://github.com/user-attachments/assets/f978858c-5430-4da8-88e5-4dd018e9420f" />

We can go ahead and say active and say permenantly assigned, and that will really just mean that's we're kind of skipping PIM. We're almost sidestepping PIM. 

If you didn't have PIM,then this is what what you are actually configuring when you create a role assignment. That it's going to always be permenantly active. 

<img width="1919" height="1029" alt="image" src="https://github.com/user-attachments/assets/872dd296-bdd7-4f24-bccd-5f325405d9ad" />

However, as we know, we want to protect these privileges, and so that's where we can configure elegibitliy.

We might allow our users to have elegibiltiy for this role always, being a part of their job, or maybe they're just working on a specific project for a period of time and we want to lock down the this elegibiltiy 

<img width="1919" height="1027" alt="image" src="https://github.com/user-attachments/assets/31c10ef5-8d84-47be-9bfe-54c43009df09" />

What what you've seen is that we've added a few extra controls to ensure that Ahmed can only elevate to permissions according to the settings we've defined here
<img width="1919" height="643" alt="image" src="https://github.com/user-attachments/assets/baee5643-e0cc-473f-8a82-24630996605d" />

But what if you had some additional controls you wanted to implement ? Well, you can brows into the role settings for each of your roles, and we can configure all sorts of controls, like whether MFA is required, justification, maybe we do want approval before the role can be activated. 

<img width="1919" height="1036" alt="image" src="https://github.com/user-attachments/assets/50c602e5-2877-40a3-8787-9cfa2af41753" />

What we're talking about is a range of different controls that we can configure on a per role basis, and we can also configure on a per assignment basis to determin what people should be doing before they can activate those roles.

So we've got everything ready to go. What we now want to do is log in as our endpoint users to test this out. 

You'll see I'm logged in as Ahmed Abdullah. Now remember, Ahmed Abdullah has just been assigned eligibility for the application administrator role for our specfic app.
<img width="1919" height="1026" alt="image" src="https://github.com/user-attachments/assets/a797448e-d38a-4e17-bbbc-7455258e01ac" />

Right now we would expect that Ahmed doesn't have permissions to do anything with this app 

<img width="1919" height="883" alt="image" src="https://github.com/user-attachments/assets/2ab2a336-9b33-4023-a85f-dbba9e2d5ed8" />

So this is PIM, we've assigned eliglibility for permissions, but permissions aren't always active. To activate those permissions, Ahmed has to go My roles section that got the different types of privilegs we might be activating, and we've got that Application Administrator role that Ahmed is eligible for.

<img width="1919" height="565" alt="image" src="https://github.com/user-attachments/assets/a5ee45b4-8532-4cfb-b23f-35fecf72b011" />

<img width="1919" height="610" alt="image" src="https://github.com/user-attachments/assets/997bf583-5492-4d96-9e60-6f7ca2995504" />
















