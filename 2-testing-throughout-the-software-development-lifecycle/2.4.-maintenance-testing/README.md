# 2.4. Maintenance Testing

Once deployed to production environments, software and systems need to be maintained. Changes of various sorts are almost inevitable in delivered software and systems, either to fix defects discovered in operational use, to add new functionality, or to delete or alter already-delivered functionality. Maintenance is also needed to preserve or improve non-functional quality characteristics of the component or system over its lifetime, especially performance efficiency, compatibility, reliability, security, , and portability. 

When any changes are made as part of maintenance, maintenance testing should be performed, both to evaluate the success with which the changes were made and to check for possible side-effects \(e.g., regressions\) in parts of the system that remain unchanged \(which is usually most of the system\). Maintenance can involve planned releases and unplanned releases \(hot fixes\). 

A maintenance release may require maintenance testing at multiple test levels, using various test types, based on its scope. The scope of maintenance testing depends on: 

* The degree of risk of the change, for example, the degree to which the changed area of software communicates with other components or systems 
* The size of the existing system 
* The size of the change

{% page-ref page="2.4.1-triggers-for-maintenance.md" %}

{% page-ref page="2.4.2-impact-analysis-for-maintenance.md" %}



