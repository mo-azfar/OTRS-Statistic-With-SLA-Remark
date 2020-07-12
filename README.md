# OTRS-Statistic-With-SLA-Remark  
- For OTRS CE v6.0  
- Extend OTRS Dynamic Statistic Module to Include SLA Remark Status(Within/Breach SLA)  
- Modification files (based on OTRS 6.0.28) has been tag with :  
  

		#=================BEGIN SLA REMARK SECTION=============================
		CODE
		#=================END SLA REMARK SECTION===============================


1. Modify your existing DynamicList / TicketList Statistic to include **FirstResponseStatus** and **SolutionStatus** field.  
2. As this involved a bit of comparison between ticket data, it may take a little time to generate statistic with a huge data.  
3. Perhaps please use ticket filter (create time, queues, services, etc) to minimize populated data.  
  
[![download.png](https://i.postimg.cc/tJ23pvJN/download.png)](https://postimg.cc/2LLbxw41)  
  
[![Capture.png](https://i.postimg.cc/br8y1XqR/Capture.png)](https://postimg.cc/FdWXQBdf)  
