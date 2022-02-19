VKEYLOGGER NEW MALWARE FULL ANALYSIS BY ME FOR CYBER RESEARCHERS …its my first ever report so ignore any flaws :D …
YESTERDAY I FOUND PANEL ACCESS TO THIS NEW KIND OF MALWARE SO GOING TO ANALYSE THE WEB INTERFACE FOR INTERESTING STUFF INSIDE….
now its time to PREPARE some coffee its show time !!
the first interesting part is the DASHBOARD PANEL AREA [ page.php ] wich clearly have 4 sections for the attacking process by the cyber criminal :
-ACTIVE BOTS ( THE TOTAL BOTS TAKEN BY THE BOTNET … )
-BOTS ONLINE ( THE TOTAL ONLINE BOTS FOR SENDING COMMANDS …. )
-SAVE LOGS ( SAVED LOGZ FROM THE ATTACKS LAUNCHED )
-TOTAL TASKS ( THE EXECUTED TASKS FROM THE THIRD PANEL SECTION [ TASK MANAGER ] )
FINALLY COMES COUNTRY AND GEO STATISTICS FOR AFFECTED COUNTRIES STATS !

— — — — — — this is just the start NEXT = BOTS SECTION :

searching panel contains :
Bot ID: unique id generated trough the panel PHP functions to identify victims!
Country: flag of country + name
Operating System: AFFECTED WINDOWS OS NUMBER + architecture
Architecture: exactly its name

# ID ( bot id ) IP address ( ipv4 ) Country Operating system ( os ) Antivirus ( antivirus used ) Last seen ( last seen by malware ) Version ( version of malwar ) Status ( offline or online )

— — — — — — — — — — — -THIRD-SECTION — — — — — — — — LOGS — — — — — — — :

similar as previous : searching panel ( bot id )

# Bot ID Last update Next action
1 5EB9C4641D621C9C61990BE3232DCA7A 19/02/2022 11:48 AM
2 7FAC12BA24EF68047BB5E112756AF93C 19/02/2022 5:00 AM
3 042BCD40780388BDC4D0501B2FAFF3B4 19/02/2022 12:42 AM
4 B12D04D2267DF5276DF95347C2F74D5B 18/02/2022 2:26 AM
5 88531FC559E80BE5E8DF1FA1822D250F 18/02/2022 12:39 AM
6 2FA2B2821211738CD35FD1E77B796206 18/02/2022 12:38 AM

— — — — — — — — — -FOURTH-SECTION — — — — — — — — -TASK-MANAGER — — — — — — :

this is the fun part we are waiting for LOL

Task List : previous executed tasks.;
New Task : make new task for HVNC EXE RUN ( hvnc : hidden virtual network computing malware )

each new task execution consist of :

Action : DOWNLOAD AND RUN ( its called downloader malware wich download + run after execution only ) OR UPDATE APPLICATION ( it means updating the same malware to the background processes )
Load method : DROPPING — MEMORY
Name : RANDOM NAME
Link : DIRECT LINK OF EXE MALWARE TO EXECUTE FROM THE PANEL …
Target ID : THIS IS COPIED FROM PREVIOUS BOT IDS ( THE LIST )
Max. execution : THE MAXIMUM EXECUTION FOR THE MALWARE..( DEFAULT IS ZERO )

Task List
New Task

# Name ( name of downloader ) Action ( selected action ) Target ID ( the victim target ) Max execution (maxiumum executions ) Registration date ( date of launch ) Status ( pending or completed ) Next action ( extra option for hiding the task )
1 hvnc Download & Run 5EB9C4641D621C9C61990BE3232DCA7A 1 / 1 19/02/2022 11:49 AM Completed
2 hvnc Download & Run 1 / 1 19/02/2022 11:48 AM Completed

— — — — — — — — — — — — — — — — -FINAL-SECTION — — — — — — — — — — — — — -CONFIGURATION — — — — — — — — -:


this section is simple consist of : [ Bots interval: the interval of bots to use per attack , Keylogging: true of false for logging keyboard of bots ]

— — — — — — — — — — LOGOUT — — — — — — — -SECTION — — — — — — — — — — — — — — -:

— — — — — — — — — — — — — — — — — —

i’ve been looking into the bots sections VIEW BUTTONS ( the output is below )

clearly its keylogging modules + LOGGING MODULES FOR THE PANEL :

    =====================================================
    (1) Jodylyn Castillo | Facebook and 3 more pages — Profile 1 — Microsoft Edge
    =====================================================
    wwww

    =====================================================
    Please Login
    =====================================================
    [VK:231][VK_TAB][VK:231][VK_RETURN]



    =====================================================
    Program Manager
    =====================================================
    [VK_SNAPSHOT][VK_SNAPSHOT][VK_SNAPSHOT][VK_SNAPSHOT][VK_SNAPSHOT][VK_SNAPSHOT][VK_SNAPSHOT][VK_SNAPSHOT][VK_SNAPSHOT][VK_SNAPSHOT]
    =====================================================
    Administrator: Windows PowerShell
    =====================================================
    [VK_SNAPSHOT][VK_SNAPSHOT]
    =====================================================
    Program Manager
    =====================================================
    [VK_SNAPSHOT][VK_SNAPSHOT][VK_SNAPSHOT][VK_SNAPSHOT][VK_SNAPSHOT][VK_SNAPSHOT][VK_SNAPSHOT][VK_SNAPSHOT]
    =====================================================

    =====================================================
    [VK_SNAPSHOT]
    =====================================================
    Program Manager
    =====================================================
    [VK_SNAPSHOT][VK_SNAPSHOT][VK_SNAPSHOT][VK_SNAPSHOT][VK_SNAPSHOT][VK_SNAPSHOT][VK_SNAPSHOT][VK_SNAPSHOT][VK_SNAPSHOT][VK_SNAPSHOT][VK_SNAPSHOT][VK_SNAPSHOT][VK_SNAPSHOT][VK_SNAPSHOT][VK_SNAPSHOT][VK_SNAPSHOT]
    =====================================================
    Administrator: Windows PowerShell
    =====================================================
    [VK_SNAPSHOT]
    =====================================================
    Program Manager
    =====================================================
    [VK_SNAPSHOT][VK_SNAPSHOT][VK_SNAPSHOT][VK_SNAPSHOT][VK_SNAPSHOT][VK_SNAPSHOT][VK_SNAPSHOT][VK_SNAPSHOT][VK_SNAPSHOT][VK_SNAPSHOT][VK_SNAPSHOT][VK_SNAPSHOT][VK_SNAPSHOT][VK_SNAPSHOT]
    =====================================================
    Administrator: Windows PowerShell
    =====================================================
    [VK_SNAPSHOT]
    =====================================================
    Program Manager
    =====================================================
    [VK_SNAPSHOT][VK_SNAPSHOT][VK_SNAPSHOT]




    THATS ALL FOR TODAY ABOUT CYBER SECURITY ….
    thanks for reading my first medium post !!
    + remember to NOT OPEN ANY LINK OR EXECUTABLE WITHOUT SCANNING FIRST :)
