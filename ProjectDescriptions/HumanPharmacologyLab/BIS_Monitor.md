BME464L Project (Fall 2013, Palmeri)
====================================

Bispectral Index (BIS) Monitor
--------------------------------

### Clinical Problem ###
Bispectral index (BIS) monitors are used to monitor the depth of anesthesia
through a complex analysis of brain electrical activity.  While the use of BIS
monitors is not universally accepted, they are becoming a more common
anesthetic metric to monitor during surgical procedures.  The Human
Pharmacology Lab (Department of Anesthesiology, Duke University Medical Center)
uses BIS monitors as part of a complex array of physiologic tests while
physiologic stresses are placed on clinical study subjects.  The Human
Pharmacology Lab uses LabChart&reg; (ADinstruments) to display and record all
of their physiologic monitors, but the BIS monitor outputs an RS232 data stream
(something that all of your are probably too young to remember being on almost
every personal computer before USB cables) that cannot directly integrate into
the LabChart hardware.  

### Project Objective ###
Design a device that converts and parses the BIS monitor RS232 output signal to
a signal that can be read into the LabChart hardware.  Time synchronization with
the other LabChart monitors will also be critical.

### Clinical Contact ###

Dr. David MacLeod, M.D.  ([david.macleod@duke.edu](mailto:david.macleod@duke.edu))
