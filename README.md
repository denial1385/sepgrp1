sepgrp1
=======

Software Engineering Project Group 1

+ Git created: 02/11/2014::1430.

+ Will house code for Group 1 : [Derek Chaney, Michael Kleban, David Ngibuini, & Daniel Simoneau]. 

+Project Overview: 2.2
  OPTION 2
  --
  Tape/DVD/Game Online Rental System --  The system simulates the Blockbuster online rental system. 
    
    People who have a member ID can rent Tapes/DVDs/Games. People can freely open/ close their account (membership). 
    When they apply their memberships, they need to provide their personal information, e.g., full name (first/last      name), SS#, email, address, phone#. 
    Tapes/DVDs/Games also have their goods' information, e.g., name, type (Tape/DVD/Game), release year, rental ID.      If goods type is Tape or DVD, it should be categorized as drama, comedy, action, horror, or special. System          should have the basic functionalities on insert membership, delete membership, edit membership, retrieve             membership (for people), insert new release, delete release, edit release, retrieve release (for                     When retrieving membership without indication, it should list all members sorted by member's last name, their        personal information, rental status, rental list, including the name, ID, rental price, check-in and check-out of     the releases they rent. When retrieving membership indicated, the system just lists the indicated member's           personal and rental information. 
    Similarly, system should be able to retrieve releases according to different types. When retrieving releases         without indication, the system should list all releases sorted by their name, release information including ID,      name, release year, release type, release category (if any),rental status, i.e., is it check-out?
    
    When retrieving release indicated, the system just lists the indicated release's information and
    who rents the release. When building the system, some issues are needed to be considered:
    1. Customer and system administrator sign-in / sign-out.
    2. Retrieve entities (releases) based on types, categories, names (partial/full) and IDs.
    3. Retrieve entities (persons) based on names (last/full), phone#, and IDs.
    4. Releases may have the same name, for example, system may store 10 bring down the house DVDs; however, each        release has a unique ID.
    5. People may have the same name, for example, two persons have the same name John Smith. However, each person       has a unique member ID.
    You can also enhance the system with more functionalities such as listing the top 10 welcomed tapes,DVDs,            and Games every month.
    
    ______ END First Commit (:DN)
    
    
