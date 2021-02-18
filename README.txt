# act
shell command line activity tracker 

#------------ # activity --------------------------------------------------------------
#.an  s1 s2 ..            - new activity for backlog - continue working on old task
.ai  s1 s2 ..            - new activity interrupt current activity 
.af                      - current activity finished 
.ala                     - list active activities in threads see also .aqt and .aqti 
.alb                     - list backlog activities 
.ali                     - list info files for actions created with .ani
.asb s1 s2 ..            - start activity from backlog
.as2 s1 s2 ..            - switch to new activity
------------ # threads --------------------------------------------------------------
.ant [name]              - new activity thread - new chain 
.alt [thr]               - list threads
------------ # query   --------------------------------------------------------------
.aqt                     - query threads simple view
.aqti                    - query threads status info 
------------ # archiving ------------------------------------------------------------
.aat [thr]               - archive thread see .aqt or .alt 
.aaa "time stamp"        - archive activity use ts from .ala 
.aab "time stamp"        - archive activity use ts from .alb 
------------ # misc -----------------------------------------------------------------
.ah                      - this help
