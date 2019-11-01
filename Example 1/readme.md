This is a quick and dirty version of the Kaseya install procedure but it works like a champ.  
[Procedure CloudRadial Agent](Procedure%20CloudRadial%20Agent.xml)

* In short:  
   Check for CloudRadial service
   
* If running:  
	Write to log "Agent already installed"
  
* If not running:  
   Write file to workstation from Kaseya server  
   Execute file silently  
   Write to log "Agent Newly Installed"
   
#### Special Thanks
 Sagiss - Travis Springer
