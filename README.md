# Zippy-Apps
It is the project name Zippy Software. It automates the text Records, their Sending and Maintenance, video charting, due to file sharing other Functions. In other words you can say it complete Intra-connect software.

	In this project we can easily maintain file sharing. It gives information’s of All Transaction of software, its services, daily charting, daily Report & maintenance.
	The Zippy Software provides ability to search any member records available in the software format.

1.3   Intended Audience and Reading Suggestions

•	This SRS is basically intended for the project managers and developers, team member who want to get the overview of the projects & its scope and the higher details of the various modules in the system. Any person who want make next version of this system can prefer this SRS. This SRS document includes the overall design description.
•	The reader should read thoroughly from first page to last page. In includes the data structure of system and hardware & software requirement for this software. It also includes the objective, purpose, scope, product feature and references.

1.4	  Project Scope

	  ‘ZS (Zippy Software)’ should help the customer query.
 The user can query the availability of a member either by using the member title or by using the full name or using by specific LAN ID. 
	If member is not currently being Available, then the customer is
Asked to enter full details of the member for procurement of the member in  
                        Future. 
	  If a member is available, then the exact member should be displayed. 
	  If a member is not available, the query for details is used to increment are quest 
     Field for the member. 
	 Here a member can contact with via video call, Audio call and Text message.
	It must sharing file information with both members.  
2. Overall Description

2.1 Product Perspective
The Zippy Software is the new, self-contained product. The ‘Zippy Software’ is using Java only. All components follow Model-View-Controller pattern. The user can retrieve information of their progress. All pages of the system are following a consistent theme and clear structure.
The occurrence of errors should be minimized through the use of checkboxes and scroll
Down in order to reduce the amount of text input from user. Error message should be located beside the error input which clearly highlight and tell user how to solve it. 
If system error, it should provide the contact methods. The page should display the project process in different colour to clearly reflect the various states. Each level of user will have its own interface and privilege to manage and modify the project information. User interface elements are easy to understand. Part of user interface is well organized on screen and the parts are concatenated right. When users look at the interface, they understand which pane is used for which purpose. Each task of an interface is specified clearly and users use them correctly. For example, when users press to any button on interface, they can know which operations are done by pressing this button.
The user interface is easy to learn. When users use the user interface, they can know which element is used to which operations. The interface actions and elements is consistent. When users press any button, required actions is done by the system. The screen layout and 
Colour of the user interface is appealing. When users look at the screen, it will have a nice vision. Colours will be selected clearly, thus eyes of users won’t be tired. Since the application must run on the PC, all the hardware shall require to connect the PC will be hardware interface 
for the system. The main interface would be the monitor, Keyboard and mouse. Zippy Software is a technology that automat the interacting with each other.
2.2	 Product Features
This technology includes more advantages over Automatic work. Here this system manages the all records of transaction in a day or month or yearly. The Zippy Software provide following facilities and services.

1) Monitoring all records
2) Searching of member by name, by Specific ID or by title or specific Lan id 
3) Updating records
4) Records of all transaction
5) Customer records
6) User records
7) Retrieving all records 
8) Saving the records
9) Audio charting and file sharing

2.3 Operating Environment
The proposed software is intended to run on client model network. A 
Client can deliver the better performance than the file server system because a client 
Application and database server work together to split processing load of applications (thus the 
Term distributed processing). The server manages the database among the number of clients, 
While the client send, request, and analyse the data entry form with small specific data set, such 
as rows in a table not file as in the file server system.
2.4 User Documentation
List the user documentation components (such as user manuals, on-line help, and
Tutorials) that will be delivered along with the software. Identify any known user documentation delivery formats or standards.

2.5 Assumptions and Dependencies
While cost estimation of the proposed system it has been assumed that the cost hardware and for license of Operating System and back end will be met by client (the organization). Hence only the cost incurred for the proposed software is included therein.
The followings are identified as some of the potential risk factors or dependencies:
(1) Non-availability of required resources.
(2) Power cuts.
(3) Slippage of schedule due to unpredictable holidays, etc.
Life Cycle Model - I am using SDLC model that begin at system level and progresses through analysis, design, coding, testing, implementation and maintenance.


3. System Features
3.1 Database – Storage
 The following features were required by the client:
1) The system should be secured enough to rely upon.
2) Users should be allowed to modify records.
3) Every report should keep the tracks of user inputting the record.
4) System should provide facility of exporting its data.
5) System should provide facility of uploading the information.

3.1.1 Description and Priority:
Provide a short description of the feature and indicate whether it is of High, Medium, or Low priority. You could also include specific priority component ratings, such as benefit, penalty, cost, and risk (each rated on a relative scale from a low of 1 to a high of 9).
3.1.2 Stimulus/Response Sequences:
List the sequences of user actions and system responses that stimulate the behaviour defined for this feature. These will correspond to the dialog elements associated with use cases.
3.2 Functional Requirements
Itemize the detailed functional requirements associated with this feature. These are the software capabilities that must be present in order for the user to carry out the services provided by the feature, or to execute the use case. Include how the product should respond to anticipated error conditions or invalid inputs. Requirements should be concise, complete, unambiguous, verifiable, and necessary. Use “TBD” as a placeholder to indicate when necessary information is not yet available. Each requirement should be uniquely.
3.2.1 Check for its working condition:
# A: select query user availability option
Input: query “user availability” option is clicked
Output: user prompted to enter the key words
#  B: Chart with video with audio calling
Input: click on video calling option
Output: both of user contact with video with audio calling
#  C: Chart with text messaging 
Input: click on user’s chart box
Output: chart with texting format with some help of letters
#  D: Both the users could share his/her document  
Input: click on browse button then upload the file such as video, audio, image or any other file format and post it to specific or publicly shared.
Output: other user can receive this file and use it easily.
#  F: Customer use Zippy Software
Input: customer should connect from respective id  through LAN connection.
Output: it will be easily communicate or file sharing.
3.2.1 Interface Requirements
3.2.1.1 User Interface:
	The user interface should be easy to learn. When users use the user interface, they should know which element is used to which operations. We should teach using of the user interface to users simply. If it is hard to learn, then teaching will take long time and there will be an extra cost for teaching of product.
4.  Non-Functional Requirement:-
4.1 User Interfaces
User interface is used to provide communication between users and system. Our product should have communication between one people to another. Because, ‘Zippy’ is a communication based system and it should get input from users for processing. Users will enter their Specific id or register via other services. When the user enters into their respective account after that he/she will call with video charting or audio calling or text messaging. Both the users can share their file with in it. Software gets these inputs by using user interface. Then, the software will study to find an optimized path for users according to their login or call or share constraint which is selected by users.
The user interface should be easy to learn. When users use the user interface, they should know which element is used to which operations. We should teach using of the user interface to users simply. If it is hard to learn, then teaching will take long time and there will be an extra cost for teaching of product.

4.2 Hardware Interfaces
The hardware interface for the user would be any PC having a configuration of
P-I and above 1.2GB HDD for loading any OS for operating the browser shall be
able to interact with the system without any problem. The main interface would
be the monitor, Keyboard and mouse. The bar code scanner is required for
scanning the assets during the yearly verification of the assets. The requirements
can be summarised as below:
4.2.1 SYSTEM REQUIREMENTS
 • WEB SERVER (Recommended)
	Hardware
	Operating System
	Windows NT/2000 Server with Option
	Pack 4.0
• WORKSTATION (Recommended)
	Hardware
	Pentium IV 1.50 GHZ.
	Operating System
	Windows 2000 Server with Option Pack

   	   4.3 Software Interfaces

	Java (for implementation purpose)
	Java Core

 	     4.4 Communications Interfaces

 Software shall be used to provide a communication between system and users. Hypertext Transfer Protocol (HTTP) is a communications protocol which is used to transfer or convey information on intranets And the World Wide Web. Its original purpose was to provide a way to publish and Retrieve hypertext pages. Development of HTTP was coordinated by the W3C (World Wide Web Consortium) and the IETF (Internet Engineering Task Force), culminating in the publication of a series of RFCs, most notably RFC 2616 (June 1999), which defines HTTP/1.1, the version of HTTP in common use. HTTP is a request/response protocol Between a client and a server. 
The client making an HTTP request, such as a web browser, is referred to as the user agent. The responding server, which stores or creates resources such as HTML files and images, is called the origin server. In between the user agent and origin server may be several intermediaries, such as proxies, gateways, and tunnels. HTTP is not constrained to using TCP/IP and its supporting layers, although this is its most popular application on the Internet. Indeed HTTP can be implemented on top of any other protocol on the Internet, or on other networks. 
HTTP only presumes a reliable transport; any protocol that provides such guarantees can be used. Typically, an HTTP client initiates a request by establishing a Transmission Control Protocol (TCP) connection to a particular port on a host (port 80 by default; see List of TCP and UDP port numbers). An HTTP server listening on that port waits for the client to send a request message.
5. Other Non-functional Requirements

5.1 Performance Requirements
As it is going to be used by the entire concerned customer within the organization, the system should have a good performance in terms of speed and accuracy. The proposed system should be accurate and fast enough to handle huge data. It should provide fast communication between server and clients.
5.2 Safety Requirements
As the system is going to handle parts records for a long run eliminating the manual system, it is supposed to ensure the retaining of data avoiding or eliminating any probable cause for data loss.
5.3 Security Requirements
The software should not allow unauthorized access to any module of the system. Besides, it should maintain the privileges granted to users at various user levels.
The prioritization of the software quality attributes are assumed as under:
1) Accurate and hence reliable.
2) Secured.
3) Fast speed.
4) Compatibility.
5) Portability
	System will use secured database
	Normal users can just read information but they cannot edit or modify anything except their personal and some other information.
	System will have different types of users and every user has access constraints
	Proper user authentication should be provided
	No one should be able to hack users’ password
	There should be separate accounts for admin and members such that no member can access the database and only admin has the rights to update the database.
5.4 Software Quality Attributes
The prioritization of the software quality attributes are assumed as under:
1) Accurate and hence reliable.
2) Secured.
3) Fast speed.
4) Compatibility.
5.5 User Requirement
      The users of the system are members and Other member who act as administrator to maintain the system. The members are assumed to have basic knowledge of the computers and internet browsing. The administrators of the system should have more knowledge of the internals of the system and is able to rectify the small problems that may arise due to disk crashes, power failures and other catastrophes to maintain the system. The proper user interface, user manual, online help and the guide to install and maintain the system must be sufficient to educate the users on how to use the system without any problems.
     The admin provides certain facilities to the users in the form of:-
	Backup and Recovery
	Data migration i.e. whenever user registers for the first time then the data is stored in the server
	Data replication i.e. if the data is lost in one branch, it is still stored with the server
	Auto Recovery i.e. frequently auto saving the information
	Maintaining files i.e. File Organization
	The server must be maintained regularly and it has to be updated from time to time

