# Design collaboration tools

I am only including detailed notes for Figma, Lunacy, and Penpot.

<div id="back-to-top"></div>

## Table of Contents

1. [Figma](#figma)
   1. [Collaboration on Figma](#collaboration-on-figma)
   1. [Collaborative tools](#collaborative-tools)
   1. [Building a more collaborative design process with Figma](#building-a-more-collaborative-design-process-with-figma)
   1. [A collaborative online whiteboard for teams](#a-collaborative-online-whiteboard-for-teams)
   1. [What is FigJam by Figma](#what-is-figjam-by-figma)
1. [Lunacy](#lunacy)
   1. [Work in a team with Lunacy](#work-in-a-team-with-lunacy)
   1. [Lunacy Review 2022](#lunacy-review-2022)
   1. [How to migrate from Figma to Lunacy](#how-to-migrate-from-figma-to-lunacy)
1. [Penpot](#penpot)
   1. [Open source design collaboration with Penpot](#open-source-design-collaboration-with-penpot)
   1. [Open-source Prototyping and design platform](#open-source-prototyping-and-design-platform)
   1. [Free open source prototyping platform](#free-open-source-prototyping-platform)
   1. [Penpot on GitHub](#penpot-on-github)
1. [InVision](#invision)
1. [Sketch](#sketch)

I'll provide links for Sketch and InVision but Figma is the best option. There are other design resources, but you can't go wrong with Figma.

## Figma

The free plan allows having projects and team members. I am not sure of how many members but at least you can collaborate. You can also invite members to review prototype designs and leave sticky note comments. You can even go into Observation mode and watch your teammates comment and make edits.

That is about the extent of collaboration with the free plan but it still offers the ability to share and contribute to projects.

The best links I found are from Figma's channel on YouTube. Here are the best videos:

1. [Figma For Beginners: Explore ideas (1/4)](https://youtu.be/dXQ7IHkTiMM)
1. [Figma For Beginners: Create designs (2/4)](https://youtu.be/wvFd-z7jSaA)
1. [Figma For Beginners: Build prototypes (3/4)](https://youtu.be/lTIeZ2ahEkQ)

<br>

<h3 id="collaborative-tools" align="center"><a href="https://help.figma.com/hc/en-us/sections/360006780134-Collaborative-tools"><strong>Collaborative tools</strong></a>
</h3>

Nothing but links on this page under the heading _Comments_:

[Guide to comments in Figma](#https://help.figma.com/hc/en-us/articles/360039825314-Guide-to-comments-in-Figma)

- You can use comments to respond to feedback, tweak your designs, and iterate faster—all from the original design file
- Long-press any area of the canvas or FigJam board to add a comment
- When you and your team add comments to a file, they're displayed on the canvas or board in the regions or locations they were added to.
- You can view and reply to them right from the canvas or board.
- On the browser and desktop apps, you can also view and manage comments from the right sidebar when you enter commenting mode.
- Comments can be hidden from your canvas or board view at any time

[Add comments to files](#https://help.figma.com/hc/en-us/articles/360041068574-Add-comments-to-files)

- Add comments to files or prototypes in comment mode. You can `@mention` your collaborators, as well as add emoji to your messages
- Add a comment to a pinned location or region on the canvas.
- Figma will attach your comment to frames when you pin a comment or select a region inside a top-level frame, component, or group.
- If those frames are moved around the canvas, their comments move with them. Comments won't attach to any nested frames, components, groups, or other layers
- `@mentions` allows you to include a collaborator in the comment thread, or draw their attention to a specific part of the design file
- Add emoji when adding or replying to comments. Figma uses the Apple emoji collection

In a team there are some general restrictions around mention behavior:

- Collaborators that have the same roles on a resource can @mention one another. For example: team members can mention anyone else who is a member of the team.
- Team members can also mention collaborators who only have a role on that specific file.
- Collaborators that only have a role on the file, and not the team or project, can only mention collaborators that are members of the team. They can't mention collaborators that are only added to that file.

Outside of a team you can mention anyone you "know" in Figma. This includes:

- People who are on the same teams, projects, or files as you.
- Anyone you have invited, or has invited you, to a file.

<div align="right">&#8673; <a href="#back-to-top" title="Table of Contents">Back to Top</a></div>

[View and manage comments](#https://help.figma.com/hc/en-us/articles/360041547593-View-and-manage-comments)

Comments in a file are pinned to the point or region of the canvas selected by the commenter. How comments display depends on your zoom level of the canvas and the amount of comments.

- **Pins**: Individual comments are represented by a . Hover over a pin to preview the comment. Click the pin to open the comment modal, where you can reply
- **Clusters**: As you zoom on the canvas, multiple comments that are pinned closely to each other are consolidated into clusters. Hover over a cluster to preview the amount of comments and avatars for their authors. Click on a cluster to focus on the comments within it, then hover or click on individual comments to view them.

You can access comments from the right sidebar. You can also dock a comment to the top left corner of the canvas to keep it open while you implement feedback in your design.

**Hide comments**:

- Comments are always visible on the canvas by default, whether or not you're in comment mode. If you rather hide comments from your canvas and only see them when in comment mode, you can do so at any time.

**Sort and filter comments**:

- All the comments in the file will be listed in the right sidebar when you're in comment mode. Comments in the right sidebar can be sorted by:
  - Date: displayed in order from the first comment in a thread
  - Unread: displayed by date, prioritizing comments that haven't been read

**Reply and react to comments**:

- Anyone can add, view, and reply to comments, including Viewers.

**Resolve comments**:

- Once the feedback has been addressed, or a resolution reached, you can Resolve the comment.
- This will hide the comment from both the right sidebar and the canvas.

**Delete comments**:

- You can also delete any comment you post. If you delete a comment with replies, this will delete the entire thread.

<div align="right">&#8673; <a href="#back-to-top" title="Table of Contents">Back to Top</a></div>

[Move or edit comments](#https://help.figma.com/hc/en-us/articles/360041547853-Move-or-edit-comments)

- You can edit the content of any comment you've posted. This is handy if you've noticed a typo, want to add a clarification, or mention a collaborator.

**Change comment location**:

Comments can be pinned to a specific frame or layer, or specific co-ordinates on the canvas. This allows you to draw attention to a specific part of the canvas, whether this is a frame, object, or layer.

You can change where the comment is pinned. To move a comment:

- Select the comment in the canvas, or from the right sidebar in comment mode.
- Click on the comment pin in the canvas.
- Drag the comment pin to its new location.

<div align="right">&#8673; <a href="#back-to-top" title="Table of Contents">Back to Top</a></div>

#### Move layers with comments

If you've pinned a comment to a specific layer, you may be able to move both the layer and its comments. Your method for moving the layer, and the layer's final destination, impact the comment's location.

**Cut and paste**:

If you cut a layer or frame and paste this in a new location, Figma disconnects the comment from that layer. You can still view and respond to that comment from the right sidebar.

If the comment wasn't pinned to the layer, you can also access that comment from it's original co-ordinates on the canvas.

Figma won't move comments if you cut and paste layers between files. Any comments will remain as detached comments in the original file.

**Move between pages**:

If you use the Move to page option to move a layer within a file, Figma also moves any comments. Right-click on the object and choose Move to page.

If the comment was linked to the canvas—not the layer or frame itself—Figma won't move the comment.

**Duplicate files**:

If you duplicate a file, Figma won't copy comments to the new file. Comments are only kept on the original file.

<div align="right">&#8673; <a href="#back-to-top" title="Table of Contents">Back to Top</a></div>

[Manage email notifications for comments on files](#https://help.figma.com/hc/en-us/articles/360041547813-Manage-email-notifications-for-comments-on-files)

If you are the owner of a file, you will receive email notifications for all comments by default. If you are not the owner of a file, you will receive notifications for mentions and replies by default.

Connect Slack to your Figma account using our Slack integration. This lets you receive notifications in Slack when a team member comments on a file or thread you're active on.

<div align="right">&#8673; <a href="#back-to-top" title="Table of Contents">Back to Top</a></div>

<br>

<h3 id="a-collaborative-online-whiteboard-for-teams" align="center"><a href="https://www.figma.com/figjam/online-whiteboard/"><strong>A collaborative online whiteboard for teams</strong></a>
</h3>

FigJam is a free and easy to use online whiteboard where teams can brainstorm, diagram, moodboard, and problem solve—together.

FigJam comes with out-of-the box features to help you run smooth and engaging meetings.

- Stay on track: Our shared timer keeps activities running on time.
- Extend what’s possible: With widgets you can customize your online whiteboard to your team’s needs.
- Invite anyone: With Open sessions anyone can join your whiteboard for 24 hours without needing to create an account.

<div align="right">&#8673; <a href="#back-to-top" title="Table of Contents">Back to Top</a></div>

<br>

<h3 id="what-is-figjam-by-figma" align="center"><a href="https://www.figma.com/figjam/online-whiteboard/"><strong>What is FigJam by Figma</strong></a>
</h3>

FigJam is a truly robust brainstorming tool that makes it easy to get your entire team involved in the collaboration process. The whiteboarding tool allows you to:

- Use sticky notes and shapes to share and group thoughts and ideas
- Use the marker to draw freehand, annotate the screen, or jot down quick thoughts
- React with stickers, stamps, and reactions to flag questions or up-vote ideas
- Seamlessly copy and paste between FigJam and Figma, so everything stays in one place together

With these tools, you can build diagrams, map out user journeys, analyze results, and much more. FigJam also offers free templates to help new users get started.

#### Resources and Guides

Here are some support resources from FigJam directly that can help you get started with using their software.

- [Templates](https://www.figma.com/community/figjam?tab=files): The FigJam community has a wide array of story mapping, flow chart, brainstorming and more templates available for download.
- [Support Guide](https://help.figma.com/hc/en-us/categories/360002051633): Browse various technical articles and guides on using FigJam.
- [Collaborating on Zoom](https://www.innovationtraining.org/how-to-use-zoom-to-facilitate-a-collaborative-workshop/): Tips to host a virtual workshop or brainstorming session using Zoom.

<div align="right">&#8673; <a href="#back-to-top" title="Table of Contents">Back to Top</a></div>

### Collaboration in Figma Is Simple and Familiar

Because Figma is browser-based, teams can collaborate as they would in Google Docs. People viewing and editing a file are shown in the top of the app as circular avatars. Each person also has a named cursor, so tracking who is doing what is easy. Clicking on someone else’s avatar zooms to what they are viewing at that time.

Real-time file collaboration helps mitigate “design drifting”—defined as either misinterpreting or straying from an agreed-upon design. Design drifting usually happens when an idea is conceived and quickly implemented while a project is in progress. Unfortunately, this often leads to deviating from the established design, causing friction and re-work.

Using Figma, a design lead can check in to see what the team is designing in real time by simply opening a shared file. If a designer somehow misinterprets the brief or user story, this feature allows the design lead to intervene, correct course, and save countless hours that would have otherwise been wasted. (By comparison, teams using Sketch have no immediate way of telling if designers are going astray.)

Side note: Some designers don’t like to be “spied on” when they’re working, so it’s up to the design lead to explain the benefits. In general, most designers quickly see the value in such a feature and easily adapt to working in a shared environment.

<div align="right">&#8673; <a href="#back-to-top" title="Table of Contents">Back to Top</a></div>

#### Figma Uses Slack for Team Communication

Figma uses Slack as its communication channel. When a Figma channel is created in Slack, any comments or design edits made in Figma are “slacked” to the team. This functionality is crucial when designing live because changes to a Figma file will update every other instance where the file is embedded (a potential headache for developers). Changes to a mockup, warranted or not, are immediately vetted, and the feedback channel is live.

#### Figma Sharing Is Uncomplicated and Flexible

Figma also allows permissions-based sharing of any file, page, or frame (called an artboard in other design tools). When a share link is created to a frame on a page, the person clicking on that link will open a browser version of Figma, and a zoomed-in view of the frame is loaded.

This form of selective sharing, from file down to frame, lets designers, product owners, and developers share exactly what is needed in bug tracking tools and community software like Confluence or SharePoint.

#### Figma Is Great for Design Review Feedback

Figma supports in-app commenting in both design and prototyping modes, and the comment thread is tracked in Slack and/or email. There’s no need to publish PNG files or perform constant updates to get feedback from a team using a third-party tool like InVision or Marvel.

During design reviews, team designers can discuss their work on a large screen, record comments, and fix issues—all in Figma. This form of live feedback is not possible with Sketch, which requires uploading to a cloud service to get team input.

<div align="right">&#8673; <a href="#back-to-top" title="Table of Contents">Back to Top</a></div>

#### Figma APIs Provide Third-party Tool Integration

Figma now has [developer APIs](https://www.figma.com/developers/api) to allow true integration with any browser-based app. Companies are using this to integrate real-time displays of design files in their apps. For example, Uber has large screens displaying design files “live on air” around their company. Designs are shared, and feedback is welcome from anyone in the company.

Atlassian’s JIRA software has implemented a Figma add-on so product owners, developers, and quality engineers are always viewing the latest version of any mockup from the designers.

Additionally, Figma’s API promises to fulfill customer requests for third-party plugins and feature enhancements that Sketch already provides.

#### File Versioning Is Automatic or On-demand

Any uncertainty surrounding live file updating is further mitigated by Figma’s built-in versioning system. At any time, a designer can create a named version and description of a Figma file; this can be done immediately after agreed changes are made to a design.

There is a lot more to this article - I skipped the following

<div align="right">&#8673; <a href="#back-to-top" title="Table of Contents">Back to Top</a></div>

#### Figma’s Team Libraries Are Ideal for Design Systems

Design systems have become a necessity for many companies, and there is a need for components (symbols in Sketch and Illustrator) that are reusable, scalable, and “tokenized” for use in the pattern libraries available to UX designers and front-end developers.

The often used phrase “single source of truth” does fit here—once a Figma team library is created, anyone with access to a project can use instances of the components in their designs and be certain they are working with the latest versions.

Figma’s approach to component libraries is simple and easy to manage. Designers can create files that are full of components or use on-page components to organize a pattern library. Each frame in a Figma page becomes the organizational section in the team library (there is no need to create hierarchies\like\this).

One way to organize libraries is to have a project dedicated solely to components. Files within that project can be organized as needed, and the pages within those files can be arranged accordingly.

#### Figma Is Built to Enhance Design Teamwork

Using Figma for any length of time will demonstrate the benefits of this live collaboration tool. It keeps teams on task and encourages full disclosure, essential when building a design system for a variety of disciplines. Figma is easy for anyone to use on any platform, and lets teams share their work and libraries quickly.

Design experts that use Figma after making the switch from Sketch (Sketch files can be imported with parity into Figma) are not disappointed:

<div align="right">&#8673; <a href="#back-to-top" title="Table of Contents">Back to Top</a></div>

<br>

<h3 id="collaboration on-figma" align="center"><a href="https://www.digidop.fr/en/blog/features-better-collaboration-figma"><strong>Collaboration on Figma</strong></a>
</h3>

### Collaboration with Figma

To improve the design phase of web projects, Figma has developed many features that will allow you to collaborate more easily.

### Create and share as a team

An essential feature for designers and developers is the ability to create a team on Figma. Figma teams will be able to access a common workspace where all your projects and files are grouped together.

The tool therefore allows you to create several teams, for example to separate your design teams dedicated to client projects from your marketing and communication teams.

#### Working simultaneously

Figma allows you to work simultaneously with several people on the same project. Either with your teams or by inviting other collaborators on a project, you can design and evolve at the same time. Each modification or new design made to a project is visible in real time to all the designers in the file.

<div align="right">&#8673; <a href="#back-to-top" title="Table of Contents">Back to Top</a></div>

#### Observation mode

When you are working with several people on the same project, this mode will allow you to take the view of one of your collaborators. You will be able to follow live where he is and what he is presenting or looking at on the file. A very useful mode for presentations, for example.

#### Accessing the modification history

When you start to design with several people on the same project, it can be useful to access the history to see who has made this or that modification, and restore a previous version if necessary. Figma gives you access to all the modification history of a project, by identifying the team member who made the modification. You can thus easily access the Figma history to restore an old version Create a new version of the file, rename a version, share or delete a version.

#### Add comments and feedback

One of the most used features to easily collaborate on Figma is the possibility to add comments. Easy to use, you can add a comment on a specific point of the file or on a larger area with one click. You can detail your comment by adding an image, a file or a link. This makes feedback clearer and more accurate for the whole team.

<div align="right">&#8673; <a href="#back-to-top" title="Table of Contents">Back to Top</a></div>

#### Launching team calls

Figma also allows you to communicate live from your project, with all the people in it, thanks to the "Conversation" feature. This means you can chat live from Figma, without having to use another tool like Slack or Google Meet.

#### Share mock-ups and designs

Project sharing on Figma is an essential feature, allowing you toinvite new people to collaborate, or simply to view a project.

- Adding a person to the project
- Sharing an editing link
- Sharing a link to view
- Embed code to integrate into a website or other tool

<div align="right">&#8673; <a href="#back-to-top" title="Table of Contents">Back to Top</a></div>

## Lunacy

Lunacy was created by ICONS8. Check out their [YouTube channel](https://www.youtube.com/c/Icons8/videos).

<h3 id="work-in-a-team-with-lunacy" align="center"><a href="https://www.androidauthority.com/how-to-use-google-docs-tutorial-tips-tricks-3110289/"><strong>Work in a team with Lunacy</strong></a>
</h3>

Now, you can create a team within Lunacy and all the team members will access the documents within the team space. Currently, you can try teamwork on a free plan:

- You can create one team and invite two more members to the team: a free team can include up to 3 members. A user can be a member of one free team only.
- Available user roles include team owner, admin, editor, developer, and viewer.
- You can create up to 10 team documents on the free plan.
- Use projects to organize team documents. Think of projects as folders.
- Document version history is limited to 30 days.
- Restore documents that have been in the trash less than 90 days

The other highlights of v.8.5 include:

- Cross-region collaboration. Now you can seamlessly work with cloud documents created in other server regions.
- Support for right-to-left languages in the user interface. We know that many of you are asking for RTL support for on-canvas texts. Please wait, we’re working on it.

<div align="right">&#8673; <a href="#back-to-top" title="Table of Contents">Back to Top</a></div>

<h3 id="lunacy-review-2022" align="center"><a href="https://www.androidauthority.com/how-to-use-google-docs-tutorial-tips-tricks-3110289/"><strong>Lunacy Review 2022</strong></a>
</h3>

Lunacy is the Vector Design software available for free without a limit. You get the freedom to create icons, illustrations, and photos. It provides you with online and offline functionality. With its online functionality, you can access your documents from anywhere. It is initially based on a sketch format which you can use, make changes, and save.

- it offers dark mode.
- It also gives you 99% rendering accuracy for any .sketch file you open, irrespective of its format
- The other best part of Lunacy is that it is not limited to Windows. macOS and Linux users can use it as well

#### Likes

- Its UX prototyping tool is better though the software is free.
- Navigation and interface are easy.
- Drawing complex images and exporting files is a simple game.
- It comes with built-in UI kits and wireframing tool.
- The team keeps updating the software promptly.
- It is responsive and good with speed.
- It takes less space in your device.
- In forums, the team addresses people’s reviews and works.
- HTML preview is amazing in this software.
- It also comes with a tutorial to use and learn about its features.

<div align="right">&#8673; <a href="#back-to-top" title="Table of Contents">Back to Top</a></div>

#### Dislikes

- The font may disappear; the font title will show the correct one, but it will be stock sans serif.
- Plugins and adding tools feature is missing.
- Opening large files may crash the app.
- It doesn’t have the option to export in a different format.
- There is no cutting tool in the software.

#### Features of Lunacy

- It allows you to export CSS and XAML code and assets in PNG and SVG format.
- It comes with a basic typography tool.
- You can arrange pages and artboards in your document.
- It publishes assets directly to a CDN.
- Automatically downloads missing Google Fonts.
- It can read .sketch files of all versions. It was tested 13 months before the launch.
- You can collaborate with your team through Sketch Cloud.
- The export format supports PNG, JPEG, BMP, TIFF, ICO, WEBP, SVG, and PDF.
- The import format supports PNG. JPG. JPEG, WEBP, BPM, ICO, GIF, and SVG.
- Lunacy takes less memory and runs fast.
- It is the only Windows app that can open and save .sketch files.
- You can draw and align vector images.

<div align="right">&#8673; <a href="#back-to-top" title="Table of Contents">Back to Top</a></div>

<h3 id="how-to-migrate-from-figma-to-lunacy" align="center"><a href="https://blog.icons8.com/articles/how-to-migrate-from-figma-to-lunacy/"><strong>How to migrate from Figma to Lunacy</strong></a>
</h3>

Lunacy is almost like Figma, but faster. It is a native app, not a sluggish Electron-wrapped browser pretending to be an app. And it can work offline. Here’re some tips on how to migrate from Figma to Lunacy.

#### Why Lunacy

- Works online and offline on Windows, macOS, and Linux.
- Has all the basic features, except for auto layout (coming soon!): collaboration, components, styles, etc. Check out the full comparison.
- Readily handles huge files of several gigabytes in size. No more annoying loading indicator!

#### How to migrate from Figma to Lunacy

All you need is to convert Figma files to .sketch. You can consider the following options:

- Convertify. Figma plugin. Сonverts first 10 files for free.
- Avocode. Free online converter. Requires a Figma access token.

Both free converters work fine, but there can be issues with components.

**Convertify**:

- Components remain components, but they don’t show up and appear as placeholders.
- Broken links with other files, design systems and their components.
- Fills can appear on masked layers. In such a case, you’ll need to remove the fills manually.

**Avocode**:

- The converter is available for free. It requires your Figma access token.
- Avocode is really a great tool for converting Figma files to .sketch. But it turns components into groups.

> You’ll have no problems switching from Figma to Lunacy: all the features and hotkeys are similar.

<div align="right">&#8673; <a href="#back-to-top" title="Table of Contents">Back to Top</a></div>

## Penpot

Check out the [Penpot YouTube Channel](https://www.youtube.com/c/Penpot).

<h3 id="open-source-design-collaboration-with-penpot" align="center"><a href="https://opensource.com/article/21/12/open-source-design-penpot"><strong>Open source design collaboration with Penpot</strong></a>
</h3>

Penpot is an online design workspace where designers can create or import graphical elements, create mock-ups, and share those mock-ups with clients and collaborators. It is open source and relies on open formats like SVG, which means your contributors have lots of choices in what tools they use to contribute assets.

#### Getting started with Penpot

- After you log in, you're presented with the Projects page.
- There are some demo files here, designed to provide you with an overview of the Penpot interface.
- A project in Penpot can have multiple pages. Select a page to view in the Pages panel
- A page in Penpot isn't like a page in the real world. A Penpot page is an infinite canvas. Middle-click and drag to move the canvas

#### Create an artboard

- An infinite canvas means you can use the same workspace to display several different options for the same page type.
- You can design a light and dark theme, a mobile and desktop version, and then several different iterations of each.
- Because everything's on the canvas, you need a way to define an area for your design, and in the terminology of design apps, that's an artboard.
- An artboard is a container (think of it as a div, in CSS terms) for a mock-up.
- It's the part of the canvas you'll show someone when they ask to see your design ideas.
- To create an artboard, click the Artboard icon in the left toolbar, or just press A on your keyboard
- Click and drag on the canvas to create an artboard
- If you need very specific sizes, you can adjust your artboard's dimensions in the properties panel on the right side of the Penpot interface
- You can perform basic maths in the text fields, e.g. if you know your design size is 1920 by 1080, but you need to allow for scrolling down the equivalent of five screens, enter `1080*5` as the height, and Penpot converts it to 5400 for you

<div align="right">&#8673; <a href="#back-to-top" title="Table of Contents">Back to Top</a></div>

#### Drawing in Penpot

- Penpot primarily uses SVG (Scalable Vector Graphics) for its design elements.
- SVG is a structured and open format that's easy for web developers to translate into code.
- drawing in Penpot is as easy as drawing in Inkscape and, just as importantly, it's easy to align, duplicate, re-use, and export for use in any other application
- In Penpot, you have these drawing tools:
  - Rectangle (R): draw rectangles, and adjust for rounded corners and fills in the properties panel
  - Ellipse (E): draw ellipses and circles
  - Text (T): create text elements
  - Image (Shift+K): import a bitmap image
  - Curve (Shift+C): a pen with Bezier curves
  - Path (P): a pen tool
- You can adjust all design elements in the properties panel on the right of the interface. Most everything that can be adjusted also maps to a CSS property
- it's that much easier for the development team to translate design to implementation accurately

#### Assets

One of the easiest ways to ensure consistency in design is to re-use assets. The fewer times a designer has to draw essentially the same button, the fewer opportunities there are for a rounded corner to be forgotten or the size to be wrong. Build a library of design elements and make those the vocabulary of your designers.

- Once you've designed an element, right-click on it, and select Create Component. The item is added to your project's Assets library
- You can access your asset library by pressing Alt+I on your keyboard or clicking the Assets icon in the lower-left corner of the interface

<div align="right">&#8673; <a href="#back-to-top" title="Table of Contents">Back to Top</a></div>

#### Comments and feedback

A healthy feedback loop is vital for collaboration, and one way to provide feedback asynchronously is the Comment (C) tool. Using the Comment tool, collaborators on a project can safely post questions and observations anywhere in the workspace. Comments are threaded, so a conversation happens within one comment block, and a comment thread can be deleted when an issue has been resolved.

#### Prototype

To capture the different states your design may go through as a user interacts with it, you can build a prototype, with no coding required. A prototype lets you set any design element as a trigger to detect a click or mouse event and to take an action such as navigating to another artboard or opening an overlay.

<div align="right">&#8673; <a href="#back-to-top" title="Table of Contents">Back to Top</a></div>

<h3 id="open-source-prototyping-and-design-platform" align="center"><a href="https://medevel.com/penpot/"><strong>Open-source Prototyping and design platform</strong></a>
</h3>

Penpot is a free, open-source web-based design and prototyping application for teams. It works with open web standards as it uses SVG (Scalable Vector Graphics) format.

Penpot can be installed on a remote server or the local machine with help of Docker and Docker Compose. With Penpot, you can quickly design a web or mobile prototype in no time.

You can use Penpot as a solo designer to work directly with your customers or, as a part of a team to work on your prototypes.

#### Penpot Features

Penpot takes care of collaboration, team management, real-time commenting, shared resources, assets library and more. Here is a list of Penpot features:

- Supports unlimited projects
- Large artboards selection: mobile, web, tablet, social media posters, and custom.
- Unlimited users with roles and different permissions
- Eases real-time collaboration between team members
- Easily switch between prototyping and design views
- Run prototyping player
- Layer support
- Enable scale text
- Drafts which helps designer publish their work as it finishes
- Export artboards to PDF
- Record your color selection
- Comments tool, Comments viewer, and System-wide comments
- Supports multiple teams
- Shared libraries among teams
- Download the source image with SVG and CSS support.
- Add your custom fonts to the asset libraries
- Shared library among designers
- Assets library
- Built-in notification
- Search assets libraries
- Convert your design elements into components
- Drafts management
- SMTP email support
- Drag-and-drop assets download
- Download full projects in a combat file
- Easily drop your downloaded project file into Penpot's page which will download all project files and assets

#### Install Penpot

- using Docker and Docker compose. You can configure SMTP, users, demo accounts, and more using config.env file. If everything is ok, you can start using Penpot at: `http://localhost:9001`. SMTP does not seem to work

<div align="right">&#8673; <a href="#back-to-top" title="Table of Contents">Back to Top</a></div>

<h3 id="free-open-source-prototyping-platform" align="center"><a href="https://www.ilovefreesoftware.com/25/webware/free-open-source-ui-prototyping-platform-for-designers-penpot.html"><strong>Free open source prototyping platform</strong></a>
  </h3>

Penpot is a free and open source UI prototyping platform for designers. Think of Penpot as a decent alternative to Figma with a few limitations.

The installation process is easy as well since it supports Docker deployment. If you wish, then you can use it online as well as offline locally on a local server running on your personal machine.

#### The main features of Penpot

- All the designing tools are in the toolbox. From shapes to layer editor, you have access to all. Just select a tool and then start drawing on the artboard.
- All the shapes and elements that you add in your design can be customized. You can configure fill color, stroke, and layer multiplication parameters. All the options are displayed in the right sidebar just like Figma.
- You can preview the design that you have created.
- Share the design with your team. Just add collaborators to share projects with your entire designing team. Also, share designs via URL.
- Design editor is very responsive and supports ruler and adjustment options. You can use zoom and pan like feature to adjust the view and also align elements according to the horizon or center.
- Penpot lets you create interactive design and mimic the product behavior. You can share them with stakeholders, present proposals to your team and do user testing all in one place.
- Penpot supports feedback features. When you share the design with others, then they can leave comments on the design for improvements.
- Export individual components as PNG, SVG, and PDF.

<div align="right">&#8673; <a href="#back-to-top" title="Table of Contents">Back to Top</a></div>

<h3 id="penpot-on-github" align="center"><a href="https://github.com/penpot/penpot"><strong>Penpot on GitHub</strong></a>
</h3>

Penpot is the first Open Source design and prototyping platform meant for cross-domain teams. Non dependent on operating systems, Penpot is web based and works with open standards (SVG).

Being web based, Penpot is not dependent on operating systems or local installations, you will only need to run a modern browser.

Using SVG as no other design and prototyping tool does, Penpot files sport compatibility with most of the vectorial tools, are tech friendly and extremely easy to use on the web. We make sure you will always own your work.

If you prefer not to install Penpot in a local environment, login or register on [Penpot cloud app](https://design.penpot.app/#/auth/login).

Join the [Penpot community](https://community.penpot.app/).

<div align="right">&#8673; <a href="#back-to-top" title="Table of Contents">Back to Top</a></div>

## InVision

Check out their [YouTube channel playlists](https://www.youtube.com/c/Invisionappinc/playlists) for tutorials on the tool. I'm not adding notes for them but here are some useful links:

1. [Working with InVision V7 prototypes](https://support.invisionapp.com/hc/en-us/articles/360003221591-Working-with-InVision-V7-prototypes)
1. [What is InVision Write](https://support.invisionapp.com/hc/en-us/articles/360038850231-What-is-InVision-Write-)
1. [InVision Spaces](https://www.invisionapp.com/inside-design/spaces-collaboration/)

<div align="right">&#8673; <a href="#back-to-top" title="Table of Contents">Back to Top</a></div>

## Sketch

Sketch is only free if you are a student or teacher so I won't be adding notes but here are some useful links:

1. [How to get started with real1.time collaboration](https://www.sketch.com/blog/2021/05/05/get-started-with-real-time-collaboration/)
1. [Get started with your Sketch 1.orkspace](https://www.sketch.com/blog/2021/11/02/get-started-sketch-workspace/)
1. [How to Collaborate With Your T1.am Using Sketch](https://webdesign.tutsplus.com/articles/how-to-collaborate-with-your-team-using-sketch--cms-25170)
