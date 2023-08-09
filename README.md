<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

## osTicket - Ticket Lifecycle: Intake Through Resolution
This tutorial outlines the lifecycle of a ticket from intake to resolution within the open-source help desk ticketing system osTicket.<br />

## Environments and Technologies Used

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

## Operating Systems Used

- Windows 10</b> (21H2)
- MacOS Ventura 13.0.1

## Ticket Lifecycle Stages
1. [Intake](https://github.com/reynaldomata/ticket-lifecycle#ticket-intake)
2. [Assignment and Communication](https://github.com/reynaldomata/ticket-lifecycle#ticket-assignment-and-communication)
3. [Working the Issue](https://github.com/reynaldomata/ticket-lifecycle#working-the-issue)
4. [Resolution](https://github.com/reynaldomata/ticket-lifecycle#ticket-resolution)

## Lifecycle Stages

### Ticket Intake 
<p>

https://github.com/dtaylor15/osTicket-LifeCycle/assets/101889571/23afe210-ade4-4fc6-8bb8-02f36e635015

</p>

<p>

For this example, I signed in with the user credentials I configured in [osTicket System Administration Configuration](https://github.com/reynaldomata/post-install-config). I submitted a ticket as "Greg Universe", an employee reporting an issue with his laptop's trackpad. Because Greg is registered on osTicket, he can view his ticket's progress and submission history. 

</p>
<br />

### Ticket Assignment and Communication
<p>

https://github.com/dtaylor15/osTicket-LifeCycle/assets/101889571/7ad7bdca-83af-42c2-8538-3fa30d7d7ebc

</p>
<p>

Because Greg used a [SEV-A](https://github.com/reynaldomata/post-install-config#configure-helpdesk-sla) help topic his ticket was categorized as an emergency and went directly to the system administrator (me). After reviewing the ticket, I determined that this request was not an emergency. His trackpad issue did not severely impact business operations, especially because he was able to maintain productivity using his external mouse. I reduced this ticket's priority to a low, SEV-C plan. I also re-assigned it to Garnet, an agent on the Level 1 Support team. Each action taken was recorded on the ticket thread. 

</p>
<br />

### Working the Issue

<p>

https://github.com/dtaylor15/osTicket-LifeCycle/assets/101889571/20c6f829-9a5c-4bdc-8e6d-e2528f0f5a91

</p>

<p>
This ticket was submitted by Jane Doe, a customer who categorized it with a normal severity level (SEV-B). After reviewing the ticket, I determined that this request was in fact an emergency. Jane received a 404 error indicating that her user portal was down. This prevented her from paying for services rendered. Because this ticket impacted business operations, I re-assigned the SLA to SEV-A and responded immediately.
</p>
<br />

### Ticket Resolution 
>**Note:**
> A warm handoff is where one colleague passes off a task to another, using clear communication. In this example, the warm handoff occurred over the phone.

<p>

https://github.com/dtaylor15/osTicket-LifeCycle/assets/101889571/61321833-541c-408c-8efe-d6fa8c5af8f4

</p>

<p>
Back to Greg's example: After a warm hand-off to Level 1 Support, this trackpad ticket was resolved by enabling the trackpad's function in Windows Device Manager. The actions taken to resolve this ticket were documented in the ticket thread. The closed ticket is available for review in Admin panel -> Tickets -> Closed. 

</p>

<br />

## osTicket - Ticket Lifecycle: Intake Through Resolution Complete!👏🏾
