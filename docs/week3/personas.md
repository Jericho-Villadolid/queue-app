## Juan Fillibuster, the person waiting

> "I just want to grab a snack and go, especially when I'm in a rush."

| | |
| --- | --- |
| **Photo or sketch** | [A drawing, an icon, or a free stock photo. Never a photo of the real person you interviewed.] |
| **Age, role and background** | 19, 2nd year CA student, has back-to-back classes|
| **Goals** | Successfully find and join a queue for an event. Acquire the food in time before his class starts|
| **Frustrations** | Requires physically waiting in a long line, sometimes in the heat. Uncertainty of the remaining availability of food supply. |
| **Devices and context** | Laptop, Smartphone. Short break 30 minute between classes. |
| **Tech comfort** | High, Is comfortable using modern technology after 2 years of studying in CA. |
| **Accessibility needs** | Nearsighted, Wears glasses. |

### Scenario

Juan’s Algorithms class ends at 11:30AM, and his next class starts at 12:00PM. On the walk out of the building he opens **BiteLine** on his phone and checks which events are still available. He picks one, taps "Join the queue", enters his name and email, and taps “Get a ticket.” His ticket number appears in large text, with “12 people ahead of you.” Instead of standing in the sun, he sits in the shade and glances at his phone now and then. When the status changes to “Next in line” he walks to the venue, receives the snack, and eats it on the way to class with ten minutes to spare.

### Top tasks in the app

| Task | Screen | Requirement ID |
| --- | --- | --- |
| Join the queue for an event line | Join | FR-00 |
| Check which events are still available before joining | Join | FR-00 |
| See ticket number and how many people  ahead | My place | FR-00 |
| Leave the queue anytime | My place | FR-00 |

### What this means for my interface

1. [Because Juan is nearsighted, and uses his phone to check the app while outdoors after class, my interface must show ticket numbers in large, high-contrast text.]
2. [Because Juan only has 30 minutes between classes and wants to avoid standing around in the heat, my interface must update its status automaically so that he can wait in any location.]
3. [Because Juan cannot accurately tell he will get a snack before supply runs out, my interface must indicate how many slots are left before the queue becomes full.]



## Anna de Serva, the staff member

> "It's hard to keep track of how many people have been served, how much food is left, and serving the food all at the same time."

| | |
| --- | --- |
| **Photo or sketch** | [A drawing, an icon, or a free stock photo. Never a photo of the real person you interviewed.] |
| **Age, role and background** | 22, 4th year CCS SC member, volunteered as a server for the free pizza event |
| **Goals** | Serve students in the correct order, fairly and without arguments. Know how many portions are left so she can tell students early. |
| **Frustrations** | Crowds pushing toward the serving table, with people cutting in line. Free food draws more students than there are portions, so she has to turn people away. |
| **Devices and context** | laptop, used while standing and serving the food. |
| **Tech comfort** | High, As a 4th-year CCS student she picks up a new web app quickly, but as a volunteer during the rush she has little time to learn it. |
| **Accessibility needs** | Noisy event, Hands busy serving food. |

### Scenario

At 11:30 the free food event opens, and a line of students is already forming at the serving table. Anna, on her shift as a Student Council volunteer, opens the staff dashboard on the laptop. The waiting list is ready with the next ticket at the top, and a count of how many are in queue. She taps “Call next,” and the student’s app updates while she prepares the serving. When the student arrives, she taps “Serve.” If nobody shows up after a couple of minutes, she taps “No-show” and moves on. She no longer shouts numbers or argues over who is next, and the crowd at the table thins out because students can wait elsewhere.

### Top tasks in the app

| Task | Screen | Requirement ID |
| --- | --- | --- |
| See the queue in order | Dashboard | FR-00 |
| Call the next person in queue | Dashboard | FR-00 |
| Mark a ticket as served | Dashboard | FR-00 |
| Mark a ticket as no-show | Dashboard | FR-00 |

### What this means for my interface

1. Because Anna serves one student after another with busy hands, my interface must put a large “Call next” button at the top of the dashboard.
2. Because Anna is in a noisy, crowded event, my interface must make the "Serve" and "No-show" buttons large, clearly separated and labeled, so she does not accidentally tap the wrong one.
3. Because Anna is busy serving, my interface must quickly refresh automatically whenever someone joins or leaves the queue.