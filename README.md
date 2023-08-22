<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Ticket Lifecycle: Intake Through Resolution</h1>
This tutorial provides a comprehensive guide to understanding the complete lifecycle of a ticket in osTicket, covering ticket creation, assignment, communication, status updates, resolution, and closure. Geared towards beginners, this tutorial offers a screenshot walkthrough of the entire ticket lifecycle in osTicket. You'll see how to create, assign, communicate, and close tickets effectively, ensuring a smooth support process for both agents and customers.<br />


<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (22H2)

<h2>Ticket Lifecycle Stages</h2>

- Intake
- Assignment and Communication
- Working the Issue
- Resolution

<h2>Lifecycle Stages</h2>

<p><img width="1202" alt="Screenshot 2023-08-18 at 4 03 55 PM" src="https://github.com/EvanGCowan/ticket-lifecycle/assets/142631599/f29502a6-ea9a-4290-9eba-d8ba31d69712"/>
</p>
<p>
Tickets are shown in the queue, ready to be assigned.
</p>
<br />

<p>
<img width="1202" alt="Screenshot 2023-08-18 at 4 05 15 PM" src="https://github.com/EvanGCowan/ticket-lifecycle/assets/142631599/e954b964-27fa-45ef-b00f-d69aabca1f28">
</p>
<p>
The ticket is opened, allowing the manager to see the details of the ticket and make changes.
</p>
<br />

<p>
<img width="1202" alt="Screenshot 2023-08-18 at 4 05 43 PM" src="https://github.com/EvanGCowan/ticket-lifecycle/assets/142631599/d0baf17f-c71b-4081-b3f9-549a5c92e033">
</p>
<p>
The manager updates the priority level. In this case, it was an emergency becuase it was a system wide outage.
</p>
<br />



<p>
<img width="1202" alt="Screenshot 2023-08-18 at 4 07 40 PM" src="https://github.com/EvanGCowan/ticket-lifecycle/assets/142631599/0a6365a1-9ac4-4624-a2a4-9f1e16502acc">
</p>
<p>
The Service Level Agreement is set to the proper plan, according to the severity of the issue. 
</p>
<br />


<p>
<img width="1202" alt="Screenshot 2023-08-18 at 4 15 33 PM" src="https://github.com/EvanGCowan/ticket-lifecycle/assets/142631599/5e727f2c-281a-41ab-8318-96b2e3fef616">
</p>
<p>
The manager replies to the creator of the ticket. This is done to let the person who created the ticket know that it has been recieved and is being worked on. Details can be provided as far as who, what, when, why, and how. In this case, the ticket has been transfered to the System Administrators to be resolved. 
</p>
<br />



<p>
<img width="1202" alt="Screenshot 2023-08-18 at 4 17 15 PM" src="https://github.com/EvanGCowan/ticket-lifecycle/assets/142631599/40dcdc32-e76a-4d30-8bba-c87732ca69ca">
</p>
<p>
This is a look at the ticket queue after the changes have been made to ticket #390480 by the manager. You can see the priority has changed as well as who the ticket has specifically been asigned to. 
</p>
<br />

<p>
<img width="1202" alt="Screenshot 2023-08-18 at 4 20 10 PM" src="https://github.com/EvanGCowan/ticket-lifecycle/assets/142631599/eb33fb3f-b197-4dc1-b166-2a6d5b508e98">
</p>
<p>
This is the record log for ticket #390480. It shows each action that has been been taken toward resolving the ticket, including time stamps, contributing users, and messages in response to this specific ticket.
</p>
<br />

<p>
<img width="1202" alt="Screenshot 2023-08-18 at 4 21 21 PM" src="https://github.com/EvanGCowan/ticket-lifecycle/assets/142631599/7a06a678-9307-4178-b93f-4e7f49c0825c">
</p>
<p>
The final message corresponding to the resolution is added and the ticket is able to be closed.
</p>
<br />

<p>
<img width="1202" alt="Screenshot 2023-08-18 at 4 21 37 PM" src="https://github.com/EvanGCowan/ticket-lifecycle/assets/142631599/d9a7c8c8-c35d-4d4c-938c-e1ae83fb15c9">
</p>
<p>
You can see in the open ticket log, ticket #390480 is no longer in the queue becuase it has been resolved. 
</p>
<br />

<p>
<img width="1202" alt="Screenshot 2023-08-18 at 4 28 26 PM" src="https://github.com/EvanGCowan/ticket-lifecycle/assets/142631599/88445b88-c1eb-4f31-aa56-3db90c74c101">
</p>
<p>
In this screenshot, we are signed in as John, an IT Support Administrator for the company. This is the view he would see as he checks the tickets he needs to work on for the day. It's his lucky day and there isn't much that has to be done so he gets to work on the first ticket.
</p>
<br />

<p>
<img width="1202" alt="Screenshot 2023-08-18 at 4 28 37 PM" src="https://github.com/EvanGCowan/ticket-lifecycle/assets/142631599/739f4686-d6f9-47f6-b569-9e0f96fb807a">
</p>
<p>
John opens the only ticket was asigned to him. He is able to see the details of the ticket, messages, and any changes that have been made. 
</p>
<br />

<p>
<img width="1202" alt="Screenshot 2023-08-18 at 4 33 25 PM" src="https://github.com/EvanGCowan/ticket-lifecycle/assets/142631599/c54659e4-cadc-4c4c-a5e9-578c6474eaa3">
</p>
<p>
<img width="1202" alt="Screenshot 2023-08-18 at 4 34 04 PM" src="https://github.com/EvanGCowan/ticket-lifecycle/assets/142631599/e40806d9-8d43-4622-ad34-03ca7a3240b9">
</p>
<p>
John wasn't able to resolve the ticket due to his access level, so he calls his supervisor Evan who makes the changes and grants him the access. In the first screenshot you can see Evan is signed in and is making the proper access changes for John. Evan calls John back and lets him know the changes have been made and that he will have to sign out of his osTicket account and sign back in for the changes to take place. In the second screenshot, John signs back into his account. 
</p>
<br />

<p>
<img width="1202" alt="Screenshot 2023-08-18 at 4 35 45 PM" src="https://github.com/EvanGCowan/ticket-lifecycle/assets/142631599/08d88a0f-570b-4f8f-94ce-897df8a5ed65">
</p>
<p>
John is signed back in and is able to resolve the ticket. He writes a message to let Ken, the user who created the ticket, know that he was able to resolve the ticket. All users are fully mission capable (FMC). John had to do some research and wanted to note the details of this in the message that way he can recall the specifics in case this issue happens again. Other staff would also be able to reference this ticket and see what he did and how he resolved the ticket. This is also done allow for process improvment by learning what did and didnt work. 
</p>
<br />


<p>
<img width="1202" alt="Screenshot 2023-08-18 at 4 36 04 PM" src="https://github.com/EvanGCowan/ticket-lifecycle/assets/142631599/92f0371e-0450-460c-8cf6-216f383b1be7">
</p>
<p>
The ticket has been resolved and is no longer in John's queue. He can now go home!
</p>
<br />

<p>
<img width="1202" alt="Screenshot 2023-08-18 at 4 36 18 PM" src="https://github.com/EvanGCowan/ticket-lifecycle/assets/142631599/5f46022b-79e4-4d26-ba90-c925bc1898d4">
</p>
<p>
Because he is such a good employee, John checks the closed tickets to get a feel for how the day went and if he can add any insight to any other tickets.
</p>
<br />

<p>
<img width="1202" alt="Screenshot 2023-08-18 at 4 37 07 PM" src="https://github.com/EvanGCowan/ticket-lifecycle/assets/142631599/ad01def7-9369-4617-a936-243c7d7d643b">
</p>
<p>
In this screenshot is a ticket that Jane has closed and added a note to. John can see that she mentioned that a hardware refresh is slated for next month. Time to take that vacation before he gets busy again.
</p>
<br />
