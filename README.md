java c
UML   Assignment – Semester 2, 2024
BISM7255
A digital solution for VendWise Solutions Vending   Machines
Assignment Overview
Assessment Weight:
40%
Individual or Group work:
Either – your choice
Maximum group size:
2
Due   Date:
13th   September 2024 at 5PM
Version:
29th   July 2024
Introduction   
Summary Task:
The assignment asks you to create a collection of UML diagrams (eight diagrams) that   visually represent an application to develop   a   commercial   software   solution.
The   work   completed   in   this   first   assignment   will   form   the   foundation   for   the   third   assignment, where you build the application.You will act as a business analyst for Smart Strategy Consultants and start to elicit and   formulate   business   requirements to   help develop an   innovative and   novel concept for   VendWise Solutions, a vending machine   manufacturer.
Assignment requirements:
1.    You   must   use   Enterprise Architect   software from   Sparx   Systems to   create   the   UML diagrams.
2.    You   must,   in   total,   create   eight   UML   diagrams   –   five   diagrams   that   follow   the   case description and three diagrams that present a feature or innovation that is   not    described       in    the    case      description       (we       refer    to    them      as      “innovation   diagrams”).   For more details, see section ‘Task   Description’   .
3.    You    must   use   UML   2.5   –   This   means   the   assignment   must   comply   with   the   tutorial   materials and,   by extension, the OMG   UML specification version 2.5   of   Sparx Systems’ UML recommendations.
4.    You will   submit   two   documents:
a.    A Word document where all   UML diagrams are   presented
b.      For the   Innovation   Diagrams a short   brief   (no   more than   100   words   per   diagram) is required explaining the purpose or intent of   the innovation(s).   This is to assist the markers to understand your intended   purpose of the   diagrams.
c.      You   must   also   submit   a   SINGLE   Enterprise Architect   file   that   includes   the   eight   UML 2.5   diagrams,   which   the   marker   uses   if the   copied   UML   diagrams are not readable, or the   marker wants to verify   something.
Students per   AssignmentThe   assignment   can    be   submitted   as   an    individual    assignment   OR   done    by   two   students   as   a   group   assignment.   When   doing   it   as   a   group   assignment,   it   is   a   UQ   requirement to do a   peer evaluation.   For more details,   refer to the   Blackboard   site.
How do   I submit the assignment?
The assignment submission must be made via the Blackboard site following the steps   below:
1.      Go to “Assessment” > “Assessment   1:   UML   Assignment”
2.      Find the   links
a.      There will   be two links - one for Blackboard,   and   another for TurnItIn
3.      Upload both your project report file and your Enterprise   Architect file (*.eapx) to   BOTH   links
a.      If   you   have   worked   as   a   group   (max   two   people)   you   will   also   submit   your peer assessment form. (.pdf) to   Blackboard
How do   I   know that my assignment submission was successful?When the assignment is successfully submitted, the student receives two   automatically generated confirmation emails   (one for the Turnitin   submission,   one   for   the    EA   project submission) in   their   student email. Each email contains a unique   submission   ID.
Important submission information:
1.      To avoid any potential technical problems with computers or the internet,   students are advised to commence   assignment   submission   at   least   3   hours   before they are   due.
2.      Students   must click on the   Submit button to   submit   their   assignments.   Do   not   save   the   project   as   a   draft;   you   must   submit   the   assignment   by   clicking   the submit   button. The submission   has   not   been finalised when the   assignment   is   only saved.
3.      If   the   student   does   not   receive   any   of   the   two   confirmation   emails   with   the   submission IDs, then the student must assume that the submission of   the entire   assignment or part of   it was   unsuccessful.
4.      If a student does not receive the TWO confirmation emails with the submission   IDs    within    60    minutes,      the      student      is      advised      to      resubmit      the      individual   assignment part of the entire assignment (word   file   and   EA   file).
5.      The two confirmation emails with the submission   IDs are the only proof that the   assignment has been successfully submitted. Do not   delete these   confirmation   emails.
6.      It is the student’s responsibility to ensure that   any   UQ   assignment   is   submitted   successfully.
Any   unsuccessful submission   may   result   in a late   penalty.
MisconductUnderstandably,   students   talk   with   each   other   regularly   and   discuss   problems   and   potential solutions.   However, it is expected that the submitted   assignment   is   a   unique   work.   All parts of   the assignment are to be completed solely by the student(s) indicated   on   the   first   page   of the   assignment.   The   best   practice   to   avoid   misconduct   is   not   to   look   at   another student’s file(s) and   not to   show your   solution   to   other   students.   If   an   assignment    is    perceived      not      to      be      a      unique      work,      a      loss      of      marks      and      other   implications can   result.For    further    information    about      academic      integrity,      plagiarism      and      consequences,   please                visit                      http://ppl.app.uq.edu.au/content/3.60.04-                student-integrity-and-   misconduct\
DETAILED   INFORMATION ABOUT THE   PROPOSED   DESIGNIn   the   following,   you   find   details   that   allow   you   to   create   a   representation   of   the   business   case.   You   must   capture   the   Vending   Machine   application’s   operation   as   described   here. You   cannot   fill   in   gaps   or   leave   information   out.   If you   do   so,   marks   will   be deducted.
User Login and Ordering   (shopping cart)   application:Smart       Strategy       Consultants       have       been       engaged       by       VendWise       Solutions,       a   manufacturer   of   Internet   enabled   Vending   Machines.   The   machines   will   allow   the   customer to   interact   with the   machine via an application on the customers   phone.
It   is   proposed that the team create an application.   Our   Minimal   Viable   Product   (MVP)   will   include:
•          User Registration   and   Login
•         Vending   Machine selection
•         Order Entry and   (simulated)   Payment
•          Electronic   Receipt generation
DETAILED   INFORMATION ABOUT THE   PROPOSED   DESIGN
The following text provides the details to create the Use Case Diagram. The Use Case   will   present the   User   Registration and   Login,   plus the Order   Entry and   Payment.

The goal of the digital solution is to specify the processes involved and the   Actors who   participate   in the   processes. The   User will complete an online   application   to   Register   their   details.   Once   the   Users   details   have   been   confirmed   they   will   be   considered   a   Customer and be able to   Login to the online system to   place   an   Order. The   Customer   choses   a vending   machine   and   selects   products to   add to their   shopping   cart   before   completing the Order and making payment.   The Vending machine then dispenses the   items and sends a   Receipt to the   Customers account.
Ordering and   Payment   ProcessThe following   provides details to create the Activity   Diagram   and Sequence   Diagram.   Both diagrams present the Ordering and Payment process for   the Customer. However,   the Activity   Diagram   needs   to   capture   the   process,   whereas   the   Sequence   Diagram   captures    the    interactions      between    the    Actors      (Customer,    Vending      Machine      and   Payment   Gateway).
The shopping process starts when a   User opts to   “Register   Now”First, the User logs into the application with their Username and Password.   If the User   is   not   a   registered   Customer,   they   will   need   to   sign   up   for   a   new   account.   To   do   so,   the user enters personal   information   including:
•         Given   Name
•          Family   Name
•          Email address (doubles as the   Username, must   be   unique   across   the   system)
•         Contact   Number
•          Password   (minimum    10   characters   with   Upper,   Lower,   Number   and   Special   characters)After submitting the   details,   a Two   Factor   Identification   system will   confirm   the   Email   and    Contact    number.      Once      the      details      have      been      confirmed      the       User    will       be   considered   a   Customer. The   User then   logs   into the system with   their   Email   address   (as a   Username) and   password.Once the Customer is logged in, they   select   a VendWise vending   machine   and virtual   display   of   the   available   products   is   presented.   Tapping   on   a   product   displays   the   details (short description and price) with an option to   Add to Cart. When the Customer   has   added   all   they   want   to   the   Shopping   Cart   they   can   see   the   Cart   to   make   a   final   check.   At the same time the machine is checked to ensure the   items are   still   available   - a purchase may have occurred while the order   was in progress. If   there are any items   unavailable, their quantity   is   reduced to zero. The Customer   can   Purchase   or   Cancel   the order which will involve:
•          Purchase:   The   Total   Amount and Order Number Reference is sent to a Payment   Gateway   (for   example   Stripe   or   PayPal) where   the   user   can   enter   credit   card   details.      NOTE:      No    Credit    Card      details      are      to       be    kept       in    the      VendWise   application. The Payment Gateway responds to the application with a Payment   status   of   Complete   or   Cancelled   and   a    Receipt    Number    (if   Cancelled,   the   Receipt   Number is 000000 and can be   ignored).   Processing   these will   involve:
o   Payment   Complete:   The   Cart   is   copied   to   become   an   Order   and   the   Receipt Number recorded.   An electronic receipt is sent to the Customers   account. At the same time the VendWise vending   machine   is   instructed   to dispense the selected   items.


o   Payment   Cancelled:   The   Customer   is   informed   the   payment   has   been   declined.
•         Cancel:   Nothing
In all cases the Cart   is   emptied. The   Customer   can   restart   the   process   by   selecting   a   VendWise vending   Machine.
Data   Requirements of the application
The   following   provides   details   needed   for   the   Domain   Class   Diagra代 写BISM7255 A digital solution for VendWise Solutions Vending Machines Semester 2, 2024SQL
代做程序编程语言m.   The   diagram   shall present the data structure for the   VendWise application.VendWise will   have   many vending   machines   in operation, each with their own unique   digital   identification,   Date   of   manufacture,   GPS   coordinates   and   a   human   readable   description   of   its   location   (for   example   “Chamberlain   Building   35,   Level   1”). Also,   a   short description of the contents from an Enumerated list. The initial list   of contents   is:
•         0000 0001:   Cold   Drinks
•         0000 0010: Cold   Snack   Food
•         0000 0100:   Hot   Drinks
•         0000   1000:   Hot   Food
•         0001 0000: Stationary   Supplies
•         0010 0000:   Electronic   Equipment (eg   Phone chargers and cables)This will   allow   the   one   machine   to   be   registered with   a   combination   of contents.   For   example,   0010   0011   represents   a   machine   with   a   combination   of   Cold   Food,   Cold   Drinks and   Electronic   Equipment.
The current status of the vending   machine will   be   sorted   in   another   Enumerated   List.   These are the States as noted   in the   Lifecycle   of the VendWise vending   machine.Lastly   the   machine   will   have   an   array   of   Slots   each   with   a   unique   number   for   the   machine. The Slot   has an   internal   location –   Row   1   being the top   row through to   Row   6 at the   bottom, and   a   Column from   1 to   12.
The   Items for sale have a   Manufacturer,   Description,   Purchase   Price,   Recommended   Retail   Price, and   Image.Between   the   Slots   and   Items   there   is   a   Configuration   which   notes   which   Slots   have   which   Items   and   their   current   quantity,   current   sale   price   and   date   for   when   it   was   stocked.    Note:   some   slots   can    be   combined   for   items   that   require   two   (or   more)   columns to dispense.   For example chips require 2 columns on a   row where chocolate   bars only require   1. This configuration is setup   by   the   person   restocking   the   machine.Besides    the    previously      mentioned      details      for      the      Customer      (see      Ordering      and   Payment Processing), when a Customer makes a purchase, the   Items purchase price   is noted on the Order along with details of   the vending machine, and date of purchase.   As   this   is   a   new   venture,   tracking   of the   performance   of different VendWise   vending   machines will   be   monitor   as   the   company   test   out   different   locations,   Configurations   and   Items   being   dispensed   from   the   vending   machines. As   such   an   Order   needs   to   capture   all   the   details   about   the   purchase   at   the   point   in   time   it was   made.   It   cannot   be   assumed   that   the   same    machine    is    dispensing   the   same    Items,    in    the    same   Configuration, or is in the same   Location with subsequent   purchases.


Lifecycle of the VendWise vending machine
The following   provides details to create the State   Machine   Diagram. The   diagram will   represent the different states of the vending machine throughout   its operation.The VendWise vending   machine   starts   in   an   Off state. After the   machine   is   powered   on it performs a startup action and enters   a   Self Test state.   If the test fails the vending   machine   goes   into   an   Out   of   Service   state,   otherwise there   is   a triggerless transition   to the   Idle state.   In this state the vending machine waits for   a   Customer   Order.The    vending    machine      state      changes    from       Idle    to      Serving      Customer    when      the   Customer Order is received. Note the transition from   Idle to Serving   Customer   can   be   triggered by cancel event   as the customer   could   cancel   the   transaction   at   any   time.
The Serving Customer state is a composite   state   with   sequential   substates:
•         Verifying   Order
•          Dispensing   ItemsThe   Serving   Customer   state   has   a   triggerless   transition   back   to   Idle   state   after   the   transaction   is   complete.   If during   the   Serving   Customer   state   encounters   an   error,   a   Service   Failed trigger   will set the vending   machine   into an Out of Service state.When the vending machine is in an Out   of Service   state,   it will signal VendWise   of the   issue   (not   part   of the   State   Diagram)   and VendWise will   respond with   a   PowerDown   trigger to send the vending machine   into an   Off state.
Task   Description
After   familiarising yourself   with the business requirements for the software application,   you are   now required to   do   THREE tasks:
1.      Task 1: Choose a name for the digital solution.   Put the name on the cover page   of   the   word   file   along   with   the   name   of   the   student(s)   in   the   group   and   their   student   number(s).
2.      Task 2:   Create five   UML models   (one for   each   type)   based   on   the   description   of    business    requirements.    Document    any      assumptions    you      made      (if      any)   underneath each diagram.
3.      Task 3: Create three additional UML models that have   not   been   detailed   in the
description (or may   have   been   hinted   at).   There are two options for these, either:
(a)   Innovation   Diagrams –   Here we ask you   to   be creative and use   your   imagination to develop something new. You can consider this task as   a   suggestion for an   additional feature,   an   innovation the   application   designer did   not think of.
(b)   Normal   Operational   Diagrams   –   These   are   normal   operations   that   you would expect from a vending machine that has not been detailed   in the text.   For example, Coin operation where only   one   item   can   be   purchased at a time,   physical cash   must   be entered   (credit   card   can   only   be   done   via   the   application),   and   change   is   dispensed   at   the   same time as the   item   purchased.
The   three   UML   models   you   are   asked   to   create   must   be   an   activity   diagram,   a   sequence diagram, and a   state   machine diagram.


To   propose something genuinely   new – you   must   keep the following   in   mind:
1.    Activity   diagram   cannot   be   the ‘Registration   Process’ or   the   ‘Ordering   and   Payment’   system.   We   recommend   returning   to   the   use   case   diagram   and   thinking about a different   business   process.
2.    Activity    diagram   and   sequence   diagram    must   depict   the   same   business   process.For   both   Innovation   Diagrams and   Normal   Operation   Diagrams a short description   of   the   intended   process   also   needs   to   be   submitted   per   diagram.   No   more   than   100   words. This is so we can assess your comprehension of UML   from what you describe.
UML   2.5   PortfolioAll   UML   models   MUST   be   created with   Enterprise Architect   (EA),   and   each   diagram   must   be   exported   as   an   image   and   pasted   into   a   Word   document   that   MUST   be   submitted as well.The   word   document   must   include   an   overview   page   containing   a   table   of   contents   with   meaningful   headings.   For   example,   "Activity   Diagram"   followed   by   the   system’s   name.   In addition, each diagram may have assumptions   underneath only   if   needed.   It   is   recommendable for approximately 200 words   (for the whole   document)   but   can   be   less    or    more.    Also,    it    is    desirable      the      use      bullet      points.      Furthermore,      the    word   document   must   have   the   pages   numbered,   and   the   diagrams   must   have   a   readable   font size.All   models   MUST   be   done   in   UML 2.5. This   means   it   must   comply with the   tutorial   material and, by extension, the OMG UML specification version 2.5 or Sparx Systems’   UML recommendations.
Please make sure that you comply with the modelling   guidelines   as follows:
1.      The   models   must   be created with   Enterprise   Architect from Sparx.
2.      The first five   models   must   represent the   business case. This   means   you   need   to create the five diagrams using the   information   provided   in the assignment.
3.    You   must   only   model   the   automated   part   of   the   digital   solutions.   This   means   any   manual   activities   not   carried   out   by   the   system   will   not   be   represented   in   the   UML models.
4.    You   must follow   appropriate   modelling   conventions   (the   rules)   specified   in the   weekly tutorial files.
5.    You must capture the relationships between different types of UML models.   This   means:
•         The   activity   diagram   must   model the   business   process   captured   in   one   or   more use cases of the   use   case   diagram.
•         Activity   diagram   and   sequence   diagram   must   depict   the   same   business   process.
•         The    information    contained    in    the    sequence    diagram    should      match    the   information captured in the   class   diagram.
•         State   machine   diagram   must   depict   the   states   of   a   single   object   (over   its   lifespan); this object   is captured as a class   in   the   class   diagram.
For Task 2 – the first five   UML diagrams (see   p.   6), you   must   have   the   following   details   in each diagram:
N
Diagram Type
Assignment (recommended minimal requirements)
1
Use Case   Diagram
2 different   actors
8 top-level   use cases
3   include relationships
2 extend   relationships
2
Activity   Diagram
3   partitions
20 – 25   activities
3 – 4 forks and joins
2 – 4 decision and   merge   activities
3
Sequence   Diagram
1 domain object that   interacts
2 actors   in a complex sequence   of   interactions
12   input   messages
13   return values
2   –   4   self-messages   and   2   –   4   self-message   returns.   Parameters/input    data    must      be      included      along    with   each   input   message.
You should also include fragments (loop, opt, and/or   alt   fragments).
4
Class   Diagram
12   -   20   domain   classes   with   multiplicities,   attributes,   and operations.
2            –            3            cases            of            generalisation/specialisation   relationships
2         –         3         cases         of       whole-part          relationships          (i.e.,   aggregation   AND composition)
2 – 3 association   classesPlease ensure that all information captured in the Class   Diagram   comes   from   the   excel   spreadsheet   and   the   case description.
5
State   Machine   Diagram1   object,   5   major   states,   1   composite   state,   1   choice   pseudo-state,   and   various   transitions   with   triggers   and guard   conditions   (if   required).
You    should    also    include    the    initial    state(s)    and    final   state(s).

         
加QQ：99515681  WX：codinghelp
