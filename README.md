# NYUAD Issue Resolution Platform: Project Proposal

## Introduction:

We are a team of visiting students from NYU Abu Dhabi who understand the daily pains of navigating administrative hurdles. Frustrated by the lack of efficient communication and transparency between the student body and various university departments, we've decided to build a system that addresses this pain point head-on. Our motivation isn't just academic; it's rooted deeply in our lived experience at NYUAD, and our desire to create a meaningful impact for our peers.

The existing procedure for filing complaints or requests usually involves sending emails to departmental aliases. These often go unanswered, ignored, or lost amidst other emails, leaving students in a state of perpetual limbo regarding the status of their issues. Urgent matters are seldom addressed promptly, if at all.

The system is fraught with inefficiencies that leave both students and staff dissatisfied. Students often resort to follow-up emails, contributing to an already-chaotic communication channel. On the other hand, department staff do their best but are hindered by the sheer volume of emails, lack of transparency, and redundant, unorganized requests. To tackle these challenges head-on, we propose the NYUAD Issue Tracker.

## Project Title

NYUAD Issue Resolution Platform

## Collaborators
Swostik Pati, Hasibur Rahman, Basil Ahmed, Avinash Gyawali, Nada Elsharkawy


## What and Why?

### Problem Statement

Currently, NYU Abu Dhabi students face a plethora of problems in getting their complaints and requests addressed by the various departments. The existing email-based system lacks transparency, accountability, and timely response. Often, issues are closed prematurely, emails go unanswered, and there's no means of tracking the status of the requests, leading to enormous inefficiency and student frustration.

### Importance

This project aims to eliminate these redundancies by developing a Request/Issue Tracker Dashboard web application. This central hub will streamline the communication process between students and departments, increase transparency, and improve the overall efficiency in resolving issues.

## For Whom?

1.  **Students at NYU Abu Dhabi**: The system will serve as a robust platform for students to put forth their complaints, queries, and requests.
2.  **Administrative Departments at NYU Abu Dhabi**: The platform will help administrative staff to manage and resolve issues more efficiently.

Both user groups are real and form the core constituents of the NYUAD community. Their needs and challenges have been assessed through conversations and observations.

## How?

### Student View

1.  **Secure Login**: Students will authenticate using Bcrypt and a database-backed login system.
2.  **Dashboard**: A portal to raise new issues, track the real-time status of existing ones, and review past issues.
3.  **Multi-Department Tagging**: While raising an issue, students can tag multiple relevant departments, to facilitate cross-departmental communication. We will make sure students aren't able to exploit this feature by putting in a cap on the maximum number of departments that can be tagged in a particular issue. 
4.  **Resolution Verification and Reopening**:  When an issue is considered resolved by the department, it is shifted to a "Resolved" tab that is also visible to the student. The student is then given a specific timeframe to confirm whether their issue has genuinely been addressed. If the problem persists, the student has the option to reopen the ticket. This not only increases transparency but also allows for a more effective problem-solving approach. Importantly, reopening an issue is made more efficient since all the historical data related to that issue is already available. Also it will help the department prioritize the issue by not seeing it as a new issue.

### Admin View

1.  **Department-Specific Dashboard**: Each department will see the issues tagged to them.
2.  **Status Management**: Ability to move issues between various statuses like "New," "In Progress," "Need More Info," and "Resolved."
3.  **Comments**: Admin can add notes or comments to an issue, viewable by the student. This would help inform students about any timlines or current blocks with their issues.
4.  **Delegation**: Departments are much more aware of which issues fall under their domain. So when a student tags multiple departments they can review the issues, and in some cases assign the issues to another department capable specifically for resolving the issue. At no point can all tagged departments remove an issue without at least one department being accountable for it. 

### Optional Features

1.  **Performance Metrics**: A departmental performance score based on metrics like response time, reopen rate, etc., could be internally stored for end of the year performance evaluation of the different departments which could help them improve and dedicate resources more efficiently. This score won't be visible to the students or anywhere else publicly.
2.  **Collective Issue Raising**: Students can join similar issues into a collective request using invite-only links. This allows students who are experiencing the same issue to combine their requests into a single, unified entry. and would help streamline the resolution process by reducing redundancy (especially of emails), and would also help the departments prioritize issues. 
3. **Scaling to other NYU campuses**: If our pilot works fine, we might even be able to scale it to other campuses of NYU and maybe to other colleges. This feature is just a "Future work" feature to work on beyond the course and most likely won't be implemented by the end of the semester.

## Scope

The scope of our proposal is carefully calibrated to be achievable yet challenging for a team of 4-6 programmers within the span of one semester. Our app at its core is basically a modified version of existing project management platforms. We deliberately steered clear of incorporating complex technologies like AI, ML, Blockchain, or VR, to ensure that the project remains within our collective skill set, especially as we progress through our MERN stack coursework. That said, the MERN stack itself presents a robust and complex architecture that demands a considerable learning curve, aligning well with the academic challenges we seek. Our goal isn't just to construct a functional backend; we also aim to focus significantly on frontend development to ensure an intuitive and visually appealing user experience. Given these factors, we believe our project strikes the right balance between complexity and feasibility. It offers us ample room for academic and practical growth without overwhelming our capabilities, making it neither too easy nor too ambitious for the semester ahead.
