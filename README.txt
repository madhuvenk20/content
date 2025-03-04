                    _     __ _               
__      _____  _ __| | __/ _| | _____      __
\ \ /\ / / _ \| '__| |/ / |_| |/ _ \ \ /\ / /
 \ V  V / (_) | |  |   <|  _| | (_) \ V  V / 
  \_/\_/ \___/|_|  |_|\_\_| |_|\___/ \_/\_/  
=============================================

Please read this document to understand the current workflow of the content for
Animal Liberation Now!  Regardless of which team you belong to, understanding
the whole flow is highly recommended.

Definitions
-----------

⊙ ALN!              -- the organisation, Animal Liberation Now!
⊙ Content team      -- the people who would be writing content for ALN!
⊙ Copyeditors       -- the people who would be responsible for copyediting.
⊙ Graphic designers -- the people responsible for graphic designing.
⊙ Social media team -- the people responsible for posting on social media.

Important links
---------------

⊙ https://github.com/animalliberationnow/content/issues/new -- create new ticket
⊙ https://github.com/animalliberationnow/content            -- GitHub project
⊙ https://github.com/orgs/animalliberationnow/projects/2    -- Project tracker

Content team
------------

The content team is responsible for coming up with the content.  After coming
up with the initial draft of the content, the content team is expected to
create a GitHub "issue".
<https://github.com/animalliberationnow/content/issues/new/>

Feel free to add the title and create an issue -- this will create a relevant
ticket for our tracker.  Please assign the ticket to yourself.

In the project option of the ticket, please add it to content-team-tracker,
keeping the status to content-team.

If you are not used to using GitHub, once you create the issue, you would see
an option to create a branch.

Please give a name to the branch, with the repository destination and branch
source being set to the default configuration.  I highly recommend the content
team to learn to use Git (even if not GitHub, but knowing that is a plus), to
make it easier to manage the workflow.

With the new branch, please add the content in the repository according to this
example folder structure.

```
.
└── 2025
    └── 02
        └── non-consensual-acts
            └── writeup.md
```

The file your final revision will go in is `writeup.md'.  `.md' is a markdown
file.  If you haven't used markdown before, please consider learning it.  It
will take no more than 10 minutes.  Knowing the syntax should be good to go.
And you can look for the basic syntax here.
<https://www.markdownguide.org/cheat-sheet/#basic-syntax>

The basic syntax should be way more than what you need.  Most of it is here:

--------------------------------------------------------------------------------

# Heading 1 (Biggest)
## Heading 2
### Heading 3
#### Heading 4
##### Heading 5
###### Heading 6 (Smallest)

**Bold**
_Italic_ or *Italic*

1. This
2. Is
3. An
4. Ordered
5. List

- This
- Is
- Unordered
- List

--------------------------------------------------------------------------------

A sample writeup file would look like:

--------------------------------------------------------------------------------

# Writeup

## Slide 1

Are you **against** _non-consensual_ acts?

## Slide 2

Video of forceful ejaculation + forceful insemination.

## Slide 3

What will **you** call _this_ act?

1. Sexual abuse.
2. Violation.
3. Rape.

## Slide 4

**Would you call this rape?**

If yes, how long will you continue to support it?

If no, tell us in the comments why you think violating an innocent is normal?

--------------------------------------------------------------------------------

Please stick to the template, as others looking at it can surely benefit from
the uniformity of content.

Once you have added your content, please create a pull request for the same.
And add that pull request to the comment of the relevant issue, and change
the status of the content-team-tracker to copyediting-team.  Don't change the
assigned ticket to others, they will pick it up from the board.

Please note, your work on this ticket isn't done yet.

Copyeditors
-----------

Once you see a ticket is moved to your board, copyeditors are supposed to pick
the ticket, assign it to themselves, and check for grammatical, spelling and
typographical errors (typo).  Once that is done, with no changes, move it to
the graphic-design-team board.

But if the changes were required, please make those changes, and proactively
speak with the said author of the content team to make sure you don't lose the
essence of the post in the way.  This can be done in the comments of the issue.
But please reach out to them for faster throughput.  Content team should add
an approval comment to the issue, if a change was made and they find it okay.
With their approval for the material, move it to the graphic-design-team board.

Copyeditors, Content team, please note that your work is not done yet.

Graphic Designers
-----------------

Once you see a ticket is moved to your board, graphic designers, you are
supposed to pick the ticket, assign it to yourself and work on it.  As the
project structure was previously mentioned, create a svg folder in the same
directory where the `writeup.md' file is located.  Create the graphic for the
slides mentioned in the markdown file.  Please do not change the content of
the slides, that is only to be done by the content team or the copyeditors.

```
.
└── 2025
    └── 02
        └── non-consensual-acts
            ├── svg
            │   ├── slide1.svg
            │   ├── slide3-iter1.svg
            │   ├── slide3-iter2.svg
            │   └── slide4.svg
            └── writeup.md
```

It would look something like that.  Once done, please ask the content team
if the slides achieve the vision that they wanted with the post.  Content team,
please be prompt in signalling them.  This would wrap up content team's
involvement.
After receiving a go-ahead (Please signal that in the issue ticket), graphic
designer should ping the copyeditors to check if the post is devoid of any
typos.  This would wrap up copyeditor's involvement.
After a similar signalling received from the copyeditors, graphic designers
should mention the commit ID, in the ticket and move it to the social media
team's board.

Social Media Team
-----------------

Once a ticket comes to your bucket, please download the SVGs, convert them to
PNGs, and decide upon the release date.  Please mention it in the ticket.
On the said date, please upload the content to the relevant social media.

Right now, the social media we are posting are on Instagram, Twitter as well
as Veganism.Social.

After posting at all places, move the ticket to done.
