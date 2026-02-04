# Tenzu FOSDEM Presentation - Content transcription

## Slide 01
I’m going to tell you a story that happened not so long ago in a country not so far away …

## Slide 02
Once upon a time in 2014 was born Taiga, from the bowels of a Spanish company named Kaleidos
Taiga soon became a well-beloved project management tool with a worldwide user base of over 20M

## Slide 03
In 2021, the Taiga team took on a new project codenamed Taiga Next
Taiga Next was announced as a fully revamped Taiga, keeping key concepts from its predecessor but designing a better user experience all around.
The focus was given on being global, inclusive and accessible

## Slide 04
But the Kaleidos company is a busy bee and they were also already working on a second product: Penpot. A design tool to bring together developers and designers.
By that time it was just starting to achieve great success.
(it’s awesome go try it)

## Slide 05
They eventually reached the decision that they couldn’t keep working on both products at the same time. 
Penpot was chosen as it was believed to fill a more prominent gap in the ecosystem.
But what did it mean then for Taiga Next? Was it the end?

## Slide 06
Well I think you knew the answer to that already

## Slide 07
At BIRU, we are a small French cooperative company, heavily invested in opensource.
In 2024, we were working on Taiga internally, trying our hands on our own revamp of the
frontend.
We decided to reach out to Kaleidos then, and they informed us that Taiga Next was
actively searching for new guardians.
We decided to seize this opportunity and the magic of opensource pretty much took care of the rest
And that's how Tenzu was born

## Slide 08
The philosophy behind Tenzu is the same as its alias Taiga Next:
To build a great tool, for everyone, promoting healthy collaboration and a polished methodology.
We have small means but we dream big and our team is fully committed to this

## Slide 09
A quick note about our business model since it's a recurrent question we get.
 
Our strategy goes three-ways:
1. Proposing a free pricing on our SaaS, no paid plan, no open-core. We also encourage any actor willing to sponsor the project
2. Staying small and focused. We are fully independent and every team member is directly involved in building Tenzu. No sales, no marketing department, no management layer, no investors. It keeps costs small and it keeps us sane, well sanish
3. We don’t directly provide services around Tenzu. Instead, in the spirit of cooperation, we are building a network of professional partners to provide everything any user could want: guaranteed support, hosting, training, etc. Tenzu is a protected trademark in order to discourage bad actors from trying to make an exclusive profit from it

## Slide 10
So, where are we at? I’m happy to say that, while not as feature-complete as Taiga, Tenzu is already used in the real world by hundreds of users and counting a few month after its release in September. (and that's awesome)
On Tenzu:
- We are able to organise the work in different spaces and assign fine-grained permissions to other team members
- We have a fully functional KANBAN where you can create stories, assign them  to your teammates and add comments and attachments. You can have multiple KANBAN boards on any single project.
- We already have a dark theme for people with refined tastes and Tenzu is actually translated in 3 languages (English, French and Spanish) with more coming
- You can configure your Tenzu instance to connect with any standard authentication provider you want

## Slide 11
And as an exclusive announcement specially for FOSDEM, as of yesterday in Tenzu v2, you can now collaborate on writing your stories!
You can see in real time the changes made by other users as they are making them and add your own input.
We were very eager to launch this feature as it is the first one we added to provide a truly different experience from our dear old Taiga.

## Slide 12
And since giving a talk is all about taking risks, now is the time for everything to go to hell. And since simple demo are obviously still not risky enough, I'll be doing a synchronised demo with my coworker's help to show you those collaboration goodies.

## DEMO
It goes like this:
Welcome to Tenzu's spaceship Guided tour
1.	Login to user account
2.	Go to an existing project called FOSDEM
3.	Demonstrate the switch to dark mode
4. At the same time, the coworker move around some stories, create and delete a kanban board, move a status, create one story, change assignees. And everything is reflected in real time
5.	Show the notifications panel and mess around some more with the interface
6.	Go to story "Prepare your schedule", add an image in the description
7.	Start a live collaborative session with coworker to write some stuff and show the WYSIWYG editor capabilities
8.	Write a comment while coworker also write one that appears instantaneously
9.	Change view mode of story
10.	Move story to another kanban
11.	Show members and invitations panel, resend an existing pending invitation
12.	Show settings and roles panel, show fine-grained permission available on role
13.	Show the user profile pages
15.	Show call for support page
16.	Back to that home menu, explain about permissions
17.	Go back to FOSDEM project and my coworker, as the project owner, will downgrade the user role to "read-only" for that project
18.	Show the UI changing in real time and the differences in display on read-only mode

## Slide 13
Now that’s done, here is what we will be working on in 2026.
To handle more use cases, especially for users coming from Taiga, we plan to work on adding support for subtasks, SCRUM and Issues. We don’t know yet what form that will take exactly as we plan to do lots of user research beforehand. If you’re a Taiga user, you can help with that as we are always looking for volunteers.

## Slide 14
And the next feature we are actually working on right now is to provide a way for Taiga users to migrate their projects to Tenzu.
While Tenzu is still evolving and not yet on feature-parity with Taiga, we still want to provide a way for users to enjoy it without losing all their hard work.
We are planning to design a legacy mode for projects created from a Taiga export with support for some stuff with no Tenzu equivalent quite yet (like story points).
And as soon as Tenzu provides an equivalent feature, the data for all previous importation will be backported automatically for you and adapted for Tenzu.

## Slide 15
As another exclusivity for FOSDEM, because we really want to spoil you today, you get to peek into what this legacy mode will look like.
The first step is with this new shiny button. And as a proof that we are currently working on this, attentive users will have noticed that this screenshot was taken directly from our dev environment.
Once you load an export file, you will be able to see the progress on it in real time  (this is a Penpot mockup by the way).
You’ll then be able to pick and choose exactly which users gets invited to collaborate with you from the pool of users that were previously members of the imported project.
Finally, you’ll be able to see your stories with all the information you are used to have in Taiga.
Release by release, this interface will be replaced with the Tenzu’s way of doing things and users that create a project from scratch won’t ever see those extra stuff until Tenzu provides them natively.
This way, users experience will converge in time all the while empowering users coming from Taiga with access to their data in advance

## Slide 16
That’s it for now, I want to conclude by saying thank you Taiga, thank you Kaleidos, thank **you** and thanks open source
