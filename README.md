# <img src="http://www.rice.edu/_images/rice-logo.jpg" width=180> Comp427, Spring 2018, Homework 1
## Rational Paranoia
The homework specifications, as well as the corresponding course slide decks,
can be found on the [Comp427 Piazza](https://piazza.com/class/jqifhp864b37ju).
This assignment is due **Thursday, January 17 at 6 p.m.**

You will do this homework by editing the _README.md_ file. It's in
[MarkDown format](https://guides.github.com/features/mastering-markdown/)
and will be rendered to beautiful HTML when you visit your GitHub repo.

## Student Information
Please also edit _README.md_ and replace your instructor's name and NetID with your own:

_Student name_: Daniel Pham

_Student NetID_: dcp5

Your NetID is typically your initials and a numeric digit. That's
what we need here.

_If you contacted us in advance and we approved a late submission,
please cut-and-paste the text from that email here._

## Problem 1
- Scenario: {Grading}
- Assumptions:
  - Students submit their assignment in person on paper. Only one submission is allowed per assignment, and each student receives the same assignment. 
  - Papers are graded by hand only by staff members (professors and TA's of that class). 
  - Grades are recorded in a paper gradebook. At any point throughout the semester, that student can request to see their grades. 
- Assets:
  - The grade of each student and the actual submission of each student are the assets in this case, both of which are protected under FERPA. 
- Threats:
  - Define a read adversary as a non-staff member who wants to view the submission or grade of someone other than themselves. This might be to obtain information about the student's performance in the class or to obtain answers from the student's submission.  
  - Define a write adversary as a non-staff member who wants to actually change the submission or grade of any student, including themselves. This type of adversary can obviously benefit from controlling the performance of students in the class, causing any student to pass or fail at the adversary's discretion. 

- Countermeasures:
  - Submissions should be kept in a place that only teaching staff has access to, by card swipe access or key. 
  - Grading should be done in pen and in a color obviously different from the writing utensil that the student submitted the assignment in. 
  - Grades should be recorded in pen into the gradebook, which should also be kept in a place that only teaching staff has access to. If a grade needs to be changed, it must be done w/ whiteout, and a timestamped record with signature and description of grade change must be attached to certify the grade change. Since this is likely a fairly small-scale operation (it's unlikely that the teaching staff will be unnecessarily large), verification can simply be done by asking the person that the record came from or checking the paper submission. All of these things can be done with minimal cost, since the majority of it is just implementing proper procedure. 

## Problem 2
- Scenario: {Stadium}
- Assumptions:
  - Stadium contains an American football field. 
  - Tickets are required for entry into the stadium. 
  - The game will be extremely well attended.
  - Seats at a college football game are generally unassigned, with the exception of possibly VIP tickets. 
- Assets:
  - The systems that control the stadium: scoreboard, jumbo screens, plumbing, lighting, etc.
  - The team's equipment should be protected from theft and damages, both from outsiders and the opposing team. 
  - The players themselves should obviously be safe while they are playing the game. 
  - Spectators and their belongings should also be protected. 
- Threats:
  - Attacker intending to cause physical harm to the players or spectators.
  - Hacker intending to damage the electrical systems.
  - People that did not pay for a ticket. 
- Countermeasures:
  - Only allow public access through specific gates, and include bag checks at every public entry point that check for weapons. Some form of authentication must be required for access to non-public areas, such as maintenance tunnels. 
  - Metal detectors might be costly, but since the stadium is at a high-ranking team's university, it would be likely that that would be affordable. TSA-level scanners, however, would not. 
  - Cameras in public spaces, private spaces. 
  - One way entrances and exits for diverting traffic and minimizing the risk of someone sneaking in without a ticket. 
  - Authentification system for tickets such that each ticket is unique; subsequent scans of the same ticket should deny access. People leaving the stadium must have another form of authentication that is only obtained when exiting the stadium, and people should only exit at designated exits. 
  - Physical security in place before, during, and after the game that watch for violence or any person that did manage to gain access to a restricted area or that were let in without a ticket. 
  - Systems should be adequately encrypted and inaccessible, at least to the average spectator. Requiring passcodes and possibly two-factor authentification that is only available on-site would be helpful for this. System should also be resilient to attacks; an attack on one part of the system should not bring down the rest of the building. 

## Problem 3
- Scenario: There's a party happening off campus, and my house is hosting.
- Assumptions:
  - Since it's my house, I know where everything is.
  - Alcohol will be present, and everyone invited to the party is over 21, or under 21 and not drinking. 
- Assets:
  - The things in my room, as well as each private room in the house should be kept confidential and safe.
  - The things that are accessible to the public (TV, picture frames, etc.) should also be kept safe.
- Threats:
  - Attendees unintentionally breaking things just out of stupidity.
  - Attendees with the intention of theft. 
  - People come that I don't want coming (people I have beef with, people that I have no relation to)
  - Attendees bring illicit drugs/weapons. 
- Countermeasures:
  - Remove all valuable items from public spaces into a private space that can be locked from the outside. Mark private spaces as private so people know to avoid them.
  - Have at least one sober friend/house member in attendance to keep track of who is/isn't supposed to be at the party and keep watch for illegal things. 
  - Have water and food to take care of drunk people. (see: the sober friend) Have spaces that people that drove to the party can stay if they're too drunk to drive home. 
  - If something ends up breaking, have a system to find out who the person was so they can be held accountable. (damage mitigation) (House cameras are costly for a broke college student, so asking around might do the job)
  - If I know two people have beef, or are likely to get belligerent, nudge them into separate parts of the house or convince one to leave altogether. Defuse unfavorable situations that I anticipate will occur. 

