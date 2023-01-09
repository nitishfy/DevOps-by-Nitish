Before understanding about DevOps, let's first understand what are the various steps included in order to build a software. This is also called as Software Development Life Cycle, or SDLC.

SDLC refers to the various steps that are required to build a software or an application from the scratch. There are various phases involved in the SDLC that are mentioned below:

**1. Requirement Analysis & Gathering:** This is the first step on building an application. All the requirements are framed in an document which is called as SRS document. This is the first step of the SDLC. The IT teams discusses on how to proceed with building the project, what is the estimation cost, language to be used and many more.

**2. Design:** In this phase, the software architecture is designed in the document called as SRS document. SRS document serves as a contract between server and client. It is designed in such a way that client gets a basic overview on how the project would be built.

**3. Coding:** Once the architecture of the software/appilcation has been designed, the coding phase generally begins by Developers. In this phase, coding is performed by the developers.

**4. Testing:** In this phase, the testing is done in order to ensure that the code that has been written does not contain any bug or errors. If there are bugs found, these are resolved here. There are different types of testing performed depening upon the application. Testing of entire application is performed, testing of individual modules is performed as well.

**5. Build:** After testing, the build phase occurs. Building is a process in which all the code that has been written and tested is converted into a single executable artifact which can be deployed on the servers by the Operation team. The written code is converted into executable code(Binary) here.

**6. Deployment:** The artifact that has been produced is deployed onto servers by the Operations team. Remember, Development team writes the code whereas Operations team deploy that code onto servers such that users can start using the application.

**7. Observability & Monitoring:** Once the code has been deployed on the servers using artifact, the end users can start using the application. Now, there might be new errors that users would generally come across. Similarly, there might be new features that development team would like to implement. Hence, in this phase new features to the application, Bug-fixes are generally done for the betterment of the application.

All this process goes on and on representing an infinite cycle. DevOps in general try to reduce each barrier that leads to delay in the new release of the software. Hence, DevOps has a symbol of infinity!
![SDLC!](//02-Software-Development/images/SDLC.png)

All the steps mentioned above when executed in the sequence leads to the formation of a model called as **Waterfall model.** In Waterfall model, the next phase is only executed once the previous phase has completely been executed.

![waterfall model!](/images/sdlc_waterfall_model.jpg)

The Waterfall model has a lot of disadvantages. For eg. You can't move to another phase unless and until the previous phase has been completed. Apart from that, It is very difficult here to go back and change something that was not well thought out in the planning. Working software is produced very late in the lifecycle.

The Waterfall model also leads to delay in the release of the software whereas DevOps is focused on removing each barrier that delays the release process of a software. It is to be noted that Waterfall model is an hypothetical model. There are various other types of model which are used like protoyping model, agile model which are all based on Waterfall model.

Let's take a look at what is an Agile model.

In Agile model, the tasks are divided into various iterations such that the entire team focuses on the tasks present in a single iteration. New ideas can be injected in the next iterations.

![agile_model!](/images/sdlc_agile_model.jpg)

Do you think Agile model is a good fit of developing an software? Well probably No. There are various iterations that are involved here due to which frequent code changes occurs. Hence it can really become messy for the Operations team to deploy the code to servers if the code is being changed frequently.

This leads to a state of confusion among Development team and Operations team. Let's take a look on how did the term DevOps rise?

- In SDLC, we've two teams - Development Team & Operations Team. The Development Team focuses upon writing better code for the software whereas Operation Team focuses upon deploying the Tested code onto the servers such that users can start using the application/software.

- It is an obvious step that code can only be deployed to the servers once the code has been written and tested well. But the problem doesn't end here. Sometimes the Operations team fails to deploy the code on the servers due to several reasons like new bugs introduced while deploying the code, code is not well documented ,etc. Hence Operations team sends the code back to the Development team to make some changes to the code whereas Development team which is already working on some new feature of the code goes through a hard time in order to find what went wrong with the code such that it can't be deployed to the servers.

Hence all these conflicts among Development Team & Operations Team leads to the delay in the release of Software. Don't forget that DevOps tries to remove all the barriers which leads to delay in the release of software.

**So who solved this big problem?**

The answer is DevOps. 

In the next module, we'd look at what exactly is DevOps and how it is solving the main problem of conflict among Development & Operations Team.

It is recommended to go through the following resources to get a better understanding of the above topic:

1. [Blog on SDLC - by Nitish Kumar](https://nitishblog.hashnode.dev/what-is-sdlc)
2. [What is SDLC - by tutorialspoint](https://www.tutorialspoint.com/sdlc/sdlc_overview.htm)
3. [What is DevOps - by Tech With Nana](https://youtu.be/0yWAtQ6wYNM)

*Advice: Watch the video at 1.00X or 1.25X while learning about any concept for the first time. Don't be in hurry!*